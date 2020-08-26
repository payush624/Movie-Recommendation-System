# Movie-Recommendation-System

Recommender systems have become ubiquitous in our lives. Yet,
currently, they are far from optimal. In this project, we attempt
to understand the different kinds of recommendation systems and
compare their performance on the MovieLens dataset. We attempt
to build a scalable model to perform this analysis. We start by
preparing and comparing the various models on a smaller dataset
of 100,000 ratings. Then, we try to scale the algorithm so that it is
able to handle 20 million ratings by using Apache Spark. We find
that for the smaller dataset, using user-based collaborative filtering
results in the lowest Mean Squared Error on our dataset.

LINK OF CREDITS.csv file
https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv
