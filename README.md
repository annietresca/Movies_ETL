# Movies_ETL

## Project Overview
This projet creates an automated pipeline that takes in new data, transforms it and loads it into existing tables.
To do this, I refractored the code I had worked on previously, ETL_cleaning_data, and created one function that took in three files- Wikipedia data, Kaggle metadata, and the MovieLens rating data.
This data was then added to a PostgreSQL database. 


## Resources
Software: Python 3.7.6 , Pandas, Jupyter Notebook, Numpy, PostgreSQL, PGAdmin
Data: ratings.csv, movies_metadata.csv, wikipedia_movies.json

## Summary
In order to complete Deliverable 1, I wrote an ETL function to read three data files (wikipedia data, kaggle metadata and movielens rating data) and then created three separate DataFrames. 

In order to complete Deliverable 2, I extracted and transformed the Wikipedia Data so that it would be mergable with the Kaggle metadata.

In order to complete Deliverable 3, I extracted and transformed the Kaggle metadata and MovieLens rating data and then converted it into separate DataFrames. 
I then merged the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create a single DataFrame. 
Finally, I merged the MovieLens rating data DataFrame with the above DF to create a single DataFrame.

In order to complete Deliverable 4, I added the DataFrames created in Deliverable 3 to a SQL database.
