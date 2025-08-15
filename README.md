# Google-Looker-Studio-Sales-Dashboard---Internship-Project
Hello there.

This repository contains the internship project deliverables for the assigned sales analytics tasks.  
The work is implemented using **Google Looker Studio** with visualisations, charts and filters to address the given business scenarios.
  
I have included a report which covers: 
- Introduction  
- Background  
- Learning Objectives  
- Activities & Tasks  
- Skills & Competencies  
- Feedback & Evidence  
- Challenges & Solutions  
- Outcomes & Impact  
- Conclusion  

## 📊 Tasks Implemented

### **Task 1 – Top 5 Products by Sales in 2022 (Mobiles & Tablets)**
- Filtered data to category = "Mobiles & Tablets", year = 2022, is_valid = 1.
- Aggregated by `sku_name` and sorted by total `qty_ordered`.
- Visualized as a **horizontal bar chart**.

---

### **Task 2 – Sales Decrease in "Others" Category (2021 vs 2022)**
- Created datasets for each year and calculated differences.
- Classified changes as "DOWN", "UP", or "FAIR".
- Displayed the **top 20 products with the largest decline**.

---

### **Task 3 – Customers Who Checked Out(is_gross =1) but Didn't Pay (2022)**
- Filtered transactions: `is_gross = 1`, `is_valid = 0`, `is_net = 0`.
- Removed duplicates on `customer_id`.
- Presented unique **customer_id** with **registered_date**.

---

### **Task 4 – Weekend vs Weekday Sales in 2022**
- Calculated average `before_discount` for weekends vs weekdays.
- Displayed monthly and overall comparisons.

---

### **Task 5 – Largest Sales Drop Between Two Periods**
- Compared `qty_ordered` for each `sku_name` between 2021 and 2022.
- Visualized **top 10 declines** as a bar chart.

## 🛠 Tools Used
- **Google Looker Studio** – Dashboard creation and data visualization.
- **Google Sheets / CSV Upload** – Data source management.
- **Python (Pandas)** – Data preprocessing and calculations before importing to Looker.

---

## 📬 Submission Details
This repository is created for submission as part of the internship requirements.  
It contains:
1. **Live Looker Studio dashboard link**
2. **Internship report (PDF)**
3. Documentation for each task
