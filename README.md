# Analysing-Data-in-Banking-Sector

The following project revolves around analysing the data in the banking sector. We analyse the customer expenditure and repayment behaviour along with evaluating areas of bankruptcy, fraud, and collections. The dataset has been attached. Exploratory data anaylsis has bee done on the dataset in order to predict chances of bankruptcy and fraud along with analysing the customer data. The information on data is as follows: - 

* Customer Acquisition: At the time of card issuing, company maintains the details of customers.
* Spend (Transaction data): Credit card spend for each customer
* Repayment: Credit card Payment done by customer

Following are the analysis that have been performed on the dataset. 
Following are some of Mr. Watson’s questions to a Consultant (like you) to understand the customers spend & repayment behavior. 
1. In the above dataset, 
* In case age is less than 18, replace it with mean of age values.
*  In case spend amount is more than the limit, replace it with 50% of that customer’s limit. (customer’s limit provided in acquisition table is the per transaction limit on his card) 
*  Incase the repayment amount is more than the limit, replace the repayment with the limit. 
2. From the above dataset create the following summaries:  
* How many distinct customers exist?  
* How many distinct categories exist?  
* What is the average monthly spend by customers?  
* What is the average monthly repayment by customers? 
* If the monthly rate of interest is 2.9%, what is the profit for the bank for each month? (Profit is defined as interest earned on Monthly Profit. Monthly Profit = Monthly repayment – Monthly spend. Interest is earned only on positive profits and not on negative amounts)
* What are the top 5 product types?  
* Which city is having maximum spend?  
* Which age group is spending more money? 
* Who are the top 10 customers in terms of repayment?
3. Calculate the city wise spend on each product on yearly basis. Also include a graphical representation for the same.
4. Create graphs for  
* Monthly comparison of total spends, city wise  
* Comparison of yearly spend on air tickets  
* Comparison of monthly spend for each product (look for any seasonality that exists in terms of spend)
5. Write user defined PYTHON function to perform the following analysis: You need to find top 10 customers for each city in terms of their repayment amount by different products and by different time periods i.e. year or month. The user should be able to specify the product (Gold/Silver/Platinum) and time period (yearly or monthly) and the function should automatically take these inputs while identifying the top 10 customers.
