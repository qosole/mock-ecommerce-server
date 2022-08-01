# Mock e-Commerce Server

## Description 

A server that holds information about various products in a mock store. The server contains data about the products themselves, the categories of products, and the tags that each product has. The server also supports API calls, allowing users to view, create, update, and delete categories, products, and tags.

This project was my first look into using the npm package Sequelize to connect to a MySQL database.

[Click here](https://drive.google.com/file/d/177xkBbVLREtLz5qyg_ZMh63X1d0gucFU/view) for a demonstration video!


## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)


## Installation

Use cmd to clone it: ```git clone ```\
or use the green code dropdown to download a zip


## Usage

1. Use the command line to navigate to the app's directory. If you downloaded a zip, make sure to extract all.
2. Type ```npm i``` to install the necessary dependencies.
3. Type ```mysql -u root -p``` to go into the SQL shell and enter your password.
4. Run schema.sql by copy-pasting.
5. Type ```exit```.
6. Type ```npm run seed``` to initialize the database.
7. Type ```touch .env``` and open it in a text editor. Insert these values into the file:  
DB_NAME='ecommerce_db'  
DB_USER='root'  
DB_PASSWORD='[YOUR PASSWORD]'

7. Type ```npm start``` to start the server.
8. To test endpoints, use Insomnia or similar application (refer to demonstration video).


## Credits

Jerome Chenette\
Manuel Nunes\
Farley


## License

[LICENSE](/LICENSE)


---


## Badges

![Javascript](https://img.shields.io/badge/JS-100%25-yellow)


---