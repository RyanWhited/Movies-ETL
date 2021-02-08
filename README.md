# Movies-ETL
## Overview
Created an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. Refactored original code form module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
## Results
1. Successfully wrote an ETL function to read three data files. 

    - [ETL_Function_Test](https://github.com/RyanWhited/Movies-ETL/blob/main/ETL_function_test.ipynb)

2. Extracted and transformed the wikipedia data. 

    - [ETL_Clean_Wiki_Movies](https://github.com/RyanWhited/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynbb)

3. Extracted and transformed the kaggle data.

    - [ETL_Clean_Kaggle_Data](https://github.com/RyanWhited/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynbb)

4. Added the movies_df dataframe and MovieLens rating CSV data to SQL database. 

    - [ETL_Create_Database](https://github.com/RyanWhited/Movies-ETL/blob/main/ETL_create_database.ipynb)

