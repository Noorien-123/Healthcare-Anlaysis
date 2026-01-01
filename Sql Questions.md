# Healthcare Analytics Dashboard Project:

#  

# Project Overview

# This project is a Healthcare Analytics Dashboard built using Power BI with a cleaned and

# structured dataset stored in healthcare\_dataset\_clean.xlsx. The goal of the project is to

# analyze patient demographics, hospital utilization, doctor performance, and financial metrics

# to support data-driven healthcare decisions.

# The Power BI file (healthcare dashboard (1).pbix) connects to the Excel dataset and provides

# interactive visualizations such as KPIs, charts, and filters for healthcare insights.

#  

# Project Objectives

# • Analyze patient demographics and medical conditions

# • Track hospital capacity and utilization

# • Understand doctor specialization and experience distribution

# • Monitor billing amounts and insurance providers

# • Enable interactive reporting through Power BI



# Dataset Description

# The dataset is stored in healthcare\_dataset\_clean.xlsx and consists of three sheets:

# 1\. Patients

# 2\. Doctors

# 3\. Hospitals

# Each sheet represents a different entity in the healthcare system and is related through

# unique IDs.



# Sheet 1: Patients

# This sheet contains patient-level information, including demographics, admission details,

# and billing data.

# Column Descriptions

# • PatientID: Unique identifier for each patient

# • Name: Full name of the patient

# • Age: Age of the patient in years

# • Gender: Gender of the patient (e.g., Male, Female)

# • Medical Condition: Primary medical condition or diagnosis of the patient

# • Date of Admission: Date when the patient was admitted to the hospital

# • Discharge Date: Date when the patient was discharged from the hospital

# • DoctorID: Unique identifier of the doctor assigned to the patient (foreign key linked

# to Doctors sheet)

# • HospitalID: Unique identifier of the hospital where the patient was treated (foreign

# key linked to Hospitals sheet)

# • Insurance Provider: Name of the patient’s insurance provider

# • Billing Amount: Total billed amount for the patient’s treatment



# Sheet 2: Doctors

# This sheet contains information about doctors and their professional background.

# Column Descriptions

# • DoctorID: Unique identifier for each doctor

# • Doctor Name: Full name of the doctor

# • Specialization: Medical specialization of the doctor (e.g., Cardiology, Neurology)

# • Experience (Years): Number of years of professional medical experience



# Sheet 3: Hospitals

# This sheet stores hospital-level details including location and capacity.

# Column Descriptions

# • HospitalID: Unique identifier for each hospital

# • Hospital Name: Official name of the hospital

# • City: City where the hospital is located

# • Capacity: Maximum number of patients the hospital can accommodate

#  

# Data Relationships

# • Patients.DoctorID → Doctors.DoctorID (Many-to-One)

# • Patients.HospitalID → Hospitals.HospitalID (Many-to-One)

# These relationships are used in Power BI to create meaningful cross-entity analysis.

# Power BI Dashboard Features

# • Patient count, average age, and total billing KPIs

# • Admissions and discharges over time

# • Billing analysis by hospital and insurance provider

# • Doctor specialization and experience analysis

# • City-wise hospital capacity overview



# Tools \& Technologies

# • Power BI: Data modeling and visualization

# • Microsoft Excel: Data storage and cleaning

#  

# Usage Instructions

# 1\. Open healthcare dashboard (1).pbix in Power BI Desktop

# 2\. Ensure healthcare\_dataset\_clean.xlsx is in the same directory or update the data

# source path

# 3\. Refresh data to load the latest dataset

# 4\. Use slicers and filters to explore insights



# Dashboard Charts Explanation

# 1\. Total Patients (KPI Card)

# • What it shows: Total number of unique patients in the dataset

# • Purpose: Provides a quick snapshot of patient volume

# • Insight: Helps assess overall hospital workload

# • 2. Average Patient Age (KPI Card)

# • What it shows: Average age of all admitted patients

# • Purpose: Understand patient demographic distribution

# • Insight: Useful for identifying age groups requiring more healthcare resources

# 3\. Total Billing Amount (KPI Card)

# • What it shows: Sum of all patient billing amounts

# • Purpose: Tracks total revenue generated

# • Insight: Helps monitor financial performance of hospitals

# 4\. Admissions Over Time (Line Chart)

# • What it shows: Number of patient admissions by admission date

# • Purpose: Identifies trends and seasonality in hospital admissions

# • Insight: Peaks may indicate outbreaks or seasonal illnesses

# 5\. Patients by Medical Condition (Bar Chart)

# • What it shows: Count of patients grouped by medical condition

# • Purpose: Identifies the most common health issues

# • Insight: Helps hospitals allocate specialized doctors and equipment

# 6\. Billing Amount by Hospital (Bar Chart)

# • What it shows: Total billing amount generated by each hospital

# • Purpose: Compares financial performance across hospitals

# • Insight: Highlights top-performing and underperforming hospitals

# 7\. Patients by Insurance Provider (Donut / Pie Chart)

# • What it shows: Distribution of patients across insurance providers

# • Purpose: Understand insurance dependency and coverage trends

# • Insight: Useful for negotiation and policy planning with insurers

# 8\. Doctor Specialization Distribution (Bar Chart)

# • What it shows: Number of doctors by specialization

# • Purpose: Evaluates availability of medical expertise

# • Insight: Identifies shortage or surplus of specialists

# 9\. Doctor Experience Analysis (Histogram / Bar Chart)

# • What it shows: Doctors grouped by years of experience

# • Purpose: Understand experience distribution in the workforce

# • Insight: Helps assess training needs and senior-to-junior balance

# 10\. Hospital Capacity by City (Bar Chart)

# • What it shows: Total hospital capacity aggregated by city

# • Purpose: Compares healthcare infrastructure across locations

# • Insight: Identifies cities with limited or high medical capacity

# 11\. Interactive Filters \& Slicers

# • Common slicers: City, Hospital Name, Gender, Medical Condition, Insurance Provider

# • Purpose: Enable drill-down analysis

# • Insight: Allows users to focus on specific subsets of data for deeper insights



# Author

# Display the first 10 transportation records.

# 

# How many trips are recorded in the transportation dataset?

# 

# What is the average number of vehicles recorded per trip?

# 

# How many records are there for each vehicle type?

# 

# How many records fall under each traffic density level?

# 

# How many records report that an accident occurred versus not occurred?

# 

# What is the count of accidents by severity level (only where accidents occurred)?

# 

# How many alerts were generated versus not generated?

# 

# Which roads have the highest traffic based on total vehicle count (top 5 roads)?

# 

# Which roads experience both high traffic density and recorded accidents?

