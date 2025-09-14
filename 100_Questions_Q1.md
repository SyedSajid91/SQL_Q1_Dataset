# SQL Practice Exercises – Employees Dataset

Welcome to this **SQL Practice Repository**!  
This exercise set is designed for learners from **Beginner to Advanced** levels.  
We are using a sample **Employees dataset** with columns like:

- `EmpID`
- `Name`
- `Salary`
- `DoJ` (Date of Joining)
- `Dept` (Department)
- `Age`
- `City`

Each level contains **20 progressive SQL questions**.

---

## Level 1 – Easy (Basic SELECT, WHERE, ORDER BY, LIMIT)

1. Retrieve **all columns** from the Employees table. (`SELECT`)  
2. Get the **Name and Salary** of all employees. (`SELECT`)  
3. Fetch employees **working in the IT department**. (`WHERE`)  
4. List employees **older than 30 years**. (`WHERE`)  
5. Get employees **from Delhi or Mumbai**. (`WHERE` + `OR`)  
6. List all employees **sorted by Salary ascending**. (`ORDER BY`)  
7. List all employees **sorted by Salary descending**. (`ORDER BY`)  
8. Fetch **top 5 highest-paid employees**. (`ORDER BY` + `LIMIT`)  
9. Get employees **joined after 2020-01-01**. (`WHERE`)  
10. List employees **whose name starts with ‘A’**. (`LIKE`)  
11. Fetch employees **from IT department and older than 30**. (`WHERE` + `AND`)  
12. Display employees with **Salary less than 50,000**. (`WHERE`)  
13. Show employees **from HR department or Support department**. (`WHERE` + `OR`)  
14. Get employees **from Jaipur or Pune and age above 30**. (`WHERE`)  
15. Fetch employees whose **Name ends with ‘Khan’**. (`LIKE`)  
16. List **distinct departments** in the company. (`SELECT DISTINCT`)  
17. Count **number of employees in IT**. (`COUNT`)  
18. Count **total number of employees**. (`COUNT`)  
19. Get the **youngest employee**. (`ORDER BY` + `LIMIT 1`)  
20. Get the **oldest employee in the company**. (`ORDER BY` + `LIMIT 1`)  

---

## Level 2 – Intermediate (Aggregate Functions & Simple Calculations)

1. Find the **average salary** of all employees. (`AVG`)  
2. Find the **maximum salary** in the company. (`MAX`)  
3. Find the **minimum salary** in the company. (`MIN`)  
4. Calculate the **total salary paid** to all employees. (`SUM`)  
5. Count **how many employees are in each department**. (`COUNT` + `GROUP BY`)  
6. Find the **average age of employees in IT**. (`AVG` + `WHERE`)  
7. Find the **maximum salary in Finance department**. (`MAX` + `WHERE`)  
8. Find **minimum age of employees in Sales**. (`MIN` + `WHERE`)  
9. Calculate **total salary per department**. (`SUM` + `GROUP BY`)  
10. List **departments with more than 20 employees**. (`GROUP BY` + `HAVING`)  
11. Find the **average salary of employees older than 30**. (`AVG` + `WHERE`)  
12. Count **employees from each city**. (`COUNT` + `GROUP BY`)  
13. Get **departments sorted by total salary descending**. (`SUM` + `GROUP BY` + `ORDER BY`)  
14. Find **number of employees in HR and Support together**. (`COUNT` + `WHERE`)  
15. Calculate **average salary for employees younger than 30**. (`AVG` + `WHERE`)  
16. Find **cities with more than 5 employees**. (`COUNT` + `GROUP BY` + `HAVING`)  
17. Show **total salary for employees in Delhi**. (`SUM` + `WHERE`)  
18. Find **highest salary per city**. (`MAX` + `GROUP BY`)  
19. Find **lowest salary per department**. (`MIN` + `GROUP BY`)  
20. Count **number of employees earning above 70,000**. (`COUNT` + `WHERE`)  

---

## Level 3 – Moderate (Joins, Subqueries, Advanced WHERE)

