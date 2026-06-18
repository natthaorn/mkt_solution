# E-commerce Marketing Performance & CRM Monetization Analytics

[![Tableau](https://img.shields.io/badge/Tableau-Public-Main?style=for-the-badge&logo=tableau&logoColor=white&color=E97627)](URL_LINK_TABLEAU_YOURS)
[![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white)](data_simulation.py)
[![SQL](https://img.shields.io/badge/SQL-SQLite%20%2F%20Postgres-blue?style=for-the-badge&logo=sqlite&logoColor=white)](marketing_logic.sql)

---

## 📌 Project Overview & Business Challenge
In the e-commerce ecosystem, brands and merchants heavily rely on **Sponsored Solutions** (in-app advertising) to drive traffic and sales. However, regional commercial teams and Key Account Managers (KAMs) often lack an integrated tool to monitor ad performance across product categories alongside platform monetization metrics. 

### Objectives:
*   Develop an end-to-end automated data pipeline on a macOS environment to eliminate manual report consolidation.
*   Engineered optimized database structures to enforce data governance and guarantee data accuracy.
*   Deliver an interactive Tableau dashboard providing actionable insights for business leaders and KAMs to optimize ad solutions and maximize platform monetization.

---

## 🛠️ Tech Stack & Architecture
*   **Data Cleansing & Simulation:** `Python 3.11` (Pandas, NumPy) used to generate and validate 1,000+ rows of marketing records[cite: 2].
*   **Data Pipeline & Logic Engineering:** `SQL (SQLite)` utilized to build robust relational architecture and pre-calculate metrics[cite: 1, 2].
*   **Business Intelligence:** `Tableau Public` for building dynamic, high-performance executive dashboards[cite: 1, 2].

---

## 🗄️ Data Pipeline & Logic Engineering (SQL)
To adhere to data governance standards and minimize computation loads on the BI layer, core business logic and marketing KPIs were pre-engineered at the database layer using **SQL Views**:
