# Exploratory Data Analysis (EDA) Portfolio

This repository contains a collection of exploratory data analysis (EDA) projects where I investigate different datasets to uncover patterns, correlations, and insights.  
The goal of this portfolio is to demonstrate my ability to clean, analyze, and visualize complex data — and to use those insights as a foundation for future **Machine Learning projects**.

---

## 📂 Projects 

### House Prices — Ames, Iowa
**Goal:** Analyze how different variables describing residential homes affect the sale price.

**Dataset:** [House Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

**Highlights:**
- 79 explanatory variables covering almost every aspect of residential homes.
- Statistical analysis using **correlation** and **ANOVA tests** to identify significant predictors.
- Handled missing and “not applicable” features (e.g., Alley, PoolQC) without losing relevant information.
- Visual exploration through **heatmaps**, **pairplots**, and **boxplots**.
- Classified variables by their impact level (elite, strong, moderate).

**Key Insights:**
- Overall quality (`OverallQual`) has the strongest correlation with price (r ≈ 0.79).
- Garage size, living area, and year built significantly influence sale price.
- Some rare or infrequent features were grouped under “Other” to improve interpretability.
- This analysis will later serve as a **feature exploration phase** for a **House Price Prediction** model in my [ML_Projects](https://github.com/Yanem-G/ML_projects) repository.

---

### Student Habits & Academic Performance
**Goal:** Explore how study habits, sleep, family support, and other personal factors influence students’ academic results.

**Dataset:** [Student Performance Dataset](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performanc)

**Highlights:**
- Analyzed categorical and numerical features (study time, absences, grades, family relations, etc.)
- Examined relationships between lifestyle and academic success.
- Used statistical summaries and visualization techniques to support conclusions.

**Key Insights:**
- Students with consistent study time and fewer absences tend to achieve higher grades.
- Social and family support play a moderate but notable role in performance.
- Alcohol consumption negatively correlates with final grades.

---

## Tools & Libraries Used
- **Python 3**
- **Pandas**, **NumPy** — data wrangling and statistics  
- **Matplotlib**, **Seaborn** — visualization  
- **Scipy.stats** — correlation and ANOVA tests  
- **Jupyter Notebook** — documentation and interactive analysis

---

## Methodology
1. Data cleaning and handling missing values appropriately.  
2. Statistical tests (Correlation, ANOVA) to identify key relationships.  
3. Visual exploration to confirm and explain numerical findings.  
4. Interpretation of insights in a business or human context.  
5. Preparation of clean, encoded data for Machine Learning pipelines.

---

## Author
**Aymen Gnaoui**  
ENSAM Casablanca – AI & Computer Engineering Student  
[LinkedIn](https://www.linkedin.com/in/aymen-gnaoui-16603730b/)  
gnaoui.aymen1@gmail.com

---

> *“EDA is not just the first step of Machine Learning — it’s how we start asking the right questions.”*
