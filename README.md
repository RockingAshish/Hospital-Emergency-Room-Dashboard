# Hospital Emergency Room Dashboard

A Power BI dashboard project for analyzing Hospital Emergency Room data.

---

## Steps in Project

1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Layouting
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation

---

## Dashboards — 4

1. Monthly View
2. Consolidated View
3. Patient Details
4. Key Takeaways

---

## Business Requirements

### KPI Requirements

To enhance operational efficiency and provide actionable insights into emergency room performance, we need to create a Hospital Emergency Room Analysis Dashboard in Power BI. This solution will enable stakeholders to track, analyze, and make data-driven decisions regarding patient management and service optimization.

**Number of Patients:**
- Measure the total number of patients visiting the ER daily.
- Display a daily trend using an area sparkline to understand patterns over time, such as peak days or seasonal trends.

**Average Wait Time:**
- Calculate the average time patients wait before being attended to by a medical professional.
- Use an area sparkline to show daily fluctuations and identify days with higher wait times that may require operational adjustments.

**Patient Satisfaction Score:**
- Analyze the average satisfaction score of patients on a daily basis to evaluate the quality of service provided.
- Present a daily trend using an area sparkline to identify dips in satisfaction and correlate them with operational challenges or peak times.

**Number of Patients Referred:**
- Count the number of patients referred to specific departments from the ER each day.
- Use an area sparkline to track daily trends and identify departments with high referral rates, which may require additional resources.

---

### Dashboard 1: Monthly View

**Objective:** Monitor key metrics and trends on a month-by-month basis to identify patterns and areas for improvement.

**Charts to Develop:**
- Patient Admission Status: Track admitted vs. non-admitted patients.
- Patient Age Distribution: Group patients by 10-year age intervals.
- Department Referrals: Analyze referral trends across different departments.
- Timeliness: Measure the percentage of patients seen within 30 minutes.
- Gender Analysis: Visualize patient distribution by gender.
- Racial Demographics: Analyze patient data by race.
- Time Analysis: Assess patient volume by day and hour.

---

### Dashboard 2: Consolidated View

**Objective:** Provide a holistic summary of hospital performance for a selected date range.

**Charts to Develop:**
- Similar metrics as the Monthly View, but aggregated over a customizable date range for broader insights and trend analysis.

---

### Dashboard 3: Patient Details

**Objective:** Offer granular insights into patient-level data to enable detailed analysis and troubleshooting.

**Charts to Develop:** A grid displaying essential fields:
- Patient ID
- Patient Full Name
- Gender
- Age
- Admission Date
- Patient Race
- Wait Time
- Department Referral
- Admission Status

---

### Dashboard 4: Key Takeaways

**Objective:** Summarize the findings from all dashboards to provide clear and actionable insights for stakeholders.

**Charts to Develop:**
- Descriptive analysis of each metric and visualization, including patterns, anomalies, and actionable recommendations to optimize emergency room operations and patient care.

---

## Data Terminology

**Patient ID:**
A unique alphanumeric code assigned to each patient. This serves as the primary identifier to distinguish one patient's records from another. It's essential for tracking individual cases while ensuring privacy in data analysis.

**Patient Admission Date:**
The specific date and potentially time the patient was admitted to the emergency room. This field helps analyze patterns such as peak admission times, seasonal trends, or emergency response rates.

**Patient First Initial:**
The first letter of the patient's first name, often used for anonymization purposes in datasets to comply with privacy regulations like HIPAA or GDPR.

**Patient Last Name:**
The last name of the patient. If anonymized, this field could still be useful for identifying trends or grouping by familial or cultural naming conventions.

**Patient Gender:**
The gender identity of the patient, typically recorded as Male, Female, or Other/Nonbinary. Useful for demographic studies and understanding healthcare disparities among different genders.

**Patient Age:**
The numerical age of the patient at the time of admission. This field is crucial for age-group analysis, helping identify trends such as which age groups frequently visit the emergency room and for what reasons.

**Patient Race:**
The racial or ethnic identity as self-reported by the patient. This is vital for studying healthcare access, outcomes, and disparities across different racial and ethnic groups.

**Department Referral:**
Specifies the department the patient was referred to (e.g., Orthopedics, Cardiology, Pediatrics). Analyzing this helps understand which specialties see the highest ER referrals, enabling resource allocation.

**Patient Admin Flag:**
A binary field that indicates whether a patient was officially admitted to the hospital during their visit to the Emergency Room (ER).
- **True:** The patient was admitted to the hospital for further observation, treatment, or care beyond the ER visit. This could mean being assigned to a specific department, ward, or intensive care.
- **False:** The patient was not admitted and was either discharged, referred to another facility, or given outpatient treatment.

**Patient Satisfaction Score:**
A measure, often on a scale (e.g., 1 to 5 or 1 to 10), that captures the patient's evaluation of their ER experience. High scores indicate satisfaction, while low scores suggest areas needing improvement. It's essential for service quality analysis.

**Patient Wait Time:**
The time elapsed from the patient's arrival at the ER to when they were first attended to by medical staff. This is critical for analyzing operational efficiency and patient experience.

**Patients CM (Case Manager):**
The individual or team responsible for coordinating the patient's care during their visit. The case manager ensures timely treatment, proper documentation, and post-discharge follow-up. Analysis can reveal workload distribution and case outcomes.
