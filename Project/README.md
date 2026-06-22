# ⚾ Advanced SQL Analytics Project

## 📌 Overview

This project explores a baseball player database using advanced SQL techniques to answer analytical questions related to player careers, salaries, schools, team spending, and player demographics.

The project was completed as part of an Advanced SQL learning path and focuses on solving real-world analytical problems using Common Table Expressions (CTEs), Window Functions, Aggregations, Ranking Functions, Rolling Calculations, String Manipulation, and Pivoting techniques.

---

## 🎯 Objectives

The goal of this project is to demonstrate practical SQL skills by solving business-style analytical questions such as:

- Which schools produced the most professional players?
- Which teams spend the most on player salaries?
- How has team spending evolved over time?
- Which players had the longest careers?
- Which players started and ended their careers with the same team?
- How have player physical characteristics changed across decades?
- What percentage of players bat right-handed, left-handed, or switch-hit for each team?

---

## 🗄 Database Structure

The project uses the following tables:

### players

Contains player biographical information.

Key columns:

- playerID
- nameGiven
- birthYear
- birthMonth
- birthDay
- debut
- finalGame
- bats
- throws
- height
- weight

---

### salaries

Contains annual salary records.

Key columns:

- playerID
- teamID
- yearID
- salary

---

### schools

Maps players to schools attended.

Key columns:

- playerID
- schoolID
- yearID

---

### school_details

Contains school information.

Key columns:

- schoolID
- name_full
- city
- state
- country

---

## 🛠 Tools Used

- SQL
- MySQL
- DBeaver
- Git
- GitHub

---

## 🧠 SQL Concepts Demonstrated

### Core SQL

- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- LIMIT

### Joins

- INNER JOIN
- LEFT JOIN

### Aggregations

- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

### Common Table Expressions (CTEs)

Used extensively to simplify complex analytical queries.

---

### Window Functions

- ROW_NUMBER()
- DENSE_RANK()
- NTILE()
- LAG()
- SUM() OVER()

---

### Analytical Techniques

- Rolling Calculations
- Ranking
- Cohort-style Analysis
- Team Spending Analysis
- Career Analysis
- Decade Analysis

---

### String Functions

- CONCAT()
- GROUP_CONCAT()

---

### Pivoting

- CASE WHEN
- Conditional Aggregation

---

## 📊 Project Sections

### Part I — School Analysis

Questions answered:

1. How many schools produced players in each decade?
2. Which schools produced the most professional players?
3. Which schools were the top talent producers in each decade?

Skills demonstrated:

- Joins
- Ranking
- Window Functions
- Aggregation

---

### Part II — Salary Analysis

Questions answered:

1. Which teams belong to the top 20% in average annual spending?
2. How has cumulative team spending evolved over time?
3. When did teams surpass $1 billion in cumulative spending?

Skills demonstrated:

- NTILE()
- Rolling Sums
- Window Functions
- CTEs

---

### Part III — Player Career Analysis

Questions answered:

1. Player starting age
2. Player ending age
3. Career length
4. Starting and ending teams
5. Players who remained with the same team for over a decade

Skills demonstrated:

- Date Functions
- Multi-table Joins
- Career Analytics

---

### Part IV — Player Comparison Analysis

Questions answered:

1. Which players share the same birthday?
2. What percentage of players bat right, left, or both for each team?
3. How have average player height and weight changed across decades?

Skills demonstrated:

- GROUP_CONCAT()
- Pivoting
- CASE WHEN
- LAG()
- Trend Analysis

---

## 📈 Advanced SQL Features Used

| Feature | Example Usage |
|----------|--------------|
| CTEs | Query modularization |
| Window Functions | Ranking and rolling calculations |
| NTILE | Team spending segmentation |
| ROW_NUMBER | Top schools per decade |
| LAG | Decade-over-decade comparisons |
| GROUP_CONCAT | Player birthday analysis |
| CASE WHEN | Pivot tables |
| SUM OVER | Cumulative team spending |

---

## 📂 Project Files

```text
.
├── Schema_And_Data.sql
├── Project_Code.sql
└── README.md
```

### Schema_And_Data.sql

Contains:

- Table creation scripts
- Primary keys
- Data loading scripts
- Sample dataset

### Project_Code.sql

Contains:

- All analytical SQL solutions
- CTE implementations
- Window Function examples
- Business analysis queries

---

## 🚀 Key Learning Outcomes

Through this project, I gained hands-on experience with:

- Writing production-style SQL queries
- Solving analytical business problems
- Building reusable CTE-based workflows
- Applying advanced Window Functions
- Performing trend and cohort analysis
- Working with large relational datasets
- Optimizing query readability and maintainability

---

## 👤 Author

**Ankita Banerjee**

Business Analyst | SQL | Python | Power BI | Data Analytics

GitHub: https://github.com/AnkitaBanerjee1998
