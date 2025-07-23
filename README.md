# 🚗 Customer 360 Data Platform – Azure Data Engineering Project

## 📌 Project Overview

This project simulates a real-time **Customer 360 Data Platform** for an **automobile dealership network**, designed to showcase data engineering skills using **Azure technologies**. It follows an enterprise-style pipeline architecture built using:

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS)
- Databricks (PySpark)
- Delta Lake
- GitHub (Version Control)

The goal is to integrate customer, vehicle, service, and finance data into a unified data platform enabling powerful business analytics and insights.

---

## ⚙️ Tools & Technologies

| Component | Technology Used |
|----------|------------------|
| Ingestion | Azure Data Factory |
| Storage | Azure Data Lake Gen2 (Bronze, Silver, Gold layers) |
| Transformation | Databricks (PySpark) |
| Format | Delta Lake |
| Version Control | GitHub |
| Orchestration | ADF Pipelines & Triggers |

---

## 🎯 Key Objectives

- Build and manage data pipelines using ADF
- Perform transformations with PySpark in Databricks
- Implement **Bronze → Silver → Gold** architecture
- Enable **schema evolution**, **partitioning**, **error handling**
- Implement **SCD Type 1 / Type 2**, **window functions**, **time travel**
- Practice **real-time project flow** and best practices

---

## 🔍 Real-World Relevance

Though this is a **self-initiated lab project**, it is based on actual architecture patterns used by enterprises.  
This project is created to **demonstrate real-time Azure Data Engineering capabilities** for interviews and portfolio.

---

## 📂 Project Structure

```bash
project/
│
├── Bronze_Layer/        # Raw data from CSVs to Delta tables
├── Silver_Layer/        # Cleaned & Joined Delta tables
├── Gold_Layer/          # Aggregated_
