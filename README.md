# 🚢 Task 5: Exploratory Data Analysis - Titanic Dataset

## 📌 Overview
This task focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset. The goal is to uncover insights, detect patterns, and understand the structure of the data through statistical summaries and visualizations using Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib**.

---

## 🧰 Tools & Libraries Used
- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

---

## 📁 Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **File Used:** `train.csv`

---

## 🔍 Key Steps Performed

1. **Data Loading and Overview**
   - Loaded the dataset using Pandas.
   - Explored shape, column types, and missing values.

2. **Univariate Analysis**
   - Count plots and histograms for columns like `Sex`, `Pclass`, `Age`, `Fare`, `Embarked`, etc.
   - Observed distributions and imbalances in categories.

3. **Bivariate Analysis**
   - Explored relationships between features and the target column `Survived`.
   - Used boxplots, scatterplots, and grouped bar charts.

4. **Multivariate Analysis**
   - Used heatmaps and pairplots to identify correlations between numeric variables.

5. **Handling Missing Values**
   - Imputed missing `Age` with median and `Embarked` with mode.
   - Dropped the `Cabin` column due to excessive missing data.

6. **Insights and Observations**
   - Summarized key findings based on visualizations and stats.

---

## 📊 Key Findings
- Female passengers had a significantly higher survival rate than males.
- 1st class passengers were more likely to survive than 2nd or 3rd class.
- Passengers aged between 20-40 were the most common.
- Fare and Pclass had a negative correlation.
- Cabin had too many missing values and was dropped.

---

## 📎 Files Included
- `EDA_Task_5.ipynb` – Jupyter notebook with code and visualizations
- `EDA_Report.pdf` – PDF summary of all visual findings and observations
- `train.csv` – Dataset used for analysis

---

## 🧑‍💻 Submitted By
**Pratham Kumar Prasad**


