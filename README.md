# React-JS--Crud-Mysql

 <p align ="center">
  <img src="frontend/src/assets/readme.png" width="600px">
</p>

## Installation

### Client

1. `$ cd frontend`
2. `$ npm install` or `$ yarn`
3. `$ npm start` or `$ yarn start`

### Server

1. `backend`
2. `$ cd api`
3. `$ npm install` or `$ yarn`
4. `$ npm start` or `$ yarn start`

### Data base

Navigate to the backend directory

`$ cd backend`

Use the following command to download MySQL images using Docker Compose

`$ docker-compose up`

Connect to the database using MySQL Workbench or your preferred MySQL client.

Use the command for created Schema and Table in your data base.

`$ docker exec -it mysqlbd mysql -uroot -p`

`$ CREATE SCHEMA `crud` ;`

`$ USE `crud`;`

`$ CREATE TABLE `usuarios`(
 `id`int NOT NULL AUTO_INCREMENT,
 `nome`varchar(255) COLLATE utf8mb4_unicode_ci NOT NULL,
 `email`varchar(255) COLLATE utf8mb4_unicode_ci NOT NULL,
 `fone`varchar(45) COLLATE utf8mb4_unicode_ci NOT NULL,
 `data_nascimento` date NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=4 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;
`

## Functionalities

- Create users in the database
- Read users in the database
- Update users in the database
- Delete usres in the database
- Click to edit and delete users

## Used Libraries

### Front-end

<div align="center"> 
  <a href = "https://react.dev"> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" target="_blank"></a>
</div>

### Back-end

<div align="center"> 
  <a href = "https://nodejs.org/en"> <img src="https://img.shields.io/badge/-Nodejs-339933?style=flat-square&logo=Node.js&logoColor=white" target="_blank"></a>
  <a href = "https://expressjs.com"> <img src="https://img.shields.io/badge/Express.js-404D59?style=flat-square" target="_blank"></a>
  <a href = "https://www.docker.com/get-started/"> <img src="https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white" target="_blank"></a>
  <a href = "https://www.mysql.com"> <img src="https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" target="_blank"></a>
 </div>
