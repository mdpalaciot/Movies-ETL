# Movies-ETL
Purpose: Creating an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables
Derivables:
  Derivable 1: Write a function that reads in the three data files and creates three separate DataFrames.
  Derivable 2: Extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping   duplicates, use a try-except block to catch errors.
  Derivable 3: Extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle         metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame   to create the movies_with_ratings_df.
  Derivable 4: Add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
