# FloralHeaven

FloralHeaven is a full-stack web application designed to provide a seamless online flower shop experience. The application allows users to browse and purchase beautiful and unique flower arrangements for various occasions. This project demonstrates the integration of a backend server with a frontend interface to create a user-friendly e-commerce platform for flower enthusiasts.

## Project Overview

FloralHeaven is built using Node.js and Express on the backend, with MongoDB as the database for storing flower details. The frontend is rendered using the Pug template engine, providing a clean and responsive user interface. The project showcases the following features:

- **Home Page**: Introduction to the website and displays a selection of trending flower products, fetched from the database.
- **Flower Page**: A comprehensive list of all available flower products, each with detailed descriptions, prices, and images.
- **About Us Page**: Provides information about FloralHeaven, including the mission statement, contact form, and details about the owner.
- **Create Page**: An admin interface for adding new flower products to the database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Running the Project](#running-the-project)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/FloralHeaven.git
   cd FloralHeaven

2. **Install dependencies:**
   ```bash
   npm install

3. **Set up the database:**
   - Make sure you have MongoDB installed and running on your machine.
   - Create a .env file in the root directory and add your MongoDB connection string:
   ```bash
   MONGODB_URI=your_mongodb_connection_string

## Usage

1. **Start the server:**
   ```bash
   npm start

2. **Access the application:**
   Open your browser and go to http://localhost:8888

## Running the Project

To run the project in a development environment, use:
   ```bash
   npm run dev

## Technologies Used

Backend:

- Node.js
- Express
- MongoDB

Frontend:

- Pug template engine
- CSS
