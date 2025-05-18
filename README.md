# Python-Capstone

# Python Data Processing Capstone Project

## 📝 Project Overview

This Python capstone project demonstrates end-to-end data wrangling and business logic implementation using three given datasets. The tasks cover essential data engineering skills such as cleaning, joining, transforming, and deriving insights using pandas, as well as applying business rules through Python programming.

---

## 🛠️ Tools Used

- **Python** (Jupyter Notebook or .py scripts)
- **pandas** for data manipulation and analysis

---

## 📂 Datasets

- **Employee dataset**
- **Project dataset**
- **Seniority Level dataset**

---

## 🔍 Key Tasks & Steps

1. **Data Preparation:**  
   - Loaded three given datasets as pandas DataFrames.
   - Saved each DataFrame as a separate `.csv` file for subsequent tasks.

2. **Missing Value Imputation:**  
   - Filled missing values in the `cost` column of the Project DataFrame using a running average (with a `for` loop).

3. **Name Splitting:**  
   - Split the `name` column in the Employee DataFrame into `First Name` and `Last Name`.
   - Removed the original `name` column.

4. **Data Merging:**  
   - Joined all three DataFrames into a single DataFrame named `Final`.

5. **Bonus Calculation:**  
   - Added a new `bonus` column in the `Final` DataFrame.
   - Granted a 5% bonus (based on project cost) only to employees who completed their projects.

6. **Designation Adjustment:**  
   - Demoted the designation level by 1 for employees whose projects had a status of "fail".
   - Removed records of employees whose designation level was above 4.

7. **Title & Gender Handling:**  
   - Prefixed `First Name` with “Mr.” or “Mrs.” based on gender.
   - Dropped the gender column.

8. **Promotion Based on Age:**  
   - Promoted (incremented designation level by 1) for employees older than 29 years (using an IF condition).

9. **Project Cost Aggregation:**  
   - Created a new DataFrame `TotalProjCost` with columns: `ID`, `First Name`, and `Total cost` (sum of all project costs per employee).

10. **Employee Filtering:**  
    - Printed details of all employees whose city name contains the letter “o”.

---

## 📈 Business Impact

- Automated data cleaning and transformation pipelines using Python and pandas.
- Demonstrated practical application of loops, conditionals, and dataframe operations for business rule execution.
- Prepared clean and insightful datasets for further analysis or reporting.

---

## Author

**Mohini Priya**  
[GitHub](https://github.com/Mohini-Priya) | [LinkedIn](https://www.linkedin.com/in/mohini-priya-9a308b128)  
Email: mmohinipriya@gmail.com
