### Developing an E-Commerce Web Application:-

To design and develop an e-commerce web application from scratch using PHP and MySQL.

### Author: ASWINI M S

This Repository contains the source code for this project: [here](https://github.com/ashwinims1103/ashwini_ecommerce)

### Running the Website Locally:-

### Clone the Repository

using the following command: [here](https://github.com/ashwinims1103/ashwini_ecommerce.git) (you must pre-installed the GIT in your system)

### Install XAMPP
Download and install XAMPP from the internet. 
click Start to initiate the Apache Tomcat server and MySQL in the XAMPP application. (Uninstall, if you have the MySQL application separately)

### Move Project Folder
Extract the project zip folder cloned from Git and move the project folder to the XAMPP directory:

`C:\xampp\htdocs<PROJECT_FOLDER>`

### Set Up Database
-- Open `localhost/phpmyadmin` in your browser.
-- Create a new database : ecommerceapp.
-- Import the SQL file `ecommerceapp.sql` located in the project folder into the `ecommerceapp` database.

### To Run the Website
Open your browser and navigate to `localhost/<PROJECT_FOLDER>` to view and interact with the website.



### Deployment on AWS EC2 Instance

### Step 1: 
## Create an EC2 Instance
1. Open your AWS Console and search for EC2.
2. click launch instance (Linux, Ubuntu, or Windows).
3. Download the key pair file for authentication.

### Step 2: 
## Configure Security Groups
1. Allow all traffic in inbound rules for the EC2 instance.
2. Manage security groups and firewall settings as needed.

### Step 3: 
## Connect to EC2 Instance
1. Download the RDP client .exe file for instances.
2. Use the key pair file for authentication and connect to the instance.

### Step 4:
## Set Up XAMPP and MySQL
1. Download and install XAMPP and MySQL on the EC2 instance ( Make installation based on the OS used in the server ).
2. Follow the steps to configure and start the servers on localhost (EC2 instance).

### Step 5: 
## Access the Website
Copy the Public IPv4 address of the EC2 instance and paste it into your browser to view the website.

### step 6:
## Host
My website is hosted on an AWS EC2 Instance. 

You can access it [here](http://16.16.143.133/ashwini_ecom_website/).



