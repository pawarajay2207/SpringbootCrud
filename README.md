# SpringbootCrud
CRUD-Operation
CrudNimap Application
Overview
Welcome to CrudNimap! This is a powerful CRUD (Create, Read, Update, Delete) application built with Spring Boot, JPA, and Hibernate. It allows users to manage categories and products seamlessly, with a clear focus on user experience and efficiency.

Features
User-Friendly Interface: Easy navigation with a clean design.
CRUD Operations: Create, read, update, and delete categories and products.
Data Persistence: Secure storage of data using a relational database (MySQL).
One-to-Many Relationship: Each category can have multiple products.
Server-Side Pagination: Efficient data retrieval with pagination support.
Detailed Responses: Fetch single product details along with its category information.
Technologies Used
Java 17: The latest version for optimal performance.
Spring Boot: Simplifies the development of Java applications.
JPA & Hibernate: For managing relational data.
MySQL: A reliable relational database management system.
API Endpoints
Category CRUD Operations
Get All Categories (with Pagination)

GET http://localhost:8080/api/categories?page=0

Screenshot 2024-10-24 074822

Create New Category

POST http://localhost:8080/api/categories Screenshot 2024-10-24 074958

Get Category by ID

GET http://localhost:8080/api/categories/{id} Screenshot 2024-10-24 075052

Update Category by ID

PUT http://localhost:8080/api/categories/{id} Screenshot 2024-10-24 081033

Delete Category by ID

DELETE http://localhost:8080/api/categories/{id} Screenshot 2024-10-24 081148

Product CRUD Operations
Get All Products (with Pagination)

GET http://localhost:8080/api/products?page=2 Screenshot 2024-10-24 081236

Create New Product

POST http://localhost:8080/api/products Screenshot 2024-10-24 081645

Get Product by ID

GET http://localhost:8080/api/products/{id}
Screenshot 2024-10-24 081742

Update Product by ID

PUT http://localhost:8080/api/products/{id} Screenshot 2024-10-24 082007

Delete Product by ID

DELETE http://localhost:8080/api/products/{id} Screenshot 2024-10-24 082118

6.**RDBMS MySql Screenshot 2024-10-24 082640

Getting Started
Follow these steps to set up the application on your local machine:

Prerequisites
JDK 17 or higher
Maven
MySQL Server
Installation
Clone the repository:

git clone https://github.com/its-vaishu2405/QuickCrud.git

Navigate to the project directory:

cd QuickCrud

Configure the MySQL database:

Create a database named nimapinfotech.
Update the application.properties file with your MySQL credentials.
Build the project:

mvn clean install

Run the application:

mvn spring-boot:run

Accessing the Application
Open your web browser and navigate to http://localhost:8080 to start using QuickCrud!

Contributing
We welcome contributions! If you have suggestions or want to improve the project, please fork the repository and create a pull request.

Steps to Contribute:
Fork the repository
Create a new branch
Make your changes
Commit your changes
Push to the branch
Open a pull request
