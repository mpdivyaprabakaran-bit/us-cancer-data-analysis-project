# 🩺 US Cancer Incidence Analytics using Python & Power BI

## 📌 Project Overview

This project presents an end-to-end exploratory data analysis (EDA) and business intelligence dashboard for the **United States Cancer Incidence Dataset**. The objective was to analyze cancer incidence patterns across different demographics, geographic regions, cancer sites, and years, and derive actionable insights to support data-driven healthcare decision-making.

The project combines **Python (Google Colab)** for data preprocessing and exploratory analysis with **Power BI** for developing an interactive executive dashboard.

---

## 🎯 Project Objectives

- Clean and preprocess the raw cancer incidence dataset.
- Perform Exploratory Data Analysis (EDA) to identify patterns, trends, and outliers.
- Analyze cancer incidence by:
  - Cancer Site
  - Region
  - State
  - Age Group
  - Race
  - Year
  - Incidence Severity
- Study statistical properties such as skewness, kurtosis, and correlations.
- Build an interactive Power BI dashboard for healthcare insights and decision-making.

---

## 🛠️ Tools & Technologies

- **Python**
- **Google Colab**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Power BI Desktop**
- **GitHub**

---

## 📂 Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning & Preprocessing (Python - Google Colab)
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Engineering & Statistical Analysis
      │
      ▼
Power BI Dashboard Development
      │
      ▼
Business Insights & Recommendations
```

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

- Data cleaning and preprocessing
- Missing value handling
- Data type conversion
- Feature engineering
- Descriptive statistics
- Distribution analysis
- Skewness & Kurtosis analysis
- Correlation analysis
- Outlier detection
- Cancer incidence trend analysis
- Regional and demographic comparisons

---

## 📈 Power BI Dashboard

The interactive dashboard provides insights into:

- Total Cancer Cases
- Average Crude Rate
- Population Coverage
- Top Cancer Sites
- Cancer Cases by Region
- Cancer Cases by State
- Cancer Cases by Age Group
- Cancer Cases by Race
- Year-wise Cancer Trends
- Interactive filtering using slicers

---

## 🔍 Major Insights

- The dataset exhibits **high positive skewness and heavy-tailed distributions**, which are characteristic of healthcare and epidemiological data.
- **Breast, Prostate, and Lung & Bronchus cancers** account for the highest number of reported cases.
- Cancer incidence increases significantly with age, with **Senior and Elderly** populations experiencing the highest burden.
- The **South** reports the highest overall number of cancer cases among all U.S. regions.
- **California, Florida, Texas, and New York** contribute the highest number of reported cancer cases.
- A strong positive correlation exists between **Crude Rate** and **Incidence Severity**, indicating that higher severity is associated with increased incidence.
- The **Critical** severity category demonstrates the highest crude rates and greatest variability.
- Cancer incidence varies across regions, states, age groups, races, and cancer sites, highlighting the importance of targeted public health interventions.

---

## 💡 Recommendations

- Strengthen screening programs for Breast, Prostate, and Lung cancers.
- Prioritize preventive healthcare for Senior and Elderly populations.
- Allocate additional healthcare resources to high-burden regions and states.
- Promote early diagnosis to reduce progression to critical severity levels.
- Use demographic and regional insights to support targeted public health policies.
- Continue monitoring cancer trends for evidence-based healthcare planning.

---

## ✅ Conclusion

This project demonstrates how Python-based data analytics combined with Power BI visualization can transform raw healthcare data into meaningful insights. The analysis highlights significant variations in cancer incidence across demographic and geographic factors and emphasizes the importance of early detection, targeted screening, and data-driven resource allocation. The resulting dashboard enables stakeholders to interactively explore cancer trends and supports informed decision-making for healthcare planning.

---

## 📁 Repository Structure

```
├── Doc/raw/
│   ├── United States and Puerto Rico Cancer Statistics - 2018 - 1.csv
│   └── United States and Puerto Rico Cancer Statistics - 2018.csv
│   └──United States and Puerto Rico Cancer Statistics - 2019 - 1.csv
│   └── United States and Puerto Rico Cancer Statistics - 2019.csv
│   └── United States and Puerto Rico Cancer Statistics - 2020 - 1.csv
│   └── United States and Puerto Rico Cancer Statistics - 2020.csv
│   └── United States and Puerto Rico Cancer Statistics - 2021 -1.csv
│   └── United States and Puerto Rico Cancer Statistics - 2021.csv
│   └── United States and Puerto Rico Cancer Statistics - 2022 -1.csv
│   └── United States and Puerto Rico Cancer Statistics - 2022.csv
│
├──Doc/Cleaned/
│   └── clean_data.csv
│
├──└── US_Cancer_Data_Analytics.ipynb
│
├── Images/
│   └── dashboard_screenshot.png
│
└── README.md
