# Fake News Classification Project

## Overview
This project aims to tackle the challenging issue of fake news, a significant problem in today's digital age where misinformation can spread rapidly. By applying machine learning techniques, we've developed a model capable of classifying news articles as "fake" or "real" based on their content. This repository contains all the resources and code used throughout the project from exploratory data analysis (EDA) to model deployment using Streamlit.

## Dataset
The dataset consists of various news articles, each labeled as either 'fake' or 'real'. The data was split into training and testing sets to evaluate the model's performance accurately.

### Exploratory Data Analysis (EDA)
- Initial analysis of the dataset to understand the distribution of fake and real news.
- Visualization of word frequencies and other relevant statistics.

## Text Preprocessing
To prepare the text data for modeling, we applied several preprocessing steps, including:
- Lowercasing the text
- Removing URLs and special characters
- Tokenizing the text
- Removing stopwords
- Applying lemmatization

## Feature Extraction using LDA
Latent Dirichlet Allocation (LDA) was used for feature extraction to identify latent topics within the text, which served as features for the classification model.

## Model Training with PyCaret
We utilized PyCaret, an open-source ML library, to train and evaluate multiple models. LightGBM emerged as the best performing model based on our evaluation criteria.

## Advanced Text Classification with RoBERTa
We also explored advanced text classification using the RoBERTa transformer model, which provided significant insights into the capabilities of transformers in NLP tasks.

## Deployment
The final model was deployed as a web application using Streamlit, allowing users to input news text and receive a prediction on whether the news is likely to be fake or real.

## Usage
Instructions on how to run the Streamlit application locally and interact with the deployed model.
