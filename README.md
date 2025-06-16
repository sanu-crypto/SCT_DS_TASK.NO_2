# SCT_DS_TASK.NO_2
# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains the complete Exploratory Data Analysis (EDA) for the Titanic dataset, as part of **Task 2** in my data science learning journey.

## 📌 Task Description

**Goal:**  
Perform data cleaning and EDA on a dataset of your choice — I chose the classic [Titanic dataset from Kaggle](https://www.kaggle.com/competitions/titanic/data). The task includes:

- Cleaning the dataset (handling missing values, dropping unnecessary columns)
- Converting categorical columns to numeric
- Visualizing trends and relationships using plots and heatmaps
- Understanding feature relationships with survival outcomes

---

## 📁 Dataset

- `Titanic-Dataset.csv` (included)
- Original Source: [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic/data)

---

## 📊 EDA Highlights

- Filled missing values in the `Age` column using the median.
- Dropped columns like `Cabin`, `Ticket`, and `Name` to reduce noise.
- Encoded categorical variables (`Sex`, `Embarked`) using one-hot encoding.
- Created visualizations to understand survival patterns:
  - Heatmap of feature correlations
  - Survival rates by sex, age, and class
  - Age distribution of survivors vs non-survivors

---

## 🔧 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`

---

## 📷 Sample Visuals

- Correlation heatmap
- Countplots of survival by sex and class
- Age distribution histogram with survival overlay

---

## 💡 Key Insights

- Females had significantly higher survival rates.
- 1st class passengers were more likely to survive.
- Younger passengers had better chances of survival.
