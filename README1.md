# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

This collaborative short project explores card attrition rates using Jupyter Notebooks for ETL along with BowerBI for visualisation. While not all customers who leave are necessarily churners, attrition data can provide a valuable insight for the trend and further investigation. Credit card churning happens when a person applies for lots of credit cards to collect big sign-up and welcome bonuses. Once they get the sign-up rewards and bonuses, a credit card churner will usually stop using the cards or cancel them, only to repeat the process again.

# Summary:
* [Data Investigations Notebook]
* [Cleaned Data]
* [Visualisations Power BI]
* [Presentation]

# DATAset:
[Kaggle Credit Card Data](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers)

# Business Requirements:
Banks strive to keep their customers, since a high attrition rate leads to reduced profits. By analyzing trends among customers who leave, banks can take steps to lower attrition—either by modifying their services or shifting their marketing focus to different demographic segments.git


# Hypotheses
## 1.Demographic factors
We are looking into how gender, age, income, and education are influencing churn.
###*Conclusion*
* Gender: Female customers exhibit a higher churn rate compared to male customers.

* Age: Customers aged 40–50 years show the highest churn rates, suggesting potential financial instability or dissatisfaction.

* Income: Customers with annual incomes below $40K are more likely to churn, possibly due to financial constraints.

## 2.Credit card usage
We analyse data by card type and credit limit and customers transaction behaviour.
###*Conclusion*
* Card Type: Overall we have a 16% churn rate. Customers holding 'Gold' cards have a higher attrition tendancy compared to other card types.

* Credit Limit: Contrary to expectations, credit limit does not significantly impact churn rates in this dataset.

* Transaction Behavior: Churned customers typically have fewer transactions in the past 12 months, indicating lower engagement.
## 3. Customer relationship and account activity
We compare customer enagagement with the product and customer service.
###*Conclusion*
* Months Inactive and on the books: The churn count picks at 36 months, increasing tenfold compared to any other values, while generaly increases on the second year and drops after the third year to almost flat on the fourth year. Also, a higher number of inactive months correlates with increased churn risk.

* Total Relationship Count: Customers with fewer products or services are more likely to churn, highlighting the importance of cross-selling.

* Contacts Count: A lower number of customer service contacts is associated with higher churn rates, suggesting that proactive engagement may reduce attrition.

## *Recommendations*
* Investigate the pick of churn on the 36th month by product reviews and customer feedback collection.
* Customer engagement, marketing campaigns and cross-selling activities need to be taylored by target audience and increased especially from the 20th month in order to avoid the churn rate increase.



## Project Plan
The three of us will collaborate as a Project Manager, Data Architect, and Data Analyst to plan, prepare, and present a data-driven story. We'll extract, transform, and analyze data to build an interactive dashboard using Power BI. The final deliverable will showcase clear insights and effective storytelling through data visualization.

# The rationale to map the business requirements to the Data Visualisations:
## 1.
## 2.
## 3.

# Analysis techniques used:
Data extraction, cleaning and transformation in Jupyter Notebooks
Visualisation in Power BI: interactive dashboards and visual tools to analyze churn through descriptive stats, correlations, customer segmentation, and churn prediction, enabling data-driven retention strategies.

# Ethical considerations:
Financial data is highly sensitive and must adhere to GDPR and other relevant regulations. To ensure the protection of this information, the data was anonymized by removing client numbers.

# Technologies used:
* VS Code
* Python
* Jupyter Notebook
* Power BI
* AI tools: ChatGPT, Co-Pilot

## Development Roadmap
We have used GitHub and various e-meetings channels to plan, contribute communicate and coordinate our tasks and workload.

# Data Analysis Libraries:
* Pandas- Purpose: Data loading, cleaning, and manipulation.
* NumPy- Purpose: Numerical operations and array handling.
* Matplotlib & Seaborn- Purpose: Data visualisation to explore relationships between variables.

## Credits 
* Code Institute https://learn.codeinstitute.net/ and GitHub: https://github.com/Code-Institute-Solutions/da-README-template, https://github.com/Code-Institute-Org/data-analytics-template
* CoPilot for code correction and predictive suggestions
* ChatGPT for text rephrasing and visualisation optimisation

### Content and Media

* The data set is from https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance 
* Instructions and project templates are from: Code Institute https://learn.codeinstitute.net/ and GitHub: https://github.com/Code-Institute-Solutions/da-README-template, https://github.com/Code-Institute-Org/data-analytics-template
* The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)


## Acknowledgements (optional)
* Really appreciated the support and guidance from my tutors, coordinators and colleagues. Thank you!