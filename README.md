# Hi, I'm Quoc Cuong

I'm a Software Engineering student in the High-Quality Program (K48) at Can Tho University, with a current GPA of 3.68.

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

- Engineered a Spark-Iceberg lakehouse processing 1.3M+ synthetic records from 10 Oracle and PostgreSQL tables into governed Customer 360 marts for 10,000 customers.
- Implemented 4 SCD Type 2 dimensions, 19 data-quality checks, PII masking, and Airflow orchestration; delivered Superset views for segmentation and campaign targeting.

### Customer 360 Behavioral Analytics

[Repository](https://github.com/MPGranji/etl-customer-360-behavioral-analytics)

- Processed JSON and Parquet telecom logs for 1.92M contracts with PySpark and Spark SQL, publishing Customer 360 datasets to MySQL and Power BI.
- Classified monthly search interests with GPT-4o-mini and window functions, finding that 69.13% of users changed their primary category between June and July.

### Recruitment Data Platform

[Repository](https://github.com/MPGranji/project_de-recruitment)

- Built a Kafka and Spark Structured Streaming pipeline that validated synthetic recruitment events and persisted checkpointed streams to Cassandra.
- Used Airflow and PySpark to refresh 6 hourly job and publisher KPIs every minute, publishing enriched MySQL tables for recruitment analytics.

### Mobile E-commerce App with Virtual Fitting & Recommendations

[Repository](https://github.com/bloodthirster2510/fashion-ecommerce-system) | [Project report](docs/fashion-ecommerce-mobile.pdf)

- Developed the customer mobile application with React Native and Expo, connecting product discovery and recommendations with virtual fitting, checkout, VNPay, and order tracking.
- Built the React and TypeScript web admin for 8 operational areas, including catalog, inventory, orders, customers, promotions, support, virtual fitting, and recommendation reporting.
- Deployed the Docker Compose stack to AWS EC2 with GitHub Actions quality gates, health checks, and automatic rollback. Collaborative project; owned mobile, web admin, and deployment.

## Contact

[vpqcuong@gmail.com](mailto:vpqcuong@gmail.com)
