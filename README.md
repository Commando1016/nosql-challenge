# Eat Safe, Love

## Overview
"Eat Safe, Love" is a data analysis project that focuses on exploring and manipulating data from the UK food establishments database. This project involves setting up a MongoDB database, importing data from a JSON file, updating the database with new records, and performing various data analysis tasks using Python and Jupyter Notebook.

## Dependencies
- MongoDB
- pymongo
- pandas
- Jupyter Notebook

## Features

### Part 1: Database and Jupyter Notebook Set Up
- Import data from `establishments.json` into a MongoDB database named `uk_food` with a collection named `establishments`.
- Set up the MongoDB connection and confirm the creation of the database and collection.

### Part 2: Update the Database
- Insert new restaurant data into the `establishments` collection.
- Update records with specific `BusinessTypeID`.
- Perform data cleaning operations such as converting string values to appropriate numeric types.

### Part 3: Exploratory Analysis
- Analyze and retrieve specific records from the database.
  - Find establishments with a hygiene score equal to 20.
  - Identify establishments in London with a `RatingValue` of 4 or higher.
  - Determine the top 5 establishments near a specific location with a `RatingValue` of 5.
  - Aggregate and sort establishments by Local Authority based on hygiene scores.

## Usage
This project is designed to be run in a Jupyter Notebook environment, allowing for interactive data analysis and visualization. To use this project:
1. Import the necessary data using the provided MongoDB import command.
2. Follow the steps in the Jupyter Notebook to connect to the MongoDB database, insert new records, and perform various analyses.
