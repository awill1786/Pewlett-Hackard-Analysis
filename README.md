# Pewlett-Hackard-Analysis

## Overview
The purpose of this analysis is to provide data to Pewlett-Hackard that informs them of the amount of employees with the potential to retire soon, and those who might be eligible for the mentorship program.

## Results
![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Retirement_Titles.png?raw=true)
### retirement_titles
This image shows us the number of retiring employees. For this list we received 133,776 rows. This list is too large however, due to the number of duplicate results from employees that changed positions over the years.

![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Unique_Titles.png?raw=true)
### unique_titles
Due to the large number of results from the retirement_titles query, I created a query that provided us with only unique results to eliminate the duplicates. This query provided us with 90,398 results.

![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Retiring_Titles.png?raw=true)
### retiring_titles
This list provides us with the amount of employees that are about retire, organized by their most recent job title. 

![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Mentorship_Eligibility.png?raw=true)
### mentorship_eligiblity
This list shows us the employees eligible for the mentorship program. We have 1,549 employees that are eligible.

## Summary
Due to the number of employees that are about to retire, it is probably a good idea to figure out how many of those will need to be filled.

![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Unique_Titles.png?raw=true)
### unique_titles_department
This list us shows the number of employees featuring their job title and department.

![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Roles_to_fill.png?raw=true)
### roles_to_fill
This list shows the count of employees per title and department. This gives us the amount of roles that need to be filled from the retiring employees. Here we have 38 different titles and departments with roles that need to be filled.

With the number of retirees leaving the company soon, will there be enough qualified staff to mentor the new employees taking over their roles?

![image](https://github.com/awill1786/Pewlett-Hackard-Analysis/blob/main/Graphics/Qualified_Staff.png?raw=true)
### qualified_staff
By filtering the list of retirees down by positions of leadership ("Senior" or "Leader" or "Manager"), we get to only 20 departments and titles that have the qualified staff to mentor the new employees.
