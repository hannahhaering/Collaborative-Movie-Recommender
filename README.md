# Collaborative Filtering for Movie Recommendations

This repository contains a Jupyter Notebook that implements a movie recommender system using collaborative filtering. 

## Technologies Used
- TensorFlow
- Keras
- Python

## Dataset
The dataset used is a subset of the **ml-small** dataset from [DataLens](https://grouplens.org/datasets/movielens/) and consists of:
- `movies.csv`: Contains movie information (ID, title, genres).
- `ratings.csv`: Contains user ratings for movies, including timestamps.

## Installation
To run this notebook, you need Python 3.x and the following dependencies:

```bash
pip install pandas numpy matplotlib tensorflow
```

## Steps Involved

### Data Preprocessing
- Load movie and rating data.
- Merge datasets and clean unnecessary columns.
- Include movie ratings of a new user.
- Normalize and structure the dataset for learning.

### Data Visualization
- Histogram of rating count per user.
- Bar chart of rating distribution.

### Learning algorithm
- Implementation of cost function with regularization.
- Learn model using a custom training loop with TensorFlow and Keras.

### Movie Rating Predictions
- Generate movie predictions for the new user.
- Recommend top-rated movies based on predicted ratings.
