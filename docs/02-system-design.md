# System Design

This project was intentionally designed around financial accuracy rather than CRUD operations.

---

# Major Design Decisions

## Snapshot Accounting

Medicine prices change over time.

Instead of recalculating historical sales using current prices, every sale stores a frozen snapshot of the medicine price.

This guarantees historical financial accuracy.

---

## Dual Financial Engines

The CRM contains two completely different business workflows.

### Prepaid

Investment Based

Investment → Sales → ROI Recovery

---

### Postpaid

Commission Based

Campaign → Sales → Commission → Settlement

---

## Append-only Financial Records

Historical financial records are never modified.

Corrections are recorded as new transactions instead of overwriting history.

---

## Role Based Access

Different dashboards and permissions exist for:

- Administrators
- Sales Representatives
- Management

---

## Analytics Engine

Business reports are generated directly from transactional data rather than manually maintained summary tables.
