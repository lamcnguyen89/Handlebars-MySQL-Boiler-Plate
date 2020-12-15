# Handlebars-MySQL-Boiler-Plate
Boilerplate code using handlebars and mysql with sequelize. There is a login component using Passport

## Web Tools:

HTML, CSS, Javascript (ES6), Bootswatch, Node.js, Express, Passport, MySQL, Sequelize, and express-handlebars.

## Table of Contents 

* [Installation](#installation)

* [Usage](#usage)



## Installation

To install necessary dependencies, run the following command in BOTH the client folder which contains React AND the root folder where server.js is located:

```
npm install
```

## Usage
``` 
    To start using this project: 

    1.  Install node modules (npm install). 
    2.  Create new database in MySQL Server. 
    3.  Create a .env file at the root location of the project and enter database credentials (see below):
    
            DB_USER = Your Database Username
            DB_PASSWORD = Your Database Password
            DB_DATABASE = Your Database Name
            DB_HOST = localhost  - ***If your are running localhost***
    (Also there is a .env.example file for you to emulate)

    4.  At least with me using the database manager DBeaver, I have to manually create the MySQL database in DBeaver first before the application can sync with MySQL. So at least name your database in DBeaver. You don't have to add any tables or fields... Just make an empty database with the same name as you specify in your .env file.
``` 