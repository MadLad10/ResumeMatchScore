

# Description

This repository contains a Jupyter Notebook for analyzing and predicting job matching scores based on candidate resumes and job descriptions. The notebook processes and analyzes resume and job description data to extract meaningful insights and predict matching scores. By leveraging natural language processing (NLP) and predictive modeling, the project aims to improve hiring efficiency.
# Purpose

The purpose of this project is to build a model that predicts the likelihood of a candidate being a good match for a job based on textual resume data. This involves:

- Cleaning and preprocessing text data.

- Extracting key features using TF-IDF and Word2Vec embeddings.

- Training machine learning models (XGBoost and LightGBM) for prediction.

- Evaluating model performance using various metrics.

# Work Done

### Data Preprocessing

- Removed unnecessary columns and handled missing values.

- Cleaned text data by removing stopwords, punctuation, and performing lemmatization.

### Feature Extraction

- Utilized TF-IDF for transforming text into numerical features.

- Trained Word2Vec models to capture semantic meanings in text.

###Entity Extraction

- Extracted key skills and job titles using keyword-based matching.

- Used Named Entity Recognition (NER) techniques to identify relevant entities.

###Machine Learning Models

- Trained XGBoost and LightGBM models for predicting job match scores.

- Performed hyperparameter tuning to optimize performance.

### Evaluation

- Used Mean Squared Error (MSE) to measure prediction accuracy.

- Evaluated with Mean Absolute Error (MAE) for error magnitude.

- Assessed model fit using R² Score.
