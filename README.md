# e-Commerce-Back-End
 ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

 ### Description
This project serves as the backend for an e-commerce site, built to leverage the latest technologies to ensure competitive advantage in the market. By utilizing Express.js for server-side operations and Sequelize as an ORM to interact with a PostgreSQL database, this backend provides robust API functionality for managing categories, products, and tags within an e-commerce platform.

 ### Table of Contents
 - [Description](description)
 - [Installation](installation)
 - [Usage](usage)
 - [Technologies](technologies)
 - [License](license)

 ### Installation
 To install necessary dependencies, run the following command:
 1. Clone the repository:
 ```
 git clone https://github.com/yueyue426/e-commerce-back-end.git
 cd e-commerce-backend
 ```
 2. Install the dependencies:
 ```
 npm install
 ```
 3. Create a .env file in the root directory and add your PostgreSQL database credentials:
 ```
 DB_NAME=your_database_name
 DB_USER=your_database_user
 DB_PASSWORD=your_database_password
 ```
 4. Create the database and seed it with the test data:
 ```
 npm run schema
 npm run seed
 ```
 5. Start the server:
 ```
 npm start
 ```

 ### Usage
To test the API routes, use Insomnia or any other API client.
- GET routes for categories, products, and tags:
- GET /api/categories
- GET /api/products
- GET /api/tags

POST, PUT, DELETE routes for creating, updating, and deleting data:
- POST /api/categories
- PUT /api/categories/:id
- DELETE /api/categories/:id
- POST /api/products
- PUT /api/products/:id
- DELETE /api/products/:id
- POST /api/tags
- PUT /api/tags/:id
- DELETE /api/tags/:id

### Technologies
- Express.js: For building the server and API routes.
- Sequelize: For ORM (Object Relational Mapping) to interact with PostgreSQL.
- PostgreSQL: As the database management system.

### License
This project is licensed under the [MIT](https://opensource.org/licenses/MIT)  License.

### Links
[GitHub Repository](https://github.com/yueyue426/e-commerce-back-end.git)