# Popcorn-Picks
(Popcorn Picks is a sophisticated movie recommendation system that leverages content-based filtering to suggest films based on their attributes and content.)

Types of Recommendation System :-
Content-Based Filtering: This method recommends movies similar to those the user has enjoyed by analyzing the content's attributes.

Project Flow:-
Dataset : Utilized the TMDB 5000 movie dataset for a rich and diverse collection of film data.
Link :- https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

Data Preprocessing:
Employed sklearn's feature extraction for effective text vectorization.
Applied nltk for stemming to normalize text data.
Calculated cosine similarity using sklearn metrics to measure the similarity between movies.
Utilized pickle for efficient data serialization and storage in PyCharm.
Model Development: Constructed a robust model to generate movie recommendations based on the processed data.

User Interface Creation: Designed an interactive UI using PyCharm to provide users with a seamless experience in accessing movie recommendations.

Key Findings :-
The combination of sklearn's text vectorization and nltk's stemming significantly enhances the accuracy of content-based recommendations.
Utilizing cosine similarity allows for precise identification of movies with similar content, improving recommendation quality.

Learning Experience :-
This project was undertaken for learning purposes, and through its development, I gained valuable insights into building a recommendation system. 
It provided hands-on experience with data preprocessing, model development, and creating a user-friendly interface. 
The process enriched my understanding of machine learning techniques and their practical applications.
