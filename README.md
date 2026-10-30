# Hi, I'm Davit 👋

**Data Engineer · BI / Analytics** — Tbilisi, Georgia  
I design **SQL / ETL flows, lakehouses, and Power BI semantic models** — from flat teaching dashboards to star-schema finance reports.

🎓 Bachelor's thesis — **Real-Time CDC + Lakehouse Platform**  
📊 **Power BI** — 2 shipped cases: sales dashboard + marketplace finance (star schema, Postgres + sheets)  
🧩 LeetCode [**SQL 50**](https://github.com/David-saytrue/leetcode-sql50-) — **30 / 50** (PostgreSQL · Easy 22 · Medium 8)  
📍 Open to **Data Engineer / BI Analyst / Analytics Engineer** (remote or Tbilisi)

---

## Featured projects

### [data-streaming-diploma](https://github.com/David-saytrue/data-streaming-diploma)
End-to-end **CDC → Lakehouse → BI / ML** on AdventureWorks:

`PostgreSQL → Debezium → Kafka → Flink → Iceberg @ MinIO → Presto / Metabase`  
(+ Airflow + Python K-Means for batch segmentation)

- Medallion architecture (Bronze + Gold star schema)
- Measured end-to-end latency **~10–14s** (INSERT → Gold)
- Fully runnable with Docker Compose

### [power-bi-wb-finance](https://github.com/David-saytrue/power-bi-wb-finance)
**Marketplace finance** model (interview Stage 2):

- Facts from **PostgreSQL** (Import) + dimensions via `Excel.Workbook(Web.Contents(...))`
- Snowflake: cost & tariffs → nomenclature → facts; `Dim_Date` for MoM
- DAX: WB revenue, commission, logistics, gross profit, ROI, decline/growth leaders
- Screenshots: [model](https://github.com/David-saytrue/power-bi-wb-finance/blob/main/docs/model-star-schema.png) · [dashboard](https://github.com/David-saytrue/power-bi-wb-finance/blob/main/docs/dashboard-owner-report.png)

### [power-bi-sales-dashboard](https://github.com/David-saytrue/power-bi-sales-dashboard)
One-page **sales report**: web-sourced workbook, Power Query merges, DAX KPIs (revenue, profit, logistics, ABC, map, manager losses).

### [leetcode-sql50-](https://github.com/David-saytrue/leetcode-sql50-)
Daily **interview SQL** — Top SQL 50 study plan, PostgreSQL dialect, versioned solutions (**30 / 50**).

---

## Tech I work with

**SQL & modeling:** PostgreSQL · joins / windows / aggregations · dimensional modeling · DBeaver  
**BI:** Power BI · Power Query (M) · DAX · Import mode · star / snowflake · KPI dashboards  
**Streaming / lakehouse:** Apache Kafka · Debezium · Apache Flink · Apache Iceberg · MinIO · Presto · Metabase  
**Orchestration / ML:** Apache Airflow · Python · pandas · scikit-learn  
**Infra:** Docker · Docker Compose · Git

---

## What I'm looking for

- Data Engineer / BI Analyst / Analytics Engineer / Streaming Engineer
- ETL/ELT, SQL, semantic models, dashboards, lakehouse / warehouse
- Ready to grow into production practices (CI/CD, monitoring, cloud)

---

## Contact

- GitHub: [David-saytrue](https://github.com/David-saytrue)
- Email: davidsaytrue@gmail.com
- Location: Tbilisi, Georgia

---

⭐ **Hiring for data or BI?** Start with the [diploma](https://github.com/David-saytrue/data-streaming-diploma) or [WB finance](https://github.com/David-saytrue/power-bi-wb-finance) — both show end-to-end modeling.
