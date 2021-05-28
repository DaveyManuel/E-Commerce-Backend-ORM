# E-Commerce-Backend-ORM

## Deployed Link

https://youtu.be/cSTtLSSGWGY

https://github.com/DaveyManuel/E-Commerce-Backend-ORM

## Description

In this project, I was able to create a server based e-commerce backend that utilizes mySQL, Sequelize, express router, and dotenv. When a user initializes the start script the seeds will populate in their mySQL workbench, and when they type api/tags or whichever model they want to view, the json data will show on the page. 

## Table of Contents

*[Usage](#Usage)
*[UserStory](#UserStory)
*[Motivation](#Motivation)

## Usage
 
To use, simply edit the .env file to your mySQL information and run the start script to populate the seeds. If you want to view the information as a parsed JSON object, type in the correct api route in your local host 3001 or use Insomnia Core. 

## UserStory

As a user, I want a backend that will seed product data based on its relationship to category, tags, and product tags so that the information will show in mySQL workbench when I run the start script.

As a user, when I add my database name, MySQL username, and MySQL password to an environment variable file, then I am able to connect to a database using Sequelize.

As a user, when I enter schema and seed commands, then a development database is created and is seeded with test data.

As a user, when I enter the command to invoke the application, then my server is started and the Sequelize models are synced to the MySQL database.

As a user, when I open API GET routes in Insomnia Core for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.

As a user, when I test API POST, PUT, and DELETE routes in Insomnia Core, then I am able to successfully create, update, and delete data in my database.


## Motivation

The motivation for my project was to create a backend server that a front-end client could use in order to seed their data and view via their localhost and mySQL workbench. 


