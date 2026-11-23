# Hi, I'm Quoc Cuong

<p align="center">
  <a href="https://mpgranji.github.io/"><img src="assets/portfolio-banner.svg" width="100%" alt="Analytics Engineer and Software Engineering student at Can Tho University. View my portfolio."></a><br>
  <a href="https://mpgranji.github.io/">Portfolio</a> · <a href="https://www.linkedin.com/in/vuong-phan-quoc-cuong-31875b451/">LinkedIn</a>
</p>

I'm a Software Engineering student in the High-Quality Program (K48) at Can Tho University, with a current GPA of 3.69.

I focus on analytics engineering, with hands-on experience building ETL pipelines, streaming systems, lakehouse platforms, and BI dashboards. For my graduation thesis, I built the React Native fashion shopping app, including product discovery, recommendations, virtual fitting, checkout, and order tracking. I also contributed to the web admin and deployment.

## Internship Experience

**SonDoong Labs** | *Aug–Nov 2026*

### Kalotoys WMS

[Download report](https://raw.githubusercontent.com/MPGranji/MPGranji/main/docs/Report_Kalotoys_WMS.pdf) | [Demo (sample data)](https://kalotoys-wms.vercel.app/tong-quan)

- Built a Next.js and MongoDB warehouse management system for a wooden educational toy manufacturer to track material receipts, issues to production, transfers, and stock by storage location.
- Integrated Power BI dashboards to monitor stock levels and inventory movements.

### Hotel Digital

[Download report](https://raw.githubusercontent.com/MPGranji/MPGranji/main/docs/Report_hotel_VPQC.pdf) | [Demo (sample data)](https://hotel-digital.vercel.app/)

- Built a front-desk system for one branch of a three-branch hotel group, covering reservations, check-in, early checkout, and payments. Deployed the backend on Azure App Service with Azure SQL Database.
- Analyzed booking records collected at that branch from June to October 2024. Occupancy averaged 46.22% and fell to 17.83% in October. The analysis informed a proposal to raise direct booking rates and keep online rates steady.

## Featured Projects

### Retail Banking Customer 360 Lakehouse

*Jul 2026* | [Repository](https://github.com/MPGranji/retail-banking-customer360-lakehouse) | [Download report](https://raw.githubusercontent.com/MPGranji/MPGranji/main/docs/Bao_cao_Customer_360_Lakehouse_Banking.pdf)

- Built an end-to-end Spark-Iceberg lakehouse across Bronze, Silver, Gold, and Sandbox layers, integrating 1.3M+ records from 10 Oracle and PostgreSQL tables into daily Customer 360 marts for 10,000 retail banking customers.
- Implemented four SCD Type 2 dimensions, masked PII with access controlled through Trino RBAC, and orchestrated the pipeline in Airflow. The acceptance run passed all 19 data quality checks. Delivered RFM, churn-risk, cross-sell, and Next Best Offer analytics in Superset.

### Customer 360 Behavioral Analytics - Telecom Content Viewing and Search

*Dec 2025* | [Repository](https://github.com/MPGranji/etl-customer-360-behavioral-analytics) | [Download report](https://raw.githubusercontent.com/MPGranji/MPGranji/main/docs/Customer_360_Behavioral_Analytics.pdf) | [Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGZmMGY1ZDktM2JlZC00YzAwLTg1YjUtNzhkY2RkMWZmZWExIiwidCI6IjZhYzJhZDA2LTY5MmMtNDY2My1iN2FmLWE5ZmYyYTg2NmQwYyIsImMiOjEwfQ%3D%3D)

- Built PySpark and Spark SQL pipelines for two telecom datasets: JSON content-viewing logs and Parquet search logs, analyzing 1.92M contracts and publishing Customer 360 datasets to MySQL and Power BI.
- Profiled viewing behavior by activity level and most-watched content. Used window functions and GPT-4o-mini to identify each user’s primary search genre. Of the 86,172 users active in both periods (June 1–14 and July 1–14, 2022), 69.13% changed their primary genre.

### Recruitment Data Platform

*May 2026* | [Repository](https://github.com/MPGranji/project_de-recruitment) | [Download report](https://raw.githubusercontent.com/MPGranji/MPGranji/main/docs/recruitment.pdf)

- Built a Lambda-style recruitment data platform combining Kafka and Spark Structured Streaming for schema-validated event ingestion into Cassandra with Airflow-orchestrated PySpark batches to MySQL.
- Implemented high-watermark incremental processing, job and company metadata enrichment, and hourly job/publisher KPIs for recruitment interaction analytics and BI reporting.

### Mobile E-commerce App with Virtual Fitting & Recommendations

*Aug 2026* | [Repository](https://github.com/phatdat2510/fashion-ecommerce-system) | [Download report](https://raw.githubusercontent.com/MPGranji/MPGranji/main/docs/fashion-ecommerce-mobile.pdf) | [Mobile App Demo](https://www.youtube.com/watch?v=jNOUzghrpYM) | [Web Admin Demo](https://youtu.be/h9GcLePPjQY)

- Developed the customer mobile application with React Native and Expo, connecting product discovery and recommendations with virtual fitting, checkout, VNPay, and order tracking.
- Built six React and TypeScript web admin areas for customers, roles, orders, support, search and recommendation analytics, and try-on management.
- Deployed the Docker Compose stack to Amazon Lightsail with GitHub Actions quality gates, health checks, and automatic rollback.

## Tech Stack

- **Languages & Data:** Python, SQL, TypeScript, JavaScript, PySpark, Spark SQL, Pandas
- **Data Engineering:** Kafka, Airflow, Iceberg
- **Databases:** MySQL, PostgreSQL, Azure SQL Database, MongoDB, Cassandra
- **Business Intelligence:** Power BI, Apache Superset
- **Applications:** React Native, Expo, React, Vite, Socket.IO
- **Infrastructure:** Docker Compose, Git, GitHub Actions

## Contact

[Portfolio](https://mpgranji.github.io/) | [LinkedIn](https://www.linkedin.com/in/vuong-phan-quoc-cuong-31875b451/) | [GitHub](https://github.com/MPGranji) | [vpqcuong@gmail.com](mailto:vpqcuong@gmail.com)
