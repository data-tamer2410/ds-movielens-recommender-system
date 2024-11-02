# MovieLens Recommender System
A collaborative filtering-based recommendation system project using the Surprise library to generate personalized suggestions.

## Description
In this project, we built a collaborative filtering recommender system for the MovieLens 100K dataset. Using the Surprise library, we explored and implemented several recommendation algorithms, including Singular Value Decomposition (SVD), SVD++, and Non-negative Matrix Factorization (NMF), to predict movie ratings based on user preferences.

Hyperparameter tuning was applied to each model: Optuna was used for SVD and NMF, while GridSearchCV optimized SVD++. We evaluated performance with RMSE and MAE metrics, finding that all models delivered competitive recommendations with SVD performing slightly better.

Additionally, a collaborative filtering algorithm was implemented from scratch, providing insights into the mechanisms of personalized recommendations. This model is further tuned with Optuna, leveraging techniques in matrix factorization and optimization.

The project demonstrates the practical implementation of collaborative filtering, tuning for optimal performance, and the power of recommendation systems in providing users with personalized content.
