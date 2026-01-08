# Advertising Data Analysis Using [![TOC](https://img.shields.io/badge/Theory%20of%20Constraints-TOC-blue)](https://en.wikipedia.org/wiki/Theory_of_constraints)





## Project Overview
This project applies the **Theory of Constraints (TOC)** to analyze advertising data and identify the factor that limits overall sales performance.  
The dataset includes advertising spend across **TV**, **Radio**, and **Newspaper** channels, with **Sales** as the output.

The objective is to identify the **constraint** in the system and optimize advertising strategy to improve throughput.

---

## Objectives
- Analyze the impact of advertising channels on sales
- Identify the system constraint using TOC principles
- Improve marketing efficiency by reallocating budget
- Provide data-driven business recommendations

---

## Dataset Description
The dataset contains the following variables:

| Column Name | Description |
|------------|-------------|
| TV | Advertising spend on TV |
| Radio | Advertising spend on Radio |
| Newspaper | Advertising spend on Newspaper |
| Sales | Product sales |

---

## TOC Framework Applied
According to **Theory of Constraints**, every system has at least one constraint that limits its performance.

TOC Steps Applied:
1. Identify the constraint  
2. Exploit the constraint  
3. Subordinate other processes  
4. Elevate the constraint  
5. Repeat the process 

---

## Constraint Identification
After performing exploratory data analysis and correlation analysis:

- **TV** shows a strong positive impact on Sales
- **Radio** shows moderate impact on Sales
- **Newspaper** shows minimal or negligible impact on Sales

### Identified Constraint: **Newspaper Advertising**

---

## Why Newspaper Is the Constraint
- Weak correlation with Sales
- Low return on investment (ROI)
- Increasing spend does not significantly improve Sales
- Consumes budget without increasing throughput

From a TOC perspective, Newspaper advertising limits overall system efficiency.

---

## Key Insights
- Sales growth is constrained by ineffective Newspaper spending
- Budget allocation is misaligned with performance drivers
- TV and Radio are higher-throughput channels

---

## Recommendations (TOC-Based)
- Reduce or eliminate Newspaper advertising spend
- Reallocate budget toward TV and Radio
- Continuously monitor performance to identify new constraints
- Treat marketing spend as a throughput optimization problem

---

## Conclusion
Using the Theory of Constraints, **Newspaper advertising** was identified as the primary constraint in the advertising system.  
By removing or minimizing this constraint, the organization can significantly improve sales performance and marketing ROI.

---

## Tools & Techniques
- Python
- Pandas
- Matplotlib / Seaborn
- Correlation Analysis
- TOC Methodology

---

## 📌 Author
Pranab Debnath
