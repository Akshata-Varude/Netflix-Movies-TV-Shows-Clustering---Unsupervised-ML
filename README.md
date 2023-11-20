# Netflix-Movies-TV-Shows-Clustering---Unsupervised-ML
I have clustered similar movies and TV Shows available on Netflix taking into account attributes like Description, Cast, Director, Genre, etc of a particular movie/show.

# Introduction
Netflix is the world’s largest on-demand internet streaming media and online DVD movie rental service provider. it was Founded on August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released on the Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.

# Problem Statement
The goal of this project is to find similarities within groups of people to build a movie recommendation system for users. We are going to analyze a dataset from the Netflix database to explore the characteristics that people share in movies. We have experienced it ourselves or have been in the room, the endless scrolling of selecting what to watch. Users spend more time deciding what to watch than watching their movies.
 
# Data Summary
This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report that shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, and rotten tomatoes can also provide many interesting findings.
show_id: Unique ID for every Movie / TV show
type: Identifier - A Movie or TV Show
title: Title of the Movie / Tv Show
director: Director of the Movie
cast: Actors involved in the movie/show
country: The country where the movie/show was produced
date_added: Date it was added on Netflix
release_year: Actual Release Year of the movie/show
rating: TV Rating of the movie/show
duration: Total Duration - in minutes or number of seasons
listed_in : Genere
description: The Summary description

# Dash Web App:
NetflixRecommender recommends Netflix movies and TV shows based on a user's favorite movie or TV show. It uses a Natural Language Processing (NLP) model and a K-means clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions. The motivation behind this project is to develop a deeper understanding of recommender systems. Specifically, thinking about how companies like Netflix and YouTube create algorithms to tailor content based on user interests and behavior. I created a Dash web app that utilizes my model to provide film recommendations based on a user's favorite movie or TV show.

# Exploring Solutions:
Having a deeper understanding of what problem we are trying to solve, what the users’ needs and frustrations are, and what the goals are for achieving the best possible solution for both the business as well as the user, I began by listing out the possible solutions that were arrived from the research.

1. Improve rating system: Use the star rating rather than a thumbs up and thumbs down rating system to help guide in decision-making when selecting a film.
2. Separate recently watched: Hide the movies and TV shows on a separate page so users don’t have to scroll through those already seen. — users have to do more searching
3. Randomize a Movie: When users are unsure of what to choose, Netflix will randomly select something to watch based on their viewing history.
4. Show popular/trending films: Create a category that showcases only trending content.
5. Connect with Friends: It was proven that users watch shows and movies based on friend recommendations so this may be useful for keeping users locked into Netflix for longer.
6. Organizing films by mood: Alongside the genre filter, it may be possible to organize content based on the mood that is experienced after watching the film.

# Steps involved:
The full code for this article can be found here. It is implemented in Python and different clustering algorithms are used. Below is a brief description of the general approach that I employed:

 - Data cleaning and pre-processing: Here I checked and dealt with missing and duplicate variables from the data set as these can grossly affect the performance of different machine learning algorithms (many algorithms do not tolerate missing data).
   
 - Exploratory Data Analysis: Here I wanted to gain important statistical insights from the data and the things that I checked for were the distributions of the different attributes, correlations of the attributes with each other, and the target variable and I calculated important odds and proportions for the categorical attributes.
 
 - Clustering: Clustering or cluster analysis is a machine learning technique, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points. The objects with the possible similarities remain in a group that has less or no similarities with another group." It does it by finding some similar patterns in the unlabelled dataset such as shape, size, color, behavior, etc., and divides them as per the presence and absence of those similar patterns. It is an unsupervised learning method; hence no supervision is provided to the algorithm, and it deals with the unlabeled dataset. After applying this clustering technique, each cluster or group is provided with a cluster ID. ML systems can use this ID to simplify the processing of large and complex datasets.

# Conclusion
In conclusion, tailored recommendations can be made based on information about movies and TV shows. In addition, similar models can be developed to provide valuable recommendations to consumers in other domains. It will solve for improved movie and TV-show selection times with a considerable growth in satisfaction of the content being consumed leading to more user engagement and greater trust in Netflix recommendations.
