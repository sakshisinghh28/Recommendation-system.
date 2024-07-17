# Movie Recommendation-system.

## Overview
This project implements a movie recommendation system using collaborative filtering techniques on the MovieLens dataset (100k) and MovieLens 20M dataset. Collaborative filtering is a method used to make automatic predictions about the interests of a user by collecting preferences or taste information from many users. The system analyzes user-item interactions to recommend movies that users might like based on their similarity to other users.

## Dataset
The MovieLens dataset used for this project contains 100,000 ratings from 943 users on 1,682 movies. Each user has rated at least 20 movies. The dataset includes ratings, user IDs, movie IDs, and timestamps.

## Methodology
### Data Preprocessing
Cleaned and explored the dataset to understand user preferences and movie popularity.

### Collaborative Filtering
Implemented a user-based collaborative filtering model using K-Nearest Neighbors (KNN). This method computes similarities between users based on their ratings and recommends movies liked by similar users.

### Evaluation
Assessed model performance using Root Mean Squared Error (RMSE). The achieved RMSE for this model was 1.33, indicating the average prediction error of the ratings.

## Results
The collaborative filtering model achieved an RMSE of 1.33, indicating its ability to predict user ratings with reasonable accuracy. Further improvements could involve exploring matrix factorization techniques or incorporating more sophisticated algorithms to enhance recommendations.

## Dependencies
- Python 3.x
- Surprise library for collaborative filtering
- Pandas, NumPy for data manipulation and preprocessing
- Matplotlib, Seaborn for visualization

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
