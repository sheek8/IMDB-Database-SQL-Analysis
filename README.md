# IMDB-Database-SQL-Analysis

This project involves working with the IMDB database using SQL to extract relevant information, perform data cleaning and transformation, and run insightful analysis using joins, aggregations, and window functions.

# Objectives
- Explore and extract relevant information from database with SQL functions
- Perform data cleaning and transformation using string functions and regex
- Use the cleaned data to run insightful analysis using joins, aggregations, and window functions

# Table Descriptions
The IMDB database contains a lot of information that has been pared down for this project. The tables we will be working with are:

actor_sample: information about the actors including id, name, and gender
cast_sample: each person on the cast of each movie gets a row including cast id, person's id (actor_sample.id), movie id, and role id
movie_sample: sample of movies the actors have been in including movie's id, title, and the production year
movie_info_sample: this table originally had a lot of information for each movie (take a look at info_type to see the information available) but we have dropped some information to make it a bit easier to manage. This table includes movie info's id, movie id, info type id, and the info itself
info_type: reference table to match each info type id to the description of the type of information
role_type: reference table for cast_sample to match role id to the description of the role

# Questions
The project involves answering several questions. Some of these questions include:

Extracting MPAA rating from the movie_sample table
Creating a view containing earnings per genre
Generating a five-number summary and the average of the US gross earnings data

# Technologies Used
- SQL
- PostgreSQL

# Conclusion
The IMDB database project is a great example of how SQL can be used to extract, transform, and analyze data. By working with a large and complex database, we can see how SQL can be used to answer important questions and gain valuable insights.




