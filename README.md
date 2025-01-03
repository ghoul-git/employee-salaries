# Employee Salary Adjustment Project

## Overview
This project is a Python-based tool designed to manage employee salary data, analyze it, and make adjustments based on years in the company and position. It includes visualization of salary data using bar charts and performs mathematical operations to adjust salaries.

## Dataset
The dataset contains at least 50 rows and includes the following columns:
- Name: Employee name.
- Department: Department of the employee.
- Salary: Employee's original salary.
- Years in Company: Number of years the employee has worked in the company.
- Position: Employee's position (e.g., Manager, Executive, Analyst, Assistant).

The project reads data from a CSV file (employees.csv) and updates it with adjusted salaries.

## Libraries
The following Python libraries were used:
- pandas: For data manipulation and analysis.
- matplotlib: For data visualization.
- numpy: For performing mathematical operations like finding maximum and minimum adjusted salaries.

## Mathematical Operations
- Calculation of adjusted salaries based on:
  - A 5% bonus for each year in the company.
  - A position-based bonus:
    - Manager: 20%
    - Executive: 10%
    - Analyst: 5%
    - Assistant: 4%
- Maximum and minimum adjusted salaries were calculated using numpy.

## Files in the Repository
1. README.md: This file, providing details about the project.
2. employees.csv: The original dataset with employee details.
3. employees_with_adjusted_salaries.csv: Output file containing updated salaries.
4. employee_salaries.py: The Python script containing the project code.
5. project_0.1.pptx: A presentation explaining the project.

## Code Description
### Classes and Methods
#### Class: Employee
- *Attributes:*
  - name: Employee's name.
  - department: Employee's department.
  - salary: Employee's original salary.
  - years_in_company: Years the employee has worked.
  - position: Employee's position.

- *Methods:*
  - calculate_adjusted_salary: Calculates the adjusted salary based on years in the company and position bonuses.

#### Main Script
1. Reads the dataset using pandas.
2. Creates Employee objects for each row in the dataset.
3. Calculates adjusted salaries and appends them to the dataset.
4. Generates a bar chart comparing original and adjusted salaries.
5. Saves the updated dataset to employees_with_adjusted_salaries.csv.
6. Finds and prints the maximum and minimum adjusted salaries using numpy.

### Inputs and Outputs
- *Input:* employees.csv (original dataset)
- *Output:*
  - Bar chart comparing original and adjusted salaries.
  - employees_with_adjusted_salaries.csv (updated dataset).

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ghoul-git/employee-salaries.git
