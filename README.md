# Data_Analytics

Project Overview:

This project offers an in-depth analysis of bank churn data. Churn in this context signifies the number of customers who have left the bank, commonly referred to as attrition. The dataset used for this analysis is a Churn analysis, utilized for the purpose of report creation and understanding the various aspects of data analysis using PowerBI.

The dataset format is given below.
Inside the dataset, there are 10000 rows and 14 different columns.

Variable  	Definition
RowNumber -	Unique Row Number

CustomerId -	Unique Customer Id

Surname -	Surname of a customer

CreditScore -	Credit Score of each Customer

Geography -	Geographical Location of Customers

City_Category -	Category of the City (A,B,C)

Gender -	Sex of Customers

Age -	Age of Each Customer

Tenure -	Number of years

Balance -	Current Balance of Customers

NumOfProducts -	Number of Products

HasCrCard -	If a customer has a credit card or not

IsActiveMember -	If a customer is active or not

EstimatedSalary -	Estimated Salary of each Customer

Exited -	Customer left the bank or Not (Target Variable)


# End To End - TASKS Performed
Data Collections (Database / CSV/ Excel)

# Data Cleaning:
- Cleaned the data and transform raw data using Power Query Editor
- Checked if there is any null values or not, Changed the data types and renamed the columns.
- Added columns from examples,Changed the data type of some columns from whole number to text and Replace the values.
- Added some Conditional columns like Age Group,Credit Score, Balance etc. and changed there datatype too.

# Data Modeling:
- Created Queries to organise data for Analysis & Reporting.
- Created a separate table for some columns and added a column that can be then used for reordering the values in some sort of orders.
- Then, viewed and edited the relationships in the model view.

# DAX Calculations:
Created some calculations and analysis like -
- No.of customers
- Customers lost
- Churn rate

# Data Visualisation (Analysis Report):
Created Dashboard to share insights -
# Cards:
- Displaying the number of customers.
- Showcasing the churn rate.
- Showing the number of lost customers.
# Charts:
Donut charts for -
- Number of customers by gender.
- Number of customers by active members.
- Number of customers by credit card status.
- Number of customers by country.
- Number of customers by Product.
- Minimum estimated salary by age group.
- Line clustered bar chart showing customers and churn rate by age group.
- Line and stacked column chart for customers and churn rate by credit score.
- Line  stacked column chart showing customers and churn rate by credit score.
- Stacked column chart representing by Acct_balance.
- Line chart showing Count of Churn status by tenure.

Insights :-
- There are 10,000 no of customers and customers we lost are 2037 that is 20.4% Churn Rate. We have most of the customers whos age is between 31-40.
- Female Churn Rate is more than Male Customers.
- Most Customers are from France and most Churn Rate is from Germany.
- The company is at Risk of loosing recently joined customers who are tenured between 1-3 years. Longer tenured customers are less likely to Churn.
- It is found that there are total of 69.17% customers who holds only 1 product and which are Churned.
- There are 70.55% of customers who owns Credit Card out of which 36.07% of customers are active and 34.48 % customers are inactive.  29.45% of customers who doesn't owns a credit card out of which 15.44% customers are active and 14.01% customers are inactive.

Conclusion :-
- churn rate helps establish targets for improvement and track progress over time.
- Develop targeted retention strategies for age groups with higher churn rates, such as tailored communication and product offerings.
- Customize marketing and customer service efforts to address the specific concerns and preferences of each gender.
- retention strategies and resources on high-churn regions. This might include local promotions, region-specific customer support, or market analysis to understand regional challenges.
- Implement loyalty programs and incentives for long-term customers to maintain their satisfaction and reduce churn.
- Promote active membership benefits and credit card usage through targeted campaigns and incentives.
- Provide financial health check-ups and personalized financial advice to customers with lower balances to help improve their financial situation and retention.
- Offer premium services and personalized financial planning to high-salary customers to retain their business.
