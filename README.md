# 340B-Covered-Entity-Data-Integration-Analytics-Dashboard

## Overview
This project streamlines **340B program data ingestion, storage, and analytics** for a hospital by building an **automated data pipeline** from contracted pharmacies to a **Power BI dashboard** for stakeholders.

## Note: The data used in this dashboard is synthetic and was generated using Python libraries like Pandas and Faker to simulate real-world scenarios.

## 📸 Dashboard Preview  
Here’s a preview of the **Hospital Billing Dashboard**:  

![340B-Covered-Entity-Data-Integration-Analytics-Dashboard](Screenshot.png)
## Key Components

### Data Ingestion
- Developed a **web portal using Python (Flask)** for contracted pharmacies to upload **340B transaction data**.

### Cloud Storage
- Stored uploaded data in **Google Cloud Storage (GCS)**.

### Automation
- Used **Google Cloud Functions (Python)** to trigger **data processing** when new files are uploaded.

### Data Processing
- Created a **master table in BigQuery**, consolidating data from multiple sources.

### Visualization
- Integrated **BigQuery with Power BI** to develop an **interactive dashboard** for hospital stakeholders.

## Technologies Used
- **Programming Language:** Python
- **Web Framework:** Flask
- **Cloud Services:** Google Cloud Storage (GCS), **Google Cloud Functions (Python), BigQuery**
- **BI Tool:** Power BI
- **Database & Querying:** BigQuery SQL

## Outcome
- **Automated data ingestion and processing**, reducing manual intervention.
- **Improved data accessibility and reporting** for hospital stakeholders.
- **Enhanced tracking** of **340B program performance, pharmacy transactions, and compliance metrics**.
