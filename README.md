# nosql-challenge
NoSQL Challenge related files are in the repository

## Solution
There are 2 parts to this challenge. Part 1 is the NoSQL setup and Part 2 is Update the database. Both Part 1 and Part 2 are found in NoSQL_setup_starter.ipynb. Part 3 is the Exploratory Analysis which is found in NoSQL_analysis_starter.ipynb.

## Task
Part 1: Database and Jupyter Notebook Set Up

- Import the data
- Import the libraries: PyMongo and Pretty Print (pprint).
- Create an instance of the Mongo Client.
- Confirm that you created the database and loaded the data properly
- List the databases you have in MongoDB.
- List the collection(s) in the database.
- Find and display one document in the establishments collection.
- Assign the establishments collection to a variable.

Part 2: Update the Database

- Add new resturant that opened in Greenwich. 
- Find the BusinessTypeID for "Restaurant/Cafe/Canteen" and return only the BusinessTypeID and BusinessType fields.
- Update the new restaurant with the BusinessTypeID you found.
- The magazine is not interested in any establishments in Dover, so check how many documents contain the Dover Local Authority. Then, remove any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
- Some of the number values are stored as strings, when they should be stored as numbers.
- Convert latitude and longitude to decimal numbers.
- Convert RatingValue to integer numbers.

Part 3: Exploratory Analysis

1. Which establishments have a hygiene score equal to 20?

2. Which establishments in London have a RatingValue greater than or equal to 4?

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
