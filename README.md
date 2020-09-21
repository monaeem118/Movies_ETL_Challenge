# Movies ETL Challenge

## Overview

This purpose of this project is to demonstrate the typical ETL process by extracting and transforming movies data from three differenct sources. In this project, an automated data pipeline is created by defining a function which takes data from three files. These files are Wikipedia data, Kaggle metadata and the MovieLens rating data. The function extracts and transforms this data into DataFrames namely "wiki_movies_df" and "kaggle_metadata", which are then merged into "movies_with_ratings_df" DataFrame after cleaning. Finally the function connects to PostgreSQL database "movie_data" and adds the "movies_df" and MovieLens "ratings.csv" data to the database.

_Note: The repository does not contain ratings.csv file as it exceeds the GitHub file size limit_ 