# nosql-challenge

## Overview

### This project involves analyzing food hygiene ratings from the UK Food Standards Agency. You’ll import data into a NoSQL database, update the database based on specific requirements, and conduct exploratory analysis to help the magazine Eat Safe, Love focus on interesting food establishments.

### Database and Jupyter Notebook Setup:
##### - Load establishments.json into a MongoDB database named uk_food and collection establishments.
##### - Connect to the MongoDB database using PyMongo.
##### - Confirm the database and data are correctly loaded by listing the databases and collections and displaying a sample document.

### Update the Database:
##### - Insert a new restaurant, “Penang Flavours,” into the database with specified details.
##### - Assign the correct BusinessTypeID to “Penang Flavours” based on its business type.
##### - Delete all establishments in the “Dover” local authority.
##### - Convert latitude, longitude to decimal numbers and RatingValue to integers.

### Exploratory Analysis:
##### - Identify establishments with a hygiene score of 20.
##### - Find London establishments with a rating value of 4 or higher.
##### - List the top 5 establishments with a rating of 5 and lowest hygiene score near “Penang Flavours.”
##### - Determine which local authority areas have the most establishments with a hygiene score of 0, and list the top ten.
