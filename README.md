# trading-post

Challenge 13 Object Relational Mapping (ORM): E-commerce Back End 🐂🤠💼

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

Our challenge is to build the back end for an e-commerce site- take a working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
