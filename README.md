# EatDaBurger

## Description
This project is a restaurant app that lets users input the names of burgers they'd like to eat. Whenever a user submits a burger name, the app will display the burger on the left side, waiting to be devoured. Each burger has a 'Devour it!' button. Upon being clicked, it will move to the devoured section on the right side. It also has a 'Dump it!' button to completely get rid of the burger. 

## Usage
To use the application locally, you would have to install the node modules ('npm init -y'). The NPM package dependencies are 'npm i mysql', 'npm i express' and 'npm i express-handlebars'. After installing these packages, you can put the schema and seeds in the MySQL Workbench to create the fundamental database. Once this is complete, open the Terminal/GitBash console and run the code 'node server.js'. This will start the app on localhost:8080 in your browser. All burgers are stored into the database, whether devoured or not. This burger logger uses MySQL for the storage, Node for hosting server, Express framework for back end API's, Handlebars for the front end display, ORM for mapping database tables to classes and instances of classes to rows in those tables, and Heroku is used to host the application. This follows the MVC pattern. 

## Links
Link to live application: https://cryptic-fjord-79089.herokuapp.com </br>
Link to GitHub Repository: https://github.com/GuilleMGN/EatDaBurger
Questions? My email: matthewguillen777@gmail.com </br>

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Demo
![eat-da-burger-demo](https://user-images.githubusercontent.com/73862470/109405093-cda2e180-793a-11eb-87b7-0b5c07f1e102.gif)
