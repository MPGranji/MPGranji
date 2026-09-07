# Hi, I'm Quoc Cuong

I'm a Software Engineering student in the High-Quality Program (K48) at Can Tho University, with a current GPA of 3.69.

My main interests are Data Analytics and Data Engineering. I enjoy building ETL pipelines, streaming systems, lakehouse platforms, BI dashboards, and data-driven applications. I also build React Native mobile/admin applications in private projects.

## What I'm Working Toward

- Data Analytics and BI reporting
- Data Engineering pipelines and orchestration
- Customer 360 and lakehouse architecture
- Backend and data-driven application development
- React Native mobile application development
- CI/CD and deployment automation

## Tech Stack

- **Languages & Data:** Python, SQL, TypeScript, JavaScript, PySpark, Spark SQL, Pandas
- **Data Platforms & BI:** Kafka, Airflow, Iceberg, Power BI, Apache Superset
- **Applications:** React Native, Expo, React, Vite, Socket.IO
- **Infrastructure:** AWS EC2, Docker Compose, Git, GitHub Actions

## Featured Projects

### Retail Banking Customer 360 Lakehouse

[Repository](https://github.com/MPGranji/retail-banking-customer360-lakehouse) | [Project report](docs/Bao_cao_Customer_360_Lakehouse_Banking.pdf)

- Built an end-to-end Spark-Iceberg lakehouse across Bronze, Silver, Gold, and Sandbox layers, integrating 1.3M+ records from 10 Oracle and PostgreSQL tables into daily Customer 360 marts for 10,000 retail banking customers.
- Implemented 4 SCD Type 2 dimensions, 19 data-quality gates, PII-masked access through Trino RBAC, and Airflow orchestration; delivered RFM, churn-risk, cross-sell, and Next Best Offer analytics in Superset.

### Customer 360 Behavioral Analytics

[Repository](https://github.com/MPGranji/etl-customer-360-behavioral-analytics)

- Built PySpark and Spark SQL pipelines for two telecom data streams: JSON content-viewing logs and Parquet search logs, analyzing 1.92M contracts and publishing Customer 360 datasets to MySQL and Power BI.
- Profiled viewing behavior through activity levels, most-watched content, and user tastes; classified monthly search interests with GPT-4o-mini and window functions, finding that 69.13% of users changed their primary category between June and July.

### Recruitment Data Platform

[Repository](https://github.com/MPGranji/project_de-recruitment)

- Built a Lambda-style recruitment data platform combining Kafka and Spark Structured Streaming for schema-validated event ingestion into Cassandra with Airflow-orchestrated PySpark batches to MySQL.
- Implemented high-watermark incremental processing, job and company metadata enrichment, and hourly job/publisher KPIs for recruitment interaction analytics and BI reporting.

### Mobile E-commerce App with Virtual Fitting & Recommendations

[Repository](https://github.com/bloodthirster2510/fashion-ecommerce-system) | [Project report](docs/fashion-ecommerce-mobile.pdf)

- Developed the customer mobile application with React Native and Expo, connecting product discovery and recommendations with virtual fitting, checkout, VNPay, and order tracking.
- Built the React and TypeScript web admin for 8 operational areas, including catalog, inventory, orders, customers, promotions, support, virtual fitting, and recommendation reporting.
- Deployed the Docker Compose stack to AWS EC2 with GitHub Actions quality gates, health checks, and automatic rollback. Collaborative project; owned mobile, web admin, and deployment.

## Contact

[vpqcuong@gmail.com](mailto:vpqcuong@gmail.com)
