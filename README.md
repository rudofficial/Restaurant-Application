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
![New](https://user-images.githubusercontent.com/72620745/221269261-a0b40e3a-f306-439d-a71a-1b377d793be5.png)
The schema contains various keys necessary to identify our data. It also includes a supertype of the user, which in turn is the basis for the employee and the client entity.As we can see, "order" is the main entity. It includes both additions to the order (ketchup, seasonings) and data from the menu that the customer ordered. After that, the order data is transmitted for delivery. Delivery is optional and by default all orders are added without it. If you want to see DB model or scripts, you must open "DataBaseInformation" folder.
####
