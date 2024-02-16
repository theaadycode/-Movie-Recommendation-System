MOVIE RECOMMENDATION SYSTEM

Data Preprocessing:
Loading Data: The code starts by importing necessary libraries and reading a dataset containing movie ratings. The dataset consists of columns: user_id, item_id (movie_id), rating, and timestamp.

Data Exploration: The script performs some exploratory data analysis, including checking the shape of the dataset, the number of unique users and movies, and merging the movie titles with the main dataframe.

Exploratory Data Analysis:
Cleaning Data: The script converts the 'rating' column to numeric values, drops rows with NaN values in the 'rating' column, and calculates the mean rating and the number of viewers for each movie.

Visualization: The code generates histograms and a joint plot to visualize the distribution of ratings and the number of viewers.

Movie Recommendation:
Creating Movie Matrix: The script creates a movie-user matrix, where rows represent users, columns represent movies, and cells contain the corresponding ratings.

Working with a Specific Movie (Star Wars): It demonstrates the process of recommending movies based on the correlation with a specific movie (Star Wars in this case).

Predicting Movies for a Given Movie (Toy Story): The function predict_movies takes a movie name as input, retrieves user ratings for that movie, calculates the correlation with other movies, filters out movies with fewer than 100 viewers, and provides a list of recommended movies based on correlation.

Summary:
In summary, the recommendation system uses collaborative filtering to suggest movies based on user ratings and movie correlations. It begins with data preprocessing and exploratory data analysis, followed by the creation of a movie-user matrix. The system then provides movie recommendations using correlation with a specific movie or user's preferences.

Note: The code provided is a part of the implementation, and the explanation assumes a basic understanding of collaborative filtering and data analysis concepts.
