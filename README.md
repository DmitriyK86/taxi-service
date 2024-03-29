﻿# Taxi Car Manager
### Project description:
A simple web application that supports authentication, registration and CRUD  operations.

### Features:
* registration like a driver;
* authentication like a driver;
* create/update/remove a driver;
* create/update/remove a manufacturer;
* create/update/remove a car;
* display list of drivers;
* display list of manufacturers;
* display list of cars;
* add driver to car;
* display all cars for current driver.

### Project structure:
#### Project has a 3-layer architecture:
* the data access layer;
* the application logic layer;
* the presentation layer.

### Used technologies:
* Java 11
* MySql 8.0.32
* Tomcat 9.0.73
* Maven
* JSP
* JSTL
* HTML
* CSS

### Instructions for running the application:
* Clone this repo to your IDE
* Install MySql Workbench 8.0.32
* Run SQL script from init_db.sql file in your Workbench
* In ConnectionUtil class use your database URL, username and password
* Install and configure Tomcat 9.0.73
* Run the application
