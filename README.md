# Movie-recommender-System-
A movie recommender system built on a distance vector Machine learning model trained on a dataset containing 5000 movies
The movie recommender system main is the main python jupyter notebook where the model is programmed
the tmdb_500movies.csv is the dataset that was imported on which the model was trained
The Movie recommender system was designed as a beginner project where i got to understand the workings of various python libraries such as pandas, numpy
The dataset was imported to the notebook via and was made into a dataframe using pandas
The datasets were merged into one dataset for easy data processing
next a table was constructed containing only the columns that were involved in building the model
title, unique id and tags column
the tag column was built using the genre of a particular movie,the top crew,cast
once the final table was prepared
we import the count vectoriser from sklearn library
all the rows in the table are then vectorised with respect to each other
we then proceed to import the cosine similarity library
this library would output the similarity of one movie with respect to all movies in the dataset and store it in the vector array
hence we obtain the similarity vector array
title of a movie is input in the recommender function the system proceds to list down the similiarity index of all movie with respect to the input movie
we sort the list in the descending order according to the similarity of the movies preserving the unique movie id using dictionaries
once found we output the titles of the top 5 movies in the list
hence the model outputs the top 5 movies recommended to be watched by the user .
