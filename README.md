# 🚗 Customer 360 Data Platform – Azure Data Engineering Project

## 🧾 Overview  
This is a **self-initiated, lab-based simulation** of a real-time **Customer 360 Data Platform** for an automobile dealership network.  
It’s built using end-to-end Azure technologies and designed to showcase enterprise-grade data pipeline skills.

### 🎯 Objective  
Integrate customer, vehicle, service, and financial data to enable business insights such as vehicle ownership trends, service patterns, and segmentation for personalized marketing.

---

## 🛠 Tools & Technologies

| Component         | Technology & Purpose                                  |
|------------------|-------------------------------------------------------|
| Orchestration    | Azure Data Factory — pipelines and scheduling         |
| Data Storage     | ADLS Gen2 — Bronze, Silver, Gold Delta Lake layers    |
| Compute          | Databricks CE with PySpark — data transformations     |
| Table Format     | Delta Lake — schema enforcement & time travel         |
| Version Control  | GitHub — notebooks, pipeline JSON, and documentation  |
| Monitoring       | ADF Monitoring + Delta History                        |

---

## 🗂 Project Structure

```text
azure-data-engineering-customer360/
│
├── Bronze_Layer/              # Raw ingestion outputs (Delta)
├── Silver_Layer/              # Cleaned/joined Delta tables
├── Gold_Layer/                # Aggregated business outputs
├── Notebooks/                 # PySpark notebooks for transformation
├── ADF_Pipelines/             # Exported ADF pipeline JSON files
├── datasets/                  # Sample CSV datasets
├── Interview_QA/              # Q&A markdown files for practice
└── README.md                  # Project documentation
