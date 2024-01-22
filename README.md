# Travel Tracker

Track the countries you have visited with this simple Travel Tracker application.

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)


## Description

Travel Tracker is a web application built with Express.js and PostgreSQL to help you keep track of the countries you have visited. It allows you to add countries and visualizes them on a map.

## Features

- Add countries to your visited list.
- Visual representation of visited countries on a map.
- Total count of visited countries displayed.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Pratiksha-NS/travel-tracker.git
   
2. Install dependencies:


   ```bash
   cd travel-tracker
   npm install
   


3. Set up your PostgreSQL database and update the configuration in app.js:
   ```bash
   // Update the database configuration in app.js

   const db = new pg.Client({
   user: "your-username",
   host: "localhost",
   database: "your-database",
   password: "your-password",
   port: 5432,
   });

4.Run the application:
  
        npm start

5. Open your browser and navigate to http://localhost:3000.

## Usage

Visit http://localhost:3000 in your browser.
Enter the name of the country you have visited and click the "Add" button.

## Dependencies

- Express.js
- PostgreSQL
- Body Parser
- dotenv
