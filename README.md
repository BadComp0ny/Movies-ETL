# Movies-ETL
The purpose of this project was to expose me to the ETL (Extract, Transform, and Load) process.  I was to take data from Wikipedia, Kaggle and combine the ratings in order to establish a clean set of data for a hackathon.

## Overview
This project required four separate steps in which ultimately lead to the full ETL process in this scenario.  

### ETL_function_test.ipynb
1. Data had to be extracted from the website in JSON and CSV formats.
2. It was then transformed into Data Frames.
3. JSON file had to first be loaded to a ledgible file and then into data frame.

### ETL_clean_wiki_movies.ipynb
Combine all languages to one grouping.

Organized columns

In the extract_transform_load function we worked through the following.  
- RegEx (regular expressions)
- how to apply and map methods along with the use of the lambda function.
- Python list comprehensions.

### ETL_clean_kaggle_data.ipynb

This needed me to identify missing values, fill them in with others and filter out any unwanted columns.
I also needed to merge dataframes through the pd_merge process.


### ETL_create_database.ipynb
This was the final process which involved setting the tables to be imported to SQL to allow the end user for more manipulation within the SQL product.
