# Hi, I'm Davit Chikvaidze

**Data Engineering & Business Intelligence | Tbilisi, Georgia**

I build data pipelines, SQL warehouses and Power BI reports. My portfolio covers
Python ingestion, PostgreSQL dimensional modeling, Airflow orchestration and
financial analytics, alongside an academic CDC and lakehouse project.

**Open to Data Engineer and BI / Power BI opportunities, remote or in Tbilisi.**

## Featured projects

### [Retail Analytics Platform](https://github.com/David-saytrue/retail-analytics-platform)

An end-to-end portfolio project that turns synthetic sales and returns into
validated financial marts and a Power BI report.

**Python · PostgreSQL · Apache Airflow · SQL · Power BI · Docker · GitHub Actions**

- Preserve source versions and handle duplicate batches, late updates and corrections.
- Build a star schema with historical product costs and partial-return accounting.
- Publish warehouse changes and quality checks in one transaction, with rollback on failure.
- Schedule daily ingestion with Airflow and check replay, recovery and financial reconciliation in CI.
- Explore revenue, gross profit, orders and product performance in a packaged PBIX with editable PBIP source.

The report uses a verified SQL snapshot of synthetic data. Direct PostgreSQL
connector refresh remains unverified; automatic Power BI refresh is not configured.

[Run the demo](https://github.com/David-saytrue/retail-analytics-platform#complete-local-demo-windows--powershell-7)
· [Validation results](https://github.com/David-saytrue/retail-analytics-platform/blob/main/docs/validation.md)
· [CI checks](https://github.com/David-saytrue/retail-analytics-platform/actions)

### [Real-Time CDC + Lakehouse Platform](https://github.com/David-saytrue/data-streaming-diploma)

Bachelor's thesis project: capture changes in PostgreSQL, process them with
streaming SQL and expose an Iceberg lakehouse for analytics.

**PostgreSQL → Debezium → Kafka → Flink → Iceberg / MinIO → Presto / Metabase**

- Bronze CDC tables and a Gold star schema on AdventureWorks data.
- Docker Compose environment with scripts for a CDC demo and latency experiment.
- Airflow-orchestrated Python K-Means customer segmentation.

### [Marketplace Finance Dashboard](https://github.com/David-saytrue/power-bi-wb-finance)

Power BI case combining PostgreSQL facts and spreadsheet dimensions to analyze
marketplace revenue, commissions, logistics, gross profit, ROI and monthly changes.

**Power BI · Power Query (M) · DAX · PostgreSQL · Dimensional modeling**

- Star / snowflake semantic model with single-direction relationships.
- Public M queries, DAX measures, model diagram and report screenshots.
- The working PBIX and source database are private; public files document how to rebuild the model.

### [Sales Dashboard](https://github.com/David-saytrue/power-bi-sales-dashboard)

A compact Power BI case with a downloadable PBIX, web-sourced data, Power Query
joins and DAX measures for revenue, profit, average order value and ABC analysis.

## Skills demonstrated in these projects

- **SQL & modeling:** PostgreSQL, joins, CTEs, window functions, aggregations, star / snowflake schemas.
- **Pipelines & reliability:** Python, ETL, source versioning, idempotent ingestion, data quality checks, transactional publication, Apache Airflow.
- **Business intelligence:** Power BI, Power Query (M), DAX, semantic models, financial KPIs and report reconciliation.
- **Streaming & lakehouse:** Kafka, Debezium, Flink SQL, Iceberg, MinIO, Presto and Metabase in my thesis project.
- **Development tools:** Git, Docker, Docker Compose and GitHub Actions.

## SQL practice

[LeetCode SQL 50 — PostgreSQL solutions](https://github.com/David-saytrue/leetcode-sql50-):
versioned interview practice covering filtering, joins, aggregations and analytical queries.
Current progress is tracked in the repository.

## Contact

- **Email:** [davidsaytrue@gmail.com](mailto:davidsaytrue@gmail.com)
- **GitHub:** [David-saytrue](https://github.com/David-saytrue)
- **Location:** Tbilisi, Georgia
