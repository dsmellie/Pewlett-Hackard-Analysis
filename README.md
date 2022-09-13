# Pewlett-Hackard-Analysis

## Project Overview
Pewlett Hackard has hired me to analyze their soon-retiring employees by job title and to identify employees for a mentorship program.

1. Combine previously existing data tables for employee information and job title to develop a list of employees soon to retire and their titles.
2. Remove duplicates from the table to determine these employees’ current job titles and put that information in a new database.
3. Using that database, determine the number of employees soon to retire that hold each job title and put that information in its own database.
4. Combine previously existing data tables for employee information, department employee information, and job title to develop a list of employees eligible to serve as mentors.
## Resources
-Data Sources: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
-Software: Visual Studio Code 1.7.1, pgAdmin4 6.12, PostgreSQL 11.17
## Results
From analyzing this data, I found several major takeaways:
  Retiring Titles:
- 25,916 senior engineers, 9285engineers, and 1090 assistant engineers are soon to retire for a total of 36,291 different engineer are soon to retire representing a large portion of the future retirees
	- Two of the nine current managers are soon to retire, which means replacements should be lined up to ensure a proper transition
- 72,458 total employees are soon to retire
Mentorship Eligibility:
-	1,549 employees are eligible for the mentorship program
-	No managers are eligible for the mentorship program
-	Given that a total of 72,458 employee are soon to retire, more than 1,549 mentors are likely needed
    

## Summary
I have been asked to answer the following questions.
•	How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Answer: There are a total of 72,458 employees that are a part of the “silver tsunami”, so assuming no downsizing 72,458 roles will need to be filled.
•	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Answer: There are only 1,549 employees are eligible for the mentorship program. As each of those employees would have to mentor 46 new employees to mentor the entire next generation of employees, there are not enough qualified, retirement-ready employees to mentor the next generation.
One other query that may be helpful to perform is a sum of the salaries of the retiring employees by department. This query would help the managers of the department know how much to budget for new employee hiring and training. A final helpful query would be a list of retiring titles by department. This information would help each department know how many of each position it has to replace.
