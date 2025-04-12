# Hiring Process Analytics

This repository provides an in-depth analysis of a company's hiring data using Microsoft Excel. The goal is to uncover meaningful insights that can improve recruitment strategies and support data-driven decision-making within the Human Resources (HR) department.

---

##  Project Objective

As a Data Analyst at a multinational company like Google, your task is to analyze the hiring process data to:

- Understand hiring patterns
- Analyze salary structures
- Explore department-wise hiring trends
- Support data-driven HR decisions

---

##  Repository Structure

```
 Hiring-Process-Analytics
├──  data
│   └── Raw and cleaned dataset files
│
├──  visuals
│   └── Charts and graphs generated in Excel
│
├──  excel_analysis
│   └── Processed Excel sheets with formulas, pivot tables, and insights
│
├──  Hiring_Insights_Report.pdf
│   └── Summary of key findings and recommendations
│
└──  README.md
    └── Project overview, tasks, and documentation
```

---

##  Data Cleaning & Preparation

### 1. Handling Missing Data
- Identified null values in critical columns (e.g., gender, department).
- Strategy: Replaced missing values with appropriate replacements (e.g., "Unknown" for gender, mode for department).

### 2. Clubbing Columns
- Combined similar job titles into broader categories for simplified analysis.
- Example: Grouped "Software Engineer" and "Developer" into "Engineering".

### 3. Outlier Detection
- Used Excel charts (box plots and histograms) and conditional formatting to detect salary and hiring anomalies.

### 4. Removing Outliers
- Strategy: Retained most values, removed extreme salary outliers to avoid skewed averages.

### 5. Data Summary
- Created pivot tables and statistical summaries to extract meaningful trends and descriptive metrics (e.g., average salary, gender ratio).

---

##  Data Analytics Tasks

### A. Hiring Analysis
**Objective:** Determine gender distribution.
- Task: Count and compare the number of male vs. female hires.
- Tool: Excel COUNTIF, Pie Chart for visualization.

### B. Salary Analysis
**Objective:** Calculate the average salary.
- Task: Use Excel AVERAGE function to compute mean salary across employees.
- Bonus: Compared average salaries by gender or department.

### C. Salary Distribution
**Objective:** Understand how salaries are spread across ranges.
- Task: Created class intervals (e.g., 0-30K, 30K-60K, 60K-90K, etc.).
- Tool: Used Excel histogram and COUNTIFS.

### D. Departmental Analysis
**Objective:** Identify department-wise hiring trends.
- Task: Used bar graph or pie chart to show hires per department.
- Insights: Highlighted which departments are expanding or stagnant.

### E. Position Tier Analysis
**Objective:** Explore tier-level distribution within the organization.
- Task: Categorized employees into tiers (e.g., Entry, Mid, Senior) and visualized the distribution.
- Tool: Excel stacked bar chart or column chart.

---

##  Tools Used
- Microsoft Excel
- Excel Formulas: COUNTIF, AVERAGE, MEDIAN, MODE, MAX, MIN, VAR, STDEV, PERCENTILE, CORREL
- Pivot Tables and Charts
- Conditional Formatting
- Data Validation

---

##  Key Insights (Examples)
- Majority of hires are in the Engineering and Marketing departments.
- Gender distribution shows a hiring gap favoring male candidates.
- Average salary offered is INR 52,000 per month.
- Most employees fall under the Entry and Mid-level tiers.
- Salary outliers removed increased the accuracy of average salary analysis by 12%.

---

##  Conclusion
This project helped uncover valuable insights about the hiring process and workforce structure. With actionable metrics and department-specific hiring patterns, stakeholders can now:
- Refine recruitment strategies
- Adjust compensation packages
- Promote diversity and inclusion
- Better allocate HR resources

This analysis contributes to building a more efficient, transparent, and data-driven hiring ecosystem.

---

