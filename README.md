# Bank-Customer-Churn-Analysis

## 🔍 Project Overview
This project is a **Python-based churn prediction model** aimed at identifying customers who are likely to leave the bank. Using a dataset of 10,000 customers, it combines **exploratory data analysis (EDA)** with a **logistic regression model** to uncover key drivers of churn and generate actionable insights. The primary goal is to support customer retention by identifying high-risk segments based on behavior and demographics.
---

## 📌 Key Insights

### 🎯 Gender-Based Churn
- **Female customers** have a churn rate of **25.07%**, higher than **16.47%** for males.
- Targeting female retention could yield major improvements.

### 🌍 Country-Level Churn
- **Germany** shows the highest churn at **32.44%**.
- France and Spain show relatively low churn rates (~16%).

### 👵 Age-Wise Churn
- **50–60 age group** is most vulnerable with **56.21%** churn.
- Followed by **40–50 group** at **33.96%**.

### ⏳ Tenure-Based Insights
- Even loyal customers (**10 years**) show **20% churn**.
- Early exits (**<1 year**) are also high at **23%**.

### 🚫 Activity Status
- **Non-active members**: **27% churn**
- **Active members**: only **14%**

### 📦 Number of Products
- Customers with **3 products** have a massive **83% churn**.
- More products don’t always mean more satisfaction.

### 💰 Balance and Credit Score
- Around **3,500 customers** have a **zero balance** — a potential sign of disengagement.
- Credit score is **normally distributed**, with a mean of ~**650**.

---

## 📈 Model Performance
- Built using **Logistic Regression**
- Achieved an **accuracy of 81%**
- Suitable for large-scale churn risk flagging

---

## 🧠 Tools Used
- Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`)
- Data Cleaning and EDA
- Logistic Regression for binary classification
- Visualization for insight generation

---

## ✅ Recommendations

### 🔴 Focus on High-Risk Segments
- Women aged **50+ in Germany** are the top churn group.
- Design targeted retention offers (loyalty programs, check-ins).

### 📣 Improve Engagement
- Encourage usage among **inactive and zero-balance** customers.
- Provide meaningful value for customers with multiple products.

### 🎁 Tenure-Based Retention
- Introduce incentives for both **new and long-time** customers.

### 🧩 Data-Driven Campaigning
- Use model predictions to trigger **personalized interventions** and offers.

---
