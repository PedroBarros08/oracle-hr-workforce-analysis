Oracle HR Workforce Analysis

SQL portfolio project focused on analysing workforce structure using the Oracle HR sample database.

The project starts with business questions and uses SQL to measure workforce concentration across departments, geography and job roles.

Business Questions

1. Department concentration

Is the workforce concentrated in a small number of departments?

Measures employee count, workforce percentage and cumulative concentration by department.

SQL → 01_department_concentration.sql

2. Geographic distribution

How is the workforce distributed across countries and regions?

Measures employee distribution by country, country share within its region and region share of the total workforce.

SQL → 02_geographic_distribution.sql

3. Department job composition

How is the workforce structured within each department?

Measures the number and percentage of employees by job title within each department.

SQL → 03_department_job_composition.sql

Key Findings

Department concentration: Shipping and Sales together account for 73.84% of the workforce.

Geographic distribution: The analysis separates country concentration within a region from the region's share of the total workforce.

Job composition: Several departments show high concentration in specific roles, such as Sales Representatives in Sales (85.29%) and Programmers in IT (100%, based on only five employees).

These findings describe workforce patterns; they do not by themselves establish operational risk or performance problems.

SQL Skills Demonstrated

LEFT JOIN and multi-table joins

Common Table Expressions (CTEs)

GROUP BY and aggregations

CASE/COALESCE-style data handling

Scalar subqueries

Window functions and PARTITION BY

Cumulative calculations

Business-oriented analytical metrics

Data Model

EMPLOYEES
    │
    ├── DEPARTMENT_ID → DEPARTMENTS → LOCATIONS → COUNTRIES → REGIONS
    │
    └── JOB_ID → JOBS

Project Structure

oracle-hr-workforce-analysis/
├── README.md
├── sql/
│   ├── 01_department_concentration.sql
│   ├── 02_geographic_distribution.sql
│   └── 03_department_job_composition.sql
├── docs/
│   ├── business-context.md
│   ├── analytical-questions.md
│   └── findings.md
└── data/
    └── README.md

Detailed business context, analytical questions and findings are available in the docs/ folder.

Author

Pedro Barros
Data Analytics | SQL | Power BI