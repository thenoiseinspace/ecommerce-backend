# ecommerce-backend

## Description

This is a back-end for an ecommerce site that uses Express.js, and Sequelize to interact with a MySQL database. Use it to track products (in this case, clothing items) and their associated data like category or price.

## Installation

This app uses Node.js, Inquirer, and MySQL.

## Usage

Use this app to track product information.

Github repo link: https://github.com/thenoiseinspace/ecommerce-backend

Video link: https://drive.google.com/file/d/1Yawaj4q1H8Dw96hxcYITjoQl376vum1i/view?usp=sharing

## Credits

Sources include course content and my tutor, Michael.

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

![In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

Your walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia Core.

## Getting Started

You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.

### Database Models

Your database should contain the following four models, including the requirements listed for each model:

-

### Walkthrough Video: 37%

- A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your readme file.

- The walkthrough video must show all of the technical acceptance criteria being met.

- The walkthrough video must demonstrate how to create the schema from the MySQL shell.

- The walkthrough video must demonstrate how to seed the database from the command line.

- The walkthrough video must demonstrate how to start the application’s server.

- The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia Core.

- The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia Core.

- The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia Core.
