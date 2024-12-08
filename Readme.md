# **IPL Winning Probability Predictor**

This project uses supervised machine learning algorithms to build a model that predicts which IPL team has a higher probability of winning a match. Although the Random Forest algorithm achieved a high accuracy of 99%, Logistic Regression was selected as the final model due to its practical applicability in real-world scenarios. Models with overly perfect results, such as 99% accuracy, often indicate overfitting or unrealistic predictions.

## **Features:**
***The model predicts the probable winning team using the various features from the dataset:***
* City: The city where the match is being played.
* Batting Team: The team currently batting in the match.
* Bowling Team: The team currently bowling in the match.
* Current Run Rate: The rate at which the batting team is scoring runs per over.
* Required Run Rate: The rate at which the batting team needs to score runs per over to win.
* Other match-related features (e.g., match details, weather conditions, etc.)

***Machine Learning Algorithms Used:***
* Random Forest
* K-Nearest Neighbors (KNN) Classification
* Decision Tree
* Gradient Boost Classifier
* Logistic Regression
* AdaBoost Classifier
* Voting Classifier

## **Key Findings:**
* Best Accuracy Achieved: Random Forest Algorithm (99% accuracy)
* Selected Model: Logistic Regression, chosen for its simplicity and relevance in practical applications.

## **Dataset:**
* You can access the dataset used for this project from the following link: https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set
