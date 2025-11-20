# 🟩 Cloud Analytics Platform (ETL + FastAPI + Streamlit) — README.md

## ☁️ Cloud-Based Sales & Inventory Intelligence Platform

A cloud-ready analytics system featuring an ETL pipeline, forecasting API, and interactive dashboard.

### 🔍 What This Project Does

* Cleans & processes **1,000+ sales records**
* Generates KPIs (revenue, top products, stock levels)
* Sends data to **FastAPI microservices**
* Displays insights in a **Streamlit dashboard**
* Designed for **Azure deployment**

### 🛠 Tech Stack

* **Python:** Pandas, NumPy
* **API:** FastAPI
* **Cloud:** Azure App Service
* **Dashboard:** Streamlit
* **Database:** SQL / CSV

## 📡 Architecture Overview

<img width="850" height="699" alt="Screenshot 2025-11-20 at 8 37 31 PM" src="https://github.com/user-attachments/assets/d5d6d3ce-7bbe-4248-bd7f-f3946782e0ad" />

**_System architecture of the Cloud-Based Sales Intelligence Platform. Azure Functions handle data ingestion, FastAPI manages processing, and Streamlit powers the analytics dashboard._**

### 📁 Folder Structure

```
/etl
   └── pipeline.py
/api
   ├── main.py
   └── forecast.py
/dashboard
   └── app.py
```
### ☁️ Deployment (Azure)

* Azure App Service (API hosting)
* Azure Storage (data files)
* Streamlit Cloud or Azure Container Apps (dashboard)

### 📌 Future Improvements

* Add Docker containerisation
* Add CI/CD (GitHub Actions)
* Migrate to Azure SQL Database
* Add authentication for the dashboard
