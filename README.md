# E-commerce-Back-End

## Table of contents

1. Descriptions
2. Installation
3. Technologies
4. Mock-Up

## Description

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Installation

- Uses the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

- Uses the [MySQL2 package](https://www.npmjs.com/package/mysql2) to connect to a MySQL database.

- Uses the [console.table package](https://www.npmjs.com/package/console.table) to print MySQL rows to the console.

## Technologies used

- Html
- JavaScript
- Express.js
- MySQL
- Node.js
