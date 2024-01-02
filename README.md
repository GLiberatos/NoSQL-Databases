# NoSQL Data Analysis Challenge
## Introduction

Welcome to the NoSQL Data Analysis Challenge! This repository is your starting point for diving into the world of NoSQL databases using MongoDB. It includes two key Jupyter notebooks: 'NoSQL_Setup.ipynb' for database setup and 'NoSQL_analysis.ipynb' for data analysis. These files guide you through the process of importing data from a JSON file, setting up a MongoDB database, and running in-depth analyses. The "Resources" folder contains the essential .json file to import data into MongoDB.

## Project Details

### Database Setup
- **Notebook:** 'NoSQL_Setup.ipynb'
- **Tasks:**
  - Import JSON data into MongoDB database named "uk_food".
  - Create a collection "establishments".
  - Insert a new restaurant document into the database.
  - Format data types for effective querying (e.g., converting string "$type" to "&toDouble").
- **Goal:** Prepare and format the database for efficient data querying.

### Data Analysis
- **Notebook:** 'NoSQL_analysis.ipynb'
- **Tasks:**
  - Execute queries to answer predefined questions.
  - Modify queries for specific parameters.
  - Convert query results to pandas dataframes for enhanced visualization and interpretation.
- **Goal:** Analyze the data to extract meaningful insights.

## Usage Instructions

### Setting Up the Database
1. **Preparing the Environment:**
   - Open a command line or Git Bash terminal.
   - Navigate to the "Resources" folder.

2. **Importing Data:**
   - Use the "mongoimport" command to load the .json file into the MongoDB database.

3. **Running the Notebook:**
   - Ensure necessary dependencies like `pymongo` and `pprint` are installed.
   - Execute cells in 'NoSQL_Setup.ipynb' to perform database operations.

### Analyzing the Data
1. **Opening the Notebook:**
   - Open 'NoSQL_analysis.ipynb' in Jupyter Notebook or VSCode. A second database import is not required.

2. **Setting Up Dependencies:**
   - Import necessary libraries such as `pymongo`, `pprint`, and `pandas`.

3. **Running Analysis:**
   - Execute cells in 'NoSQL_analysis.ipynb' to perform data analysis tasks.
