# HR Data Analysis with Python 📊

An exploratory data analysis (EDA) project on HR employee data using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. The notebook walks through cleaning the dataset and answering 15 real-world HR business questions through visualizations and statistics.

## 📁 Dataset

The analysis uses `HR_Data.csv`, which contains employee-level records including:

- `Employee_ID`, `Job_Title`, `Department`
- `Hire_Date`, `Experience_Years`, `Status` (Active, Resigned, Retired, Terminated)
- `Work_Mode` (On-site, Remote), `Location`
- `Salary_INR`, `Performance_Rating`

## 🧹 Data Cleaning

- Removed unwanted index column (`Unnamed: 0`)
- Converted `Hire_Date` to proper datetime format
- Extracted `Year` from `Hire_Date` for trend analysis
- Extracted `Country` from the `Location` column

## ❓ Business Questions Answered

1. Distribution of Employee Status (Active, Resigned, Retired, Terminated)
2. Distribution of Work Modes (On-site vs Remote)
3. Employee count by department
4. Average salary by department
5. Job title with the highest average salary
6. Average salary by department and job title
7. Number of resigned & terminated employees per department
8. Salary variation with years of experience
9. Average performance rating by department
10. Country with the highest concentration of employees
11. Correlation between performance rating and salary
12. Hiring trend over the years
13. Salary comparison: Remote vs. On-site employees
14. Top 10 highest-paid employees in each department
15. Departments with the highest attrition rate (Resigned %)

## 🛠️ Tools & Libraries

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📈 Visualizations

The notebook includes pie charts, bar charts, horizontal bar charts, count plots, and a correlation heatmap to support the analysis.

## 🚀 How to Run

1. Clone this repository
   git clone https://github.com/<your-username>/hr-data-analysis-with-python.git
   cd hr-data-analysis-with-python

2. Install dependencies
   pip install pandas matplotlib seaborn jupyter

3. Make sure `HR_Data.csv` is in the same directory as the notebook

4. Launch Jupyter Notebook
   jupyter notebook hr-data-analysis-with-python.ipynb

## 📌 Key Insights

- Identifies departments with the highest attrition and termination rates
- Highlights salary trends across departments, job titles, and experience levels
- Compares compensation between remote and on-site employees
- Reveals hiring trends over time and workforce distribution by country
