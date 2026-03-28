# HR_Analytics_Dashboard
# HR Analytics Dashboard (Power BI)

## 📊 Project Overview

This project presents an **HR Analytics Dashboard** built using Power BI to analyze employee data and provide insights into workforce trends such as attrition, employee distribution, and job satisfaction.

---

## 🎯 Objectives

* Analyze employee count and attrition trends
* Identify patterns across departments and demographics
* Evaluate job satisfaction levels
* Support HR decision-making through data-driven insights

---

## 📌 Key Metrics (Cards)

The dashboard includes the following key performance indicators:

1. **Overall Employees**: 1,000 employees
2. **Attrition Count**: 237 employees
3. **Attrition Rate**: 16.12%

   * Calculated using:
     `Attrition Count / Total Employees`
4. **Active Employees**:

   * Calculated using:
     `SUM(Employee Count) - SUM(Attrition Count)`
5. **Average Age**: 37 years

---

## 📈 Visualizations

### 1️⃣ Attrition by Department (Pie Chart)

* **Legend**: Department
* **Values**: Attrition Count
* Purpose: Identifies departments with the highest attrition rates

---

### 2️⃣ Employees by Age Group (Stacked Column Chart)

* **X-Axis**: CF_age_band
* **Y-Axis**: Employee Count
* Purpose: Shows employee distribution across age groups

---

### 3️⃣ Job Satisfaction Analysis (Matrix)

* **Columns**: Job Satisfaction
* **Rows**: Job Role
* **Values**: Employee Count
* Purpose: Evaluates satisfaction levels across different job roles

---

### 4️⃣ Attrition by Education Field (Stacked Bar Chart)

* **Y-Axis**: Education Field
* **X-Axis**: Attrition Count
* Purpose: Analyzes attrition trends based on educational background

---

### 5️⃣ Attrition by Gender & Age Group (Donut Charts)

Five donut charts were created for different age groups:

* Under 25
* 25–34
* 35–44
* 45–54
* Over 55

**Configuration:**

* **Legend**: Gender
* **Values**: Employee Count
* **Details**: CF_age_band

Purpose: Provides a breakdown of attrition distribution by gender within each age group

---

## 🛠 Tools & Technologies

* Power BI
* DAX (for calculated measures)
* Power Query (for data transformation)

---

## 💡 Key Insights

* Attrition rate stands at **16.12%**, indicating workforce turnover
* Employee distribution varies across age groups and departments
* Job satisfaction differs by role, highlighting areas for improvement
* Attrition patterns vary by education field and gender

---

## 🚀 How to Use

1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Interact with visuals using filters and slicers

---

## 📷 Dashboard Preview

*(Add screenshots here for better visualization)*

---

## 📌 Conclusion

This dashboard provides a comprehensive view of HR data, enabling organizations to monitor employee trends, improve retention strategies, and make informed decisions.


