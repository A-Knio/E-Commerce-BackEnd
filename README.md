# E-Commerce-BackEnd

This guide will assist you in setting up and utilizing a functional Express.js API with Sequelize ORM for MySQL database. Please follow the steps below to ensure a smooth setup process.

## Prerequisites

Before proceeding, make sure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MySQL Server

## Installation

1. Clone this repository to your local machine.

2. Navigate to the project directory using your terminal or command prompt.

3. Install dependencies by running the following command:

npm install 


## Configuration

1. Create a `.env` file in the root directory of the project.

2. Inside the `.env` file, add the following variables:

DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password


Replace `your_database_name`, `your_mysql_username`, and `your_mysql_password` with your actual MySQL database name, username, and password respectively.

## Database Setup

1. Run the following command to create and seed the database:

npm run setup


This command will execute schema and seed commands, creating a development database and populating it with test data.

## Running the Application

1. To start the server and sync Sequelize models with the MySQL database, run:

npm start


## Testing the API

1. Open your preferred API testing tool (e.g., Insomnia, Postman).

2. Access the API GET routes for categories, products, or tags.

- Categories: `GET /api/categories`
- Products: `GET /api/products`
- Tags: `GET /api/tags`

You should receive formatted JSON data for each route.

3. Test API POST, PUT, and DELETE routes in your API testing tool to create, update, and delete data in the database.

## Additional Information

- For more detailed information about API routes and endpoints, refer to the API documentation or explore the codebase.

- Feel free to customize the API according to your requirements and extend its functionality as needed.

