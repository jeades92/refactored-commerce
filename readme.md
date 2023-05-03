



# Description

This project provides the back-end functionality for an e-commerce site using Node.js, Express.js, Sequelize, and MySQL2. It allows users to perform CRUD operations on the product, tag, and category data of the e-commerce site. This project follows the Model-View-Controller (MVC) architectural pattern, where the Model represents the data, the View represents the user interface, and the Controller handles the logic between the Model and the View.

# Installation

 To install this project, clone the repository to your local machine, navigate to the root directory of the project, and run the following command to install the necessary dependencies:

##### npm install

 <br>

Then, create a .env file in the root directory of the project and add the following code:

<br>

##### DB_NAME='ecommerce_db'
##### DB_USER='your_mysql_username'
##### DB_PW='your_mysql_password'

<br>

Replace your_mysql_username and your_mysql_password with your MySQL username and password, respectively.

To create the database and seed it with test data, run the following commands:

<br>

##### mysql -u root -p

<br>

Enter your MySQL root password, then run:

<br>

##### source db/schema.sql
##### exit

<br>

Then run the following command to seed the database:

<br>

npm run seed

<br>

# Usage

To start the server, run the following command:

##### npm start

<br>

Once the server is running, you can use an API development environment like Insomnia or Postman to test the API routes.

<br>

# [Walkthrough Video](https://drive.google.com/file/d/1HATXIIidfBBXXkJWc7LDOxZeA9-ODpvJ/view)

## Collaboration

Meg Meyers

