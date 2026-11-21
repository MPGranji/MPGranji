# Hi, I'm Quoc Cuong

I'm a Software Engineering student in the High-Quality Program (K48) at Can Tho University, with a current GPA of 3.69.

I focus on data analytics and data engineering, with hands-on experience building ETL pipelines, streaming systems, lakehouse platforms, and BI dashboards. For my graduation thesis, I built a React Native fashion shopping app with virtual fitting and product recommendations, along with a web dashboard for managing products, inventory, and orders.

## Internship Experience

**SonDoong Labs** | *Jun–Nov 2026*

### Kalotoys WMS

[Project report](docs/Report_Kalotoys_WMS.pdf) | [Product demo](https://kalotoys-wms.vercel.app/tong-quan)

- Built a Next.js and MongoDB warehouse management system for a wooden educational toy manufacturer to track material receipts, issues to production, transfers, and stock by storage location.
- Integrated Power BI dashboards to monitor stock levels and inventory movements.

### Hotel Digital

[Project report](docs/Report_hotel_VPQC.pdf) | [Project website](https://hotel-digital.vercel.app/)

- Digitized front-desk operations for a hotel group with three properties rated 3 or 4 stars, covering reservations, check-in, early checkout, and payments. Deployed the backend on Azure App Service with Azure SQL Database.
- Analyzed booking records from June to October to investigate why revenue fell below target. Occupancy averaged 46.22% and fell to 17.83% in October. The analysis informed a proposal to raise direct booking rates and keep online rates steady.

## Featured Projects

### Retail Banking Customer 360 Lakehouse

*Jul 2026* | [Repository](https://github.com/MPGranji/retail-banking-customer360-lakehouse) | [Project report](docs/Bao_cao_Customer_360_Lakehouse_Banking.pdf)

- Built an end-to-end Spark-Iceberg lakehouse across Bronze, Silver, Gold, and Sandbox layers, integrating 1.3M+ records from 10 Oracle and PostgreSQL tables into daily Customer 360 marts for 10,000 retail banking customers.
- Implemented 4 SCD Type 2 dimensions, 19 data-quality gates, PII-masked access through Trino RBAC, and Airflow orchestration; delivered RFM, churn-risk, cross-sell, and Next Best Offer analytics in Superset.

### Customer 360 Behavioral Analytics

*Dec 2025* | [Repository](https://github.com/MPGranji/etl-customer-360-behavioral-analytics) | [Project report](docs/Customer_360_Behavioral_Analytics.pdf) | [Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGZmMGY1ZDktM2JlZC00YzAwLTg1YjUtNzhkY2RkMWZmZWExIiwidCI6IjZhYzJhZDA2LTY5MmMtNDY2My1iN2FmLWE5ZmYyYTg2NmQwYyIsImMiOjEwfQ%3D%3D)

- Built PySpark and Spark SQL pipelines for two telecom datasets: JSON content-viewing logs and Parquet search logs, analyzing 1.92M contracts and publishing Customer 360 datasets to MySQL and Power BI.
- Profiled viewing behavior through activity levels, most-watched content, and user tastes; classified monthly search interests with GPT-4o-mini and window functions, finding that 69.13% of users changed their primary category between June and July.

### Recruitment Data Platform

*May 2026* | [Repository](https://github.com/MPGranji/project_de-recruitment) | [Project report](docs/recruitment.pdf)

- Built a Lambda-style recruitment data platform combining Kafka and Spark Structured Streaming for schema-validated event ingestion into Cassandra with Airflow-orchestrated PySpark batches to MySQL.
- Implemented high-watermark incremental processing, job and company metadata enrichment, and hourly job/publisher KPIs for recruitment interaction analytics and BI reporting.

### Mobile E-commerce App with Virtual Fitting & Recommendations

*Aug 2026* | [Repository](https://github.com/bloodthirster2510/fashion-ecommerce-system) | [Project report](docs/fashion-ecommerce-mobile.pdf) | [Mobile App Demo](https://www.youtube.com/watch?v=jNOUzghrpYM) | [Web Admin Demo](https://youtu.be/h9GcLePPjQY)

- Developed the customer mobile application with React Native and Expo, connecting product discovery and recommendations with virtual fitting, checkout, VNPay, and order tracking.
- Built the React and TypeScript web admin for 8 operational areas, including catalog, inventory, orders, customers, promotions, support, virtual fitting, and recommendation reporting.
- Deployed the Docker Compose stack to Amazon Lightsail with GitHub Actions quality gates, health checks, and automatic rollback. Collaborative project; owned mobile, web admin, and deployment.

## Tech Stack

- **Languages & Data:** Python, SQL, TypeScript, JavaScript, PySpark, Spark SQL, Pandas
- **Data Engineering:** Kafka, Airflow, Iceberg
- **Databases:** MySQL, PostgreSQL, Azure SQL Database, MongoDB, Cassandra
- **Business Intelligence:** Power BI, Apache Superset
- **Applications:** React Native, Expo, React, Vite, Socket.IO
- **Infrastructure:** Docker Compose, Git, GitHub Actions

## Contact

[vpqcuong@gmail.com](mailto:vpqcuong@gmail.com)
