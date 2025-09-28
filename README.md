# 📊 E-commerce Customer Spending Analysis

## 💡 Project Overview
This project provides a comprehensive data analysis of an **E-commerce store's customer spending data**. The main goal is to leverage core Python data science libraries—specifically Pandas, NumPy, Matplotlib, and Seaborn—to extract actionable business intelligence regarding customer behavior and revenue trends.
The analysis is broken down into four key components:

- Statistical Analysis (NumPy): Core numerical insights.
- Visual Insights (Matplotlib): Trend and total visualizations.
- Statistical Visualization (Seaborn): Advanced relationship exploration.
- Business Report (Part D): Final executive conclusions.

------

## 📁 Repository Structure

**Description**
***ecommerce_customer_spending.csv***
The primary dataset used for this analysis.
***analysis report.py***

The complete Python script containing all data cleaning, statistical calculations, and visualization code.
Then:
***business_report.md***

A template for the final PDF report, summarizing the key business insights (Part D).
Then:
***README.md***
This is the documentation file.

------

## ⚙️ Prerequisites and Setup
To run this analysis locally, you must have Python 3.x installed along with the following libraries:
**pip install pandas numpy matplotlib seaborn**

------

## 📋 Dataset Structure and Functions
The ecommerce_customer_spending.csv dataset includes the following columns:
Customer_ID |	Age	Gender | Product_Category | Purchase_Amount |	Purchase_Date |	Payment_Mode

Method used for payment (e.g., Credit Card, Cash).

------

## 🛠️ Core Data Preparation Functions
The Python script performs the following critical data preparation steps:

Data Cleaning: Converts the Purchase_Date column to the appropriate datetime object for accurate time-series analysis.
Age Grouping: Creates a new categorical column, Age_Group, to segment customers into actionable demographic bins (18-25, 26-35, 36-45, 46-60).

------

## 🚀 Analysis Breakdown

### Part A: Statistical Analysis (NumPy & Pandas)

Calculations for the Mean, Median, Standard Deviation, Max, Min, and Variance of Purchase_Amount.
Identification of the highest spending age group.
Comparison of the average spending between Male and Female customers.

---

### Part B: Visual Insights (Matplotlib)

Line Chart: Visualizing the revenue trend over time.
Bar Chart: Showing total sales by Product_Category.
Pie Chart: Illustrating the percentage contribution of different Payment_Modes.
Scatter Plot: Exploring the relationship between Age and Purchase_Amount.

---

### Part C: Statistical Visualizations (Seaborn)

Histogram (with KDE): Examining the distribution shape of Purchase_Amount.
Boxplot: Comparing the distribution and spread of spending across Gender.
Heatmap: Calculating and visualizing the Correlation Matrix between numerical features.
Pairplot: Exploring multivariate relationships between Age and Purchase_Amount, grouped by Gender.

---

# 📈 Key Business Insights (Part D)
The full findings are detailed in the final PDF Report, but the core business insights derived from this analysis include:

Revenue Driver: Identifying the single highest revenue-generating product category for inventory focus.
Payment Preference: Pinpointing the most popular payment method to optimize transaction infrastructure.
Customer Value: Determining which age demographic (e.g., 26-35) represents the highest average spending customer segment.
Gender Parity: Analyzing whether there are significant differences in spending behavior between male and female customers.

------
