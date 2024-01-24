# Distributed Recommender System with Apache Spark

## Purpose
This project involves creating a recommender system using Apache Spark, specifically focusing on the efficiency of the system and considering Spark's complexity. The dataset for this implementation is provided in the files `movies.csv`.

## 1. Introduction:
- The goal of this project is to implement a distributed recommender system using Apache Spark, focusing on efficiency and addressing Spark's complexity.
- 
## 2. Implementation Steps:

### 2.1. Load Dataset and Import Libraries:
- Loading the dataset "movies.csv" into the Spark environment.
- Importing the required libraries for data manipulation and collaborative filtering.

### 2.2. Collaborative Filtering Recommendation System:
- Implemented a recommendation system using collaborative filtering, a technique that makes automatic predictions about the preferences of a user by collecting preferences from many users.
  
## 3. Data Exploration and Analysis:

### 3.1. Describing the Data:
- Provided a detailed description of the dataset, including its structure, key features, and any other relevant information.
- Calculated the top 20 movies with the highest ratings and the top 15 users who provided the highest ratings. Display both the code and the output.

### 3.2. Train-Test Split:
- Splitting the dataset into training and testing sets using different combinations (e.g., 60/40, 70/30, 75/25, and 80/20).
- Training the collaborative filtering model on 70% of the data and test it on the remaining 30%, repeating the process for each combination.

### 3.3. Evaluation Metrics:
- Evaluate both models using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE), and compared the performance of different train-test split ratios.

## 4. Hyperparameter Tuning:
- Explained the different parameters of the collaborative filtering algorithm chosen for tuning.
- Tuned the parameters of the collaborative filtering algorithm to find the best set of values.
- Evaluated all models again using the tuned parameters.

## 5. Movie Recommendations:
- Calculated the top 15 movie recommendations for user ID 10 and user ID 14 using the collaborative filtering model.
