# 📊 Excel Data Cleaning & Pivot Table Analysis

## 📌 Project Overview
Is project me maine ek **1500+ rows** ke messy aur complicated retail sales dataset ko complete clean kiya hai aur Excel Pivot Tables ka use karke real business insights generate kiye hain.

---

## 🛠️ Data Cleaning Challenges Solved
Pivot Table lagane se pehle data me kaafi issues the, jinhe maine in techniques se fix kiya:
1. **Remove Duplicates:** Data me se saare duplicate rows ko identify karke delete kiya (`Data Tab -> Remove Duplicates`).
2. **Text Standardization (Casing):** `Payment Method` aur `Customer Segment` me lowercase/uppercase ki errors thin (jaise `upi` aur `UPI`). Unhe `=UPPER()` formula aur *Paste Special Values* ka use karke uniform CAPITAL letters me convert kiya.
3. **Handling Missing Values:** `Region` aur `City` columns ke blank (missing) cells ko filter karke unhe **"Unknown"** text se fill kiya taaki Pivot Table me blank errors na aayein.

---

## 📈 Key Insights & Results (Pivot Table Analysis)

* **Task 1: Top Region by Sales**
  - **North Region** sabse top par raha, jahan **₹1,01,82,546** ki sabse zyada sales hui.
  
* **Task 2: Category & Product Breakdown**
  - Data ko hierarchical structure me row-wise set kiya (Category -> Product) jisse pata chala ki `ELECTRONICS` me `LAPTOP` aur `CLOTHING` me `JACKET` top-selling items hain.

* **Task 3: Date wise Sales Trend**
  - `Order Date` column ke through pure 1.5 years ka sales breakdown analyze kiya.

* **Task 4: Payment Method Break-up**
  - **CASH (₹1.02 Crore+)** sabse zyada prefer kiya jaane wala payment mode raha, jiske baad **UPI** ka number aata hai.

---

## 💻 Tech Stack Used
* **Tool:** Microsoft Excel (Excel Online)
* **Features:** Pivot Tables, Data Filters, Text Formulas (`UPPER`), Paste Special, Formatting.
