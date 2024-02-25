# Restaurant-Manager-Application
This application developed for management a restaurant in Oracle Apex.
####
The goal of my project was to create a restaurant management application. The restaurant management app is a universal tool created to improve the restaurant's operation. Whether you are an employee managing the day-to-day operations of a restaurant or a customer looking to place an order, this app offers intuitive user interfaces and advanced features to meet your needs.
####
Initially, the principle of operation was that you have two modules: the employee and customer module, but this task has not been fully implemented and the application works only on behalf of the employee. The module, designed for employees, allows you to effectively manage operations in the restaurant. Employees have the ability to add, update and remove products from the menu, customize orders by adding various add-ons, and effectively manage customer comments. Thus, the restaurant staff can easily and effectively adapt the offer to the changing preferences of customers and effectively respond to their comments and opinions. The module, designed for customers, was supposed to allow them to place orders seamlessly and adapt them to individual tastes by choosing different fillings (ketchup, sauce, etc.).  
####
Using the Oracle database, the application is ready to handle even the most demanding data management needs, while ensuring ease of maintenance and system expansion. The restaurant management app not only facilitates the work of the staff, but also provides a user-friendly experience for customers, allowing them to customize orders according to their individual preferences.
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
####
Home window:
![Home window](https://github.com/rudofficial/Restaurant-Application/blob/main/1.png)
####
Menu window:
![Menu window](https://github.com/rudofficial/Restaurant-Application/blob/main/2.png)
####
Window with additions:
![Additions window](https://github.com/rudofficial/Restaurant-Application/blob/main/3.png)
####
Window with your orders:
![Orders window](https://github.com/rudofficial/Restaurant-Application/blob/main/4.png)
####
Window for making order:
![Order window](https://github.com/rudofficial/Restaurant-Application/blob/main/5.png)
####
Reviews window:
![Reviews window](https://github.com/rudofficial/Restaurant-Application/blob/main/6.png)
####
Statistics window:
![Statistics window](https://github.com/rudofficial/Restaurant-Application/blob/main/7.png)





