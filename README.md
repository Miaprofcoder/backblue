# E-Commerce-Back-End
Module# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description
This is the 13th assignment or challenge for our bootcamp class. Our assignment this week is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

## Installation

MySQL2, Sequelize and dotenv packages are needed to connect Express.js API to MySQL and store sensitive data.

```
npm install express sequelize mysql2 dotenv
```

* Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands.

* After creating the models and routes, run `npm run seed` to seed data to your database


## Usage
Given a functional Express.js API. When a user add database name, MySQL username, and MySQL password to an environment variable file they're able to connect to a database using Sequelize. When they run `npm run seed` in the comman line, their table is seeded with data. When they run the file using `npm server.js` server is started and sequelize models are synced to the MyQQL database and they're able to open API routes in Insomnia for categories, products and tags.


URL of Github repository : https://github.com/mvfranzke/E-Commerce-Back-End

Video Link (user flow): https://drive.google.com/file/d/1pqCWYUp9qFVoo614znAGnO_v2jPlMeXE/view

## Credits

## License
N/A
