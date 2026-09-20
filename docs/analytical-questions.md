# Analytical Questions

## Question 1 — Departmental Concentration

**Business question:**

Is the workforce concentrated in a small number of departments?

**Analytical approach:**

Calculate the number and percentage of employees in each department and determine the cumulative workforce percentage when departments are ordered by workforce size.

**Granularity:**

1 row per department.

---

## Question 2 — Geographic Distribution

**Business question:**

How are employees distributed across countries and regions, and is there relevant geographic concentration?

**Analytical approach:**

Connect employees to their department, location, country and region, then calculate:

* Employees by country
* Total employees within each region
* Country percentage within its region
* Region percentage within the company

**Granularity:**

1 row per country within a region.

---

## Question 3 — Department Job Composition

**Business question:**

How is the workforce structured within each department? Are departments strongly dependent on specific job roles?

**Analytical approach:**

Group employees by department and job title and calculate the percentage that each job represents within its department.

**Granularity:**

1 row per department and job title.
