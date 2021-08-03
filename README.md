#Movies_ETL

##Background
The purpose of this project is to create an ETL function to extra movie related data from 3 different files, 2 from CSV files and 1 from a JSON file, transform and clean the data, then load into a SQL database.  Please see the following deliverables.
  1. Write an ETL function to read three data files
  2. Extract and transform the wikipedia movie data
  3. Extract and transform the kaggle data
  4. Create the moview database

##Resources
- Software: Python 3.8.8,  Postgres/pgAdmin4 , Jupyter Lab
- [Movies_Metadata_CSV](https://github.com/sbretag/Movie_ETL/blob/main/Resources/movies_metadata.csv)
- [Rankings_CSV, Source: Kaggle](https://github.com/sbretag/Movie_ETL/blob/main/Resources/ratings.csv)
- [Movies_Wiki_JSON, Source: Wikipedia](https://github.com/sbretag/Movie_ETL/blob/main/Resources/wikipedia-movies.json)
- Code
  - [Create Function Code (Deliverable 1)](https://github.com/sbretag/Movie_ETL/blob/main/ETL_function_test.ipynb)
  - [Clean Wiki Code (Deliverable 2)](https://github.com/sbretag/Movie_ETL/blob/main/ETL_clean_wiki_movies.ipynb)
  - [Clean Kaggle Code (Deliverable 3)](https://github.com/sbretag/Movie_ETL/blob/main/ETL_clean_kaggle_data.ipynb)
  - [Create DB Code (Deliverable 4)](https://github.com/sbretag/Movie_ETL/blob/main/ETL_create_database.ipynb)

##Database Output

###Movies Query
![image](https://github.com/sbretag/Movie_ETL/blob/main/Resources/movie_query.png)

###Rankings Query
![image](https://github.com/sbretag/Movie_ETL/blob/main/Resources/ratings_query.png)
