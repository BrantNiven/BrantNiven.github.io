# BrantNiven.github.io
# Brant M. Niven
### Data Analyst | Business Intelligence | Revenue & Marketing Analytics

📍 Chicago, IL  
📊 Analytics professional focused on transforming operational and marketing data into actionable insights.

---

## About Me
I am a Data Analyst specializing in revenue and marketing analytics across large, multi-property real estate portfolios.

A core strength of my work is **unifying fragmented data across multiple systems and sources** — including ILS platforms, internal leasing data, marketing expenses, and operational reports — into standardized, reusable analytical models.

I focus on:
- Normalizing inconsistent schemas and definitions
- Aligning time series and multi-year datasets
- Building single-source-of-truth tables that support funnels, forecasting, and ROI analysis

My work enables leadership teams to move from siloed reports to cohesive, decision-ready insights.

Tools I regularly use include **Excel (Power Query & advanced formulas), SQL Server, Python, and BI / Looker dashboards**

---

## 🔍 Featured Project: LTA Explorer (Leads → Tours → Applications)

**LTA Explorer** is an end-to-end analytics framework designed to unify multiple data streams across the leasing funnel and transform them into actionable performance insights.

### What This Project Does
- Integrates **Leads, Tours, Applications, and Marketing Expenses** into a single analytical model  
- Normalizes inconsistent source naming, property identifiers, and timelines  
- Enables **true funnel conversion analysis** across channels, properties, and years  
- Calculates **cost-per-lead, cost-per-tour, and cost-per-application** using blended expense data  

### Key Capabilities
- Multi-source ingestion (ILS platforms, internal systems, manual feeds)
- Cleaned and standardized dimensions (source, property, date, year)
- Funnel metrics:
  - Leads → Tours
  - Tours → Applications
- Spend efficiency metrics:
  - $ / Lead
  - $ / Tour
  - $ / Application
- Year-over-year and source-level performance comparisons

### Tools & Stack
- **SQL Server** — core data modeling and joins  
- **Excel / Power Query** — transformation, normalization, and QA  
- **Looker Studio** — interactive dashboards and reporting  
- **Mapping Tables** — source and property standardization  

### Outcome
LTA Explorer replaces static, siloed reporting with a unified analytics layer that supports:
- Marketing ROI evaluation
- Channel optimization
- Property-level performance diagnostics
- Executive-ready dashboards

-<img width="1920" height="1080" alt="LTA - Explorer" src="https://github.com/user-attachments/assets/2e1c1efa-593c-4f91-8b20-fdf00030a856" />

-<img width="1920" height="1080" alt="LTA - Explorer 2" src="https://github.com/user-attachments/assets/5ebf9ebd-2891-4449-b41e-949b06486a2f" />

---
## 🏢 Vacancy Forecasting Engine (4-Week Forward)

### Overview
The **Vacancy Forecasting Engine** is a forward-looking occupancy model built to replace static vacancy snapshots with a **unit-level, rolling 4-week forecast**.

Rather than reporting vacancy at a single point in time, this system predicts **future availability by property and date**, enabling proactive leasing, staffing, and marketing decisions.

---

### Core Concept
Vacancy is modeled at the **individual unit level**, treating each unit as a time-based record with upcoming state changes.

This approach allows vacancy to be **calculated dynamically**, instead of relying on a single Rent Manager vacancy export.

---

### Data Sources (Rent Manager)
The model unifies multiple operational reports exported from Rent Manager:

- **Move-Outs** — confirmed and scheduled unit departures  
- **Move-Ins** — future occupancy commitments  
- **Lease Renewals** — renewal status and effective dates  
- **Lease Expirations** — upcoming exposure risk  

Each report is normalized and merged into a single **Unit Tracker**.

---

### Individual Unit Tracker
Every unit is represented as a unique record with:
- Property and unit identifiers  
- Key lease dates (expiration, renewal, move-in, move-out)  
- Status flags used to determine future vacancy  

This structure allows vacancy to be calculated **by date**, not just by unit count.

---

### Vacancy Forecast Logic
Using the unit tracker, vacancy is projected across a **4-week horizon** by evaluating each unit’s expected state on specific future dates.

Forecast dates are standardized to:
- Weekly checkpoints (e.g., Thursdays)
- Rolling forward automatically as new data is ingested

The output answers:
- How many units are vacant **now**
- How many units will be vacant **1–4 weeks out**
- Where upcoming exposure exists before it appears in traditional reports

---

### Automation & Refresh
- Data refreshes **weekly (every Thursday)**
- Forecast windows shift forward automatically
- No manual intervention required after setup

---

### Tools & Stack
- **Google Sheets / Excel** — unit-level modeling and forecast logic  
- **Power Query** — data normalization and joins  
- **Rent Manager exports** — source system  
- **Looker Studio** — visualization and distribution  

---

### Outcome
This framework transforms vacancy reporting from:
- ❌ Static, backward-looking counts  
- ✅ Dynamic, forward-looking forecasts  

Key benefits:
- Improved leasing prioritization  
- Earlier visibility into vacancy risk  
- Executive-ready forecasting views  
- Scalable across properties and portfolios
---

## Core Skills
- Excel (Advanced formulas, Power Query, Pivot Tables)
- SQL Server (Data modeling, joins, transformations)
- Funnel & Conversion Analysis
- Marketing ROI & Performance Attribution
- Data Normalization & QA
- Dashboard Design & Executive Reporting

-<img width="1920" height="1080" alt="Vacancy Forecaster" src="https://github.com/user-attachments/assets/87476ece-c578-4bd0-9469-862a1fdf4af0" />


---

## Contact
- 📧 Email: nivenbrant@gmail.com  
- 💼 LinkedIn: https://www.linkedin.com/in/brant-niven/ 
- 🧠 GitHub: https://github.com/BrantNiven
