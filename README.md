# Restaurant Database API

This is a RESTful API for managing restaurant data using Node.js, Express.js, and MongoDB.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Usage](#usage)
    - [Running the Server](#running-the-server)
    - [API Endpoints](#api-endpoints)
        - [Get All Restaurants](#get-all-restaurants)
        - [Get Restaurants by Cuisine](#get-restaurants-by-cuisine)
        - [Sort Restaurants](#sort-restaurants)
        - [Get Delicatessen Restaurants](#get-delicatessen-restaurants)
        - [Add a New Restaurant](#add-a-new-restaurant)
        - [Get Restaurant by ID](#get-restaurant-by-id)
        - [Update Restaurant](#update-restaurant)
        - [Delete Restaurant](#delete-restaurant)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a RESTful API that allows you to perform CRUD (Create, Read, Update, Delete) operations on restaurant data. It includes various endpoints to retrieve restaurant details, add new restaurants, update existing ones, and delete restaurants. Additionally, it supports sorting and filtering of restaurant data.

## Getting Started

### Prerequisites

Before you can run this project, make sure you have the following prerequisites installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (Make sure the MongoDB server is running)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/restaurant-database-api.git

Navigate to the project directory:

bash
Copy code
cd restaurant-database-api
Install dependencies:

bash
Copy code
npm install

### Usage
## Running the Server
To start the API server, use the following command:

bash
Copy code
npm start
The server will run on port 3000 by default. You can access it at http://localhost:3000.

### API Endpoints

# Get All Restaurants
Endpoint: /restaurants
Method: GET
Description: Retrieve a list of all restaurants.

# Get Restaurants by Cuisine
Endpoint: /restaurants/cuisine/:cuisine
Method: GET
Description: Retrieve restaurants by cuisine (e.g., Japanese, Bakery, Italian).

# Sort Restaurants
Endpoint: /restaurants/sort
Method: GET
Description: Sort restaurants by restaurant_id in ascending or descending order using query parameters sortBy (ASC or DESC).

# Get Delicatessen Restaurants
Endpoint: /restaurants/Delicatessen
Method: GET
Description: Retrieve restaurants with cuisine 'Delicatessen' and not located in 'Brooklyn', sorted by name.

# Add a New Restaurant
Endpoint: /restaurants
Method: POST
Description: Add a new restaurant to the database.

# Get Restaurant by ID
Endpoint: /restaurants/:id
Method: GET
Description: Retrieve a restaurant by its unique ID.

# Update Restaurant
Endpoint: /restaurants/:id
Method: PUT
Description: Update an existing restaurant's details.

# Delete Restaurant
Endpoint: /restaurants/:id
Method: DELETE
Description: Delete a restaurant by its ID.

# Configuration
You can configure the MongoDB connection by modifying the .env file. Ensure that you have a valid MongoDB URI.

# Example .env file:

bash
Copy code
MONGO_URI=mongodb+srv://your-username:your-password@cluster0.mongodb.net/your-database?retryWrites=true&w=majority
PORT=3000

# Contributing
Contributions are welcome! If you have any improvements or bug fixes, please submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# vbnet
Copy code

You can copy and paste this entire README content into a `README.md` file in your project's root directory. Make sure to replace placeholders like `your-username`, `your-password`, and `your-database` in the MongoDB URI with your actual database credentials. Additionally, customize any other sections as needed for your project.

# Author:

Rauny Martinelli
