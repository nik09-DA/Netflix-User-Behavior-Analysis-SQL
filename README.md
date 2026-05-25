# 🎬 Netflix User Behavior & Revenue Analysis — SQL Case Study

A complete SQL-based analysis of Netflix user behavior, subscription trends, revenue patterns, and churn using a dataset of 50,000 users across 10 countries.

---

## 🛠️ Tools Used

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 📌 Project Objective

Analyze Netflix user behavior and business performance using SQL to generate insights on:
- Revenue and subscription trends
- Customer preferences and engagement
- Market performance by country
- Churn patterns and retention risk

---

## 📂 Dataset Overview

| Field | Details |
|---|---|
| Total Users | 50,000 |
| Countries | 10 (Brazil, USA, India, Spain, Germany, Australia, Canada, UK, France, Japan) |
| Subscription Types | Basic, Standard, Premium |
| Key Columns | user_id, age, gender, country, subscription_type, monthly_fee, payment_method, primary_device, favorite_genre, avg_watch_time_minutes, churned, completion_rate |

---

## 🧹 Data Cleaning & Quality Checks

Before analysis, the following data quality checks were performed:

1. **Missing Values** — Identified NULL values across key columns (user_id, country, subscription_type, age)
2. **Duplicate Records** — Checked for duplicate user_id entries using `GROUP BY` + `HAVING`
3. **Outlier Check** — Validated age values (filtered out age < 18 or age > 100) → Result: 0 outliers
4. **Monthly Fee Validation** — Checked for zero or negative fee records → Result: No invalid fees found

---

## 📊 Exploratory Data Analysis — Questions Explored

| # | Question |
|---|---|
| Q1 | Total number of users |
| Q2 | Average age of Netflix users |
| Q3 | Count of users by country |
| Q4 | Distribution of subscription types |
| Q5 | Most popular genre |
| Q6 | Gender distribution by country |
| Q7 | Top 5 countries with highest Premium subscribers |
| Q8 | Total monthly revenue by subscription plan |
| Q9 | Most preferred payment method by country |
| Q10 | Country with highest content completion rate |
| Q11 | Subscription plan with highest churn rate |

---

## 🔑 Key Findings

- 🌎 **Brazil, USA, and India** are Netflix's top 3 markets by total user count
- 👤 **Average user age is 41**, indicating strong engagement among mature audiences
- 💳 **Standard plan** generates the highest monthly revenue ($245,835) and has the most users (19,931)
- 🎬 **Documentary** is the most popular genre across the platform
- 🏆 **USA leads** in both Premium subscribers (1,609) and content completion rate (65.03%)
- ⚠️ **Premium plan has the highest churn percentage (20.39%)** — a key retention risk
- 💰 **PayPal** is the most preferred payment method, followed by Credit Card and UPI

---

## 📈 Revenue Summary

| Subscription Plan | Monthly Revenue |
|---|---|
| Standard | $245,835.69 |
| Premium | $187,125.04 |
| Basic | $183,206.27 |

---

## 📄 Full Case Study

👉 [Netflix User Behavior Final_SQL.pdf](./Netflix_User_Behavior_Final_SQL_.pdf)

---

## 💡 Business Recommendations

- **Reduce Premium churn** by improving perceived value — exclusive content or perks for Premium users
- **Focus marketing in Brazil and India** — large user bases with room to upsell to higher plans
- **Invest in Documentary content** — highest genre preference across the platform
- **Leverage PayPal & UPI** as primary payment options in regional campaigns

---

## 👤 Author

**Nikhil Sharma**
📧 Connect with me on [LinkedIn](https://www.linkedin.com/in/YOUR_LINK_HERE)
🐙 [GitHub](https://github.com/nik09-DA)
