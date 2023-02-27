# To-Do-List
A To-Do-List using Full-Stack Development

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Installation

To install the dependencies, run the following command in the root directory:

npm install

Then navigate to the view directory and run the same command:

cd view
npm install

## Usage

To start the server, run the following command in the root directory:

npm start

This will load the server on localhost:8000. To start the client, navigate to the view directory and run the following command:

cd view
npm start

This will load the client on localhost:3000.

Please note that this application uses a database to hold data. You will need to create a .env file in the root directory and add the following environment variables to link to your database:

For example if you are using MongoDB 

MONGO_URI=your-mongodb-uri

However, I am using Postbird for this application:

DB_USER='enter_username'
DB_PASSWORD='enter_password'
DB_HOST=localhost
DB_POST=5432
DB_DATABASE='enter_database_name'
PORT=8000

### Licence

This project is licenced under the MIT Licence. See the LICENCE file for more information.

### Acknowledgments

This project was inspired by [Codecademy](https://www.codecademy.com/learn).
