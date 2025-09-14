
---

## 📘 SQL_Practice_Questions.md
```markdown
# SQL Practice Questions – Employee Dataset

This file contains **50 SQL questions** designed to train your analytical mindset using the `Employees` table.

---

## 🟢 Level 1: Easy (Basics – SELECT, WHERE, ORDER BY)
1. Display all employees’ names and salaries. *(Hint: SELECT)*  
2. List all employees who work in the **IT** department. *(Hint: WHERE)*  
3. Show employees who are older than 30. *(Hint: WHERE Age >)*  
4. Get employees from **Mumbai** sorted by salary (highest first). *(Hint: ORDER BY DESC)*  

---

## 🟡 Level 2: Filtering & Patterns
5. Find employees whose names start with **‘A’**. *(Hint: LIKE)*  
6. Show employees with salaries **between 50,000 and 80,000**. *(Hint: BETWEEN)*  
7. Display employees from **Delhi, Chennai, and Lucknow** only. *(Hint: IN)*  
8. Find employees who joined **after 2020-01-01**. *(Hint: WHERE DoJ >)*  

---

## 🟠 Level 3: Aggregates
9. Count total employees. *(Hint: COUNT)*  
10. Find the highest salary. *(Hint: MAX)*  
11. Show average age. *(Hint: AVG)*  
12. Find total salary in **Finance** dept. *(Hint: SUM + WHERE)*  

---

## 🔵 Level 4: Grouping
13. Show employee count per department. *(Hint: GROUP BY)*  
14. Find average salary by city. *(Hint: GROUP BY)*  
15. Departments with more than 20 employees. *(Hint: HAVING)*  
16. Highest salary per department. *(Hint: MAX + GROUP BY)*  

---

## 🟣 Level 5: Analyst Thinking
17. Employees in same city with salary > 80k. *(Hint: GROUP BY + HAVING)*  
18. Employees with duplicate ages. *(Hint: GROUP BY Age)*  
19. Earliest joined employee per dept. *(Hint: MIN DoJ)*  
20. Employees earning more than avg salary. *(Hint: Subquery)*  

---

## 🔴 Level 6: Subqueries
21. Employees with max salary. *(Hint: Subquery)*  
22. Employees older than avg age. *(Hint: Subquery)*  
23. Employees joined before Finance dept. *(Hint: Subquery)*  
24. Second highest salary. *(Hint: Subquery)*  

---

## 🟤 Level 7: String Functions
25. Names in UPPERCASE. *(Hint: UPPER)*  
26. First 3 letters of names. *(Hint: SUBSTRING)*  
27. Names containing “an”. *(Hint: LIKE)*  
28. Count names with “Khan”. *(Hint: COUNT + LIKE)*  

---

## ⚫ Level 8: Date Functions
29. Employees joined in 2020. *(Hint: YEAR)*  
30. Employees joined in last 5 years. *(Hint: DATEDIFF)*  
31. Employees joined in January. *(Hint: MONTH)*  
32. Most recent employee. *(Hint: MAX DoJ)*  

---

## 🟢 Level 9: CASE Conditions
33. Label Senior if Age > 35 else Junior. *(Hint: CASE)*  
34. Salary with 10% bonus. *(Hint: Arithmetic)*  
35. Categorize salary → High/Mid/Low. *(Hint: CASE)*  
36. Mark Yes if city = Delhi, else No. *(Hint: CASE)*  

---

## 🟡 Level 10: Advanced Aggregates
37. Top 3 highest salaries. *(Hint: ORDER BY LIMIT)*  
38. 3 youngest employees. *(Hint: ORDER BY Age)*  
39. City with highest total salary. *(Hint: GROUP BY + SUM)*  
40. Dept with max employees. *(Hint: GROUP BY + COUNT)*  

---

## 🟠 Level 11: Window Functions
41. Rank employees by salary. *(Hint: RANK)*  
42. Salary deviation per dept. *(Hint: AVG OVER PARTITION)*  
43. Running salary total by DoJ. *(Hint: SUM OVER ORDER BY)*  
44. Top 2 salaries per dept. *(Hint: ROW_NUMBER)*  

---

## 🔵 Level 12: Fun Challenges
45. Youngest employee in IT.  
46. Dept with oldest employee.  
47. Top 5 cities by employee count.  
48. Earliest joined employee overall.  

---

## 🔴 Analyst Challenge (No Hints)
49. Employees with median salary.  
50. Employee count by age groups (20–25, 26–30, 31–35, 36–40).  
