# trading-post

Challenge 13 Object Relational Mapping (ORM): E-commerce Back End 🐂🤠💼

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Our challenge is to build the back end for an e-commerce site- take a working Express.js API and configuring it to use Sequelize to interact with a MySQL database. Based on the User Story:

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

For this challenge, we were provided a functional Express.js API. Our job was to define the columns in the models folder for Category.js, Product.js, ProductTag.js, and Tag.js. Then, we wrote the get, post, put, and delete routes for category-routes.js and tag-routes.js. Lastly, we wrote get and delete routes for product-routes.js.

When the user starts the server, and the Sequelize models are synced to the MySQL database, the user can perform API GET, POST, PUT, and DELETE routes in Insomnia for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON. Users are able to successfully create, update, and delete data in the Ecomerce Database (ecommerce_db).

[Click to view Walkthrough Video](https://drive.google.com/file/d/1Pjj1g-7rd-aFZJs74tHenJw5iOjHELoc/view)

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

## Documentation

- [Sequelize Models Definitions Documentation](https://sequelize.org/v5/manual/models-definition.html)
- [Attribute Validators (Sequelize) Documentation](https://sequelize.org/v5/manual/models-definition.html#per-attribute-validators-and--code-allownull--code-)
- [belongsToMany relationships (Sequelize) Documentation](https://sequelize.org/master/manual/assocs.html#-code-foo-belongstomany-bar----through--baz-----code-)

© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
