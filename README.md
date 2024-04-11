# Movie-Recommender-System

This repository contains a movie recommender system implemented in Python using [Surprise](https://surpriselib.com/), a scikit for building and analyzing recommender systems, along with Pandas for data manipulation.

## Features

- **Collaborative Filtering**: Utilizes KNNBasic collaborative filtering algorithm to recommend movies based on user ratings.
- **Item-based Filtering**: Recommends movies based on similarities between items (movies) using cosine similarity.
- **Evaluation**: Evaluates the model's performance using Root Mean Squared Error (RMSE).
- **Top-N Recommendations**: Provides top N movie recommendations for a given user.

## Requirements

- Python 3.x
- numpy
- pandas
- scikit-surprise
- seaborn
- matplotlib
