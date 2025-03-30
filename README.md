# CGPA-Calculator
A student’s cumulative grade point average (CGPA) can be determined using the C++ program CGPA Calculator. The user’s input is used to compute the CGPA, which includes information like the number of courses taken and the grades earned in each one. The program also shows each student’s overall course grade. CGPA Calculator calculates a student’s Cumulative Grade Point Average (CGPA) from the given exam results.

# Project Descriptions 
The program can show the individual grades of each course, calculate total credits and total grade points achieved, determine the GPA for the semester, and based on all the data, it can generate and present the CGPA of the student. 
This program calculates a student’s Cumulative Grade Point Average (CGPA). It takes:

The number of courses

Grade received for each course

Credit hours for each course

Then it:

Converts letter grades to numeric grade points

Multiplies each grade point by its credit hour to get total grade points

Sums total credits and total grade points

Computes the final CGPA

Displays a detailed report
Let's build a CGPA Calculator in C++, step-by-step.

✅ Take input for the number of courses

✅ Collect course grades and credit hours

✅ Compute total grade points

✅ Compute CGPA

✅ Display a summary with per-course details and overall CGPA

# Step-by-Step Guide to Building a CGPA Calculator in C++
🔹 Step 1: Understand the Formula
CGPA is calculated as:


CGPA = Total Grade Points
/Total Credit Hours

​
 
Where:

Grade Point = Grade value × Credit hours

Example Grade Scale (modifiable according the school grading system):

A = 4.0

B = 3.0

C = 2.0

D = 1.0

F = 0.0
