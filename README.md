# 🩺 Healthcare Data Analysis Project

This project focuses on analyzing synthetic healthcare data to uncover patterns in patient demographics, medical conditions, hospital admissions, medications, and outcomes. The analysis helps identify trends that can support hospital decision-making and improve patient care.

---

## 🎯 Business Objective

To perform data-driven exploration on healthcare records to:

- Understand the relationship between medical conditions, gender, and admission types.
- Analyze test results and prescribed medications across different diseases.
- Detect insights that could assist hospitals in resource planning and treatment strategies.

---

## 🗂️ Folder Structure
healthcare-data-analysis/
├── clean_healthcare_data/ # Final cleaned dataset
├── healthcare_data_cleaning/ # Notebooks for data cleaning (Day 1)
├── healthcare_dataset/ # Raw and synthetic dataset files
├── healthcare_eda_analysis/ # Visualizations and EDA notebooks (Day 3)
├── README.md

---

## 🧾 Dataset Overview

- **Type:** Synthetic healthcare dataset  
- **Source:** https://www.kaggle.com/datasets/prasad22/healthcare-dataset
- **Features Include:**
  - Medical condition  
  - Gender  
  - Age  
  - Admission type (Urgent, Emergency, Elective)  
  - Test result status  
  - Blood type  
  - Prescribed medications  
  - Length of hospital stay  

---

## ⚙️ Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🔍 EDA Summary 

- Most patient attributes showed balanced distributions due to synthetic nature.
- Cancer and asthma cases had more abnormal test results, while hypertension showed mostly normal outcomes.
- Male patients dominated cancer cases; arthritis had more female patients.
- Admission types varied:
  - **Diabetes → Urgent**
  - **Hypertension → Elective**
  - **Obesity → Emergency**
- Medications were condition-specific:
  - Obesity patients were prescribed **Penicillin**
  - Hypertension patients received **Ibuprofen**
  - Cancer and asthma patients received **Lipter** and **Paracetamol**
- Length of stay was balanced across medical conditions and admission types.
- Correlation heatmap showed minor relationships between features.

---

## ✅ Conclusion 

> The EDA phase has revealed meaningful patterns across conditions, test results, medications, and admissions — despite being synthetic data. These insights provide the groundwork for hospital strategy modeling, and further visualization will strengthen data storytelling.
