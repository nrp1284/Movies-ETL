## Project: Movie Database

Project Sponser: Amazing Prime

Projecct manager: Nayan patel

Project Scope: - Extract and Transform the Wikipedia Data and kaggle data

## Deliverables: Consists of four technical analysis deliverables

Deliverable 1: Write an ETL Function to Read Three Data Files

Deliverable 2: Extract and Transform the Wikipedia Data

Deliverable 3: Extract and Transform the Kaggle data

Deliverable 4: Create the Movie Database

## Overview of the analysis: 

a. Creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.

b. Use Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.



## Summary: 

Availbale Resources:

wikipedia wikipedia-movies.json 

MovieLens is a website run by the GroupLens research group at the University of Minnesota.

The Kaggle dataset pulls from the MovieLens dataset of over 20 million reviews and contains a metadata file

ratings.csv

## Results:

## Deliverable 1: Write an ETL Function to Read Three Data Files

1. The wiki_movies_df DataFrame

![wiki_movies](class/wiki_movies_df.png)

2. kaggle_metadata dataframe

![kaggle_metadata](class/kaggle_metadata.png)

3. The ratings dataframe

![ratings_df](class/ratings_df.png)

## Deliverable 2: Extract and Transform the Wikipedia Data

1. Checking wiki_movies_df

![wiki_movies](class/wiki_movies_dframe.png)

2. Adding the columns from wiki_movies_df

![wiki_movies_addingcolumns](class/added_columns_to_df.png)

## Deliverable 3: Extract and Transform the Kaggle data

1. checking movies_with_ratings_df after exract

![movies_with_ratings_df](class/movies_with_ratings_df.png)

2. kaggle_movies_dtafram after cleanup

![kaggle_movies_df](class/kaggle_movies_df.png)

## Deliverable 4: Create the Movie Database

1. The data from the movies_df DataFrame replaces the current data in the movies table in the SQL database, as determined by the movies_query.png. 

![movies_query](class/movies_query.png)

2. The data from the MovieLens rating CSV file is added to the ratings table in the SQL database, as determined by the ratings_query.png.

![ratings_query](class/ratings_query.png)

 









 

