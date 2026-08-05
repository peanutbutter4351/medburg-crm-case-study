# Production Deployment

## Infrastructure

Ubuntu VPS

↓

Nginx

↓

Gunicorn

↓

Django

↓

PostgreSQL

---

## Deployment Workflow

1. Develop locally
2. Commit changes
3. Push to GitHub
4. Checkout release tag on VPS
5. Activate production environment
6. Run migrations
7. Collect static files
8. Restart Gunicorn
9. Reload Nginx
10. Smoke test

---

## Key Lessons

One of the major deployment lessons during development was ensuring that the production environment loads the correct environment variables before running management commands.

Without loading `.env.prod`, Django defaults to SQLite development settings instead of PostgreSQL.

This became an important deployment checklist item.
