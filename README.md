# pandas-challenge
anlaysis of school and student data

We are analysing two data files which are connected by School name 
The Student.cssv files contains all students going to the different schools in the School.csv file along with their marks.

We are required to analyse the following :- 
# District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
Total number of unique schools,
Total students,
Total budget,
Average math score,
Average reading score,
% passing math (the percentage of students who passed math),
% passing reading (the percentage of students who passed reading),
% overall passing (the percentage of students who passed math AND reading).

# School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:
School name,
School type,
Total students,
Total school budget,
Per student budget,
Average math score,
Average reading score,
% passing math (the percentage of students who passed math),
% passing reading (the percentage of students who passed reading),
% overall passing (the percentage of students who passed math AND reading).

Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

# NOTE : DIFFERENCE BETTER DISTRICT AND CHARTER SCHOOLS
public school district,  dictates curriculum and standards in all schools, charters operate autonomously through individual agreements, or charters, with state or local governments that dictate rules and performance standards

# OBSERVATIONS:- 
We noticed that the budget spent per student has no do direct relation with better performance of a student academically. We noticed where schools with a budget per student of less than 585 had performed better academically in terms of average percentage of students passing  maths and reading. 
Charter schools have outperformed district school acedemically. 
The perventage of students passing drops as school size keeps gettign bigger.

