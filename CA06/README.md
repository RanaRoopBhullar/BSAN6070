# CA06 - kNN Based Recommender Engine

## Datasource
At scale, this would look like recommending products on Amazon, articles on Medium, movies on Netflix, or videos on YouTube. Although, we can be certain they all use more efficient means of making recommendations due to the enormous volume of data they process. However, we could replicate one of these recommender systems on a smaller scale using what we have learned here in this article. Let us build the core of a movies recommender system.

What question are we trying to answer? Given a movies data set, what are the 5 most similar movies to a movie query?
The sample dataset we will be using is obtained from the UCI Machine Learning Repository and is found at the following url in csv format:
"https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv”
Use the link to read the data in Python.

## Table of Contents
- Import Packages
- Read Data
- Data Quality Analysis
- Building Recommendation System
- Final Results
