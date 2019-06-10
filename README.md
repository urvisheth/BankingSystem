# BankingSystem
Banking System is a web application that will allow user to do all banking operations online

There would be two main roles, Banker and Customer

This application will allow Customer to perform basic actions like creating an account, update information, internal fund transfer, money transfer to another merchant and can register complaint to administrator

Banker can add,update or delete a Customer, can approve credit/debit money for customer, can approve money transfer to another merchant.

Administrator or Maintenance is a secondary role for the system, that do not make a difference to the main system, but it take care of the functionality problem registered by other two users

Technology Used:
HTML
CSS
Bootstrap
JavaScript
Ajax
Java
JSP
Servlets
Java Beans
MySQL
MongoDB


______________________________________________________________________________

BANKING SYSTEM (Chicago Bank) User Document:
______________________________________________________________________________

Instructions on show how to deploy and run the bank project:

	1. Start tomcat server
	2. Copy "BankingSystem1" folder to the tomcat webapp folder.
	3. Start the MySQL database with database name as bns. The username is root and password is root to connect to the MySQL DB.
	4. Start the MongoDB server with mongo.exe and mongod.exe with database name as complaint and collection name as complaintStored.
	5. In order to start the application open the browser and type http://localhost/BankingSystem1/ or http://localhost/BankingSystem1/Home.

----------------------------------------------------------------------------------------------------------------------------------------------------
Note:

To compile Java files, use this command:
javac *.java

If in case it doesn't work then, use the following cmd:

javac -cp "C:/tommy/tomcat-7.0.34-preconfigured/apache-tomcat-7.0.34/lib/mongo-java-driver-3.2.2.jar;C:\tommy\tomcat-7.0.34-preconfigured\apache-tomcat-7.0.34\lib\servlet-api.jar;C:\tommy\tomcat-7.0.34-preconfigured\apache-tomcat-7.0.34\lib\mysql-connector-java-5.1.23-bin.jar;C:\tommy\tomcat-7.0.34-preconfigured\apache-tomcat-7.0.34\lib\gson-2.6.2.jar;" *.java

------------------------------------------------------------------------------------------------------------------------------------------------------
Role Information
______________________________________________________________________________
There are three ROLES:
a. Customer
b. Banker
c. Administrator
______________________________________________________________________________

a.) Customer:
______________________________________________________________________________
For testing purposes you can give as:
User Name: Adi
Password:  yaji

Customer can,

1.> Funds Transfer Within Bank 
2.> Funds Transfer to Other Bank 
3.> Register a Complaint 
4.> View Complaints' status 
5.> View Transactions 
6.> Change User Credentials 
5.> Log out

_________________________________________________________________________________

b.) Banker:
__________________________________________________________________________________
User Name: banker
Password:  urvi


Banker can,

1.> Create New customer 
2.> Update a Customer 
3.> Delete a Customer 
4.> Register a Complaint 
5.> View Complaints' status 
6.> Add Customer Transactions 
7.> View all customer Transactions 
8.> Money Transfer Request 
9.> Change User Credentials 
10> Log out

___________________________________________________________________________________

c.) Administrator:
___________________________________________________________________________________
User Name: admin
Password:  admin

Admin can,

1.> View all the complaints registered.
2.> Able to change the status of the complaints.

------------------------------------------------------------------------------------------------------------------------------------------------------

