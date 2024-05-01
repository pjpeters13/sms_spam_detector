# SMS Spam Detector Project

## Overview
This project implements an SMS Spam Detector using a linear Support Vector Machine (SVM) classifier and Term Frequency-Inverse Document Frequency (TF-IDF) for feature extraction. The model is trained on a dataset of SMS messages labeled as spam or ham (non-spam), aiming to accurately classify incoming messages. We use scikit-learn for machine learning operations and Gradio to create an interactive web interface.

## Features
- **Linear SVM Classifier:** Utilizes a linear SVM model for classification tasks due to its effectiveness in text classification.
- **TF-IDF Vectorization:** Employs TF-IDF to convert text data into a format suitable for the SVM classifier.
- **Gradio Interface:** Provides an easy-to-use web interface where users can input SMS messages and receive instant spam/ham predictions.

# How it Works:

## Data Preprocessing:** SMS messages are cleaned and preprocessed to remove noise.
- **Feature Extraction:** TF-IDF vectorization is applied to transform the text data into numerical features.
- **Model Training:** A linear SVM classifier is trained on the preprocessed and vectorized data.
- **Prediction:** The trained model is used to predict whether new messages are spam or ham.

- ** Used the pipeline
