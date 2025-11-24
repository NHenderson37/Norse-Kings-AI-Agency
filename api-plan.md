# Norse Kings AI — API Plan

## 🛠 Architecture
- Node.js backend
- Python micro-services for AI
- REST + Webhook triggers
- Google Sheets API for data sync
- Stripe API for billing

---

## 🔑 Endpoints (Planned)
### `/api/creators`
- GET: list creators
- POST: add creator
- PATCH: update tier or status

### `/api/analytics`
- GET: pull analytics data
- POST: update new metrics

### `/api/ideas`
- POST: generate ideas
- POST: generate scripts

### `/api/reports`
- POST: send weekly report
- GET: fetch past reports

### `/api/trends`
- GET: latest trends
- POST: update trend database

---

## ⚙️ Webhooks
- Stripe subscription updates
- Daily cron jobs
- Weekly email triggers
