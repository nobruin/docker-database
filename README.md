# How to create a database with table using dockerfile

This project is a example that how to create a database with a table using sql file. 

The structure the project is:
```
Dockerfile
README.md
└── db/
    └── CreateDatabase.sql
```
The following commands must be executed inside the project.

Docker build:
```
docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=nodedb -e MYSQL_USER=nodedb -e MYSQL_PASSWORD=nodedb mysql-with-table

```


docker run:
```
docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=nodedb -e MYSQL_USER=nodedb -e MYSQL_PASSWORD=nodedb mysql-with-table
```