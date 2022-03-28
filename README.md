# Team Maxtermind Role Management Application

## Project Description

A single page web application for managing internal company promotions.

## Technologies Used

Front-end
- React - version 17.0.2
- React-Bootstrap - version 2.2.1
- React-Router - version 6.2.2
- Create-React-App - version 5.0.0

Back-end
- Java - version 11.0
- Maven - version 4.0.0
- Spring-Boot - version 2.6.4
- Log4J - version 1.2.17
- Lombok - version 1.18.22
- JUnit - version 4.13.2
- MSSQL JDBC - version 10.2.0

## Features

List of features ready and TODOs for future development

- Employees can sign in and view their profile with identifying information
- Employees have the ability to apply for open positions within the company
- After applying for a postion an employee can view their current applications
- Admins/Managers can sign in and approve or reject employee applications
- Once an application is approved/rejected an employee is notified of their application status

To-do list:

- Allow for employees to customize profile with metric and idenifiers that would help with job candidacy
- Implement Spring Security to improve user credentials saftey and sign in flow
- Add front-end unit testing with JEST
- Incorporate better error handling throughout the app

## Getting Started
Begin by cloning the parent repository
```console
$ git clone https://github.com/SequelTeamSix/Team-Maxtermind
$ cd Team-Maxermind
```

To get started with the back-end portion you will need [Java](https://www.oracle.com/java/technologies/downloads/) 11 or greater installed as well as [Maven](https://maven.apache.org/download.cgi) version 4 or greater
```console
$ cd back-end
$ mvn install
$ mvn spring-boot:run
```
To get started with the front-end portion of the app you will need [Nodejs](https://nodejs.org/en/download/) version 12 or greater installed
```console
$ cd front-end
$ npm install
$ npm run start
```

## Usage

On startup you will find yourself on the landing page, from here you have a two options...

> Login with the admin panel to approve or reject employee applications  
> Login with the employee page to apply for current open positions within the company

## Contributors

- Max Hilken
- Eric O'Brien
- Jake Morris
- Maikel Vera
- Shawntaria Burden
