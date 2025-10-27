# 🌦️ Joe – AI Weather Prediction System Design and Prototype

**Type:** Individual Project (COMP 248 – AI System Design)  
**Author:** Tesneem Awut 
**Date:** September 2025  

---

## 🧩 Overview
**Joe** is a scalable AI system designed to integrate heterogeneous weather data sources and prepare them for predictive analysis.  
It unifies historical and forecast data through an **ETL (Extract, Transform, Load)** pipeline to enable **24-hour temperature forecasting**.

---

## 🧠 Problem Statement
Traditional weather models often rely on isolated datasets.  
Joe solves this by combining:
- **Environment & Climate Change Canada (ECCC)** historical data  
- **Open-Meteo API** forecast data  

These are transformed into a unified structured dataset suitable for machine learning prediction tasks.

---

## 🔧 System Design
The system includes:
1. **Data Ingestion Component** – extracts data from ECCC and Open-Meteo sources  
2. **Data Transformation Component** – cleans, merges, and aligns date/time inconsistencies  
3. **Data Loading Component** – prepares the processed dataset for the prediction engine
   

### 🧱 Architecture Diagram
<img width="916" height="412" alt="image" src="https://github.com/user-attachments/assets/04bd86e8-5184-466a-8cc2-e6600dbc9dec" />


## 🧰 Tools & Technologies
| Category | Tools Used |
|-----------|-------------|
| Language | Python |
| Libraries | Pandas, Requests |
| Design | Visio / PowerPoint |
| Data Sources | ECCC CSV, Open-Meteo API |
| IDE | Anaconda |

---

## 📊 Prototype
A lightweight Python prototype demonstrates the ETL pipeline — from data extraction and transformation to generating a unified dataset.

---

## 🎥 Demonstration
A short recorded demo explains the system workflow, components, and design rationale.  

## 📄 Documentation
| File | Description |
|------|--------------|
| `Analysis_Report.pdf` | Detailed design analysis and component explanation |
| `Component_Diagram` | Component-level diagrams |
| `Architecture Diagram` | System Architecture diagrams |
| `Prototype_Script.py` | Python code implementing the ETL prototype |
| `WeatherData_ECCC.csv` | Historical dataset |
| `OpenMeteo_API_Sample.csv` | Forecast dataset |

---

## 🧩 Learning Outcome
This project demonstrates:
- Data model and architecture design for AI systems  
- Building an ETL pipeline for heterogeneous sources  
- Applying data cleaning and transformation techniques  
- Explaining design trade-offs and component interactions

---
## 👩‍💻 Author
**Tesneem Awut**  
AI & Software Engineering Technology, Centennial College  

