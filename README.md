# Titanic Data Cleaning & Visualization Project

## Overview
This project focuses on cleaning, preprocessing, and visualizing the Titanic dataset using Python libraries such as Pandas, Matplotlib, and Seaborn.

The objective of this project is to transform raw data into a clean and understandable format by handling missing values, duplicates, and outliers while generating meaningful visual insights.

---

## Objectives
- Clean and preprocess raw data
- Handle missing values and duplicates
- Detect and remove outliers
- Perform Exploratory Data Analysis (EDA)
- Create visual reports and insights

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## Dataset
- Titanic Dataset (CSV Format)

---

## Data Cleaning Process

### 1. Handling Missing Values
- Filled missing values in:
  - `Age` column using mean
  - `Embarked` column using mode
  - `Fare` column using mean
- Removed the `Cabin` column due to excessive missing values

### 2. Removing Duplicates
- Removed duplicate rows from the dataset

### 3. Outlier Detection & Removal
- Used Boxplot visualization
- Applied IQR (Interquartile Range) method to remove outliers from the `Fare` column

---

## Data Visualization
The following visualizations were created:
- Survival Count Plot
- Gender Distribution Plot
- Age Distribution Histogram
- Fare Boxplot
- Correlation Heatmap

---

## Key Insights
- Most passengers were male
- Younger passengers had better survival rates
- Fare column contained several outliers
- Missing values were successfully handled
- Passenger class and fare showed strong correlation

---

## Project Structure

```text
Titanic-Data-Cleaning-Visualization/
│
├── Titanic.csv
├── cleaned_titanic.csv
├── Data_Cleaning_Visualization.ipynb
├── screenshots/
└── README.md
```

---

## Output
- Cleaned dataset ready for analysis
- Visual insights from the Titanic dataset
- Improved understanding of data preprocessing and visualization techniques

---

## Conclusion
This project demonstrates the complete workflow of data cleaning and visualization using Python. It provides practical experience in preprocessing real-world datasets and generating insights through visual storytelling.

---
