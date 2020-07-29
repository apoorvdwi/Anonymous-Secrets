# Anonymous Secrets

## Dependencies

1.  Node
2.  NPM
3.  MongoDB (prefferably version 4.2.8)

## Setup Procedure

1.  Clone the repository using **git clone <https://github.com/apoorvdwi/Anonymous-Secrets.git>**
2.  Make sure Node and NPM are updated by running the command **node -v** and **npm -v**
3.  Make sure the mongod process is running in background .
4.  Since the app uses google OAuth, so a .env file needs to be created in the root repository.
5.  the .env file should contain CLINET_ID and CLIENT_SECRET for google OAuth .
6.  Cd into the project directory and run the command **node app.js**
7.  Open the url **localhost:3000** in the browser

## Features

1.  This is a secret sharing app with the idea of sharing secrets anonymously and read secrets other people's secrets .
2.  MongoDB has been used for the database .
3.  Passport.js is used for the authentication and Google Oauth 2.0 support has been provided .
