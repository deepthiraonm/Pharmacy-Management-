# Pharmacy-Management-
The project aims to assist a pharmacy in managing its inventory, details of customers, employees and suppliers as well as keeping track of its purchases and sales. It is a web-based application implemented using PHP with MySQL as the Database Management System. User Interface is designed using HTML5, CSS3 and JavaScript.

# Getting Started-
# Installation and Setup
1. Download and Install XAMPP
2. Open XAMPP Control Panel and start Apache and MySQL.
3. Clone the repository to your system or download and extract the zipped folder.
4. Place the folder PHARMACY in C:\xampp\htdocs.
5. In web browser, open localhost/phpmyadmin.
6. Create a new database called 'pharmacy' in phpmyadmin.
7. Import the file 'pharmacy.sql' into the database.

# Launch
1. After successfully importing, start the project by typing the following in the web browser: localhost/PHARMACY/mainpage.php
   
2. The Login Page for Admin opens up by default. Login as Admin by using:
##
      Username: admin
      Password: password   
3. For Pharmacist Login, refer to the 'emplogin' table in the database. Example:
##
      Username: varshini
      Password: pass7

# About the Project-
# Introduction
Pharmacia, a Pharmacy Management System aims to help in maintaining and managing the records for a pharmaceutical store by improving efficiency, accuracy and security.

Pharmacies need to maintain details of medicine stock, suppliers, employees, customers, any stock purchased by the pharmacy and any sales made by the pharmacy. The previous manual methods require the pharmacists to manually monitor all the records lists and transactions and to verify the presence of the each drug in the pharmacy. Searching for any required drug may be difficult.

Using the Pharmacy Management System, one can maintain stock and inventory, oversee transactions, manage suppliers and employees and maintains records of its customers. The system will help prevent waste of time and resources, allow easy access to medicines, as well as ensure more security and reliability for the data compared to the manual systems. The system assists the pharmacy in handling the daily requirements in a smoother, better and effective manner.

# Objectives
The main objectives/features of the system are:

* Ease of use
* Deals with automation of tasks
* Provides fast searching capabilities
* Time and resources utilization is maximized via digitalisation
* Generate alerts and reports as required on sales and medicines.

# Users of the System
The system is developed for use by either the Admin or Pharmacists.

# Admin Capabilities:
* Access and update the list of available medicines/drugs
* Access and modify drug suppliers’ data
* Access and update any details of new purchases of stock for the company
* Access and update all employees’ details
* Access and update all customers’ details
* Keep track of all sale transactions
* Generate and view reports based on the data

# Screenshots
Admin Login Page
![Image](https://github.com/user-attachments/assets/06b96d71-e8cf-43ea-8c0d-203f67411c7c) 

Admin DashBoard
![Image](https://github.com/user-attachments/assets/4de9bfce-7c0b-454d-b865-65542cb80028) 

Pharmacist Capabilities:
* View the inventory of medicines, their price, quantity and other details – no changes are allowed from a pharmacist point of view
* View minimal details regarding existing customers
* Add a new customer to their database
* Make a new sale and register the sale details onto the database

# Screenshots
Pharmacist Login Page
![Image](https://github.com/user-attachments/assets/5f8ae6cf-0fef-4e7a-8de8-3d00c5e8b819) 

Pharmacist DashBoard
![Image](https://github.com/user-attachments/assets/8844753f-83fb-45a2-b649-1c3565f638bd) 

# Database Architecture
# MEDS: 
Contains details regarding the list of all medicines, mainly their type, the quantity currently present in the store and their price.

# SUPPLIERS: 
Contains details regarding any of the drug suppliers who supply stock to the pharmacy.

# PURCHASE: 
Contains details regarding any stock purchased by the company. Purchasing a stock consists of placing an order for multiple medicines and multiple suppliers via a single purchase on an online platform on a date as specified by purchase date (based on date of delivery). It also contains the manufacturing and expiry dates for the purchased items.

# EMPLOYEES: 
Contains details regarding all employees, including Admin, Managers and Pharmacists.

# CUSTOMERS: 
Contains details of all customers for ease during sales transactions.

# SALES: 
Contains details regarding all sales made by the pharmacy. It keeps track of the sale invoice number, the customer ID of the customer, the employee ID of the employee who conducted the sales, the total amount of sale and the sale date and time.

# SALES_ITEMS: 
Contains details regarding the particular medicines sold during each sale. It keeps track of the sale invoice number, the medicine ID, the quantity of that medicine purchased and total cost for that particular sale.

# ADMIN: 
Contains the employee ID, the username and password for the Admin. Only a single record exists. Admin capabilities can be implemented only by this login.

# EMPLOGIN: 
Contains the employee ID, the employee username and password for all the pharmacists and managers, apart from Admin. Pharmacist capabilities can be implemented by using any of the login details in the table.

# ER Diagram
![Image](https://github.com/user-attachments/assets/76755e83-de4e-44ff-a1e6-291846e1cfc6) 

# Relational Database Model
![Image](https://github.com/user-attachments/assets/4d747c06-7246-40b2-b419-cbeba524f4a5) 
