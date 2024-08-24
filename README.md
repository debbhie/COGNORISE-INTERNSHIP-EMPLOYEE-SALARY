## EMPLOYEE-SALARY

 ## TABLE OF CONTENT
- [EMPLOYEE SALARIES OVERVIEW](#employee-salaries-overview)
- [LANDING PAGE](#landing-page)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [TYPES OF ANALYSIS USED FOR THIS PROJECT](#types-of-analysis-used-for-this-project)
- [KEY PERFORMANCE INDICATORS](#key-performance-indicators)
- [DATA ANALYSIS](#data-analysis)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)

## EMPLOYEE SALARIES OVERVIEW
The employee salary dataset provides a comprehensive overview of salary information across various dimensions such as work year, experience level, employment type, job title, and geographic locations.

## LANDING PAGE
* Work Year (work_year): Represents the year of employment, allowing for analysis of trends over time, such as year-over-year changes in average salaries.
* Experience Level (experience_level): Categorizes employees based on their experience, such as entry-level, mid-level, and senior-level positions. This allows for analysis of how experience impacts salary.
* Employment Type (employment_type): Indicates the nature of employment, whether full-time, part-time, or contract, enabling comparisons of salary distributions across different employment types.
* Job Title (job_title): Describes the specific role or position of the employee within the company. This column is essential for analyzing salary variations by job role and identifying the highest and lowest paying positions.
* Salary (salary): The salary amount in the local currency, which is essential for analyzing compensation within a specific geographic or economic context.
* Salary Currency (salary_currency): Specifies the currency in which the salary is paid, such as USD or EUR, allowing for the conversion of salaries to a common currency for comparison.
* Salary in USD (salary_in_usd): The salary converted to United States Dollars (USD), enabling direct comparison of salaries across different currencies and regions.
* Employee Residence (employee_residence): The location of the employee's residence, which can be analyzed to understand how geographic factors influence salary levels.
* Remote Ratio (remote_ratio): Indicates the percentage of remote work allowed for the position, providing insight into how remote work flexibility might correlate with salary.
* Company Location (company_location): The geographic location of the company, which is useful for comparing how company location impacts salaries, especially in a global context.
* Company Size (company_size): Describes the size of the company (e.g., small, medium, large), which can be used to analyze how company scale affects salary structures.

## DATA SOURCE
This dataset was gotten from cognorise internship as part of the required tasks.
[download here](https://www.kaggle.com/datasets/inductiveanks/employee-salaries-for-different-job-roles)

## TOOLS
- Analysis - jupyter notebook
- Visualization - jupyter notebook

## TYPES OF ANALYSIS USED FOR THIS PROJECT
* Salary Distribution Analysis: To analyze how salaries vary across different job titles.
* Experience and Employment Analysis: To explore the relationship between experience level and employment type.
* Remote Work Analysis: To analyze the impact of remote work across different job titles.
* Company Location Analysis: To identify trends in employment types, experience levels and job title by company location.

## KEY PERFORMANCE INDICATORS
* Top 5 median salary in usd for each job title.
* Year over year percentage change in average salary in usd.
* Comparison of average salaries between different employee residence location and company locations.
* Identify the top 10 job titles with the highest average salaries in usd.
* The difference between the highest and lowest salaries in usd, segmented by job title and experience level.
* Percentage of employees in each experience level category.
* Ratio of fulltime to parttime to contract employee.
* Average remote work percentage across the company with breakdown by job title and experience.
* Percentage of employee working insmall, medium and large companies.
* Percentage of employee working remotely vs those living in the same location as the company.
* Comparison of average salaries in usd across small, medium and large companies.
* Analysis of how remote work percentage influence salary level.
* Trends in the proportion of fulltime, parttime and contract employement over the years.

## DATA ANALYSIS
* Average Salary in USD by Experience Level:
EN (Entry-Level): $61,643.32
EX (Executive-Level): $199,392.04
MI (Mid-Level): $87,996.06
SE (Senior-Level): $138,617.29
  As expected, salaries increase with experience. Entry-level positions have the lowest average salary, while executive-level roles command the highest. Senior-level employees earn significantly more than mid-level and entry-level employees, reflecting their expertise and responsibilities.

* Top 5 Median Salaries in USD:
Data Analytics Lead: $405,000
Financial Data Analyst: $275,000
Head of Data: $200,000
Principal Data Engineer: $200,000
Data Architect: $180,000
  These roles represent high-demand, high-responsibility positions within data science and analytics. The substantial median salaries indicate that professionals in these roles are well-compensated, especially for leadership or specialized technical positions like Data Analytics Lead and Principal Data Engineer.

* Salary Range by Experience Level:
EN (Entry-Level): $246,000
EX (Executive-Level): $530,259
MI (Mid-Level): $447,141
SE (Senior-Level): $393,093
 The salary range represents the difference between the highest and lowest salaries within each experience level. Executive-level roles have the widest range, reflecting diverse compensation packages that might include bonuses, stock options, or other benefits. Even within the same experience level, there can be substantial differences in pay based on job role, industry, and company.

* Percentage of Employees by Experience Level:
SE (Senior-Level): 46.13%
MI (Mid-Level): 35.09%
EN (Entry-Level): 14.50%
EX (Executive-Level): 4.28%
 The distribution shows a significant concentration of employees at the senior and mid-levels. This suggests that the organization may prioritize experience and expertise, with fewer positions available for entry-level or executive roles. The lower percentage of executives is typical, as these roles are usually fewer in number and higher in authority.

* Ratio of Employment Type:
FT (Full-Time): 96.87%
PT (Part-Time): 1.65%
CT (Contract): 0.82%
FL (Freelance): 0.66%
 The overwhelming majority of employees are full-time, indicating a stable workforce with fewer part-time, contract, or freelance positions. This suggests that the company values long-term employment relationships, possibly due to the need for continuity and stability in roles that require ongoing development and deep understanding.

* Year Over Year Percentage Change in Average Salary:
2020: $95,813 (Baseline year)
2021: $99,853.79 (4.22% increase)
2022: $124,522.01 (24.70% increase)
 The average salary has steadily increased year over year, with a significant jump in 2022. This sharp rise could be attributed to various factors such as inflation, increased demand for skilled professionals, or changes in the industry that necessitate higher compensation to attract and retain talent.

* Top 10 Average Salaries in USD:
Data Analytics Lead: $405,000
Principal Data Engineer: $328,333.33
Financial Data Analyst: $275,000
Principal Data Scientist: $215,242.43
Director of Data Science: $195,074.00
Data Architect: $177,873.91
Applied Data Scientist: $175,655.00
Analytics Engineer: $175,000.00
Data Specialist: $165,000.00
Head of Data: $160,162.60
 These roles represent some of the highest-paying positions in the dataset. Leadership roles, specialized technical positions, and those requiring advanced analytics and data science skills dominate the top 10. The high average salaries reflect the critical importance of these roles in driving data-driven decision-making and innovation within the organization.

* Average Remote Work Percentage Across the Company: 70.92%
  On average, employees in the company work remotely 70.92% of the time. This high percentage suggests that the company has adopted a flexible or hybrid work model, allowing a significant portion of its workforce to work from locations other than the company's physical office. This trend aligns with global shifts towards remote work, especially in tech and data-related roles.

* Average Remote Work by Experience Level:
EN (Entry-Level): 69.89%
EX (Executive-Level): 78.85%
MI (Mid-Level): 63.85%
SE (Senior-Level): 75.89%
- Executives and Senior-Level Employees have the highest average remote work percentages. This indicates that higher-ranking positions are more likely to have the flexibility to work remotely, possibly due to their greater autonomy and the nature of their responsibilities, which might not require daily on-site presence.
- Mid-Level Employees have the lowest average remote work percentage. This may be because they are often in roles that require coordination between teams, necessitating more frequent in-person interactions.
- Entry-Level Employees also have a relatively high percentage of remote work, reflecting the trend of integrating remote work even at the beginning stages of an employee's career.

* Percentage of Employees Working Remotely: 79.08%
  A large majority (79.08%) of employees are working remotely, which reinforces the company’s strong inclination towards remote work. This trend might be a response to employee preferences, operational flexibility, or external factors like the COVID-19 pandemic, which accelerated remote work adoption.

* Percentage of Employees Living in the Same Location as the Company: 91.60%
  Despite the high percentage of remote work, a significant proportion of employees (91.60%) live in the same location as the company. This suggests that while employees have the option to work remotely, many still choose to reside close to the company’s physical offices, possibly to maintain the option of in-office work or due to personal reasons such as family or lifestyle preferences.

* Average Salary in USD by Company Size:
Large Companies (L): $119,242.99
Medium Companies (M): $116,905.47
Small Companies (S): $77,632.67
 Large and Medium Companies offer significantly higher average salaries compared to Small Companies. This is typical, as larger organizations generally have more resources and can offer more competitive salaries to attract top talent.
Small Companies tend to offer lower salaries, possibly due to limited budgets or resources. However, they may compensate with other benefits such as equity, flexible work conditions, or opportunities for rapid career growth.

* Trends in Employment Type Proportion Over the Years:
- 2020: Full-Time (FT) 94.44%, Part-Time (PT) 2.78%, Contract (CT) 1.39%, Freelance (FL) 1.39%
- 2021: Full-Time (FT) 94.93%, Part-Time (PT) 2.76%, Contract (CT) 1.38%, Freelance (FL) 0.92%
- 2022: Full-Time (FT) 98.74%, Part-Time (PT) 0.63%, Contract (CT) 0.31%, Freelance (FL) 0.31%
  Increase in Full-Time Employment: There is a clear trend towards a higher proportion of full-time employment over the years, peaking at 98.74% in 2022. This suggests a shift towards more stable, long-term employment arrangements, possibly reflecting the company’s confidence in its growth and need for dedicated employees.
Decline in Part-Time, Contract, and Freelance Roles: The reduction in part-time, contract, and freelance positions over the years indicates a move away from flexible or temporary employment arrangements. This could be due to various factors such as increased demand for full-time roles, changes in business strategy, or a shift towards in-house talent development.

* Correlation Coefficient: 0.13
The correlation coefficient of 0.13 indicates a weak positive relationship between remote work percentage and salary. This suggests that as the percentage of remote work increases, salary tends to increase slightly, but the relationship is not strong. A correlation of 0.13 means that other factors likely play a more significant role in determining salaries than remote work percentage alone.
* OLS Regression Results:
Key Metrics:
- R-squared (uncentered) 0.591: The R-squared value represents the proportion of the variance in the dependent variable (salary) that is predictable from the independent variable (remote work percentage). An R-squared of 0.591 indicates that about 59.1% of the variance in salaries can be explained by the remote work percentage. This is a moderately high value, suggesting that while remote work percentage is a significant predictor of salary, other factors also contribute.
- Adjusted R-squared (uncentered) 0.590: The adjusted R-squared accounts for the number of predictors in the model, and it is slightly lower than the R-squared, which is typical. This indicates that the model is well-fitted without overfitting.
* Coefficient for Remote Work Percentage (remote_ratio): 1248.4789:
This coefficient represents the amount by which the salary is expected to increase for each 1% increase in remote work percentage. Specifically, for every 1% increase in remote work percentage, the salary is expected to increase by approximately $1,248.48.
The p-value (P>|t|) is 0.000, which is highly significant, indicating that the relationship between remote work percentage and salary is statistically significant.
* F-statistic: 874.7:
The F-statistic measures the overall significance of the model. A high F-statistic with a very low p-value (Prob > F) of 1.15e-119 indicates that the model as a whole is statistically significant, meaning that the remote work percentage is a meaningful predictor of salary.
* Log-Likelihood: -7750.7 and AIC (Akaike Information Criterion): 1.550e+04:
These are metrics used to compare models. The log-likelihood value indicates how likely the observed data is under the model, with higher values generally indicating a better fit. The AIC provides a measure of the model's quality, with lower values indicating a better fit when comparing different models.
* Skewness (1.175) and Kurtosis (6.162):
The skewness and kurtosis values indicate the distribution of the residuals (errors). A skewness of 1.175 suggests a right-skewed distribution, meaning there are more high residuals than expected in a normal distribution. A kurtosis of 6.162 indicates a leptokurtic distribution, meaning there are more outliers than in a normal distribution.
* Interpretation and Implications:
The results indicate that remote work percentage has a significant but relatively modest impact on salary. While an increase in remote work percentage is associated with higher salaries, this factor alone doesn't account for the majority of the variation in salaries, as evidenced by the R-squared value.
The significant p-value and F-statistic show that remote work percentage is an important predictor, but other factors (such as job title, experience, industry, and company size) are also likely influencing salaries.
The skewness and kurtosis suggest that the salary data may not be perfectly normally distributed, which could influence the regression results. However, the overall model fit is reasonable.

## INSIGHTS
