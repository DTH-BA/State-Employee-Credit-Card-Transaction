# 📊 State Employee Credit Card Transactions Analysis

## 📌 Overview
Analysis of **742k+ state employee credit card transactions (2022–2025)** with goals to:  
1. Detect anomalous / potentially fraudulent transactions  
2. Identify high-risk merchants and departments  
3. Explore spending trends over time  

---

## ⚙️ Workflow
1. **Data Overview** – Structure & quality check  
2. **SOW & SMART Questions** – Define objectives  
3. **Cleaning** – Handle duplicates, negatives, formatting  
4. **EDA** – Overview Dashboard  
5. **Modeling** – Outlier detection (Isolation Forest, IQR, Z-score, LOF)  
6. **Reporting** – Insights + GitHub repo  

---

## 🚀 Tech Stack
- **Python** – pandas, seaborn, scikit-learn  
- **Tableau** – Interactive dashboards  
- **Excel** – Data checks  
- **GitHub** – Documentation & repo  

---

## 📌 Key Insights (According Dasboard)
- Total spend: **$342.4M** from **742k transactions**, with **2.07% refunds**  
- Spending dominated by **small transactions (~409k)**, but **3,773 high-value outliers** detected  
- **Dept of Corrections** leads with >$106M, nearly double the next department  
- Heatmap shows spending occurs **across all days**, with peaks in fiscal periods 5–7    

---

## ⚠️ Limitations
- No unique Transaction ID or timestamp granularity  
- No cardholder-level data  

