# 🏥 Power BI Project: Healthcare Waitlist Analysis

## 📁 Project Description

This Power BI project focuses on analyzing healthcare patient waitlist data to uncover patterns in appointment delays, patient counts, and departmental efficiency. It helps identify key issues in patient management and offers data-driven insights to improve healthcare services.

---

## 📊 Dataset Overview

Each row in the dataset represents a patient entry in the healthcare waitlist and includes the following features:

- **Patient_ID**: Unique identifier for each patient  
- **Age**: Age of the patient  
- **Gender**: Gender of the patient (e.g., Male, Female, Other)  
- **Department**: Medical department (e.g., Cardiology, Orthopedics)  
- **Appointment_Date**: Date scheduled for the appointment  
- **Registration_Date**: Date when the patient registered  
- **Wait_Days**: Number of days the patient had to wait  
- **Priority_Level**: Level of urgency (e.g., High, Medium, Low)  
- **Status**: Whether the appointment is completed, cancelled, or pending  
- **Hospital_Branch**: Location of the hospital branch

---

## 📈 Key Insights & Visuals

- Average wait time by department  
- Patient count by gender and age group  
- Top 5 departments with longest waitlists  
- Percentage of high-priority cases  
- Status-wise patient breakdown  
- Comparison of wait times across hospital branches

---

## ⚙️ Tools Used

- Power BI (Dashboard & Data Model)  
- Microsoft Excel (Data Cleaning)

---

## 🔧 How It Was Built

1. **Data Cleaning:**
   - Imported raw CSV/XLSX data into Power BI.
   - Handled missing values and duplicates.
   - Standardized date formats and column names.

2. **Data Modeling:**
   - Created relationships between tables (e.g., Patients ↔ Treatments).
   - Used `Date` table for time-based analysis.

3. **DAX Measures:**
   - Total Admissions, Discharges, Success Rate, etc.

4. **Visualizations:**
   - Pie charts for gender distribution.
   - Bar charts for treatments per department.
   - Line charts for admissions over time.

   ---

   ## 📚 Folder Structure

```
Healthcare-Waitlist-Dashboard/
│
├── Data/
│
├── dashboard_screenshot.png
│
├── Healthcare_Waitlist_Dashboard.pbix
│
└── README.md

```

- DAX (Measures and Calculated Columns)

---
