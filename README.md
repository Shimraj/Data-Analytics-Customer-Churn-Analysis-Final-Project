# Data-Analytics-Customer-Churn-Analysis-Final-Project
Customer Churn Analysis using Python and Google Colab

# 📊 Telco Customer Churn Analysis using Python

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-purple)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow)

## 📌 Project Overview

This project was completed as part of the **Program in AI Driven Data Analytics**.

The objective of this project is to analyze customer churn in a telecommunications company using the **IBM Telco Customer Churn Dataset**. The project follows a complete data analytics workflow, including data cleaning, preprocessing, exploratory data analysis (EDA), visualization, and business insight generation.

Understanding the factors that influence customer churn helps organizations improve customer retention strategies and reduce revenue loss.

---

## 🎯 Problem Statement

Customer churn is one of the major challenges faced by telecom companies. Losing existing customers is significantly more expensive than retaining them.

This project aims to answer the following question:

> **Which customer characteristics and services contribute most to customer churn, and how can these insights help improve customer retention?**

---

## 🎯 Project Objectives

- Load and understand the dataset
- Perform data cleaning and preprocessing
- Handle missing values and incorrect data types
- Create useful derived features
- Perform Univariate, Bivariate and Multivariate Analysis
- Generate meaningful visualizations
- Extract actionable business insights
- Provide recommendations for customer retention

---

## 📂 Dataset Information

| Item | Details |
|------|---------|
| Dataset | IBM Telco Customer Churn |
| Domain | Telecommunications |
| Records | 7,043 |
| Features | 21 Columns |
| Target Variable | Churn |

The dataset contains:

- Customer demographics
- Account information
- Internet and phone services
- Billing information
- Contract details
- Payment methods
- Customer churn status

---

## 🛠 Technologies Used

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

## 📁 Repository Structure

```
Telco-Customer-Churn-Analysis/
│
├── DAFinal_Assignment.ipynb          # Google Colab Notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Dataset_Recommendation_Report.pdf
├── README.md
```

---

## 🔄 Project Workflow

```
Dataset
   │
   ▼
Data Loading
   │
   ▼
Data Cleaning
   │
   ▼
Data Preprocessing
   │
   ▼
Feature Engineering
   │
   ▼
Exploratory Data Analysis
   │
   ├── Univariate Analysis
   ├── Bivariate Analysis
   └── Multivariate Analysis
   │
   ▼
Business Insights
   │
   ▼
Recommendations
```

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Imported required libraries
- Loaded the dataset
- Inspected dataset structure
- Checked missing values
- Converted `TotalCharges` to numeric
- Removed or handled missing records
- Checked duplicate rows
- Created derived features
- Dropped unnecessary columns
- Verified cleaned dataset

---

## 📊 Exploratory Data Analysis (EDA)

The project includes multiple visualizations such as:

- Churn Distribution
- Gender Distribution
- Contract Type Analysis
- Payment Method Analysis
- Monthly Charges Distribution
- Total Charges Distribution
- Tenure Distribution
- Correlation Heatmap
- Boxplots
- Countplots
- Scatter Plots
- Histograms
- Pairwise Comparisons

---

## 💡 Key Business Insights

Some of the important findings include:

- Customers with month-to-month contracts are more likely to churn.
- Longer customer tenure generally reduces churn.
- Higher monthly charges are associated with higher churn.
- Customers without Online Security or Tech Support services tend to leave more frequently.
- Electronic Check payment users have comparatively higher churn.
- Fiber Optic internet users show higher churn than DSL users.
- Long-term contracts improve customer retention.

---

## 📈 Business Recommendations

- Encourage customers to switch to long-term contracts.
- Offer discounts for customers with high monthly charges.
- Bundle Online Security and Tech Support services.
- Launch targeted retention campaigns for high-risk customers.
- Improve customer engagement during the initial months of service.

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Telco-Customer-Churn-Analysis.git
```

2. Navigate to the project folder

```bash
cd Telco-Customer-Churn-Analysis
```

3. Open the notebook

```
DAFinal_Assignment.ipynb
```

4. Run all cells using Google Colab or Jupyter Notebook.

---

## 📷 Sample Visualizations

The notebook contains various charts including:

- Count Plots
- Histograms
- Heatmaps
- Scatter Plots
- Boxplots
- Pie Charts
- Distribution Plots

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Business Insight Generation
- Python for Data Analytics

---

## 👨‍💻 Author

**Shimraj K J**

Program in AI Driven Data Analytics

---

## ⭐ Acknowledgements

- IBM Sample Dataset
- Kaggle
- Google Colab
- Pandas Documentation
- Matplotlib
- Seaborn
