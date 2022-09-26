** Table of Contents **
- Description
- Usage
- Video and Github
- Installation
- Features
- Learnings
- Challenges
- Future Iterations


** Description **
Took a working Express.js API and configured it to use Sequelize to interact with a MySQL database.

** Usage **
![screenshot](./Develop/images/Screen%20Shot%202022-09-26%20at%205.11.45%20PM.png)

** Video and Github **
- https://github.com/spencerjpross/e-commerce

** Installation **
- Install Dotenv, express, sequelize, and mysql

** Credits **
- Had help with some tutors from the bootcamp and TA's during office hours

** Features **

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

** Things I learned in this project **
- Learned how to create validations on Models
- learned how to connect different models through the reference and primary keys
- 

** Challenges **
- Understanding the index.js on the models.  Still trying to understand the hasmany, belongstomany and belongs to and how they connect.  


** Future Iterations **
- coming soon.