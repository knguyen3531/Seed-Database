E-Commerce Back End
Description
This project involves developing the back end for an e-commerce site. Utilizing Express.js for server operations and Sequelize as the ORM to interact with a MySQL database, this application demonstrates fundamental back-end configurations used in many e-commerce platforms. The application allows for handling data related to products, categories, and tags.

Features
Express.js API: Utilizes Express.js for handling API requests and routing.
MySQL Database: Incorporates MySQL for database management, using Sequelize as the ORM.
CRUD Operations: Supports Create, Read, Update, and Delete operations for products, categories, and tags.
Data Validation: Ensures data integrity through Sequelize validations.
Environment Variables: Uses .env file to store sensitive configuration details like database credentials.
Installation
To run this application locally, follow these steps:


Certainly! Below is a template for a README file for your e-commerce back-end project:

E-Commerce Back End
Description
This project involves developing the back end for an e-commerce site. Utilizing Express.js for server operations and Sequelize as the ORM to interact with a MySQL database, this application demonstrates fundamental back-end configurations used in many e-commerce platforms. The application allows for handling data related to products, categories, and tags.

Features
Express.js API: Utilizes Express.js for handling API requests and routing.
MySQL Database: Incorporates MySQL for database management, using Sequelize as the ORM.
CRUD Operations: Supports Create, Read, Update, and Delete operations for products, categories, and tags.
Data Validation: Ensures data integrity through Sequelize validations.
Environment Variables: Uses .env file to store sensitive configuration details like database credentials.
Installation
To run this application locally, follow these steps:

Clone the Repository:

URL:https://knguyen3531.github.io/Seed-Database/
Install Dependencies:
Navigate to the root directory of the project and run:

npm install
Set Up the Database:

Create a .env file in the root directory with your MySQL username, password, and database name.
Run MySQL commands to create the database using the schema provided in schema.sql.
Seed the Database:

npm run seed
Start the Application:

npm start
Usage
Use an API client like Insomnia or Postman to test the API endpoints. The API allows you to:

View, add, update, and delete categories.
View, add, update, and delete products.
View, add, update, and delete tags.


Technologies Used
Node.js
Express.js
MySQL
Sequelize ORM
dotenv for environment variables
Contribution
Made with ❤️ by [KHOI NGUYEN]
