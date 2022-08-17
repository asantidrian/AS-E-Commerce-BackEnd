# AS-E-Commerce-BackEnd

## Summary

This is a back end e-commerce website that uses MySQL as data base, and RESTful API and CRUD operations.
Given a functional Express.js API, when the database name, MySQL username, and MySQL password are added to an environment variable file, we can connect to a database using Sequelize.


## Installation

Run/Start the datebase:
mysql -u root -p
source ./db/schema.sql   

Run the code below to seed the database:
npm run seed

## Usage

After running schema and seed commands we can start the application typing the command 'npm start'
Once the app in running on the specified server,we can create the  API GET routes in Insomnia for categories, products, or tags

To be able to  use the this back end applicationthe following packages have to be installed:
[MySQL2](https://www.npmjs.com/package/mysql2)   
[Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database.   
[dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

## video Demo

[VideoDemo Node and SQL](https://drive.google.com/file/d/1k_4G88D7d2-rcwkCOoK02ANkMvWIetjy/view)
[VideDemo Category Routes](https://drive.google.com/file/d/1zjqExEIWFihmb8EXzqZQuSQvGomgdrrc/view)
[VideoDemo Product Routes](https://drive.google.com/file/d/1NX88XChOEV7JeQp1q78vWI_b-aXYMoKQ/view)
[VideoDemo Tags Routes](https://drive.google.com/file/d/1ijtieOq9-3K2dONUwaDKsqKQfqT5K9uP/view)

## Links

[Github](https://github.com/asantidrian/AS-E-Commerce-BackEnd)




