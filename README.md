# Capstone Project: Data Cleaning, Transformation & Business Logic Automation with Python

## 🧠 Overview

This Python-based capstone project simulates a real-world corporate data transformation challenge involving HR and project management analytics. The focus was on cleaning, transforming, and integrating three key datasets — Employee, Project, and Seniority Level — using Python, Pandas, and NumPy, while embedding business logic and automation strategies into the workflow.

---

## 👨‍💻 Role

**Data Analyst | Python Developer**  
Capstone Project

---

## 🛠️ Tools & Technologies

Python | Pandas | NumPy | Jupyter Notebook | CSV Handling | Data Cleaning | Business Logic | Data Aggregation

---

## 🎯 Project Goals

- Clean and preprocess interrelated datasets.
- Automate business logic such as bonus calculation, promotion/demotion logic, and designation updates.
- Simulate HR and operational workflows using Python and Pandas fundamentals.
- Deliver clean, aggregated datasets ready for executive-level reporting.

---

## 📊 Core Contributions & Breakdown

### 🗃️ Modular Data Setup
- Created three core DataFrames: `Employee`, `Project`, and `SeniorityLevel`.
- Exported as `.csv` files to simulate modular, real-world workflows and persistent storage.

### 🧹 Data Cleaning & Normalization
- Handled missing `Project Cost` values using a **custom for-loop-based running average imputation** (not in-built functions), reflecting real-world iterative logic.
- Split combined `Name` column into `First Name` and `Last Name`, then dropped the original to allow granular identity analysis.

### 🔗 Data Integration
- Performed multi-table joins using ID as the primary key to form a unified `Final` DataFrame.
- This joined dataset mirrored relational database consolidation for analytics.

### 💸 Business Logic Automation

#### ✅ Bonus Allocation
- Added a `Bonus` column calculated as 5% of the `Project Cost` for completed projects (`status = Finished`).

#### 📉 Demotion & Deletion Logic
- Demoted employees (designation -1) whose project status was `Failed`.
- Deleted records where designation level exceeded `4` (non-compliant with company policy).

#### 🔄 Promotion by Age
- Applied conditional promotion: employees over the age of 29 were promoted (designation +1), reflecting seniority-driven growth.

#### 🧍‍♂️ Gender-Based Titles
- Added `"Mr."` or `"Mrs."` prefix to `First Name` based on gender and dropped the `Gender` column — enhancing professional identity representation.

---

## 📈 Analytical Summary Table

- Created a new DataFrame: `TotalProjCost`, summarizing total project cost handled by each employee using `groupby` operations.
- Used for executive reporting and cost attribution per resource.

---

## 🔍 Additional Filters & Queries

- Selected all employees whose `City` names contain the letter `"o"` — demonstrating text pattern filtering and customer segmentation logic.

---

## 🧪 Skills Demonstrated

- ✅ Data Cleaning & Preprocessing  
- 🔁 For-Loop Calculations for Missing Values  
- 🧱 DataFrame Merging (Multi-Table Joins)  
- 🧠 Conditional Logic (if/else, multiple conditions)  
- 📊 GroupBy & Aggregation  
- 🔤 String Manipulation  
- 🔄 Feature Engineering  
- 🗂️ CSV Read/Write & Data Export  
- 👨‍💼 HR & Operational Business Simulation

---

## 📂 Deliverables

- 📓 Jupyter Notebook (.ipynb) with step-by-step code and in-line documentation  
- 🗃️ Cleaned CSV exports for each DataFrame  
- 📊 `TotalProjCost` DataFrame with grouped analytics  
- 🧾 Fully documented transformation and logic pipeline

---

## 🚀 Impact

This capstone provided a practical simulation of real-world data operations where data preprocessing, logic-based transformations, and reporting automation are key. It sharpened my ability to handle business requirements through clean, readable, and effective Python code. The logic structures mimic actual HR operations, bonus structures, and project performance metrics—offering transferable value to multiple industries.

---

## 🔑 Keywords

Python for Data Analysis | Pandas | NumPy | Data Cleaning | Business Logic | Project Analytics | HR Analytics | Real-World Data Simulation | Conditional Logic | Feature Engineering | Aggregation | Jupyter Notebook | Employee Performance | CSV Operations | Designation Management | Bonus Logic | Python Capstone

---

*Focused on code clarity, business relevance, and transformation accuracy.*
