# SQL_Q1_Dataset
SQL dataset of employees with practice questions (Beginner → Analyst level)
# Employee SQL Dataset – Practice Playground 🎯

Welcome to the **Employee SQL Dataset** project!  
This repository is built for **SQL beginners and aspiring data analysts** who want to learn and practice SQL using a realistic dataset.

---

## 📂 What’s Inside
- **employees_data.sql** → SQL script with 300 sample employee records.  
- **SQL_Practice_Questions.md** → 50 SQL practice questions.  
- **README.md** → Project overview and instructions.  
- **LICENSE** → MIT License (open-source use).  

---

## 🏗 Table Schema
```sql
CREATE TABLE Employees (
    EmpID INT PRIMARY KEY,
    Name VARCHAR(100),
    Salary INT,
    DoJ DATE,
    Dept VARCHAR(50),
    Age INT,
    City VARCHAR(50)
);
