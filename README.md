# MovieRecommendationSystem
It is a Movie Recommendation System based on Content-Based Filtering Approach


Project
My project is about movie recommendation system 
Pre covid post covid 
Otts
Two types of recommendation
content-based filtering and collaborative filtering approaches. Content-based filtering approach primarily focuses on the item similarity content of the movie
collaborative filtering same account two users 

We have done our project based upon content based recommendation

Based on the plot of a movie that was watched by the user in the past, movies with a similar plot can be recommended to the user. This approach comes under content-based filtering as the recommendations are done only based on the user’s past activity.

Dataset used: A kaggle dataset which contains 5000 movies 

Import pd numpy
Preprocess that data set
Delete null values
Remove the unwanted info like budget etc
Add tags, tags = cast + crew+overview +zoner etc
Tags convert to vectors using Vectorization
Cosine similarity 
Front end using stream lit
Connecting both
