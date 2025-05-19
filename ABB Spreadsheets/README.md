# 🏙️ Manhattan Airbnb Vacation Rental Analysis - Sprint 1

## 📊 Overview

This project analyzes the Manhattan vacation rental market using Airbnb listing and calendar data to uncover high-performing neighborhoods and property types. The goal is to provide investment guidance by identifying which combinations of neighborhood and bedroom count are most attractive and how much revenue top listings can generate.

**Deliverable:** [View Full Analysis (PDF)](./ABB%20spreadsheet.pdf)

---

## 📌 Project Objectives

### 1. Identify Attractive Neighborhoods and Property Sizes
- **Metric used:** `number_of_reviews_ltm` (last 12 months)
- **Top neighborhoods:** 
  - Lower East Side
  - Hell's Kitchen
  - Harlem
- **Most popular property sizes:**
  - Studios
  - 1-bedrooms
  - 2-bedrooms

### 2. Estimate Revenue Generation
- Revenue was calculated using `adjusted_price` for booked dates in the calendar data.
- Top listings were identified using pivot tables and filtered based on popularity and location.
- The highest earning listing ID: `49946551`
  - **30-day Revenue:** $29,940  
  - **Estimated Annual Revenue:** $359,280

---

## 🛠️ Methods

### 📁 Data Cleaning
- Standardized `neighborhood` values (`neighborhood_clean`)
- Converted empty `bedrooms` cells to 0 (`bedrooms_clean`)
- Created `top_listing` column to filter optimal listings
- Calculated `revenue_earned` in calendar data and mapped to listings

### 📊 Pivot Table Analysis
- Identified trends in listing popularity and size by neighborhood
- Used reviews as a proxy for rental demand
- Aggregated revenue data to estimate profitability

---

## 📈 Visuals & Charts
- Bar chart of Top 10 neighborhoods by review volume
- Pivot tables summarizing:
  - Review counts by neighborhood and bedroom
  - Revenue estimates for top listings

---

## 📌 Key Recommendations

- **Invest in 1-bedroom properties** in most top neighborhoods (except Midtown, where studios perform best).
- Focus investment in the following neighborhoods: Lower East Side, Hell’s Kitchen, Harlem.
- Monitor and optimize for review frequency, as it's a strong proxy for occupancy and income.

---

## ✅ Completion Checklist

- [x] Cleaned and documented raw data
- [x] Created executive summary and TOC
- [x] Used consistent formatting and cell styles
- [x] Included calculated fields and assumptions
- [x] Shared deliverable for stakeholder review

---

## 🔗 Resources

- [NYC Airbnb Data](https://insideairbnb.com/get-the-data.html)  
- [Sprint Project Brief](#) *(Link to brief if available)*

---

## 🧾 License

This project is for educational and portfolio purposes only. Data used from publicly available sources.

---

## 👤 Author

*LaShawn Adams*  
*BI Analyst in Training*


