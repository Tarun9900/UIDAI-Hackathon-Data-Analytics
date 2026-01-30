# UIDAI Data Hackathon Analysis

## 📌 Overview
This repository contains my end-to-end analytical work developed as part of the **UIDAI Data Hackathon 2026**.  
The project focuses on exploratory analysis and visualisation of Aadhaar **enrolment**, **demographic update**, and **biometric update** data to understand lifecycle patterns, geographic distribution, and age-wise trends across India.

---

## 🎯 Problem Statement
Although Aadhaar has achieved wide national coverage, enrolment growth and update activities vary significantly across regions and age groups.  
These variations impact infrastructure planning, resource allocation, and service demand management.

The objective of this study is to:
- Analyse temporal, geographic, and age-wise patterns in Aadhaar enrolments
- Examine demographic and biometric update trends
- Understand Aadhaar lifecycle behaviour using data-driven insights

---

## 🛠️ Tools & Technologies Used
- **Python (Pandas)** – Data consolidation, cleaning, preprocessing
- **Jupyter Notebook** – Exploratory analysis and validation
- **Power BI Desktop** – Data modeling, DAX measures, and dashboard visualisation

---

## 📂 Repository Structure
UIDAI-Data-Hackathon-Analysis/

│

├── README.md

│

├── code/

│ ├── [UIDAI_Data_Combine.ipynb](https://github.com/Tarun9900/UIDAI-Hackathon-Data-Analytics/blob/main/UIDAI_Data_Cleaning.ipynb)

│ └── [UIDAI_Data_Cleaning.ipynb](https://github.com/Tarun9900/UIDAI-Hackathon-Data-Analytics/blob/main/UIDAI_Data_Combine.ipynb)

│

├── dashboards/

│ ├── Aadhaar Enrolments Preview

│ ├── Demographic Updates Preview

│ └── Biometric Updates Preview

│

└── report/

└── [UIDAI_Data_Hackathon_2026_Report.pdf](https://github.com/Tarun9900/UIDAI-Hackathon-Data-Analytics/blob/main/UIDAI_Data_Hackathon_2026_Report.pdf)

---

## 🧠 Methodology
1. **Data Consolidation**  
   - Multiple UIDAI CSV sub-parts were combined into unified datasets using Pandas.

2. **Data Cleaning & Standardisation**  
   - Removal of invalid state entries  
   - Standardisation of state and district names  
   - Correction of formatting and consistency issues  

3. **Data Validation**  
   - Cross-verification of geographic attributes  
   - Validation of numeric and temporal fields  

4. **Data Analysis & Modelling**  
   - Time-series analysis  
   - Age-group based aggregation  
   - State and district level comparisons  

5. **Visualisation**  
   - Interactive dashboards developed in Power BI  
   - KPIs and measures created using DAX  

---

## 📊 Dashboard Previews

### Aadhaar Enrolments Analysis

<img width="1314" height="743" alt="Screenshot 2026-01-31 022319" src="https://github.com/user-attachments/assets/0143a6cd-a70c-4b5d-9e4b-add908010242" />

### Demographic Updates Analysis

<img width="1305" height="720" alt="Screenshot 2026-01-31 022358" src="https://github.com/user-attachments/assets/20497408-fa8c-46f2-a719-5253d53761d2" />

### Biometric Updates Analysis

<img width="1303" height="715" alt="Screenshot 2026-01-31 022420" src="https://github.com/user-attachments/assets/30c561c3-baf9-44cc-a04a-77939f2c0d8c" />

---

## 📄 Analysis Report
A detailed explanation of the problem statement, datasets, methodology, insights, and conclusions is available in the final PDF report:

📁 [UIDAI_Data_Hackathon_2026_Report.pdf](https://github.com/Tarun9900/UIDAI-Hackathon-Data-Analytics/blob/main/UIDAI_Data_Hackathon_2026_Report.pdf)

---

## 🔑 Key Insights
- Aadhaar enrolments are predominantly driven by the **0–5** and **5–17** age groups  
- **Demographic and biometric updates** are dominated by the **17+** age group  
- Update volumes significantly exceed new enrolments, indicating a **mature Aadhaar ecosystem**
- Urban and high-population regions consistently show higher update activity
- Clear lifecycle behaviour is observed: early enrolment followed by recurring updates

---

## 🔒 Data Usage & Privacy Note
- Original UIDAI datasets are **not included** in this repository  
- Only analysis code, dashboard visuals, and aggregated insights are shared  
- This repository strictly adheres to data usage and privacy guidelines  

---

## 📌 Disclaimer
This project was developed **solely for academic and portfolio purposes** as part of the UIDAI Data Hackathon 2026.

---

## 👤 Author
**Tarun**  
Data Analytics | Python | Power BI
