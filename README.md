# login system

front-end = Angular
back-end = nodejs
dependencies = bcrypt and jwt

backend ----
cd to backend and run these command

1. npm init -y
2. npm i express mysql2 body-parser express-validator bcryptjs jsonwebtoken
3. npm i -D nodemon

change the start script to "nodemon index.js"

4. touch index.js

----------------commit push----------------

1. created database in xamp server = loginsystem
   schema:
   CREATE TABLE `loginsystem`.`users` (
   `id` INT NOT NULL AUTO_INCREMENT,
   `name` VARCHAR(255) NOT NULL,
   `email` VARCHAR(255) NOT NULL,
   `password` VARCHAR(255) NOT NULL,
   PRIMARY KEY(`id`)
   );

2. express server created
