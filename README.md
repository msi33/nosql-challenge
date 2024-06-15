# nosql-challenge: Module 12 Challenge
#1. Background

The data is from The UK Food Standards Agency. The agency evaluate establishments and give food hygiene rating.The goal is to help the editors of Food magazine, Eat Safe, Love to understand the rating data for journalists and food critics purpose for future articles. Used MongoDB for database for setup, data loading and frequent updates of the database.Deepdive into data and use exploratory queries to identify establihments with hygiene scores of 20, determined highly-rated establishments in London, top-rated eateries near "Penang Flavours," and localities with hygiene score of 0


#2. The challenge has three main components

Part 1: Database and Setup (using: 'NoSQL_setup_starter.ipynb')

#1. Import necessary depenencies: PyMongo,pandas and Pretty Print (pprint).
#2. Import the data from establishments.json into the "uk_food" database and the "establishments" collection.
#3. Create and establish Mongo Client and display the database adn collection ('establishments') and format for exploratory review


Part 2: Update to the Database (using: ''NoSQL_setup_starter.ipynb')

#1. Add a new halal restaurant's information to the database.
#2. Find and update the BusinessTypeID for "Restaurant/Cafe/Canteen".
#3. Count and remove establishments in the Dover Local Authority.
#4. Convert latitude and longitude to decimal numbers.
#5. Change the data type from String to Integer for RatingValue

Part 3: Exploratory Analysis (Using: 'NoSQL_analysis_starter.ipynb')

#1. find establishments with Hygiene Score of 20, count and display
#2. find RatingValue in London count, display and extract those with rating of  
    4 or more
#3. Find, extract and count establishments with ratingvalue of 5 and display, 
    apply sort to them based on geoloc of 'Penang Flavours'
#4. Find those with ratingvalue of 0, count, sort and display top ten each 
    Local Authority area 

