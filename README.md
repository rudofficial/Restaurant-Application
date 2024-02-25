# Restaurant-Manager-Application
This application developed for management a restaurant in Oracle Apex.
####
You can add products, additions for products, delete comments etc as employees.
If you customer you can order products, additions and add products for delivery and write a comment, update comment etc.
####
Information about orders, deliveries and ... is stored in the database.
The database for this application has functions and stored procedures. DB has different queries(simple(standart select operation) and difficult(joins, groups etc.));
####
This is Visual Model of DataBase:
![New](https://github.com/rudofficial/Restaurant-Application/blob/main/encji.png)
The schema contains various keys necessary to identify our data. It also includes a supertype of the user, which in turn is the basis for the employee and the client entity.As we can see, "order" is the main entity. It includes both additions to the order (ketchup, seasonings) and data from the menu that the customer ordered. After that, the order data is transmitted for delivery. Delivery is optional and by default all orders are added without it. If you want to see DB model or scripts, you must open "DataBaseInformation" folder.
####
The application has protection from "fool". For example if you want to write an empty comment, the system will not allow you to do it. You will not be able to order delivery for a product that is already being delivered etc.
####
Application has ~ 7 windows. Examples:
####Home window:
![Home window](https://github.com/rudofficial/Restaurant-Application/blob/main/1.png)
