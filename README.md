# 🚗 Customer 360 Data Platform – Automobile Dealership

This project simulates a real-time Customer 360 data analytics platform built for an automobile dealership. It demonstrates how raw customer and vehicle data is ingested, processed, and transformed into business-ready insights using the modern data engineering stack on Azure.

---

## 🛠 Tools & Technologies

| Category          | Technology              |
|------------------|--------------------------|
| Data Ingestion    | Azure Data Factory (ADF) |
| Storage           | Azure Data Lake Storage (ADLS Gen2) |
| Processing        | Azure Databricks (PySpark) |
| Orchestration     | ADF Pipelines            |
| Delta Lake        | Bronze, Silver, Gold architecture |
| Versioning        | GitHub                   |
| Visualization     | Power BI (future scope)  |

---

## 📂 Project Layers

| Layer   | Description |
|---------|-------------|
| Bronze  | Raw data ingestion from CSV files into ADLS using ADF |
| Silver  | Data cleansing, filtering, and business rule application using PySpark |
| Gold    | Aggregated and business-ready data tables stored as Delta tables |

---

## 📁 Project Structure

```text
azure-data-engineering-customer360/
│
├── bronze/                # Raw data stored in Delta format
├── silver/                # Cleaned & transformed data
├── gold/                  # Aggregated, ready-to-consume data
├── notebooks/             # PySpark notebooks (Databricks)
├── adf_pipelines/         # ADF pipeline JSON export files
├── resources/             # Sample source CSV files
└── README.md              # Project documentation
