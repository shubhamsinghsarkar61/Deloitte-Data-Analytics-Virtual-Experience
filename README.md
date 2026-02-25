# Deloitte Australia Data Analytics Virtual Experience (Forage)

This repository contains my work completed as part of the Deloitte Australia Data Analytics Virtual Experience program on Forage.

The project includes two tasks:
1. Machine downtime analysis using Tableau
2. Gender pay equality classification using Excel

---

## 🔹 Task 1: Machine Downtime Analysis (Tableau)

### Objective
- Identify the factory with the highest machine downtime.
- Identify the device type contributing most to downtime in that factory.

### Work Completed
- Imported the provided JSON telemetry dataset into Tableau.
- Created a calculated field **"Unhealthy"** (10 minutes downtime per unhealthy record).
- Built:
  - Bar chart: Down Time per Factory
  - Bar chart: Down Time per Device Type
- Created a dashboard combining both charts.
- Applied factory selection as a filter so the device chart updates dynamically.

### Result
- Daikibo Factory Seiko (Osaka) had the highest downtime.
- LaserWelder had the highest downtime in that factory.

### Tool Used
- Tableau Public

---

## 🔹 Task 2: Gender Pay Equality Classification (Excel)

### Objective
Classify each job role based on its Equality Score (-100 to +100) into:
- Fair
- Unfair
- Highly Discriminative

### Work Completed
- Added a new column named **"Equality Class"**.
- Used the following Excel formula to classify the scores:
-   =IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))  
- Applied the formula to all rows in the dataset.
- Submitted the updated Excel file.

### Tool Used
- Microsoft Excel

## 📌 Skills Practiced
- Creating calculated fields in Tableau
- Building bar charts and dashboards
- Applying filters in Tableau dashboards
- Writing conditional formulas in Excel (IF, ABS)
- Following business instructions to solve structured tasks

---

## 👤 Author
Shubham Singh Sarkar
Deloitte Australia Data Analytics Virtual Experience (Forage)

