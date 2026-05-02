# Saudi Port Real Projects — Complete Guide

---

## Minimum কতটা লাগবে?

```
Minimum = 5 টা (কিন্তু quality হতে হবে)
Ideal   = 7-8 টা
Maximum = 10 টা (এর বেশি দরকার নেই)

Quality > Quantity
একটা ভালো project = পাঁচটা খারাপ project
```

---

## Project List — Priority অনুযায়ী

---

### 🔴 Project 1 — Vessel Arrival & Berth Management System
**সবচেয়ে important — এটা ছাড়া portfolio incomplete**

- [ ] Vessel registration (name, IMO number, flag, type)
- [ ] Arrival/departure date & time tracking
- [ ] Berth allocation system (কোন berth খালি, কোনটা occupied)
- [ ] Vessel status (expected, arrived, berthed, departed)
- [ ] Search & filter by date, vessel name, status
- [ ] Berth occupancy calendar view
- [ ] Print/export daily vessel report
- [ ] Mobile responsive dark theme
- [ ] Tech: Node.js + Express + SQLite + HTML/CSS/JS

---

### 🔴 Project 2 — CF Agent Billing & Wharfrent Calculator
**তোমার portbill.vercel.app-এর advanced version**

- [ ] CF agent registration & profile
- [ ] Cargo entry (type, quantity, vessel link)
- [ ] Free period calculation (7 days automatic)
- [ ] Daily wharfrent auto-calculate after free period
- [ ] Multiple cargo types (container, bulk, general, vehicle)
- [ ] Different rates per cargo type
- [ ] Invoice generation with print button
- [ ] Overdue alert (cargo নিয়ে দেরি হলে)
- [ ] Payment status tracking (paid/unpaid/partial)
- [ ] Monthly revenue summary
- [ ] Tech: Node.js + Express + SQLite + HTML/CSS/JS

---

### 🔴 Project 3 — Port Operations Dashboard
**Saudi interview-এ সবচেয়ে বেশি impress করবে**

- [ ] Real-time vessel count (today arrived, berthed, departed)
- [ ] Berth utilization percentage (chart)
- [ ] Revenue today / this week / this month (chart)
- [ ] Top 5 CF agents by cargo volume
- [ ] Overdue cargo alerts list
- [ ] Cargo type breakdown (pie chart)
- [ ] Last 7 days vessel traffic (bar chart)
- [ ] Quick action buttons (add vessel, new billing)
- [ ] Auto-refresh every 5 minutes
- [ ] Tech: Node.js + Express + SQLite + Chart.js

---

### 🟡 Project 4 — Cargo Manifest Management System
**Saudi customs process directly relate করে**

- [ ] Cargo manifest upload & entry
- [ ] Consignee information (importer details)
- [ ] Cargo description, HS code, quantity, weight
- [ ] Manifest status (pending, cleared, released)
- [ ] Link cargo to vessel & CF agent
- [ ] Customs clearance date tracking
- [ ] Dwell time calculation (arrival to clearance)
- [ ] Overdue manifest alert (7+ days not cleared)
- [ ] Search by consignee, vessel, cargo type
- [ ] Export manifest list to CSV
- [ ] Tech: Node.js + Express + SQLite + HTML/CSS/JS

---

### 🟡 Project 5 — Port Staff & Shift Management
**HR + Operations একসাথে**

- [ ] Staff registration (name, designation, department)
- [ ] Shift schedule creation (morning/afternoon/night)
- [ ] Daily attendance marking
- [ ] Overtime calculation
- [ ] Department-wise staff list
- [ ] Today's on-duty staff quick view
- [ ] Shift swap request system
- [ ] Monthly attendance report
- [ ] Tech: Node.js + Express + SQLite + HTML/CSS/JS

---

### 🟡 Project 6 — Port Maintenance & Equipment Tracker
**Saudi port-এ equipment management critical**

- [ ] Equipment registration (crane, forklift, vehicle)
- [ ] Maintenance schedule (next service date)
- [ ] Maintenance history log
- [ ] Equipment status (operational, under maintenance, breakdown)
- [ ] Alert system (service due in 7 days)
- [ ] Breakdown report submission
- [ ] Spare parts inventory basic tracking
- [ ] Monthly maintenance cost report
- [ ] Tech: Node.js + Express + SQLite + HTML/CSS/JS

---

### 🟢 Project 7 — Saudi Port KPI Analytics Dashboard
**Management level-এ present করার জন্য**

- [ ] Monthly vessel throughput trend (line chart)
- [ ] Average dwell time by cargo type (bar chart)
- [ ] Revenue growth month over month
- [ ] CF agent performance ranking
- [ ] Berth utilization rate over time
- [ ] Cargo clearance time average
- [ ] Compare current month vs last month
- [ ] Date range filter
- [ ] PDF report export
- [ ] Tech: Node.js + Chart.js + jsPDF

---

### 🟢 Project 8 — Port Document Management System
**Saudi-তে documentation খুব important**

- [ ] Document upload (PDF, image)
- [ ] Document categories (vessel, cargo, compliance, HR)
- [ ] Document expiry tracking (certificate, license)
- [ ] Expiry alert (30 days before)
- [ ] Search by document name, category, date
- [ ] Document version history
- [ ] Access by department
- [ ] Tech: Node.js + Express + SQLite + Multer

---

## কোনটা আগে করবে — Priority Order

```
① Vessel Arrival System     ← Phase 4-এ করো
② CF Agent Billing          ← Phase 4-এ করো (তোমার base already আছে)
③ Operations Dashboard      ← Phase 4-5-এ করো
④ Cargo Manifest            ← Phase 6-এ করো
⑤ Staff Management          ← Phase 6-এ করো
⑥ Equipment Tracker         ← Phase 7-8-এ করো
⑦ KPI Analytics             ← Phase 8-9-এ করো
⑧ Document Management       ← Phase 9-এ করো
```

---

## প্রতিটা Project-এ Must থাকতে হবে

- [ ] Live URL (Vercel/Railway deploy)
- [ ] GitHub repo with README
- [ ] Screenshot in README
- [ ] "Saudi Port Connection" section in README
- [ ] Mobile responsive
- [ ] No console errors
- [ ] Dummy data pre-loaded (demo করার জন্য)

---

## Interview-এ এই ৩টা দেখালেই হবে

```
Project 1 → Vessel Arrival System
Project 2 → CF Agent Billing (already আছে — upgrade করো)
Project 3 → Operations Dashboard

এই ৩টা strong হলে Saudi interviewer impress হবেই।
বাকিগুলো bonus।
```

---

## README Template — প্রতিটা Project-এ Use করো

```markdown
# Project Name

## 🚢 Saudi Port Connection
[এই project Saudi port-এ কীভাবে use হবে — 2-3 lines]

## Features
- Feature 1
- Feature 2

## Tech Stack
- Node.js + Express
- SQLite
- HTML/CSS/Vanilla JS

## Live Demo
[Vercel/Railway URL]

## Screenshots
[Add screenshots here]

## Setup
git clone [repo]
npm install
npm start
```

---

## Salary Impact — Project Quality অনুযায়ী

| Portfolio Strength | Expected Starting Salary (Saudi) |
|-------------------|----------------------------------|
| 3 weak projects | SAR 6,000–7,000/month |
| 5 average projects | SAR 8,000–10,000/month |
| 5 strong projects | SAR 10,000–13,000/month |
| 7-8 strong projects | SAR 13,000–18,000/month |

---

_MD. Samiul Alam Sumel | Saudi Arabia Port IT Roadmap 2027 Q2_
_github.com/samiulAsumel | Mongla Port Authority — 12 Years Experience_
