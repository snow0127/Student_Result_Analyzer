# Student_Result_Analyzer

## Project Overview
The **Student Result Analyzer** is a Python-based data analysis project that evaluates and analyzes student performance data.  
The project performs data processing, analysis, and generates insights such as Total Marks, PErcentage, Grades, and Status.

---

## Objectives
- Analyze student marks data
- Calculate total, average, and percentage
- Assign grades based on performance
- Identify top performers
- Generate summary statistics
- Visualize performance (if applicable)

---

## Technologies Used
- Python
- Jupyter Notebook
- Tkinter

---

## Features

- Data Cleaning and Preprocessing
- Calculation of Total Marks
- Percentage Calculation
- Grade Assignment Logic
- Performance Analysis
- Summary Report Generation  

---

## Analysis Performed

The notebook includes:

- Loading and inspecting dataset
- Handling missing or incorrect data
- Computing:
  - Total Marks
  - Average Marks
  - Percentage
- Grade classification logic
- Identifying:
  - Highest scorer
  - Lowest scorer
  - Overall class performance

---

## Example Grade Logic

```python
if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 50:
    grade = "D"
else:
    grade = "Fail"
