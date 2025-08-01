# 🏥 Healthcare Waitlist Dashboard (Power BI Project)

This Power BI project analyzes patient waitlist data across different case types (*Outpatient, Day Case, Inpatient*), age profiles, and specialties. It helps visualize bottlenecks and trends over time, supporting data-driven healthcare decision-making.

---

## 📁 Dataset Overview

Each record contains attributes like:

- **Case_Type**: Outpatient, Day Case, Inpatient  
- **Age_Profile**: 0–15, 16–64, 65+  
- **Archive_Date**: Snapshot date of the waitlist  
- **Specialty_Name**: e.g. Cardiology, Orthopaedics, ENT  
- **Time_Bands**: Wait time groupings (e.g. 0–3 months, 3–6 months)  
- **Total Wait List**: Number of patients waiting  

---

## 🎯 Project Objective

- Compare waitlist volumes across months and years  
- Highlight long-wait trends by **Case Type** and **Specialty**  
- Enable dynamic slicing using age and time bands  
- Identify service delivery bottlenecks and demand peaks  

---

## 🔍 Key Visuals & Metrics

- **KPI Cards**: Latest month vs. previous year waitlist totals  
- **Donut Chart**: Waitlist distribution by Case Type  
- **Bar Chart**: Wait times segmented by Age Profile  
- **Line Charts**: Trends over time by Case Type  
- **Top Specialties Table**: Sorted by highest waitlist count  
- **Slicers**: Filters by Date Range, Cleanup Case Type & Age Group  

---

- Inpatient / Outpatient (source split)
- Mapping_Specialty (lookup for specialty grouping)
