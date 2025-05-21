# 🛒 E-Commerce Funnel and Retention Analysis

This project showcases my ability to transform raw user activity logs into business metrics that provide strategic insights into customer behavior. The analysis was performed using Google Sheets and follows a structured approach to assess conversion performance and user retention for an e-commerce company.

---

## 📋 Project Overview

**Objective:**  
Analyze raw event logs to build a 3-step conversion funnel and cohort-based retention rates over time. Deliver insights that help the executive team understand where users drop off and how long they continue purchasing after their first transaction.

**Tools Used:**  
Google Sheets (Pivot Tables, VLOOKUP, TEXT, DATEDIF, and custom formulas)

---

## 🔍 Key Business Questions Answered

1. **How effectively does the website convert visitors into paying customers?**  
2. **How well are we retaining customers after their first purchase?**  
3. **What patterns emerge across acquisition cohorts over multiple months?**

---

## 📊 Results Summary

| 📈 Metric            | 🔎 Insight                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| Conversion Funnel     | ~90% drop-off between viewing a product and shopping cart engagement       |
| Retention Rates       | Revenue and active users consistently declined month-to-month              |

---

## 📑 Analysis Breakdown

### 🔄 Conversion Funnel

- Built using **raw user activity logs** (`raw_user_activity` tab)
- 3 funnel stages:
  1. Viewing product pages
  2. Opening the shopping cart
  3. Completing a purchase
- Calculated both total conversion and step-wise conversion rates using formulas
- Used unique `user_id` counts to maintain accuracy

### 📆 Cohort Analysis & Retention Rates

- Users grouped by **month of first purchase**
- Created a custom pivot table to track each cohort's repeat purchase behavior
- Calculated **cohort age** (months since first purchase)
- Computed **retention rates** using unique user counts and formulas
- Observed significant drop-off in retention after the first month across all cohorts

---

## 📂 Sheets & Data Flow

| Sheet Name           | Description                                                                 |
|----------------------|------------------------------------------------------------------------------|
| Table of Contents     | Organized view of all sheets and their purpose                              |
| Executive Summary     | High-level synopsis of results and methodology                              |
| conversion_funnel     | Funnel stage data with user counts and conversion rates                     |
| cohort_analysis       | Pivot table displaying cohort behaviors by month                            |
| retention_rates       | Final retention rate calculations for cohorts                               |
| first_purchase        | First purchase date per user (used for cohort grouping)                     |
| purchase_activity     | Filtered event log showing only purchase data                               |
| raw_user_activity     | Complete raw dataset of all events, including views and cart activity       |

---

## 📌 Skills Demonstrated

- Data cleaning and filtering
- Advanced spreadsheet functions: `VLOOKUP`, `TEXT`, `DATEDIF`
- Funnel metrics and drop-off analysis
- Cohort analysis and retention rate modeling
- Clear communication of business metrics via structured dashboards

---

## 🧠 Key Takeaways

- A large portion of users view products without advancing to checkout
- Customer retention falls off steeply after the first month
- These insights highlight areas for UX optimization and customer engagement strategies

---

## 📬 Contact

**LaShawn Adams**  
[Email](lashawnadams91@gmail.com) • [LinkedIn](https://www.linkedin.com/in/lashawn-adams/) • [GitHub](https://github.com/LasAdams)

---

> *"From raw logs to revenue insights—data speaks, I translate."*
