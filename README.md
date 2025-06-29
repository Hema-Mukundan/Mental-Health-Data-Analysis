# Mental-Health-Data-Analysis
# 🧠 Mental Health in Tech Workplace – Exploratory Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a public dataset from a 2014 survey about mental health in the tech workplace. The aim is to understand patterns, perceptions, and influencing factors of mental health issues and workplace attitudes across geographic and demographic segments.

> 📊 **Note:** This project focuses purely on data cleaning, preprocessing, and insightful visualization.

---

## 🎯 Problem Statement

Mental health is often stigmatized in professional environments, especially in fast-paced industries like tech. This project seeks to answer:

- How do mental health issues and attitudes vary across countries and workplace types?
- What are the strongest predictors of seeking mental health treatment or encountering work interference?
- How can organizations improve awareness and support for mental health?

---

## ✅ Business Objective

To analyze the frequency and factors influencing mental health concerns in the tech industry and provide data-driven insights that can help organizations build inclusive and supportive workplace environments.

---

## 🧩 Dataset

- **Source**: [Open Sourcing Mental Illness (OSMI)](https://osmihelp.org/research)
- **Year**: 2014  
- **Size**: 1250+ rows, 27 columns  
- **Features include**:
  - Demographics: Age, Gender, Country, State
  - Employment details: Self-employed, No. of employees, Tech company
  - Mental health factors: Treatment, Interference, Benefits, Anonymity, Leave policy
  - Perceptions and Attitudes: Willingness to discuss with coworkers/supervisors, observed consequences, etc.

---

## 🔧 Data Wrangling & Cleaning

The following columns were cleaned/preprocessed:
- `Age`: Outlier removal, valid age range filtering
- `Gender`: Standardized into Male, Female, Other
- `self_employed` & `work_interfere`: Missing values handled with logical imputations
- `Timestamp`: Dropped after initial validation
- `no_employees` & `leave`: Standardized for consistency

---

## 📊 Visualizations & Insights

A total of **15+ visualizations** were created including:
- Age distribution histogram
- Country-wise respondent count bar chart
- Gender-wise treatment comparison
- Mental health interference by age (boxplot)
- Leave difficulty levels
- Wellness program availability vs. treatment
- Tech vs. non-tech mental health benefits
- Correlation heatmap & pairplot for key factors

Each visualization includes:
- The reason it was chosen
- Key insights derived
- Its potential business impact (positive/negative)

---

## 💡 Key Takeaways

- Younger employees (25–40) are more affected and more likely to seek help.
- Anonymity, wellness programs, and leave flexibility are **strong influencers** on treatment-seeking behavior.
- Employees with a family history of mental illness are significantly more open to getting help.
- Smaller companies show a **lack of benefits and awareness**, highlighting a gap in mental health support.

---

## 🛠 Tools Used
Python (Pandas, NumPy)

Matplotlib & Seaborn

Jupyter Notebook
