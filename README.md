# 📘 End-to-End Cloud Data Pipeline (Python, SQL, FastAPI, Azure)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue" />
  <img src="https://img.shields.io/badge/FastAPI-Backend-success" />
  <img src="https://img.shields.io/badge/Streamlit-Dashboard-red" />
  <img src="https://img.shields.io/badge/Azure-Deployment-blueviolet" />
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

## 🚀 Overview

This project is an **end-to-end cloud-ready data pipeline** designed to simulate a real enterprise analytics workflow. It integrates **Python-based ETL**, **SQL transformations**, **FastAPI backend services**, and a **Streamlit analytics dashboard**, all prepared for **Azure cloud deployment**.

This project demonstrates my ability to build production-minded data pipelines suitable for analytics workflows, cloud deployment, and real-time dashboarding at scale.

## ⭐ Features

### ✅ Implemented

* Python ETL pipeline (extraction, validation, transformation)
* SQL schema + transformations
* FastAPI backend with structured API routes
* Streamlit dashboard for data exploration
* Azure-ready project structure for deployment

### 🔧 In Progress

* Azure deployment pipeline
* Authentication for API + dashboard
* Automated scheduled ETL jobs

## 🏗️ Architecture

```
              ┌──────────────────────────┐
              │        Raw Data         │
              └────────────┬────────────┘
                           ↓
               Python ETL (Ingestion, Cleaning)
                           ↓
             ┌──────────────────────────┐
             │       SQL Database       │
             └────────────┬────────────┘
                           ↓
                    FastAPI Backend
                           ↓
                  Streamlit Dashboard
                           ↓
                      Azure Cloud
```

## 📂 Tech Stack

* **Core:** Python, SQL
* **Backend:** FastAPI, Uvicorn
* **Dashboard:** Streamlit
* **Cloud:** Azure (App Services + SQL deployment target)
* **Libraries:** Pandas, Pydantic

## 🖥️ Screenshots (Add your screenshots here)


## 🛠️ Setup

```bash
git clone <repo-url>
cd cloud-pipeline
pip install -r requirements.txt

# Run API
uvicorn main:app --reload

# Run Dashboard
streamlit run dashboard.py
```

## 📌 Future Enhancements

* Full Azure CI/CD
* API rate limiting + caching
* Expanded dashboard analytics

---