1. Find employees **earning more than the average salary**. (`WHERE` + subquery)  
2. Get employees **younger than the average age**. (`WHERE` + subquery)  
3. Find employees **whose salary is above the max salary in Sales**. (`WHERE` + subquery)  
4. Find employees **not in IT department**. (`WHERE` + `NOT`)  
5. Get employees **whose city is not Delhi or Mumbai**. (`WHERE` + `NOT IN`)  
6. Find employees **with Salary between 50,000 and 80,000**. (`BETWEEN`)  
7. List employees **whose Name contains ‘a’ or ‘i’**. (`LIKE`)  
8. Find employees **whose age is either 25, 28, or 32**. (`IN`)  
9. Get employees **whose DoJ is in 2020**. (`YEAR()` function)  
10. Fetch **employees earning more than their department average**. (subquery + `AVG`)  
11. List employees **whose salary is equal to the second highest salary**. (Subquery + `LIMIT`)  
12. Count **employees earning below the company average salary**. (subquery + `COUNT`)  
13. List **employees earning the max salary per department**. (`JOIN` or subquery)  
14. Find employees **older than the youngest employee in IT**. (Subquery + `MIN`)  
15. Find **employees whose salary is between min and max of Marketing dept**. (`BETWEEN` + subquery)  
16. Get **employees who joined before the oldest HR employee**. (`WHERE` + subquery + `MIN`)  
17. Find **employees whose city has more than 10 employees**. (`WHERE` + subquery + `COUNT`)  
18. Get **employees whose salary is equal to the median salary**. (Subquery + `ORDER BY`)  
19. List **employees who earn more than the average salary of their city**. (Subquery + `AVG`)  
20. Find employees **not in the top 3 highest salaries**. (Subquery + `ORDER BY` + `LIMIT`)  

---

## Level 4 – Hard (Window Functions, Ranking, Complex Aggregates)

1. Rank employees by **salary descending** using `RANK()`.  
2. Assign **row numbers** to employees based on `DoJ`. (`ROW_NUMBER()`)  
3. Find **top 3 earners in each department**. (`ROW_NUMBER()` + `PARTITION BY`)  
4. Find employees with **salary above the department average using window function**. (`AVG() OVER(PARTITION BY Dept)`)  
5. Calculate **cumulative salary per department**. (`SUM() OVER(PARTITION BY Dept ORDER BY Salary)`)  
6. Find **percentile rank of employees based on salary**. (`PERCENT_RANK()`)  
7. List **departments along with average and max salary** using `GROUP BY`.  
8. Show employees with **salary greater than 1.5 times department median**. (Window function)  
9. Find employees who **joined in the same year as the youngest employee**. (Window function + `MIN`)  
10. List **cities and department combinations with total salary and average age**.  
11. Identify employees with **top 5 salaries in the company**. (`RANK()` or `ROW_NUMBER()`)  
12. Show employees whose **salary is higher than 80% of their department peers**. (`PERCENT_RANK()`)  
13. Calculate **difference between each employee salary and department average**. (`AVG() OVER(PARTITION BY Dept)`)  
14. Find employees **whose salary is increasing year over year**. (`LAG()`)  
15. Find **departments where average salary increased compared to previous year**. (`LAG() + AVG()`)  
16. Rank employees **within each city by salary descending**. (`RANK() OVER(PARTITION BY City ORDER BY Salary DESC)`)  
17. Show **moving average of salaries for last 3 employees by DoJ**. (`AVG() OVER(ORDER BY DoJ ROWS 2 PRECEDING)`)  
18. Identify employees **with salary closest to department median**. (Window function + `ABS`)  
19. Get employees **who are top 10% earners in the company**. (`NTILE(10)`)  
20. Find employees **whose salary is greater than their department average but less than max salary**. (Window function + conditional)  

---

## Level 5 – Challenge (Problem Solving Without Query Reference)

1. List employees who are **eligible for promotion** based on high salary and experience.  
2. Find cities where **average age of employees is above 30**.  
3. Identify employees with **salary outliers** (much higher or lower than dept average).  
4. Determine which department **contributes most to total salary cost**.  
5. Find **employees who joined on the same day as another employee**.  
6. List **employees with similar salaries but different departments**.  
7. Identify **departments where number of employees decreased in last 3 years**.  
8. Find cities with **more than 10 employees under 30 years old**.  
9. Identify **employees whose salary has not changed significantly** compared to their department peers.  
10. Find employees who are **closest in age to the average age of their department**.  

---

**Happy Practicing!**  
💡 Tip: Try solving first without looking at answers. Use **subqueries, aggregate functions, and window functions** for advanced exercises.

