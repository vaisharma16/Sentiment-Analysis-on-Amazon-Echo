# Sentiment-Analysis-on-Amazon-Echo

Summary of End-to-End NLP Sentiment Analysis Project
## Objective:

Build a sentiment analysis model to analyze Amazon Alexa reviews.

## Data Exploration:

* Analyzed review ratings, feedback, variation, and length.
* Identified that feedback values represent positive or negative sentiments.
* Explored the distribution of ratings, variation, and feedback.
  
## Preprocessing and Model Building:

* Preprocessed reviews using stemming, stop word removal and count vectorization.
* Built Random Forest, XGBoost, and Decision Tree models.
* Evaluated models using cross-validation and hyperparameter tuning.
* Selected XGBoost model based on its higher training and testing accuracies.

## Flask Application:

* Created a Flask application using HTML and CSS for the front end.
* Integrated the XGBoost model into the application.
* Enabled users to input text or upload a CSV file for sentiment analysis.
* Displayed predictions and a graph showing the distribution of positive and negative reviews.

## Key Points:

* End-to-end NLP project, covering data exploration, model building, and deployment.
* Demonstrates the use of NLP techniques in sentiment analysis.
* Employs XGBoost model for accurate predictions.
* Includes a user-friendly Flask application for practical use.
