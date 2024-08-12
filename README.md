E-commerce Back End with ORM: Project README
Project Overview

This project involves building the back end for an e-commerce site using modern technologies such as Express.js, Sequelize, and PostgreSQL. The aim is to create a fully functional API that can handle the storage, retrieval, and management of e-commerce data, such as products, categories, and tags. This back end will serve as the foundation for a complete e-commerce application, supporting the needs of businesses and consumers in the digital marketplace.

In 2021, the e-commerce sector in the United States generated a staggering US$2.54 trillion, according to the United Nations Conference on Trade and Development. This underscores the critical role that e-commerce plays in the electronics industry, making it imperative for developers to understand the architecture of e-commerce platforms.
Key Features

    Express.js API: The project utilizes Express.js to build a RESTful API for the e-commerce site.
    Sequelize ORM: Sequelize is used to manage the interaction between the API and a PostgreSQL database, providing an efficient and scalable solution for data management.
    PostgreSQL Database: A robust PostgreSQL database is used to store all the relevant e-commerce data.
    CRUD Operations: The API supports full CRUD (Create, Read, Update, Delete) operations on the product, category, and tag data.
    API Testing: Routes can be tested using Insomnia Core to ensure proper functionality.

User Story

As a manager at an internet retail company, I want a back end for my e-commerce website that uses the latest technologies so that my company can compete with other e-commerce companies.
Acceptance Criteria

    Database Configuration:
        When the database name, PostgreSQL username, and PostgreSQL password are added to an environment variable file, a connection to the database is established using Sequelize.

    Database Setup:
        Upon entering the schema and seed commands, a development database is created and populated with test data.

    Application Invocation:
        When the command to invoke the application is entered, the server starts, and the Sequelize models are synced to the PostgreSQL database.

    API Route Testing:
        When API GET routes are opened in Insomnia Core for categories, products, or tags, the data is displayed in a formatted JSON.
        When API POST, PUT, and DELETE routes are tested in Insomnia Core, the corresponding operations are performed on the data.

Installation and Setup

    Clone the Repository:
        Clone the starter code from the provided repository link.

    Install Dependencies:
        Run npm install to install all the necessary dependencies.

    Environment Variables:
        Create a .env file in the root directory and add your database name, PostgreSQL username, and PostgreSQL password.

    Database Initialization:
        Run npm run schema to create the database schema.
        Run npm run seed to seed the database with initial data.

    Start the Server:
        Run npm start to start the server and sync the Sequelize models to the PostgreSQL database.

Testing the API

    Use Insomnia Core or any other API testing tool to test the API endpoints.
    Ensure that all CRUD operations (GET, POST, PUT, DELETE) are functioning correctly by testing the routes for categories, products, and tags.
