🔍 Project Overview
This Power BI dashboard explores patient waitlist trends across specialties, case types, and age profiles. It helps healthcare providers identify key bottlenecks, monitor performance over time, and prioritize interventions.

The project was built to practice real-world data analysis skills and showcase practical dashboarding capabilities.

📁 Dataset Description
Each record in the source data includes:

Patient_ID: Unique identifier

Waitlist_Date: Entry date to waitlist

Age: Patient age

Specialty: Medical specialty (e.g., Cardiology)

Case_Type: Case classification (Elective/Emergency)

Status: Waitlist status (Active/Completed)

District: Hospital region

Gender: Patient gender

Entry_Channel: Registration method (Referral, Walk-in, etc.)

🧩 Data Model Structure
Table Name	Description
Inpatient	Contains inpatient data and specialty breakdowns
Outpatient	Focuses on outpatient volumes and age grouping
All_Data	Aggregated table for summary metrics
Mapping_Specialty	Maps and groups specialty names for uniform filtering
Includes fields like Age_Profile, Specialty_Name, Case_Type, Median Wait List, PY Latest Month Wait List, and Archive_Date.

📊 Dashboard Highlights
Wait List Comparison

Latest Month: 709K

Previous Year Same Month: 640K

Wait List Bifurcation (Case Type)

Top 5 Specialties with Highest Wait Lists

📈 Visualizations
Monthly trends from July 2018 to January 2021

Age profile vs time band waitlist analysis

Specialty hotspots

Patient status breakdown

Geographic filtering by district

🧠 Smart Filters
Archive_Date

Specialty_Name

Case_Type

⚙️ Tools Used
Power BI

Excel (Data Preprocessing)

GitHub (Version Control)
