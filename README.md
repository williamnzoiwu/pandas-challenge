# pandas-challenge
Pandas Module 4 Challenge

This Jupyter notebook analyzes the test schoors from students at various schools. It first reads two csv files, "schools_complete.csv," which contains the complete list of schools, and "students_complete.csv" which contains the complete list of students from all the schools. From the two csv files, it then creates a dataframe which sorts all the students by name, grade, the school they go to, and their reading and math scores. It also sorts the schools by type, amount of students, and budget.

From there, it sorts the district's key metrics in a DataFrame, includes the following:
Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Next it creates a new DataFrame that summarizes key metrics about each school, which includes the following:
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

In the sorts the schools by % Overall Passing in descending order and displays the top 5 rows in a new DataFrame called "top_schools".
Subsequently, sorts the schools by % Overall Passing in ascending order and display the top 5 rows in another DataFrame called "bottom_schools".
Then creates a new DataFrame that lists the average math score for students of each grade level at each school, and another one that lists the average reading score.

Next, creates a table that breaks down school performance based on average spending ranges per student, then calculates mean scores per spending range and lists in a DataFrame called "spending_summary" which includes the following:
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).
Then creates another table in a very similar fashion to the last one that breaks down school performance based on size (small, medium, or large) and lists those results in a DataFrame called "size_summary."

Lastly, creates another table like the last two that breaks down school performance based on type and lists those results in a DataFrame called "type_summary."
