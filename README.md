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


-  **Dataset Overview** - Reviewed structure, 1,200 rows × 14 columns → Confirmed `OrderID` and `TrackingNumber` fully unique
-  **Duplicate Check** - Scanned full dataset for duplicate observations → **0 duplicates found**
-  **Data Type Validation** - Verified type of every column in Power Query → All columns correctly typed (text, date, numeric)
-  **Missing Value Treatment** - Found **309 blank `CouponCode`** values (~25.8%) → Replaced with explicit label **`No Coupon`** instead of deleting rows
-  **Text Standardization** - Cleaned text fields for consistent casing/formatting → Standardized across all text columns

---

## 🧰 Tools Used

- **Microsoft Excel**
- **Power Query Editor**

---

**Prepared by:** Sandeepani Rathnayake
