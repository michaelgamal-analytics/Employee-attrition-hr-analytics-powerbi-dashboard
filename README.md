# employee-attrition-hr-analytics-powerbi-dashboard
# HR Analytics Dashboard – Power BI

This is an end-to-end HR analytics project I built using Power BI to explore employee data and understand the key drivers behind employee attrition.

The goal of this project was to analyze the workforce, identify patterns in employee turnover, and generate insights that could help HR teams make better decisions regarding retention and workforce management.

---

## Project Objectives

In this project I focused on answering several important HR questions:

* What is the overall employee attrition rate?
* Which departments and job roles experience the highest attrition?
* How do satisfaction metrics relate to employee turnover?
* What demographic patterns exist across the workforce?
![power bi file ](<HR STUDY.pbix>)
---

## Data Modeling

I designed a structured **data model** inside Power BI to organize the HR dataset and enable efficient analysis.

Key steps included:

* Building relationships between tables
* Structuring the data to support time-based analysis
* Creating a clean model for reporting and insights
![Relationships](<Relationships.png>)
---

## DAX Calculations

To perform deeper analysis, I created multiple **DAX measures**, including:

* Attrition Rate
* Active Employees
* Total Employees
* Attrition by Department
* Attrition by Job Role

I also used advanced DAX techniques such as:

* **USERELATIONSHIP()** to activate inactive relationships for time-based calculations.
* Custom **measures** to calculate KPIs and performance indicators.
* Aggregations and conditional calculations to better analyze employee behavior.
![Measures](<Total -measures.png>)
---

## Dashboard Structure

### 1. Overview Dashboard

Provides a high-level summary of the workforce including:

* Total employees
* Attrition rate
* Department level insights
* Employee distribution

This page allows HR managers to quickly understand the overall company workforce situation.
![Overview](<Screenshot 2026-03-14 002351.png>)

---

### 2. Demographics Analysis

This section focuses on employee demographic data such as:

* Gender distribution
* Age groups
* Education level
* Marital status

These insights help understand the structure of the workforce and identify patterns across different employee groups.
![Demographics](<Screenshot 2026-03-14 203444.png>)


---

### 3. Performance & Satisfaction

This page analyzes employee satisfaction metrics including:

* Job Satisfaction
* Environment Satisfaction
* Work-Life Balance
* Relationship Satisfaction

The analysis helps determine how workplace conditions may influence employee retention.
![Performance](<Screenshot 2026-03-14 203455.png>)

---

### 4. Attrition Analysis

This section focuses specifically on employee turnover.

Key insights include:

* Departments with thDepartment-levelion
* Job roles most affected by attrition
* Travel frequency vs attrition patterns
* Attrition trends over time

These insights help identify potential retention issues and workforce risks.
![Attrition](<Screenshot 2026-03-14 203504.png>)

---

## Key Insights

Through this analysis, I discovered several important patterns:
,
* Certain departments and job roles experience significantly higher attrition rates.
* Satisfaction metrics appear to correlate with employee turnover.
* Workforce demographics reveal imbalances in some categories.

These insights can help HR teams take proactive steps to improve employee retention.

---

## Tools Used

* Power BI
* Data Modeling
* DAX Calculations
* Data Visualization
* HR Analytics

