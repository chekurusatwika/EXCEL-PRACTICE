# 👨‍💼 Employee Data Cleaning and Transformation using Excel Power Query

## 📌 Project Overview

This project demonstrates how Microsoft Excel Power Query can be used to clean, transform, and prepare employee data for reporting and business analysis.

The project uses a sample employee dataset containing staff information such as employee names, gender, salary, joining date, and employment status.

---

## 🎯 Objective

The objective of this project is to automate data cleaning and transformation using Power Query while maintaining a dynamic connection to the source Excel file.

---

## 🛠 Tools Used

- Microsoft Excel
- Power Query
- Excel Formulas
- Data Transformation

---

## 🔄 Power Query Transformations

The following data cleaning and transformation steps were performed:

### ✅ Name Standardization
- Split the Full Name column into First Name and Last Name.
- Removed extra spaces using the Trim transformation.

### ✅ Missing Value Handling
- Replaced null values in the Gender column with **"Need to Change"** instead of leaving them blank.

### ✅ Salary Categorization
Created a Salary Range column using conditional logic.

| Salary | Category |
|---------|-----------|
| Below 50,000 | Below 50K |
| 50,000 – 100,000 | 50K – 100K |
| Above 100,000 | Above 100K |

### ✅ Date Formatting
- Standardized the date format for consistency.

### ✅ Work Type Classification
Created a new Work Type column based on FTE.

- FTE = 1 → Full-Time
- Otherwise → Part-Time

### ✅ Employee Experience
Calculated the number of years each employee has worked in the company using the joining date.

### ✅ Dynamic Data Refresh
The Power Query maintains a connection with the source Excel file.

Whenever the source data is updated, clicking **Refresh** automatically updates the transformed dataset without repeating the cleaning process.

---

## 📊 Skills Demonstrated

- Power Query
- Data Cleaning
- Data Transformation
- Handling Missing Values
- Conditional Columns
- Split Columns
- Text Transformations
- Date Formatting
- Dynamic Data Refresh
- Business Data Preparation

---

## 📁 Files Included

- Employee_Data_Raw.xlsx
- Employee_Data_Cleaned.xlsx

---

## 📷 Project Preview

### Raw Data

(Add Screenshot)

### Power Query Editor

(Add Screenshot)

### Final Cleaned Dataset

(Add Screenshot)

---

## 📈 Learning Outcome

This project demonstrates how Power Query can automate repetitive data cleaning tasks and build a reusable data preparation workflow for business reporting and analytics.

---

## 👩‍💻 Author

Chekuru Satwika

Aspiring Business Analyst | Data Analyst
