# ⚡ EV Charging Data Pipeline Project

## 🚀 Overview
This project builds an **end-to-end Big Data Pipeline** for analyzing electric vehicle (EV) charging sessions.  
The pipeline automates ingestion, processing, and analysis of charging data using **MySQL, Sqoop, HDFS, Hive, and Airflow**.

---
MySQL → Sqoop → HDFS → Hive → Airflow.
---

ev_charging_pipeline_project/
├── dags/
│ └── # Airflow DAG
├── hive/
│ └── # Hive transformation script
├── mysql/
│ └── # MySQL Setup & Data Load
├── README.md # Project instructions

---


## 🧰 Tech Stack
- **Database:** MySQL  
- **Big Data Tools:** Hadoop (HDFS), Hive, Sqoop  
- **Workflow Orchestration:** Apache Airflow  
- **Language:** Python

---

## 📊 Dataset
Contains **1.2 million** synthetic EV charging sessions:
| Column | Description |
|--------|-------------|
| session_id | Unique session ID |
| station_id | EV charging station ID |
| city | City name |
| start_time | Session start time |
| end_time | Session end time |
| kWh_consumed | Energy consumed |
| cost | Total session cost |
| charger_type | Fast / Slow / UltraFast |

---
