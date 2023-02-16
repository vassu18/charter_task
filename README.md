# charter_task
assignment for charter communications from Vasavi lingala 
Rewards Application - Java backend
Vasavi L, 2023/02/16 


This is an overview of the Java Web Application to fulfill the job requirement Web Application developer.

My Name is Vasavi Lingala (she). I designed and developed this application using Spring Boot (3.0) with H2 Database. 

The gitlab <<<<>>> contains the Java Code for this web application.
Requirement
A retailer offers a rewards program to its customers, awarding points based on each recorded purchase.

A customer receives 2 points for every dollar spent over $100 in each transaction, plus 1 point for every dollar spent between $50 and $100 in each transaction.
(e.g. a $120 purchase = 2x$20 + 1x$50 = 90 points).

Given a record of every transaction during a three month period, calculate the reward points earned for each customer per month and total.

·         Solve using Spring Boot
·         Create a RESTful endpoint
·         Make up a data set to best demonstrate your solution
·         Check solution into GitHub Sent from my iPhone
Solution Overview
There are two main flows using REST API (postman) to demonstrate 

Customer (end-user) purchases and the order, payment details are submitted using a REST POST request and creates a new Purchase table row in DB
This also creates another row in the Reward table
Customer can view the rewards points using REST GET (month/cust)
Admin can view the purchases, rewards, customers and products
H2 Database table contents has persisted data
Screen Shots (Postman, H2DB, IntelliJ)

IDE source code structure and report rest api screen 
List of Purchases, Rewards postman  (end point on my pc localhost:8181/sales/purchase )
H2DB Tables and rows
Spring boot console logs 










List of Purchases and Reward points 







New Purchase and auto created reward (# 43) 



Reward row with ID 43 new 

H2 DB Schema and tables  overview


















Reward points Monthly report ( month 12 (Dec) and custid 11)






