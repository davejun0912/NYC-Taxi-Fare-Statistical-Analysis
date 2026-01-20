Project Overview
This project is a key component of the Google Advanced Data Analytics Professional Certificate program. It involves a workplace scenario for a fictional consulting firm, Automatidata, representing a real-world data analysis task for the New York City Taxi & Limousine Commission (TLC). The primary objective is to conduct a formal hypothesis test to determine if there is a statistically significant difference in the average fare amount between customers who pay with credit cards and those who pay with cash.

Problem Statement
The New York City TLC seeks to optimize revenue and improve payment efficiency. The core business question is whether credit card transactions are associated with higher fare amounts. If a significant relationship is found, the organization can develop data-driven strategies to encourage credit card adoption, potentially leading to higher overall trip value and improved data tracking.

Methodology
The analysis follows the PACE (Plan, Analyze, Construct, Execute) framework to ensure a structured approach to data science:

Plan: Defined the business problem and identified the appropriate statistical test.

Analyze: Conducted Exploratory Data Analysis (EDA) to assess data distribution and quality.

Construct: Performed a two-sample t-test (Welch's t-test) to account for potential unequal variances between the two payment groups.

Execute: Interpreted the p-value and provided strategic recommendations to stakeholders.

Hypothesis Testing
Null Hypothesis (H 
0
​	
 )

There is no difference in the average fare amount between customers who pay with credit cards and those who pay with cash (μ 
credit
​	
 =μ 
cash
​	
 ).

Alternative Hypothesis (H 
a
​	
 )

Customers who use credit cards pay a higher average fare amount than those who use cash (μ 
credit
​	
 >μ 
cash
​	
 ).

Statistical Results

Confidence Level: 95% (α=0.05)

T-statistic: [Insert your T-statistic here, e.g., 20.12]

P-value: [Insert your P-value here, e.g., p < 0.001]

Conclusion and Business Insights
The statistical analysis resulted in a p-value significantly lower than the significance level of 0.05, leading to the rejection of the null hypothesis. The data provides sufficient evidence to conclude that credit card transactions are associated with higher fare amounts compared to cash payments.

Strategic Recommendations:

Credit Card Incentivization: Implement marketing initiatives or loyalty programs to promote credit card usage.

Driver Education: Educate drivers on the statistical correlation between card payments and higher fares to encourage adoption of the digital payment system.

User Experience Optimization: Ensure the payment interface is seamless to reduce friction for passengers during the checkout process.

Repository Structure
notebooks/: Contains the Jupyter Notebook with complete Python code, EDA, and visualizations.

reports/: Includes the Executive Summary and PACE strategy document.

data/: Information regarding the TLC dataset and variable definitions.
