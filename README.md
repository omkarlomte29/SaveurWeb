download and extract this file 
---> 
setup mysql 
---> 
create a db as name "saveur_db"
run below query in mysql workbench:
--->
CREATE DATABASE saveur_db;

USE saveur_db;

CREATE TABLE users(
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  email VARCHAR(100) UNIQUE,
  password VARCHAR(255)
);

