
# Online Shopping App

## Overview

The Online Shopping App is a web-based application that allows users to browse, search, and purchase products online. This project demonstrates the integration of Java Server Pages (JSP), Java Servlets, JDBC, and MySQL for building a robust and scalable e-commerce platform.

![image](https://github.com/user-attachments/assets/9eeafef5-2f7f-4461-bc4f-823f55908cf5)


## Features

- User registration and authentication
- Product browsing and searching
- Shopping cart functionality
- Secure checkout process
- Order history tracking
- Admin dashboard for managing products and orders

## Technologies Used

- **Front-end:** HTML, CSS, JavaScript
- **Back-end:** JSP, Servlets
- **Database:** MySQL
- **Connectivity:** JDBC

## Getting Started

### Prerequisites

To run this project locally, you need to have the following software installed:

- [JDK (Java Development Kit)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) - Java 8 or higher
- [Apache Tomcat](https://tomcat.apache.org/download-90.cgi) - Version 9.0 or higher
- [MySQL](https://www.mysql.com/downloads/) - Version 5.7 or higher
- [Eclipse IDE](https://www.eclipse.org/downloads/) or any other Java IDE

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/hemanthsaich/OnlineShopingApp.git
   ```

2. **Set up the database:**

   - Create a database named `shopping_db` in MySQL.
   - Import the `shopping_db.sql` file located in the `database` folder of this project into the `shoppingsystem` database.
   - Update the database configuration in the `db.properties` file located in the `src` folder.

3. **Configure the project in the IDE:**

   - Open the project in Eclipse or any other IDE.
   - Add the Apache Tomcat server to the IDE and configure the project to run on it.
   - Right-click on the project, go to `Properties` > `Java Build Path` > `Libraries`, and add the MySQL JDBC driver to the project.

4. **Run the project:**

   - Start the Apache Tomcat server.
   - Deploy the project on the server.
   - Open a web browser and navigate to `http://localhost:8080/OnlineShopingApp`.

## Usage

1. **User Registration:**
   - New users can register by clicking on the "Sign Up" link and filling out the registration form.
     ![image](https://github.com/user-attachments/assets/61d0d362-0c13-4d7b-82ff-82d1c2351bd9)

2. **Product Browsing:**
   - Users can browse available products from the homepage.
   - Products are categorized.
   ![image](https://github.com/user-attachments/assets/439f12d6-4d92-41e9-962a-9c844f63b10c)

3. **Shopping Cart:**
   - Users can add products to their shopping cart.
   - The cart displays all selected items with the total price.
  ![image](https://github.com/user-attachments/assets/11745b56-5750-4672-aaee-332fcb44af3b)

4. **Checkout:**
   - Users can proceed to checkout from their shopping cart.
   - A secure payment gateway is simulated for completing purchases.
  ![image](https://github.com/user-attachments/assets/4a63be6f-be8b-496f-8243-78adb03c8b72)

5. **Order History:**
   - Users can view their past orders and track order status.
  ![image](https://github.com/user-attachments/assets/349595be-7933-4c41-816e-00ddc9af36ce)

6. **Admin Dashboard:**
   - Admin users can manage products, view orders, and update order statuses.
![image](https://github.com/user-attachments/assets/1cb9101e-9822-4d9a-af87-777b8d5f1d90)
