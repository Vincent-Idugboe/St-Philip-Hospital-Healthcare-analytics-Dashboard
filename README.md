# St-Philip-Hospital-Healthcare-analytics-Dashboard
Multi page Power BI dashboard analysing patient volumes, revenue distribution, departmental performance, and workforce data for St Philip Hospital
Overview
A multi-page interactive healthcare analytics dashboard built in Microsoft Power BI, analysing operational performance, population health trends, and workforce data for St Philip Hospital. The dashboard provides senior management with a single unified view of hospital activity, enabling data-driven decisions across patient care, revenue management, and staffing.

Problem Statement

Hospital management required clear visibility into key operational metrics — including patient volumes, revenue distribution, departmental efficiency, and workforce performance — to identify bottlenecks, optimise resources, and improve patient outcomes. Raw data alone was insufficient for strategic decision making without structured analysis and visual reporting.

Tools & Techniques

Microsoft Power BI — dashboard development and visualisation
Power Query — data transformation and cleaning
DAX (Data Analysis Expressions) — custom measures and calculated columns for KPIs
Data Modelling — table relationships built to enable cross-filtering across pages
Real-world hospital dataset — patient records, revenue data, and employee information

Dashboard Structure
Page 1 — Hospital Visit & Revenue
Tracks core operational KPIs and financial performance across the hospital.
Key metrics displayed:

Average Wait Time: 92.36 minutes
Total Doctors: 100
Total Patients: 2,000
Total Visits: 10,000
Total Revenue: $24.3M
Insured Patients: 69.4%

Visuals included:

Revenue distribution by US State — map visual identifying California and Texas as highest revenue-generating states
Number of Patients by Month — area chart revealing seasonal patient volume fluctuations throughout the year
Age Group Distribution — Adults lead at 278, followed by Seniors at 265, with Teenagers the smallest cohort at 59
Health Condition of Patients — horizontal bar chart breaking down the prevalence of conditions including hypertension, diabetes, and asthma across the patient population

Page 2 — Population Health
Examines patient demographics and health behaviour patterns.
Key metrics displayed:

Gender split: 983 male patients (49.57%) vs 1,000 female patients (50.43%)
Percentage of smokers: 49.72% and 49.17% across patient segments

Visuals included:

Donut chart showing gender distribution across the patient population
Smoker percentage gauges by patient segment — highlighting that nearly half the patient population are smokers, a critical public health insight for resource planning and preventative care prioritisation

Page 3 — Employee Tab
Analyses medical workforce composition, speciality experience, and departmental performance.
Key metrics displayed:

Doctor gender split: 54 male (54%) vs 46 female (46%)
Average spend: $2.43K
Total Revenue: $24.3M

Visuals included:

Treemap of Years of Experience across specialities — Cardiology and Paediatrics hold the largest experience pools
Top 10 Doctors by Patient Attendance — bar chart identifying highest performing clinicians
Avg Effectiveness Satisfaction across Department — Cardiology leads at 8.2, Dermatology lowest at 7.3
Department summary table showing Total Doctors, Total Patients, Avg Doctor Satisfaction, and Readmission Rate — Paediatrics handles the highest patient load at 1,211 patients across 19 doctors


Key Insights Uncovered

Revenue concentration — California and Texas account for the majority of hospital revenue by state, suggesting geographic dependency risk
Seasonal demand — Patient volumes peak in March and September, dip sharply in May and July — directly informing staffing and resource planning cycles
Insurance gap — 30.6% of patients are uninsured, representing a significant revenue recovery and financial risk management opportunity
Paediatrics under pressure — Highest patient volume department (1,211 patients) yet satisfaction and readmission metrics suggest capacity strain
Cardiology efficiency — Highest satisfaction score (8.2) with strong revenue contribution despite the smallest doctor count (8), indicating high-performing clinical efficiency
Smoking prevalence — Nearly 50% of patients are smokers across all segments, with direct implications for long-term condition management and preventative care investment


Technical Highlights

Built DAX measures for dynamic KPI calculations including average wait time, revenue totals, insurance percentages, and satisfaction scores
Created table relationships enabling seamless cross-page filtering between patient, revenue, and employee datasets
Designed consistent dark theme UI with teal accent colour scheme for professional visual clarity and readability
Implemented navigation tabs for multi-page user experience, replicating enterprise dashboard standards


What This Demonstrates
This project demonstrates the ability to take raw hospital data, model it relationally, apply DAX logic for meaningful KPIs, and present findings in a format that non-technical stakeholders — including hospital directors, finance leads, and HR managers — can act on immediately.
Tools Used
Microsoft Power BI DAX Power Query Data Modelling Healthcare Analytics Real Dataset









