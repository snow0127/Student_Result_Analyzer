<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<div class="container">

<h1>Student Result Analyzer</h1>

<h2>Project Overview</h2>
<p>
The <strong>Student Result Analyzer</strong> is a Python-based data analysis project 
that evaluates and analyzes student performance data.
The project performs data processing, analysis, and generates insights such as 
<strong>Total Marks, Percentage, Grades, and Status</strong>.
</p>

<h2>Objectives</h2>
<ul>
    <li>Analyze student marks data</li>
    <li>Calculate total, average, and percentage</li>
    <li>Assign grades based on performance</li>
    <li>Identify top performers</li>
    <li>Generate summary statistics</li>
    <li>Visualize performance (if applicable)</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>Jupyter Notebook</li>
    <li>Tkinter</li>
</ul>

<h2>Features</h2>
<ul>
    <li>Data Cleaning and Preprocessing</li>
    <li>Calculation of Total Marks</li>
    <li>Percentage Calculation</li>
    <li>Grade Assignment Logic</li>
    <li>Performance Analysis</li>
    <li>Summary Report Generation</li>
</ul>

<h2>Analysis Performed</h2>
<ul>
    <li>Loading and inspecting dataset</li>
    <li>Handling missing or incorrect data</li>
    <li>Computing:
        <ul>
            <li>Total Marks</li>
            <li>Percentage</li>
            <li>Grade</li>
            <li>Status</li>
        </ul>
    </li>
    <li>Grade classification logic</li>
</ul>

<h2>Subjects Included</h2>
<ul>
    <li>Computer</li>
    <li>Physics</li>
    <li>Chemistry</li>
    <li>English</li>
    <li>Maths</li>
</ul>

<h2>Grade Logic</h2>

<pre><code>
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
</code></pre>

</div>

</body>
</html>
