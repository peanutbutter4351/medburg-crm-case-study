# Medburg CRM
### Enterprise Pharmaceutical CRM for Sales, ROI Tracking & Commission Management

![Python](https://img.shields.io/badge/Python-3.12-yellow?logo=python)
![Django](https://img.shields.io/badge/Django-4.2-success?logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-blue?logo=postgresql)
![Gunicorn](https://img.shields.io/badge/Gunicorn-Application%20Server-brightgreen)
![Nginx](https://img.shields.io/badge/Nginx-Reverse%20Proxy-green?logo=nginx)
![Status](https://img.shields.io/badge/Status-Production-success)

> Medburg CRM is a production-ready Pharmaceutical Customer Relationship Management platform designed to simplify doctor engagement, sales operations, ROI tracking, commission management, and enterprise reporting through a unified workflow.

---

<p align="center">
  <img src="images/hero.png" width="100%">
</p>

---

## Project Snapshot

| Attribute | Value |
|------|------|
| **Industry** | Pharmaceutical |
| **Architecture** | Full Stack Web Application |
| **Backend** | Django |
| **Database** | PostgreSQL |
| **Deployment** | Ubuntu VPS |
| **Application Server** | Gunicorn |
| **Reverse Proxy** | Nginx |
| **Static File Pipeline** | WhiteNoise |
| **Authentication** | Role-Based |
| **Reporting** | Excel Export |
| **Current Release** | v1.3.0 |
| **Production Status** | Live Deployment |

</p>

---

## Highlights

- Production-deployed enterprise CRM
- Snapshot-based ROI accounting system
- Dual financial workflows (Prepaid & Postpaid)
- Interactive analytics dashboard
- Excel reporting and exports
- Role-based authentication
- Semantic versioning with release candidates
- Production VPS deployment using Gunicorn & Nginx

---

# The Business Problem

Many small and mid-sized pharmaceutical distributors still rely on spreadsheets, paper records, and disconnected software to manage their day-to-day sales operations.

This often results in:

- Difficulty tracking doctor relationships and product promotions
- Manual ROI calculations for prepaid investments
- Complex commission calculations for postpaid campaigns
- Lack of centralized sales reporting
- Limited business visibility for management
- Time-consuming Excel-based workflows prone to human error

As the business grows, these disconnected processes become increasingly difficult to maintain, making financial reconciliation and performance tracking both slow and error-prone.

---

# The Solution

Medburg CRM was designed as a centralized platform that digitizes pharmaceutical sales operations while preserving financial accuracy and operational transparency.

The system provides dedicated workflows for both prepaid investment tracking and postpaid commission campaigns, enabling representatives and administrators to manage doctor relationships, sales entries, settlements, and business analytics through a unified interface.

Rather than replacing business processes, the CRM was designed to model and automate the existing operational workflow while maintaining complete auditability of financial records.

---

# Users

The CRM supports multiple user roles, each with dedicated workflows and permissions.

| Role | Responsibilities |
|------|------------------|
| **Administrator** | Manage doctors, medicines, representatives, campaigns, investments, reports, settlements, dashboards, and overall business operations. |
| **Sales Representative** | Record sales, manage assigned doctors, monitor active investments, and submit daily field activities. |
| **Management** | Monitor company-wide KPIs, revenue trends, representative performance, ROI tracking, and business reports. |

---

# Core Modules

| Module | Purpose |
|---------|---------|
| Dashboard | Company-wide KPIs and business analytics |
| Doctor Management | Manage prepaid and postpaid doctors |
| Medicine Management | Centralized medicine catalog |
| Sales Entry | Record prepaid and postpaid sales |
| Investment Lifecycle | Track ROI-based prepaid investments |
| Campaign Management | Configure postpaid commission campaigns |
| Settlement Ledger | Financial reconciliation and payment tracking |
| Reports | Interactive reports with Excel exports |
| User Management | Role-based authentication and authorization |

## Dashboard Overview
Real-time business analytics showing revenue trends, investment activity, doctor performance, and sales insights for administrators.

<p align="center">
  <img src="images/01-dashboard-overview.png" width="95%" style="border-radius: 15px">
</p>

## ROI Tracking
Snapshot-based prepaid investment tracking with frozen pricing, recovery monitoring, and Excel-ready reporting.

<p align="center">
  <img src="images/02-prepaid-roi-tracking.png" width="95%" style="border-radius: 15px">
</p>

## Campaign Monitor
Commission lifecycle management for postpaid campaigns, including outstanding balances and payment workflows.

<p align="center">
  <img src="images/03-postpaid-campaign-monitor.png" width="95%" style="border-radius: 15px">
</p>

## Settlement Ledger
Centralized financial reconciliation system for campaign settlements, payment history, and outstanding commission tracking.

<p align="center">
  <img src="images/04-settlement-ledger.png" width="95%" style="border-radius: 15px">
</p>

## Admin Console
Customized Django administration interface for secure management of users, medicines, campaigns, investments, and operational data.

<p align="center">
  <img src="images/05-admin-console.png" width="95%" style="border-radius: 15px">
</p>

---

## Engineering Journey

This repository showcases the complete engineering journey behind **Medburg CRM** — from understanding the business problem to designing the architecture, implementing financial workflows, deploying to a production VPS, and maintaining multiple production releases.

> **Looking for the production source code?**
>
> **Production Repository**
>
> https://github.com/peanutbutter4351/medburg-crm
