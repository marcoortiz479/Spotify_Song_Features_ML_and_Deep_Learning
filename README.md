# Spotify_Song_Features_ML_and_Deep_Learning


---

## Project Overview
This project predicts Spotify track popularity (0–100) using audio features provided by Spotify.
It combines exploratory data analysis (EDA), classical machine learning, ensemble methods, and deep learning, all wrapped inside a fully interactive Streamlit web application.

Users can:
- Explore the dataset visually
- Train and compare multiple models
- Perform hyperparameter tuning
- Generate predictions for new tracks
- Interpret model behavior using SHAP explainability

---

##🎯 Objectives

- Understand which audio features influence track popularity
- Compare traditional ML models vs deep learning
- Build a production-style Streamlit app
- Practice model tuning, evaluation, and explainability
- Deploy a reproducible ML application to Streamlit Cloud

---

## 📂 Project Structure
- `spotify_song_features.py`
- `spotify_songs.csv`
- `requirements.txt`

---

## 📊 Dataset & Features

The dataset includes Spotify audio features such as:
- `danceability`
- `energy`
- `loudness`
- `speechiness`
- `acousticness`
- `instrumentalness`
- `liveness`
- `valence`
- `tempo`
- `duration_ms`

🎯 Target Variable:
`track_popularity` (0–100)

Data cleaning steps include:
- Removing duplicates
- Handling missing values
- Feature selection via Streamlit UI

---

##🔍 Exploratory Data Analysis (EDA)

Inside the app, users can:

* Visualize popularity distributions
* Inspect feature correlations via heatmaps
* Create interactive scatter plots with OLS trendlines
* View summary statistics dynamically

📈 EDA is optional and toggleable to improve app performance.

---

## 🧠 Models Implemented
Baseline & Linear Models

Linear Regression

Ridge Regression

Lasso Regression

Tree-Based & Ensemble Models

Random Forest

Extra Trees

Gradient Boosting

AdaBoost

Distance & Kernel Methods

K-Nearest Neighbors (KNN)

Support Vector Regression (SVR)

Deep Learning

Fully connected Neural Network (TensorFlow/Keras)

Standardization + Early Stopping

Optional (Auto-Detected)

XGBoost

LightGBM

CatBoost

Optional models are safely handled with try/except to avoid breaking deployment.
