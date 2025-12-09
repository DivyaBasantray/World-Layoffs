# Layoff Dataset – SQL Data Cleaning Project

This project focuses on cleaning a raw layoff dataset using SQL. The goal was to transform messy data into a reliable, analysis-ready dataset.

---

## 🔍 Project Overview

The raw layoff dataset had several issues, including inconsistent values, missing entries, formatting problems and duplicate records. This project documents the full cleaning workflow with clear SQL scripts that show how each issue was handled.

---

## 🧹 Key Cleaning Steps

### 1. Standardized column values
- Fixed inconsistent company names  
- Standardized industry labels  
- Cleaned country and location formatting  
- Converted text-based dates into proper date format

### 2. Handled missing and incorrect values
- Identified NULLs  
- Replaced or corrected missing fields  
- Cleaned illogical numeric values

### 3. Removed duplicates and validated data
- Used window functions to detect duplicate rows  
- Applied ROW_NUMBER() to keep only the correct entries  
- Verified record counts after cleaning

### 4. Fixed structural issues
- Trimmed extra spaces  
- Normalized columns  
- Cleaned percentage and numeric fields for accurate calculations

---

## 🗂️ Files in This Repository
- `layoff_data_cleaning.sql` – Complete SQL script with step-by-step cleaning

---

## 🛠️ Tools Used
- MySQL  
- Reference: Alex The Analyst (YouTube)

---

## 📊 What You Can Do With This Cleaned Dataset
- Industry-wise analysis  
- Country-specific layoff trends  
- Company-level comparisons  
- Time-series pattern analysis

---

## 📘 Learning Outcome
This project helped build strong SQL cleaning skills, including:
- Working with inconsistent text fields  
- Cleaning categorical and numeric data  
- Using window functions for duplicates  
- Writing clear SQL queries  
- Preparing datasets for deeper analysis
