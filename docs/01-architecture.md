# System Architecture

## Overview

Medburg CRM is a production-grade Pharmaceutical Customer Relationship Management platform developed using Django and PostgreSQL. The application manages doctor relationships, pharmaceutical sales, ROI tracking, commission settlements, reporting, and business analytics through a centralized web interface.

---

## High-Level Architecture

```
Browser
    │
    ▼
Nginx Reverse Proxy
    │
    ▼
Gunicorn
    │
    ▼
Django Application
    │
    ▼
PostgreSQL
```

---

## Technology Stack

- Python 3.12
- Django 4.2
- PostgreSQL
- Gunicorn
- Nginx
- WhiteNoise
- Chart.js
- HTML/CSS/JavaScript

---

## Application Structure

The project is divided into multiple Django applications.

| App | Purpose |
|------|----------|
| accounts | Authentication & Users |
| doctors | Doctor Management |
| medicines | Medicine Catalog |
| sales | Prepaid & Postpaid Sales |
| reports | Business Reports |
| core | Shared utilities |

---

## Deployment

The production application runs on an Ubuntu VPS using:

- Gunicorn
- Nginx
- PostgreSQL
- WhiteNoise

The deployment follows a Git-based release workflow with semantic versioning.
