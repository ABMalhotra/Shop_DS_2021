#### Question 1: Given some sample data, write a program to answer the following: click here to access the required data set.

This question is answered here:
https://github.com/ABMalhotra/Shop_DS_2021/blob/master/Sneaker_Pricing.ipynb

What metric would you report for this dataset? 
#### mean of order_amount/total_items

What is its value? 
#### $387.74


-------------------------------------------------


#### Question 2: For this question you’ll need to use SQL. Follow this link to access the data set required for the challenge. Please use queries to answer the following questions. Paste your queries along with your final numerical answers below.

How many orders were shipped by Speedy Express in total? 54
#### SQL Query:
SELECT COUNT(*)
FROM Orders O INNER JOIN Shippers S
ON S.ShipperID = O.ShipperID
WHERE ShipperName = 'Speedy Express'


What is the last name of the employee with the most orders?


What product was ordered the most by customers in Germany?
