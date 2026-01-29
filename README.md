# GCP Cloud Log Analytics Dashboard

This project presents a conceptual and architectural implementation of a cloud log analytics pipeline on Google Cloud Platform (GCP).

The goal of the project is to demonstrate how operational logs can be collected, centralized, analyzed, and visualized using native GCP services, following real-world cloud operations and monitoring practices.

---

## Project Overview

The solution is designed around an end-to-end log analytics workflow:

- Cloud resources generate operational and access logs
- Logs are centralized using Cloud Logging
- Selected logs are exported to BigQuery for analytics
- Analytical queries are executed on log data
- Dashboards are built to visualize trends and insights

This repository focuses on the architecture, data flow, and design decisions rather than live infrastructure deployment.

---

## Architecture Design

**Log Sources**
- Compute Engine (VM logs)
- Cloud Run (application access logs)
- External log files (optional)

**Log Collection**
- Cloud Logging acts as the central log aggregation layer

**Analytics Layer**
- BigQuery is used to store and analyze log data at scale

**Visualization**
- Looker Studio dashboards are used to visualize requests, errors, and usage patterns

---

## Project Flow

1. Cloud services emit operational logs
2. Logs are collected and centralized in Cloud Logging
3. Logs are exported to BigQuery using log sinks
4. SQL queries analyze request volume, errors, and trends
5. Dashboards present insights for monitoring and analysis

---

## Use Cases

- Cloud operations monitoring
- Log-based performance analysis
- Error and request trend analysis
- Foundation for security and audit logging

---

## Status

This project is a **design and architecture-focused implementation** intended for learning, documentation, and portfolio demonstration purposes.

---

## Author
Bandar Alhujayri
