# 🧠 Chronic Depression Data Analysis
![Python](https://img.shields.io/badge/Python-3.9-blue)
![SQL](https://img.shields.io/badge/SQL-MySQL-orange)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Dataset](https://img.shields.io/badge/Dataset-400K%2B%20records-blueviolet)

**Tools:** SQL • Python • Power BI  
**Dataset Size:** 400K+ records  
**Objective:** Identify key depression risk drivers and enable data-driven insights

---

## 📌 Overview

This project presents an end-to-end exploratory data analysis of factors associated with chronic depression risk. The dataset (`depression_data`) contains demographic, lifestyle, and medical attributes including age, marital status, education level, smoking habits, physical activity, alcohol consumption, medical history, and income levels.

The goal of this analysis is to uncover meaningful patterns, correlations, and risk indicators that support data-driven understanding of mental health trends and potential intervention strategies.

---

## 📊 Dashboard Preview

![Power BI Dashboard](assets/dashboard.png)

---

## 📁 Project Structure
.
├── assets/ # Dashboard images
├── depression_data.csv # Cleaned dataset
├── depression_data_analysis.sql # SQL queries
├── depression.pbix # Power BI dashboard
└── README.md


---

## 🔍 Key Analysis & Insights

### Age and Income Relationship
Calculated average age and income across age groups to examine demographic income patterns.

### Marital Status and Income
Analyzed income distribution by marital status to identify socio-economic variations.

### Smoking Status vs Physical Activity
Evaluated record distribution across smoking status and activity levels to detect lifestyle risk patterns.

### Employment Status and Income
Compared average income between employed and unemployed populations.

### Chronic Medical Conditions
Measured prevalence of chronic medical conditions within the dataset.

### Physical Activity and Sleep Patterns
Explored associations between activity levels and sleep behavior using relational joins.

### Dietary Habits and Chronic Conditions
Assessed how dietary patterns correlate with chronic health issues.

### Lifestyle Risk Segmentation
Engineered a **Lifestyle Risk Factor** feature based on smoking, alcohol consumption, and physical activity.

### Family Health Risk Indicator
Created a **Family Health Risk** variable using family depression history and chronic condition presence.

### Age Group with Highest Smokers
Identified the age segment with the maximum number of current smokers.

### Mental Illness and Substance Abuse
Computed overlap between mental illness history and substance abuse indicators.

### Income vs Mental Illness Correlation
Performed correlation analysis revealing a weak negative relationship, indicating low dependency between income and mental illness history.

---

## ⚙️ How to Use

1. Execute `depression_data_analysis.sql` in MySQL to reproduce the analysis  
2. Open `depression.pbix` using Power BI Desktop  
3. Use interactive filters to explore risk segments and insights  

---

## ✅ Conclusion

This project demonstrates how SQL-driven exploratory analysis combined with interactive Power BI visualization can transform large-scale health data into actionable insights. The findings highlight key demographic and lifestyle patterns associated with depression risk and showcase practical data analytics techniques applicable to real-world decision-making.

---

## 👤 Author

**Debabrata Debnath**  
B.Tech — Computer Science & Business Systems  
Techno Main Salt Lake

---
