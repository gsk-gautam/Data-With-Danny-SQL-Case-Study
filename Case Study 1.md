
# Introduction
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen.

Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.

## Problem Statement
Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

Danny has provided you with a sample of his overall customer data due to privacy issues - but he hopes that these examples are enough for you to write fully functioning SQL queries to help him answer his questions!

Danny has shared with you 3 key datasets for this case study:
-sales
-menu
-members

You can inspect the entity relationship diagram and example data below.

## Entity Relationship Diagram 
![image](https://github.com/user-attachments/assets/f588c582-737e-4db9-ad0c-0a3154a008ed)

### Example Datasets
All datasets exist within the dannys_diner database schema - be sure to include this reference within your SQL scripts as you start exploring the data and answering the case study questions.

#### Table 1: sales
The sales table captures all customer_id level purchases with an corresponding order_date and product_id information for when and what menu items were ordered.

![image](https://github.com/user-attachments/assets/80c144c3-5186-4c5c-baa5-4fba7b357dbe)

### Table 2: menu
The menu table maps the product_id to the actual product_name and price of each menu item.
![image](https://github.com/user-attachments/assets/ec38a2a5-d178-4d3d-93d8-9f91c778376d)

### Table 3: members
The final members table captures the join_date when a customer_id joined the beta version of the Danny’s Diner loyalty program.
![image](https://github.com/user-attachments/assets/ae92ac98-8660-4188-9395-e653d0c018ed)


 
