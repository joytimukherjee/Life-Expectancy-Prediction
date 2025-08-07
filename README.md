# 🏦 Banking Customer Analysis Project

## 📘 Project Overview

This project aims to analyze customer data from a **banking domain**, retrieved using Python via SQL connection. The processed data undergoes exploratory analysis, and the insights are visualized using **Power BI**, enhanced with **Canva-based templates** for a professional and clean visual appeal.

The entire workflow is structured to deliver meaningful insights into customer behaviors, patterns, and key banking trends.

---

## ⚙️ Tech Stack

- **Python** for ETL and EDA
- **MySQL** for backend database
- **Power BI** for dashboard visualizations
- **Canva** for designing report templates
- **Jupyter Notebook** for development & documentation

---

## 🔁 Workflow Summary

### 1. 🛢️ Data Extraction
- Connected to MySQL database using `mysql.connector`
- Queried customer data from the table `banking_cases.customer`

### 2. 📊 Exploratory Data Analysis
#### 🔹 Univariate Analysis
- Examined distributions of single variables (e.g., age, income, gender, credit score)
- Identified outliers and skewness using histograms and boxplots

#### 🔹 Bivariate Analysis
- Explored relationships between pairs of features (e.g., income vs credit score)
- Correlation heatmaps and scatterplots used for numeric comparisons

### 3. 🧠 Insight Generation
- Key insights were derived regarding:
  - Customer segmentation
  - Spending habits
  - Risk profiling
  - Account activity trends

### 4. 📈 Power BI Dashboard
- Imported cleaned & structured data into **Power BI**
- Visuals include:
  - KPI Cards for summary stats
  - Line & bar charts for trends
  - Pie charts for segmentation
- Templates were designed using **Canva** to give it a polished report look

## 📁 Repository Structure
├── data.ipynb # Python notebook for SQL data extraction & EDA
├── actual_dataset.ipynb # Additional notebook for cleaned dataset analysis
├── banking.pbix # Power BI file with interactive dashboards
├── cleaning_log.txt # Logs of data transformation steps
└── README.md # Project documentation (this file)

### 'Install Requirements'
- Install required packages using pip install -r requirements.txt


## 📁 Repository Structure

