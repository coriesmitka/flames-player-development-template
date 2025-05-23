# 🔥 Flames Player Development – Analytics & Insights Project

This project is a data-driven analysis platform for NHL player development, with a focus on the Calgary Flames. It integrates real-time API data, Power BI dashboards, and machine learning models to study performance growth over time — with future phases comparing men's and women's professional hockey.

---

## 📌 Project Goals

- Extract, normalize, and analyze NHL player data (starting with the Calgary Flames)
- Build Power BI dashboards for trend insights and development tracking
- Compare male and female player trajectories using ML-based growth modeling
- Advocate for gender equity in sports through meaningful, data-backed insights

---

## 📁 Folder Structure
`/data/` – Raw + normalized SQLite schemas & sample exports  
- `/scripts/` – ETL + API loaders, DB maintenance scripts  
  - `/scripts/api/` – NHL & PWHL API integration  
  - `/scripts/maintenance/` – Indexing, cleanup, data validation  
  - `/scripts/star_profiles/` – Spotlight & elite player enrichment  
- `/dashboard/` – Power BI .pbix files and screenshots  
- `/notebooks/` – Exploratory analysis (Jupyter)  
- `/docs/` – ERD diagrams, planning notes, schema references  
- `/.github/workflows/` – GitHub Actions automation (CI/CD)

---

## :clipboard: Project Status

| Epic                            | Component                       | Status     | Notes                                                                 |
|---------------------------------|----------------------------------|------------|-----------------------------------------------------------------------|
| **Epic 1: NHL (Calgary Flames)** | API Ingestion                    | ✅ Complete | Scripts for Roster, Player, Game Logs, Faceoffs, Team Analytics done  |
|                                 | Database Normalization           | ✅ Complete | `api_` vs `core_` structure live                                      |
|                                 | Power BI Dashboard               | 🟡 In Progress | ODBC connection live; report building underway                    |
|                                 | Historical Team Comparisons      | 🟡 In Progress | Stanley Cup team data collection scoped                            |
| **Epic 2: PWHL (Women’s Hockey)** | API Discovery & Validation       | ✅ Complete | Endpoints and keys confirmed                                          |
|                                 | Initial Data Ingestion           | 🟡 In Progress | Team stats and structure under testing                               |
|                                 | Expansion Readiness              | ⏳ Planned   | League growing from 6 to 8 teams; structure to adapt in next phase   |
|                                 | ML Preparation                   | ⏳ Planned   | Data harmonization and metadata strategy coming post-ingestion       |
| **Epic 3: ML Comparison Models** | Player Dev Cross-League          | ⏳ Planned   | Waiting on full PWHL integration                                     |
|                                 | Time-Series Growth Models        | ⏳ Planned   | Focus on growth trajectories (NHL vs. PWHL)                          |
