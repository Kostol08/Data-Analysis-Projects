# Employee Diversity, Inclusion & Organizational Performance Analysis

## Overview

This project analyzes employee survey data to understand perceptions of:

- Workforce diversity
- Inclusion practices
- Organizational performance
- Equity, belongingness and psychological safety

The analysis uses **Microsoft Excel** and **Power BI** to turn employee responses into measurable insights and management recommendations.

## Dataset

- 75 valid employee responses
- 37 Likert-scale items
- Five-point scale: 1 = Strongly Disagree, 5 = Strongly Agree
- Workforce Diversity: 9 items
- Inclusion Practices: 10 items
- Organizational Performance: 11 items
- Relationship Assessment: 7 items

## Key Findings

- Workforce Diversity mean: **4.08/5**
- Inclusion Practices mean: **4.08/5**
- Organizational Performance mean: **4.18/5**
- Relationship Assessment mean: **4.08/5**
- Inclusion Practices vs Organizational Performance: **r = 0.606, p < 0.001**
- Equity/Belongingness/Safety vs Organizational Performance: **r = 0.589, p < 0.001**
- Workforce Diversity vs Organizational Performance: **r = 0.469, p < 0.001**
- Gender vs Organizational Performance: **p = 0.681**
- Age vs Organizational Performance: **p = 0.801**
- Lowest item: equal employment opportunities for people with disabilities: **3.29/5**
- Next-lowest item: employee involvement in decision-making: **3.76/5**

## Analysis Performed

- Data cleaning and preparation
- Likert-scale coding
- Descriptive statistics
- Section-level scoring
- Item-level analysis
- Reliability analysis using Cronbach's alpha
- Pearson correlation
- One-way ANOVA
- Demographic analysis
- Open-ended response theme aggregation
- Dashboard development

## Tools

- Microsoft Excel
- Microsoft Power BI

## Files

| File | Description |
|---|---|
| `Employee_Diversity_Inclusion_Analysis_Report.pdf` | Complete analysis report |
| `Employee_Diversity_Inclusion_Analysis.xlsx` | Excel analysis workbook |
| `PowerBI_Dashboard_Specification.md` | Dashboard structure, visuals and measures |
| `dashboard/employee_diversity_inclusion_dashboard.png` | Executive dashboard image |
| `data/Cleaned_Data.csv` | Cleaned dataset |
| `data/Fact_Respondent.csv` | Respondent-level analytical table |
| `data/Fact_Likert.csv` | Long-format Likert response table |
| `data/Dim_Item.csv` | Item/dimension reference table |

## Main Insight

The strongest relationship in the dataset is between inclusion practices and perceived organizational performance. The results also highlight disability inclusion and employee participation in decision-making as the clearest areas requiring attention.

## Data Privacy

Only cleaned and anonymized data should be published in a public repository. Direct identifiers, email addresses, exact timestamps and raw employee comments should not be published.
