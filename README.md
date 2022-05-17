# Restful-Node-Api
Representational State Transfer Application Programming Interface

This is a simple REST API developed using node and express js

alt text

❤️ Found this project useful?
If you found this project useful, then please consider giving it a ⭐️ on Github and sharing it with your friends via social media.

Requirements
Node.js, express javascript (Postman)

Getting Started
Setup DB

you can find the DB and other details under src/db create a database with the name node-typescript-rest-api and then run/ import the .sql files (extract the sql files from sql.zip). Or you can run npm run seed.

install pm2 globally with npm install -g pm2

Run the app locally

npm install

npm start - This will start the application and run on port 3000

npm run dev - This will start the application in development mode

npm run watch & pm2 start ecosystem.config.js to start the application with cluster for scalability

you can change port in .env file check .env-sample

Folder Structure
src
└───index.ts          # Application entry point
└───routes            # Application routes / endpoints
└───controllers       # Express route controllers for all the endpoints of the app
└───repositories      # All the database interaction logic is here
└───db                # DB related files like connection / seed data
└───handlers          # Common logic
└───logs              # application logs
└───middlewares       # express middlewares
└───models            # DB Models (Postgress)
└───validators        # API Request object validations

Features
CRUD operations for books/movies
CRUD operations for Lessons/Titles
REST API Request object validations - Basic
Error Logs
Setup docs
Seeder for DB
Planned
