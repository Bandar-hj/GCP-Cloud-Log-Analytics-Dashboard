# GCP-Cloud-Log-Analytics-Dashboard
An end-to-end cloud log analytics project on Google Cloud Platform using Cloud Logging, BigQuery, and Looker Studio to collect, analyze, and visualize operational logs.
## Architecture Overview
This project implements a centralized log analytics pipeline on Google Cloud Platform. 
Logs generated from cloud resources are collected using Cloud Logging, stored and analyzed in BigQuery, 
and visualized through interactive dashboards in Looker Studio.

---

## Technologies Used
- Google Cloud Platform (GCP)
- Cloud Logging
- BigQuery
- Looker Studio
- Compute Engine (VM)

---

## Project Flow
1. A virtual machine (Compute Engine) generates system and application logs.
2. Logs are collected and centralized using Cloud Logging.
3. Selected logs are exported to BigQuery for analysis.
4. Analytical queries are executed on log data.
5. Dashboards are built in Looker Studio to visualize insights.

---

## Use Cases
- Monitoring system activity and operational health
- Analyzing request volume and error trends
- Understanding usage patterns through log data
- Building a foundation for security and audit analysis

---

## Project Status
🚧 This project is under active development.  
The initial phase focuses on log ingestion and analysis, followed by dashboard creation and optimization.

---

## Author
Bandar Alhujayri
