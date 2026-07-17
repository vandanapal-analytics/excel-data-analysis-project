# 📊 Retail Sales Data Cleaning & Pivot Table Analysis

## 📌 Project Overview
In this project, I processed and analyzed a messy retail sales dataset containing over **1,500 rows** of transactional data. The primary objective was to clean structural inconsistencies, handle missing values, and leverage Excel Pivot Tables to extract actionable business insights.

---

## 🛠️ Data Cleaning Steps Performed
Before conducting any analysis, the dataset required rigorous cleaning to ensure data integrity:
1. **Deduplication:** Identified and eliminated duplicate records across the dataset using `Data Tab -> Remove Duplicates`.
2. **Text Standardization:** Fixed casing inconsistencies in columns like `Payment Method` and `Customer Segment` (e.g., converting mixed cases like `upi` and `UPI`) using the `=UPPER()` function combined with *Paste Special Values*.
3. **Handling Missing Values:** Screened the dataset for blank/null cells in the `Region` and `City` fields and standardized them by replacing empty cells with **"Unknown"** to prevent breakdown errors during pivot generation.

---

## 📈 Key Insights & Analytics (Pivot Table Results)

* **Top Performing Region (Task 1)**
  - The **North Region** emerged as the primary revenue driver, generating the highest total sales amounting to **₹10,182,546.11**.
  
* **Product Hierarchy & Category Breakdown (Task 2)**
  - Organised product distributions hierarchically (`Category` -> `Product`) inside the rows, highlighting that **Laptops** dominate the `ELECTRONICS` sector, while **Jackets** lead the `CLOTHING` segment.

* **Date-Wise Sales Trend (Task 3)**
  - Formatted and mapped the transaction timelines chronologically across the 1.5-year span to evaluate day-to-day revenue fluctuations.

* **Payment Method Distribution (Task 4)**
  - **CASH** remains the most dominant transactional channel, bringing in over **₹1.02 Crore**, closely followed by **UPI** as the runner-up medium.

---

## 💻 Tech Stack & Tools Used
* **Software:** Microsoft Excel (Excel Online Interface)
* **Core Techniques:** Pivot Tables, Data Filtering, Text Transformations (`UPPER`), Paste Special, Layout Formatting.
