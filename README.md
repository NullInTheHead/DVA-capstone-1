# Retail Store Sales Performance Dataset

## Project Overview

This dataset contains detailed transactional sales records from a retail store environment. It was used to perform revenue analysis, discount evaluation, KPI development, and operational performance assessment. The dataset required cleaning and transformation before analytical use.

---

## File Details

**Total Records:** 12,575 transactions
**Primary Key:** Transaction ID
**Time Period:** Multi-period retail transactions (as provided)
**Granularity:** One row per transaction

---

## Data Dictionary

| Column Name      | Description                     | Data Type         |
| ---------------- | ------------------------------- | ----------------- |
| Transaction ID   | Unique identifier for each sale | String            |
| Customer ID      | Unique customer reference       | String            |
| Category         | Product category                | Categorical       |
| Item             | Specific product name           | Categorical       |
| Price Per Unit   | Unit price                      | Numeric (Float)   |
| Quantity         | Units purchased                 | Numeric (Integer) |
| Total Spent      | Total transaction value         | Numeric (Float)   |
| Payment Method   | Mode of payment                 | Categorical       |
| Location         | Store location                  | Categorical       |
| Transaction Date | Date of purchase                | Date              |
| Discount Applied | Discount indicator              | Numeric (Binary)  |

---

## Key Metrics

**Total Revenue:** Derived from Total Spent
**Total Transactions:** 12,575
**Top Revenue Drivers:** High-performing product categories
**Discount Impact:** Discounts do not significantly increase transaction frequency

---

## Analysis Focus

* Revenue concentration by category
* Discount effectiveness evaluation
* Monthly and day-of-week sales trends
* Operational data quality assessment

---

## Data Cleaning Notes

* Missing items replaced with “Unknown”
* Missing discount values assumed as 0
* Missing price/quantity derived where possible
* Zero-value transactions flagged for monitoring
* Month and Day of Week derived for trend analysis

---

GO SUBMIT. YOU ARE SAFE. 🚀
