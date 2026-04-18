# 🚬 Smoking Health Data Analysis




---

## 📊 Project Overview

This project explores a **Smoking Health Dataset** to understand how lifestyle factors—particularly smoking—impact cardiovascular health indicators such as blood pressure, heart rate, and cholesterol.

The goal is to uncover **data-driven insights** that explain hypertension risk and support better health awareness. The analysis combines **Excel and Power BI** with strong emphasis on **data cleaning, exploratory data analysis (EDA), correlation, and regression techniques**.

---

## 🎯 Objectives

* Compare **smokers vs non-smokers** across key health metrics
* Identify relationships between **age, smoking habits, and blood pressure**
* Determine the **strongest predictors of hypertension**
* Communicate findings using **interactive dashboards and visualizations**

---

## 🧹 Data Cleaning & Preparation (Power Query – Excel)

Before analysis, the dataset required significant preprocessing using **Power Query**:

* Converted blood pressure values (e.g., *120/80*) into **numerical systolic values**
* Handled missing and inconsistent data entries
* Standardized column formats (age, cholesterol, cigarettes per day)
* Created calculated columns for improved analysis

This step ensured **data accuracy, consistency, and reliability** for further analysis.

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was conducted primarily in **Excel** using a combination of:

* **Pivot Tables** to summarize key variables
* **Charts (bar charts, line charts, histograms)** to visualize distributions and trends
* Grouping data by **age categories, smoking status, and consumption levels**

### Key EDA Insights:

* Smokers generally show **higher average systolic blood pressure**
* Blood pressure increases steadily with **age**
* Heavy smokers tend to cluster within **specific age groups**
* Higher cholesterol levels are associated with elevated BP

EDA helped uncover **patterns, outliers, and initial relationships** before deeper statistical analysis.

---

## 🔗 Correlation Analysis

Correlation analysis was performed to measure the strength of relationships between variables using Excel.

### Correlation Coefficients:

| Variable Pair                 | Correlation (r) | Interpretation         |
| ----------------------------- | --------------- | ---------------------- |
| Age vs Blood Pressure         | 0.29            | Weak–Moderate Positive |
| Cigarettes per Day vs BP      | 0.18            | Weak Positive          |
| Cholesterol vs Blood Pressure | 0.22            | Weak Positive          |
| Heart Rate vs Blood Pressure  | 0.10            | Very Weak Positive     |

### Insights:

* **Age** has the strongest correlation with blood pressure among all variables
* Smoking-related variables show **positive but weaker relationships**
* Hypertension is influenced by **multiple interacting factors**, not a single variable

---

## 📉 Regression Analysis

A **multiple linear regression** model was built in Excel to predict blood pressure based on key independent variables.

### Model Summary:

* **Multiple R:** 0.295
* **R Square:** 0.087
* **Adjusted R Square:** 0.086
* **Standard Error:** 42.46
* **Observations:** 3,879

### Interpretation:

* The model explains approximately **8.7% of the variation** in blood pressure
* This indicates that while the variables are relevant, **other external factors** also influence hypertension
* The relatively low R² reflects the **complex nature of health data**

### Key Coefficients Insight:

* **Age** → Strongest positive predictor
* **Cigarettes per Day** → Positive contribution to BP
* **Cholesterol** → Moderate positive influence
* **Heart Rate** → Minimal impact

Regression analysis confirms that **age is the dominant factor**, while smoking contributes but is not the sole driver of hypertension risk.

---

## 📊 Data Visualization (Excel & Power BI)

### Excel

* Pivot charts for quick insights
* Trend analysis using line and bar charts
* Summary dashboards for exploratory insights

### Power BI

* Interactive dashboards for deeper exploration
* Filters for **age groups, smoking status, and cholesterol levels**
* Visual storytelling to communicate key findings

These tools helped transform raw analysis into **clear, interactive, and actionable insights**.

---

## 📌 Key Insights

* Smokers generally have **higher blood pressure** than non-smokers
* **Age is the strongest predictor** of hypertension
* Increased cigarette consumption correlates with **higher health risks**
* Cholesterol levels contribute significantly to cardiovascular risk
* Unexpected patterns were observed in the **age distribution of heavy smokers**

---

## 🧠 Conclusion

This project demonstrates the power of combining **EDA, correlation, and regression analysis** with strong data visualization tools like **Excel and Power BI**.

By leveraging structured analysis techniques, this study provides meaningful insights into how smoking and other factors influence hypertension risk, reinforcing the importance of **data-driven health awareness**.

---

## 🛠️ Tools Used

* Microsoft Excel (Pivot Tables, Charts, Regression Analysis)
* Power Query (Data Cleaning & Transformation)
* Power BI (Dashboard & Visualization)

---

## 📎 Author

**Ikenna Ngwuta**
Data Analyst | Turning Data into Insights

---

⭐️ *Feel free to explore the project and connect with me!*

