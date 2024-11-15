# Employee Attendance and Attrition Analysis
This repository contains a comprehensive HR data analytics project, focusing on employee attendance trends and attrition factors. The analysis leverages Power BI and Advanced Excel to uncover actionable insights, enabling HR departments to optimize work policies and improve employee retention strategies.

## Project Overview
### Objective
Analyze employee attendance data to identify working preferences (Work From Office vs. Work From Home).
Determine trends in sick leave usage, including:
Percentage of employees taking sick leave on a given day.
Frequency of sick leaves across the workforce.
### Tools and Techniques
Power BI: Used for interactive data visualization and dashboard creation.
Advanced Excel: Applied for data preparation, cleaning, and basic exploratory analysis.
DAX: Utilized for creating calculated metrics and deriving insights within Power BI.
### Dataset Description
The dataset includes anonymized employee attendance records and demographic information. Key attributes:

Employee ID: Unique identifier for each employee.
Work Mode: Indicates if the employee is working from home or office.
Attendance Status: Captures the employee's status (Present, Sick Leave, etc.).
Date: Tracks daily attendance data.
Other Columns: May include job role, department, and tenure for contextual analysis.


## Analysis and Insights

### 1. Working Preference Analysis
Goal: To determine whether employees prefer working from home or office.

Steps:
Data Preparation:
Filter records for "Work From Home" and "Work From Office."
Aggregate the count of days employees chose each mode.

Visualization:
Bar chart comparing the total days for "Work From Home" vs. "Work From Office."
Interactive slicer by department, job role, or tenure for detailed exploration.

Insights:
Percentage distribution of work mode preference.
Departments or roles with a stronger inclination toward remote work.

### 2. Sick Leave Analysis
Goal: To analyze trends in sick leave usage, focusing on frequency and percentage.

Steps:

Daily Sick Leave Percentage:
Calculate the number of employees taking sick leave on each date.
Divide this count by the total number of employees to get a daily percentage.
Plot a line chart to observe patterns over time.

Frequency of Sick Leaves:
Count the total sick leaves for each employee.
Categorize employees into groups based on leave frequency (e.g., 0–2 days, 3–5 days, etc.).
Create a histogram to display the distribution.

Visualization:
Heatmap showing sick leave trends by day of the week.
Department-wise breakdown of frequent sick leave takers.

Insights:
Days with the highest percentage of employees on sick leave.
Common patterns, such as high sick leave frequency on Mondays or Fridays.
Departments requiring health and wellness interventions.
