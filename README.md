# Hospital-Emergency-Room-Dashboard

## **Project Title**

**Hospital Emergency Room Analytics Dashboard**

An interactive Excel dashboard designed to monitor hospital emergency room performance by analyzing patient volume, wait times, admission status, satisfaction scores, and department referrals.

---

## **Short Purpose**

The Hospital Emergency Room Dashboard helps hospital administrators monitor patient flow and operational efficiency through interactive KPIs and visual reports.

The dashboard enables stakeholders to analyze patient demographics, track wait times, monitor admission rates, evaluate department referrals, and improve overall healthcare service delivery.

---

## **Tech Stack**

The dashboard was built using the following tools and technologies:

* **Microsoft Excel** — Primary platform for dashboard development
* **Power Query** — Data import, cleaning, transformation, and shaping
* **Power Pivot** — Data modeling and relationship management
* **DAX (Data Analysis Expressions)** — Calculated columns, measures, and KPIs
* **Pivot Tables & Pivot Charts** — Interactive reporting and data summarization
* **Slicers & Timeline Filters** — Dynamic filtering by Month and Year
* **Excel Charts & Conditional Formatting** — Dashboard visualization and KPI presentation

---

## **Data Source**

Source data used in the dashboard:

* Hospital Emergency Room patient records
* Patient demographics
* Admission status
* Department referral details
* Wait time records
* Patient satisfaction scores

The dataset includes information such as:

* Patient ID
* Age
* Gender
* Admission Status
* Wait Time
* Referral Department
* Visit Date
* Satisfaction Score

---

## **Data Cleaning & Transformation**

Performed using **Power Query**:

* Removed duplicate and null records
* Corrected data types
* Replaced missing values
* Split and transformed date columns
* Created a Calendar Table for time-based analysis
* Added calculated columns for:

  * Age Group
  * Wait Time Status (On-Time/Delayed)
  * Visit Month and Year

---

## **Data Modeling**

Created a relational data model using:

* Power Pivot Data Model
* One-to-many relationships
* Calendar table for time intelligence
* Common lookup tables

Tables connected:

* Patient Data
* Calendar Table
* Department Table
* Admission Status Table

---

## **DAX Measures Created**

Key DAX measures used in the dashboard:

| Measure                    | Purpose                                 |
| -------------------------- | --------------------------------------- |
| Total Patients             | Counts total patient visits             |
| Average Wait Time          | Calculates average patient waiting time |
| Patient Satisfaction Score | Average satisfaction rating             |
| Admission Count            | Number of admitted patients             |
| Non-Admission Count        | Number of non-admitted patients         |
| On-Time Patients           | Patients seen within 30 minutes         |
| Delayed Patients           | Patients waiting more than 30 minutes   |
| Referral Count             | Total department referrals              |

---

## **Dashboard Features**

### KPI Cards

* Total Patients
* Average Wait Time
* Patient Satisfaction Score
* Admission Status

### Interactive Visuals

* Patient Age Distribution
* Gender Analysis
* Admission Status Analysis
* Department Referral Analysis
* Patients Seen Within 30 Minutes
* Monthly Trend Analysis

### Filters / Slicers

* Month
* Year

---

## **Business Insights**

Some key insights identified from the dashboard:

* Monitored total emergency room patient visits and admission rates.
* Identified average patient wait time and percentage of patients seen within 30 minutes.
* Analyzed patient demographics using age group and gender distributions.
* Evaluated department referral patterns to optimize resource allocation.
* Tracked patient satisfaction to support improvements in healthcare service quality.

---

## **Conclusion**

The Hospital Emergency Room Dashboard provides a comprehensive overview of emergency room operations, enabling stakeholders to monitor key healthcare metrics and improve patient care through data-driven decision-making.

The project demonstrates skills in:

* Excel Dashboard Development
* Power Query (ETL)
* Power Pivot Data Modeling
* DAX Calculations
* Data Cleaning & Transformation
* Pivot Tables & Pivot Charts
* Interactive Dashboard Design
* Healthcare Data Analysis
* Business Intelligence & Reporting
