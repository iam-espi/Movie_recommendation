# Movie_recommendation

## Project Overview

The objective of this project is to demonstrate the build of a simple movie recommendation system using Python with the help of Simple Python RecommendatIon System Engine (Surprise).

## Business Understanding

### Problem Statement:
How might we help a movie streaming business to increase revenue and improve customer satisfaction?

### Hypothesis:
Customers will continue watching when they receives recommendations. 

### Proposal:
Predict the ratings and preferences of users on movies follow by recommending additional movies to the users.

## Data Understanding

For education and development purpose, MovieLens Latest Datasets is selected. The small dataset has been chosen so that the workload can be run on normal laptop without GPU.

*This dataset (ml-latest-small) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users between March 29, 1996 and September 24, 2018. This dataset was generated on September 26, 2018.*

Two datasets, movies.csv and ratings.csv, have been uploaded and formatted to use with Surprise. 

*MovieLens users were selected at random for inclusion. Their ids have been anonymized. User ids are consistent between ratings.csv and tags.csv (i.e., the same id refers to the same user across the two files).*

*Only movies with at least one rating or tag are included in the dataset. These movie ids are consistent with those used on the MovieLens web site (e.g., id 1 corresponds to the URL https://movielens.org/movies/1). Movie ids are consistent between ratings.csv, tags.csv, movies.csv, and links.csv (i.e., the same id refers to the same movie across these four data files).*

*Ratings are made on a 5-star scale, with half-star increments (0.5 stars - 5.0 stars).*

## Modeling and Evaluation

Surprise simplifies the process of building and evaluation of recommendation system. It contains a varieties of prediction algorithms. It also provide tools to evaluate, analyze and compare the algorithms' performance. 

Cross Validation was performed on a few algorithms to find the better algorithms to use. SVD was selected as the best algorithm. Hyperparameters tuning was perform on SVD using GridSearch to find the best parameters for use. 

## Conclusion

A Collaborative Filtering recommndation system for any products and services can be build using Surprise if data can be structured into user ID, item ID and rating.



