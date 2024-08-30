
# Online Shopping App

## Overview

The Online Shopping App is a web-based application that allows users to browse, search, and purchase products online. This project demonstrates the integration of Java Server Pages (JSP), Java Servlets, JDBC, and MySQL for building a robust and scalable e-commerce platform.

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

2. **Product Browsing:**
   - Users can browse available products from the homepage.
   - Products are categorized for easier navigation.

3. **Shopping Cart:**
   - Users can add products to their shopping cart.
   - The cart displays all selected items with the total price.

4. **Checkout:**
   - Users can proceed to checkout from their shopping cart.
   - A secure payment gateway is simulated for completing purchases.

5. **Order History:**
   - Users can view their past orders and track order status.

6. **Admin Dashboard:**
   - Admin users can manage products, view orders, and update order statuses.
