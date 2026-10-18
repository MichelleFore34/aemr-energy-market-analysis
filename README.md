# AEMR Energy Market Analysis – SQL Operational Audit & PowerPoint Data Story

## ⚡ Project Overview
The American Energy Market Regulator (AEMR) is responsible for managing grid stability, reliability, and market efficiency. Recently, the energy market has faced an increase in unexpected power outages and forced energy grid shutdowns. 

This project delivers an end-to-end analytics solution requested by the AEMR Management Team. First, a comprehensive **operational audit was conducted using SQL within a Jupyter Notebook** to dissect historical outage logs. Second, these backend database findings were translated into a **strategic executive presentation in PowerPoint**, providing leadership with clear, non-technical paths toward safeguarding grid stability and minimizing economic energy losses.

## 🔗 Project Links & Assets
*   👉 **[View the Executive Presentation Here](https://docs.google.com/presentation/d/1d1wLk8-K-K-MDlFoAZHyRFpMpBlIRCOeIfbByZkAJW8/edit?usp=sharing)**
*   📁 **[Open the SQL Analytics Jupyter Notebook](Aemr Case Study - SQL Project Complete.ipynb)**

---

## 🛠️ Tech Stack & Advanced Skills
*   **Database Querying & Optimization:** SQL (Using `%%sql` magics in Python to query the AEMR relational database).
*   **Core SQL Techniques:** Common Table Expressions (CTEs), Subqueries, Multi-table Joins, Aggregations, Case Statements, and Window Functions.
*   **Data Visualization & Strategic Storytelling:** Tableau Public (Executive Story Points, interactive parameter filters, KPI cards).
*   **Analytical Frameworks:** Problem decomposition using Issue Trees to map grid failures back to high-level strategic themes (Energy Stability vs. Energy Losses).

---

## 🔍 Strategic Analysis Framework (Issue Tree Approach)
The analysis answers core stakeholder mandates and expands into advanced trend patterns:

### Theme 1: Energy Grid Stability (Outage Frequency & Approvals)
*   **Chronological Volatility:** Contrasting monthly outage types across 2016 vs. 2017 to isolate structural grid improvements or degrading infrastructure.
*   **Operational Governance:** Auditing the ratio of approved outages against canceled events to assess planning efficiency.
*   **Qualitative Diagnostics:** Extracting text-mining insights from engineering logs to pinpoint the most common specific machinery or description failures.

### Theme 2: Energy & Financial Losses (Impact Auditing)
*   **Participant Performance:** Ranking market participants to identify the "chronic offenders" driving the highest duration of grid downtime.
*   **Loss Disconnection Analysis:** Cross-referencing **Energy Losses (MW)**, **Outage Durations**, and **Outage Frequencies** to determine if separate market players dominate different risk vectors.

---

## 📁 Repository Structure
*   `Aemr Case Study - SQL Project Complete.ipynb` — Jupyter Notebook containing the 10-part SQL diagnostic exercise and deep-dive queries.
*   `temp_db_file.db` — The relational database file containing historical provider metrics and grid event logs.
*   `README.md` — Strategic executive portfolio brief.

---
*Created by Michelle Fore. Connect with me on LinkedIn(https://www.linkedin.com/in/michellemajorfore/).
