Databases are a vital tool for managing and retrieving information for online market systems.
Online market database consists these four basic tables:
1) User table - stores all necessary data like personal information, address and etc about users of our online market.
2) Products table - stores product information like product name, description and others.
3) Orders table - holds data on when order, shipping, payment, etc.
4) Order details table - information about each product that are ordered.

In total there are 20 tables: User_info, User_adress, Address_details, Country, Shopping_basket, Shopping_basket_item, Payment_type, Payment_type_method, Product_item, Product, Supplier, Product_category, Variation, Variation_option, Product_variation, Shop_order, Order status, User_comment, Shopping_method, Order_details. 

In this system customers who are willing to purchase a product my order them online to their address. Users of online market should register to it with email and add detailed data about their home address. Products that they wish to buy should be added to shopping basket from where they can order them lately. In the product item table there is stored information about product in stock. Product table stores all the detailed data about products. Each product belong to certain category and each product is in a relationship with its supplier. Shop order table contains information about an order that the user made. And each shop order is in a relationship with order details. Shipping method, User comment, Order status are all in a relationship with Shop order.
