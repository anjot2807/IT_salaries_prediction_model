# IT_salaries_prediction_model
This project predicts salaries for tech roles (e.g., Data Scientists, Software Engineers) using regression models. The dataset includes job attributes like experience level and company size, allowing an exploration of how these factors impact compensation in the tech industry.



Dataset Description
This dataset contains information about salaries for various job titles in the tech industry, specifically focusing on roles such as Data Scientists and Software Engineers. Each row represents a unique job position with several attributes that provide insights into the employment conditions and compensation.

Key Features:
work_year: The year in which the job was held, indicating the temporal context of the salary data.

experience_level: The level of experience required for the position, categorized as "MI" (Mid-Level) or "SE" (Senior Level). This feature helps differentiate salaries based on experience.

employment_type: Indicates whether the position is full-time (FT), part-time, or contract-based. Employment type can significantly affect salary levels.

job_title: The specific title of the job, such as "Data Scientist" or "Software Engineer." Different titles often correlate with varying salary ranges.

salary: The nominal salary offered for the position, expressed in the currency specified in the salary_currency column.

salary_currency: The currency in which the salary is paid (e.g., GBP for British Pounds, USD for United States Dollars). This feature is essential for understanding and comparing salaries across different regions.

salary_in_usd: The equivalent salary converted into US Dollars, allowing for easier comparison of salaries regardless of currency differences.

employee_residence: The country where the employee resides, which can influence salary due to local economic conditions.

remote_ratio: The percentage of remote work associated with the position. This can impact salary negotiations and expectations.

company_location: The geographical location of the company offering the job, which often correlates with varying cost-of-living adjustments in salaries.

company_size: Indicates whether the company is small (S), medium (M), or large (L). Company size can influence salary structures and benefits offered to employees.

Objective
For this exercise, I aim to predict salaries using regression models based on the features provided in this dataset. By building a regression model, I can explore how different factors—such as experience level, job title, and company size—affect compensation in the tech industry. This exercise will not only enhance my understanding of regression techniques but also provide valuable insights into salary dynamics within this sector.
