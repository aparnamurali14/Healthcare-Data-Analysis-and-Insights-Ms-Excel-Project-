# Healthcare-Data-Analysis-and-Insights-  Ms-Excel-Project


## 📌 Project Overview
The healthcare industry generates vast amounts of data that can be leveraged to improve **patient care, resource allocation, and healthcare cost management**.  
This project analyzes a comprehensive healthcare dataset using **Microsoft Excel** to extract insights related to **patient health profiles, medical history, and healthcare charges**.

The project involves **data cleaning, transformation, exploration, visualization, and dashboard creation** to deliver actionable insights for healthcare stakeholders.

---

## 🎯 Problem Statement
This project aims to analyze healthcare data comprising:
- Medical examinations
- Hospitalization details
- Customer demographic profiles  

By identifying trends, correlations, and patterns among metrics such as **BMI, HbA1C, age, surgeries, and charges**, the project supports informed decision-making in healthcare analytics.

---

## 🛠️ Tools Used
- **Microsoft Excel**
  - Data Cleaning & Transformation
  - VLOOKUP
  - Pivot Tables
  - Charts & Visualizations
  - Interactive Dashboard
- **Excel Functions**
  - IF, VLOOKUP, TEXT, ROUND, SUBSTITUTE
  - Date and time functions
- **Slicers**
  - Interactive filtering across dashboards

---

## 📂 Dataset
- **Source:** Healthcare Dataset (Medical Examinations, Hospitalization Details, Customer Profiles)
- **Download Link:**  
  https://drive.google.com/uc?export=download&id=1zelh7bZrE7F290QtTABHgHYn4B7JDbZO

---

## 📁 Project Structure

```text
Healthcare-Data-Analysis-Excel/
│
├── data/
│   └── healthcare_dataset.xlsx
│
├── analysis/
│   ├── data_cleaning.xlsx
│   ├── data_transformation.xlsx
│   └── data_analysis.xlsx
│
└── dashboard/
    └── healthcare_dashboard.xlsx

```



## 🧹 Data Cleaning
- Identified missing values marked as `?` in the **Medical Examinations** and **Hospitalization Details** tables.
- Replaced missing **Month** values with *September*.
- Filled missing **Year** values using the rounded average year.
- Filled missing values in **Smoker**, **Hospital Tier**, and **City Tier** columns using the most frequently occurring values (mode).
- Handled missing **State ID** values using appropriate placeholders such as *Unknown*.

---

## 🔄 Data Transformation
- Split the **Names** column into three meaningful columns:
  - Title  
  - First Name  
  - Last Name
- Converted **NumberOfMajorSurgeries** into numeric format by replacing non-numeric characters.
- Checked and corrected inconsistencies in **Smoker** and **Heart Issues** columns.
- Created a new column **Weight Status** based on BMI categories:
  - Underweight  
  - Normal Weight  
  - Overweight  
  - Obesity
- Created a new column **Diabetes Status** based on HbA1C levels:
  - Normal  
  - Prediabetes  
  - Diabetes
- Merged **Day, Month, and Year** into a single **Date of Birth** column formatted as *DD-MMM-YYYY*.
- Calculated **Age** for each customer as of **8th June 2023**.
- Formatted **Charges** as currency ($).

---

## 📊 Data Analysis & Visualization
- Combined all three tables into a single **Healthcare** sheet using **Customer ID** with VLOOKUP.
- Retained only relevant columns required for analysis.
- Created **Pivot Tables** to summarize healthcare metrics.
- Used appropriate chart types for effective visualization:
  - Pie / Donut charts
  - Column / Bar charts
  - Line and Scatter plots

---

## 📈 Key Analyses Performed

### 🥧 Pie / Donut Chart Analysis
- Distribution of cancer history among **smokers vs non-smokers**.
- Comparison of **total major surgeries** and **average HbA1C** between patients **with and without transplant history**.

### 📊 Column / Bar Chart Analysis
- Variation of healthcare charges across different **Weight Status** and **Diabetes Status**.
- Comparison of **average healthcare charges** by **Hospital Tier** across different **States**.

### 📉 Line / Scatter Plot Analysis
- Relationship between **Age and BMI**.
- Relationship between **Age and HbA1C**.
- Correlation between **Age and Healthcare Charges**.

---

## 📌 Key Findings
- Smokers show a higher prevalence of cancer history compared to non-smokers.
- Patients with transplant history tend to undergo more major surgeries and show higher HbA1C levels.
- Obese and diabetic patients generally incur higher healthcare charges.
- Higher hospital tiers are associated with increased average healthcare costs.
- Healthcare charges tend to increase with patient age.

---

## 📊 Dashboard
- Developed an **interactive Excel dashboard** consolidating all key insights.
- Integrated **slicers** for:
  - Weight Status
  - Diabetes Status
- Enabled dynamic filtering across all visualizations for easy comparison and interpretation.
