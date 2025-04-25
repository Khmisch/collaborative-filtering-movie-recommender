**🎬 Collaborative Filtering Movie Recommender System**

This project implements a Collaborative Filtering-based Movie Recommender System using NumPy and TensorFlow. It leverages matrix factorization to predict user ratings for movies they haven't rated yet, enabling personalized recommendations.

**📌 Features**

  - Collaborative filtering using latent factor models

  - Normalization of ratings to account for movie popularity bias

  - Pre-trained model parameters for fast predictions

  - Utilities for loading and processing rating data

  - Recommendation outputs based on user preferences

**🧠 Core Concepts**

  - Matrix Factorization: Learn latent features for users and movies

  - Rating Normalization: Center ratings around the mean to handle sparse matrices better

  - Prediction: Estimate unknown ratings using dot products of learned features

**📁 Files**

  - CollaborativeRecSys.ipynb – Jupyter notebook with all steps: data loading, normalization, prediction, and visualization.

  - recsys_utils.py – Helper functions for loading data, normalizing ratings, and handling model parameters.

  - ./data/ – Folder containing:

  - small_movies_X.csv, small_movies_W.csv, small_movies_b.csv: Pre-learned parameters

  - small_movies_Y.csv, small_movies_R.csv: Ratings matrix and binary mask

  - small_movie_list.csv: List of movies with IDs and titles

**📊 Example Output**

Given a set of movies manually rated by the user, the model predicts the most relevant unseen movies based on learned user/movie features:
![image](https://github.com/user-attachments/assets/69c86931-95f9-4098-b094-33a4d98271e4)
![image](https://github.com/user-attachments/assets/b9aab195-18e9-4f12-a3af-98ff1177f782)

**📚 Acknowledgments**

This project is based on techniques taught in DeepLearning.AI and Stanford’s Machine Learning course and adapted for practical implementation.
