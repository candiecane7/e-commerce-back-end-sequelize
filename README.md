# e-commerce-back-end-sequelize

## Purpose
To create models, associations and the routes needed for CRUD operations on the Categories, Tags, and Products of a company's database.

## Installation
Git clone this repositories code into your chosen folder. Open terminal in root folder and "npm install" to install all needed dependencies. Create a .env folder and add your database name, your mysql username and password. Make sure the database name is also changed in the db/schema file. 

## Usage
To start, go into your MySQL shell and write: "source db/schema.sql" to create the database. You can now quit MySql. 
In the server.js file you will need to change this line: sequelize.sync({ force: false }) to true, and then write: "npm start" in the command line.
Once that is finished, Ctrl + C to quit. Now you can seed the data by writing "npm run seed". Before restarting the application, make sure to switch back to false in the server.js file.

There is no front end to this application, so to test routes, open up in whichever testing app works for you, I use insomnia to test routes. 

## Built With
- Express
- MySql + Sequelize

## Video Walkthrough
[Click here](https://drive.google.com/file/d/1z1PkUMSuCKm2E_nbOyVkzKJDSMVHoz_Z/view) to watch a walkthrough demonstration of the application.

## Questions
Any questions about this application or questions in general please <a href="mailto:hall.candice@outlook.com">email me</a>
