# Bicycle-Manufacturing-Analytics-Insights-with-Python-SQL-and-Power-BI

## What is the Problem Solved?

Bike company executives needed clarity on their sales, employee performance, and store operations. The aim is to visualize the data in an easily digestible format to answer specific business questions, helping in decision-making across various departments.

## How it is Solved?

Used SQL and Python to analyze datasets related to sales, employee leave, bonuses, and store performance. Our approach included generating detailed visualizations and calculating correlation coefficients where necessary, ensuring that the insights were backed by data.

## Solution

The analysis is structured around answering the following key business questions:
1. **What are the regional sales in the best-performing country?**
2. **What is the relationship between annual leave taken and bonuses?**
3. **What is the relationship between country and revenue?**
4. **What is the relationship between sick leave and job title?**
5. **What is the relationship between store trading duration and revenue?**
6. **What is the relationship between the size of stores, number of employees, and revenue?**

Each question was explored using SQL queries and visualizations, and we provided a narrative around the findings to make the results actionable.

### Key Findings:
1. **Regional Sales:**
   - The U.S. is the best-performing country, with $45.8M in total sales over the last two years.
   - The Southwest region leads in sales with $10.5M, followed by the Northwest with $7.8M.
   - A significant increase in sales share was observed in these two regions.

2. **Annual Leave and Bonus Relationship:**
   - A moderate positive correlation (0.3821) between annual leave and bonuses was found, but the p-value was greater than 0.1, suggesting that this relationship is not statistically significant.

3. **Country and Revenue:**
   - The U.S. is responsible for 62.9% of Adventure Works’ revenue, with the Australian and European markets showing rapid growth.

4. **Sick Leave and Job Title:**
   - No significant trend was found between sick leave and job titles, though entry-level and senior roles tend to take more sick leave than directors.

5. **Store Trading Duration and Revenue:**
   - Stores with longer trading durations tend to generate less revenue, though stores operating for over 14 years showed minimum annual revenues of $80K.

6. **Store Size, Employees, and Revenue:**
   - A strong positive correlation between store size, number of employees, and revenue was observed. Larger stores with more employees consistently brought in higher revenue.

## Outcome Results (Quantitative Impact)

- **Increased Sales Focus:** The executives can now target specific regions such as the Southwest and Northwest for further investment.
- **Expansion Opportunities:** Data suggests potential for growth in Australia and Europe, where revenues have nearly doubled over the past year.
- **Operational Efficiency:** Insights on store size, trading duration, and employee count will guide more efficient allocation of resources and staffing.
- **HR and Compensation Strategy:** The findings on annual leave and bonus relationships allow Adventure Works to reconsider compensation strategies, especially for the sales department.

## Conclusion

This report provides actionable insights to drive key business decisions. However, certain data limitations (e.g., missing bonus data for all employees, lack of precise revenue figures for all stores) suggest that future data collection and consistency should be improved to support more robust analyses.
