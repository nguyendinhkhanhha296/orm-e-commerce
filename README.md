<h1 align="center">E-Commerce</h1>
   
  
<p align="center">
    <img src="https://img.shields.io/github/repo-size/nguyendinhkhanhha296/orm-e-commerce" />
    <img src="https://img.shields.io/github/languages/top/nguyendinhkhanhha296/orm-e-commerce"  />
    <img src="https://img.shields.io/github/issues/nguyendinhkhanhha296/orm-e-commerce" />
    <img src="https://img.shields.io/github/last-commit/nguyendinhkhanhha296/orm-e-commerce" >
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/jQuery-blue"  />
    <img src="https://img.shields.io/badge/mySQL-pink"  />
    <img src="https://img.shields.io/badge/Insomnia-purple"  />
    <img src="https://img.shields.io/badge/-Node.js-green" />
    <img src="https://img.shields.io/badge/-inquirer-red" >
    <img src="https://img.shields.io/badge/-json-orange" />
</p>


   
## Description
  
🔍 Configuring a working Express.js API to use Sequelize to interact with a MySQL database  
  
💻 Below is the gif showing the functionality of the application:
  
![Gif](./assets/ecommerce.gif)
  
🎥 The full movie file showing functionality of the application can be found [here](./assets/Screen%20Recording%202022-09-10%20at%202.46.42%20AM.mov)  
  
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies 
```
  
## Acceptance Criteria
  
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
  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)

## Installation
💾   
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install express`

`npm install dotenv`
  
## Usage
💻   
  
Run the following command at th root of your project and answer the prompted questions:

`npm run seed`
  
`npm start`