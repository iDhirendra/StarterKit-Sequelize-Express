# StarterKit-Sequelize-Express
A Starter Kit for node, sequelize and express.

## install node modules
npm install

## update config.json
username -> your system username
password -> db password
database -> database name
dialect -> database(postgres, mysql, etc)

## To setup project for production
update config.json development to
"use_env_variable": "DATABASE_URL"
where DATABASE_URL is the URL of your database server.

## run server
npm run start:dev

## DATABASE
create a database todos-dev

## How to use sequelize commands
use node_modules/.bin/sequelize insted of sequelize

# APIs
127.0.0.1:8000/api/