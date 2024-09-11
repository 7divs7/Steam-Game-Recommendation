# Steam Game Recommendation Engine

## Objective Specification/ Data Exploration
Identify the data mining problem type - Supervised or Unsupervised
Supervised: Classification, Regression, Prediction
Unsupervised: Clustering based on similarity, Find correlations or associations 

For recommendation engine, the problem type is Unsupervised. 

games.csv can be used to filter games which are similar to other games

users.csv and games.csv together can be used to filter user profiles which are similar and recommend games for a specific user 

## Data Loading
Kaggle Dataset: https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam
1. games.csv: table of games with prices, ratings and release date
2. users.csv: table of user profiles - number of purchased products and reviews 

## Data Preprocessing

## Model Building
Task 1: For a given user, recommend top 5 games based on user profile
Model: Instance-based model- KNN

Task 2: For a given user, find top 5 similar users based on user profile
Model: Instance-based model - KNN

Task 3: For a given game, find top 5 similar games based on description
Model: Text mining task, I can either use TF-IDF score and cosine similarity or use LangChain model to find games with similar description


## Model Evaluation

