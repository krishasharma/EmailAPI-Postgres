# Email API - Node.js, Express, and PostgreSQL

This is my submission for CSE186 Summer 2024 Assignment 6. In this project, I developed a RESTful E-Mail API using Node.js and Express, backed by a PostgreSQL database. The API is designed to handle emails across different mailboxes, and I wrote tests to ensure the API meets the specified requirements.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Database Setup](#database-setup)
- [Testing](#testing)
- [Advanced & Stretch Features](#advanced--stretch-features)

## Project Overview
This project focuses on building a RESTful API for managing emails stored in a PostgreSQL database. The API provides endpoints to perform CRUD operations on emails, and it strictly adheres to the OpenAPI 3.0.3 schema. The project helped me gain experience in integrating databases with Node.js and testing complex API behaviors.

## Installation
To set up and run this project locally, follow these commands:
To install node packages:

  $ npm install

To start the database: 

  $ docker-compose up -d

To run the Web App: 

  $ npm start

To run tests: 

  $ npm test

To run the linter: 

  $ npm run lint

To generate a Canvas submission ZIP: 

  $ npm run zip

To stop the database: 

  $ docker-compose down
