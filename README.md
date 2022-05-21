# trading-post

Object Relational Mapping (ORM): E-commerce Back End 🐂🤠💼

Trading post includes the back end for an e-commerce site- by using a working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

For this project, a functional Express.js API was used to build Sequelize models of the Categories, Products, Product Tags, and Tags. Additionally, Trading Post adds CRUD routes for Category and Tags, and a delete route for Products.

Built with- Sequelize, Express.js, MySQL2, and Dotenv.

[Click to view Walkthrough Video](https://drive.google.com/file/d/1SRutGehUJppRpqErkV0tVWyVBW2eAMnU/view)

## Usage/Example

The video above shows a walkthrough of the application. Follow the installation instructions below to test!

## Installation

This project requires node.js. and [MySQL](https://dev.mysql.com/doc/). In the terminal-

Install npm packages

```bash
npm i
```

Create an .env file to hold mySQL login credentials:

```bash
DB_NAME='ecommerce_db'
DB_US='<insert username here>'
DB_PW='<insert password here>'
```

Run the db folder in the mySQL shell:

```bash
source db/schema.sql;
```

Seed the Database in the terminal:

```bash
npm run seed
```

Invoke the application by running-

```bash
npm start
```

# User Story and Criteria

This project was developed based on the User Story:

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

and Criteria:

```
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

```

## Documentation

- [Sequelize Models Definitions Documentation](https://sequelize.org/v5/manual/models-definition.html)
- [Attribute Validators (Sequelize) Documentation](https://sequelize.org/v5/manual/models-definition.html#per-attribute-validators-and--code-allownull--code-)
- [belongsToMany relationships (Sequelize) Documentation](https://sequelize.org/master/manual/assocs.html#-code-foo-belongstomany-bar----through--baz-----code-)

© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
