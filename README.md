# 🧹 E-Commerce Data Cleaning & Preparation

### Data Cleaning Project | Excel & Power Query

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-blue?style=for-the-badge)
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-orange?style=for-the-badge)

---

## 📄 Project Overview

A data cleaning and preparation project built on a raw e-commerce orders dataset of **1,200 transactions** across **14 fields** covering order details, payment methods, shipping, coupons, and referral sources. The raw dataset was audited, cleaned, and standardized using **Excel Power Query**, producing a consistent, analysis-ready dataset with full documentation of every change made.

---

## 🎯 Purpose of the Project

The purpose of this cleaning process is to ensure the dataset is trustworthy before any analysis is built on top of it:

- 🔍 Identify missing or null values across all columns
- 🧬 Check for duplicate records (`OrderID`, `TrackingNumber`)
- 📅 Validate and correct data types (dates, numbers, text)
- 🏷️ Standardize text fields for consistency
- 📋 Document every change in an auditable change log

---

## 🛠️ Data Cleaning Process

| Step | Action | Result |
|---|---|---|
| 1️⃣ Dataset Overview | Reviewed structure, 1,200 rows × 14 columns | Confirmed `OrderID` and `TrackingNumber` fully unique |
| 2️⃣ Duplicate Check | Scanned full dataset for duplicate observations | **0 duplicates found** |
| 3️⃣ Data Type Validation | Verified type of every column in Power Query | All columns correctly typed (text, date, numeric) |
| 4️⃣ Missing Value Treatment | Found **309 blank `CouponCode`** values (~25.8%) | Replaced with explicit label **`No Coupon`** instead of deleting rows |
| 5️⃣ Text Standardization | Cleaned text fields for consistent casing/formatting | Standardized across all text columns |

---

## 📊 Key Results

- ✅ 1,200 records preserved
- ✅ 0 duplicate OrderIDs
- ✅ 0 missing values after cleaning (down from 309)
- ✅ 100% of records retained through cleaning

---

## 🗂️ Repository Structure

```
├── data/
│   ├── raw/
│   │   └── Dataset.csv              
│   └── cleaned/
│       └── Cleaned_Data.xlsx     
├── docs/
│   └── Data_Cleaning_Report.pdf    
└── README.md
```

---

## 🧰 Tools Used

- **Microsoft Excel**
- **Power Query Editor**

---

**Prepared by:** Sandeepani Rathnayake
