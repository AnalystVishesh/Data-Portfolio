# 📊 HR Analytics Dashboard

[🔗 View Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjNhODU3NDYtZTgxNC00MWY1LTliY2EtZDNiNjJlM2FjYjk1IiwidCI6IjM3NjFjYzBlLWMwNmMtNGY2Zi1iYjE2LWQwYTA1NDc0OGM4YiJ9)

## 📌 Problem Statement

The **HR Analytics Dashboard** empowers HR teams with data-driven insights into employee headcount, retention, and turnover. It supports strategic decision-making by uncovering workforce patterns, identifying potential issues, and improving talent management across the organization.

---

## 🚨 Key Issues Addressed

- **Headcount Trends:** Track growth, department size, and workforce composition.
- **Retention Rates:** Analyze how well departments and roles retain talent.
- **Turnover Statistics:** Understand why employees leave and which roles/departments are most affected.

---

## 🎯 Project Goals

- **Optimize Workforce Planning**  
  Use historical trends and segmentation to improve hiring and workforce allocation.

- **Boost Employee Retention**  
  Identify retention pain points and success factors to build a stable workforce.

- **Support Strategic HR Decisions**  
  Enable HR leaders with visuals that highlight risks and opportunities.

---

## 🧱 Data Model & Transformation

### 1️⃣ Data Preparation
- Loaded two CSV files:
  - **People Data Table**: `EmployeeID`, `Gender`, `Race`, `Birthdate`, `Education`, `Location`, etc.
  - **Employment History Table**: `Department`, `Job Level`, `Salary`, `Hire Date`, `Termination`, etc.

### 2️⃣ Data Cleaning & Transformation
- Calculated **age** from `birthdate`.
- Converted binary **active status** (1/0) into categorical ("Yes"/"No").

### 3️⃣ Data Modeling
- Built a **People Fact Table** and several **Dimension Tables**:
  - Department, Job Level, Termination Reason, Education, Marital Status, Manager, Location, Date
- Normalized data by removing redundant columns and linking keys.

### 4️⃣ Relationship Mapping
- Established star schema with **People Fact Table** at the center.
- Verified relationships and ensured correct cardinality.

---

## 📈 Visualizations

Dashboard built using **Power BI**, divided into 4 main report pages:

- **Cover Page**: Overview & navigation.
- **Headcount Page**: Headcount distribution by department, location, gender.
- **Retention Page**: Retention by department, job level, and demographics.
- **Turnover Page**: Reasons for leaving, voluntary/involuntary trends, departmental turnover.

---

## 🔍 Key Insights

### 👥 Workforce Composition
- **Software** & **Sales** are the largest departments.
- **80% of employees are remote**, signaling a shift to virtual work.

### 📊 Demographics
- **75% are individual contributors**, suggesting a flat org structure.
- **61% male workforce**; **71% single** — impacting diversity & benefits planning.

### 🔒 Retention & Turnover
- **Overall retention**: 83.6% (strong).
- **Turnover rate**: 37.4% (high), with **82% voluntary** exits.
- Key reasons: better opportunities, desire for flexible benefits.
- **R&D** and **Sales** departments have the highest turnover.

---

## ✅ Recommendations

- **Remote Workforce Strategy**: Strengthen virtual collaboration and engagement.
- **Diversity & Inclusion**: Address gender imbalance and create inclusive policies.
- **Retention Programs**: Target high-turnover departments with tailored strategies.
- **Competitive Packages**: Improve benefits and advancement opportunities.
- **Leadership Support**: Reduce director-level turnover with mentorship and growth paths.

---

## 🛠 Tools & Skills Used

- **Power BI**
- **Power Query**
- **DAX**
- **Data Cleaning & Transformation**
- **Dimensional Modeling (Star Schema)**
- **Business Intelligence & Reporting**

---

## 📂 Project Structure


