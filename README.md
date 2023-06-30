# **Customer Churn Analysis Using Power BI**
![](churn-rate.png)

## 1. **INTRODUCTION**
Customer churn is not merely a statistic or a metric; it represents a missed opportunity and a potential warning sign for any business. When customers decide to discontinue their relationship with a company, it not only affects revenue and profitability but also has broader implications for brand reputation, customer loyalty, and overall growth. 
In this project, I will explore the multifaceted nature of customer churn and its implications. We will examine the underlying reasons behind churn, such as subpar customer experiences, lack of personalization, and failure to meet evolving customer needs. By understanding these root causes, we can begin to address them head-on and develop proactive strategies to mitigate churn rate.

## 2. **Problem Statement: Churn Analysis**
The problem at hand is to analyze customer churn for a company and develop a predictive model that can identify customers who are most likely to churn. The goal of this analysis is to understand the factors that contribute to customer churn and develop a model that can accurately predict churn behavior. By identifying customers who are at a high risk of churning, the company can proactively take actions to retain them, such as offering personalized incentives, improving customer service, or enhancing the value proposition of their products or services.

The following imperative tasks must be completed in order to address this issue:
- Data Preparation and Cleaning
- Exploratory Data Analysis and Data Insights
- Recommendation for Retaining Customers
- Data Visualization
  
**Data Cleaning and Preparation** 

- I replaced all null values with "0" or "NA" depending on the column.
- I also changed some of the datatypes for all the non-quanlative numerical columns to text data types.
- To track Churn tenure, I introduced a conditional column.
- 
 applied_step      
![](applied_step.jpg)   
conditional_column
 ![](Conditional_column.jpg)

**Exploratory Analysis**
In total, there are 7,043 customers.

How much revenue was lost to churned customers?
Maven lost 1869 clients, who were responsible for 17% of its overall income. It's a significant number.

DAX to count the total churn    
![](DAX_count_churned.jpg)      

DAX to calculate the % churn on revenue

![](Churn_on_revenue.jpg)

Outcome

![](churn.jpg)  

How Long does customers stay before churning?
I used the Conditional column function in Power query to determine how long consumers normally stay at Maven before departing. 
I discovered that 42% of consumers who left Maven within 6 months or less.

conditional_column
 ![](Conditional_column.jpg)

Churn Tenurn

What cities have the greatest rates of Churn?
**San Diego** had the highest churn rate at 185, with 78 customers from **Los Angeles** also churned this two cities should be a concern 
to Maven telecom because this representate half of there customers on those cities





