# HR Analytics - Power BI Report
This Power BI dashboard provides a detailed analysis of employee demographics, performance trends, and attrition patterns. It leverages data modeling, DAX calculations, and interactive visuals to generate actionable insights.
## Measures Created:
1. AverageSalary: Average Salary of all employees
2. TotalEmployees: COUNT of all employees
3. TotalEmployeesDate: Calculated Total Employees Hired by Date using CALCULATE() function and USERELATIONSHIP() function 
4. % Attrition Rate: InactiveEmployees/TotalEmployees (Percentage Format)
5. LastReviewDate: The last performance review for the selected individual (Date Format)
6. NextReviewDate: When the next review is due (It's 365 days after the LastReviewDate)
7. JobSatifaction : Max of PerformanceRating-JobSatisfaction level
8. Environment Satisfaction
9. Relationship Satisfaction
10. WorkLifeBalance
11. SelfRating (provides max rating id)
12. ManagerRating
13. InactiveEmployeesDate: Inactive Employees by Date
14. %Attriton Rate Date: The rate of attrition based on InactiveEmployeesDate and TotalEmployeesDate

## Power Query:
Created a conditional column that separates employees ages by bins

