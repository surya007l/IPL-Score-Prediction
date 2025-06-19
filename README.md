# IPL-Score-Prediction

This project predicts the final score of an IPL (Indian Premier League) innings based on the current match state using a machine learning model. It provides an interactive interface with ipywidgets for user-friendly inputs and uses a trained regression model to estimate the score.

🎯 Features
Predicts total runs in an IPL match innings based on live match parameters.

Interactive form using ipywidgets to input:

Venue

Batting team

Bowling team

Striker and bowler

Current runs, wickets, overs, and striker index

Scikit-learn model training and preprocessing

Supports use in both Jupyter Notebook and Google Colab

🧠 Machine Learning Model
Model Type: Linear Regression / Random Forest (configurable)

Input Features:

Encoded teams and players

Match venue

Current stats: runs, wickets, overs

Striker index (optional)

Output: Predicted total innings score (integer)

