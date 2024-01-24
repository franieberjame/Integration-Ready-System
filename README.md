# Integration-Ready-System
IT SIA Final Task 

This cafe billing system is a flexible system that allows the client to add various category types and products seamlessly. With an intuitive user interface, this system simplifies the process of managing and generating bills for a cafe or any small businesses. Client admin can easily customize the system by adding new categories such as beverages, snacks, or desserts, and populate them with specific products.

*Instruction*
1. download and extract the file cafe_system.rar 
2. copy the extracted file and paste it to your local Disk C:/xampp/htdocts
3. go to xampp and start Apache and MySQL
4. in your chrome type "localhost/phpmyadmin" and enter
5. after that, click new to create your database.
6. name the database "cafe" and then click create.
7. click import -> choose and then browse the database located in cafe_system/database/cafe.sql and then click go.
8. in your chrome type localhost/cafe_system

credentials
admin acc.
user: admin
pass: admin123

user acc.
user: user
pass: user123


# Web Service Integration
This website provides a comprehensive web service featuring a curated list of its products. This website's web service isn't just about showcasing products; it's a versatile solution that enhances overall business efficiency. The integration potential with other systems such as inventory system opens up new possibilities for businesses looking to streamline their operations and maintain accurate records.  

The system offers this webservices: Product ID, Category ID, Product Name, Description, Price, and Status (1 if the product is still available).

Web Service URI: "http://localhost/cafe_system/webservice/server.php"

Method to call: getProducts()

Instruction for Integration:
1. Define the SOAP service endpoint
2. Create a SOAP client
3. Navigate to your $result by calling the getProducts() method.

Sample Integration
![image](https://github.com/franieberjame/Integration-Ready-System/assets/147252157/995d6306-727c-46c1-b541-7d08056c6fe5)

# API Integration
This website is already integrated with PayPal. Through PayPal payment gateway, this website is integrated and can accept payment online. However, this is still needed an update and further configuration; Because It has not undergone testing with live account transactions, and I encountered an issue retrieving transaction information with PayPal. Thus, the PayPal payment integration can be done using SandBox testing account.

For transaction testing with Paypal, use this credentials:

username: sb-xwlrt29377643@personal.example.com

password: berjame123


Video Presentation link:
https://youtu.be/luVtMlG71gQ
