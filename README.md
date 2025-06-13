# TASK-5-Exploratory-Data-Analysis-EDA-
# 🧪 Titanic Data Exploration Project

This repository contains a basic Exploratory Data Analysis (EDA) project using a sample Titanic dataset with over 100 rows and 10+ columns.

---

## 📁 Dataset
- `titanic_sample.csv` — Cleaned mock Titanic dataset with 120 rows and 11 columns.
- Includes columns like `Survived`, `Pclass`, `Age`, `Fare`, `Sex`, `Embarked`, and more.

---

## ✅ EDA Tasks Completed

### a) Basic Data Summary
- Used `.info()`, `.describe()`, and `.value_counts()` to understand:
  - Data types
  - Missing values
  - Basic statistics
  - Class and gender distributions

### b) Visualizations with Seaborn
- Used `sns.pairplot()` to view relationships between numeric columns, colored by survival.
- Created a `sns.heatmap()` to analyze correlations among features like age, fare, and class.

### c) Identified Relationships and Trends
- Found that:
  - Higher class passengers had higher survival.
  - Females had better survival rates.
  - Fare and Pclass are strongly linked.
  - Younger passengers had slightly better chances of survival.

### d) Plotted Various Graphs
- ✅ **Histogram**: Distribution of `Age`
- ✅ **Boxplot**: `Age` vs `Survived`
- ✅ **Scatterplot**: `Age` vs `Fare` colored by `Survived`

### e) Observations for Each Visual
- Younger and wealthier passengers were more likely to survive.
- Higher Fare → Higher chance of survival.
- Outliers present in age and fare distributions.
- Pclass 3 passengers had the lowest survival.

### f) Summary of Findings
```text
Survival was strongly influenced by socioeconomic status and gender.
Fare, Pclass, and Sex had the most noticeable effects on survival.
There is weak correlation with numerical features, indicating categorical variables play a larger role.

