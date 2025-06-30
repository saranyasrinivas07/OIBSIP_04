# OIBSIP Project 4 – Spam Detection

This repository contains my submission for Project 4 of the Oasis Infobyte Data Science Internship.

## Objective

To build a machine learning model that classifies text messages as spam or not spam using natural language processing and machine learning techniques.

## Tools and Libraries Used

- Python
- Pandas
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Import and Exploration
- Loaded the SMS spam dataset using Pandas
- Explored data structure, summary statistics, and class distributions

### 2. Data Preprocessing
- Balanced the dataset for spam and ham messages
- Converted text labels into numeric values

### 3. Text Vectorization
- Transformed text messages into numerical vectors using TF-IDF

### 4. Model Training
- Split data into training and testing sets
- Trained a Random Forest Classifier

### 5. Model Evaluation
- Evaluated model using accuracy score, classification report, and confusion matrix
- Achieved ~98% accuracy on test data

### 6. Visualization
- Plotted a heatmap of the confusion matrix

### 7. Predicting New Messages
- Developed a function to predict whether a new message is spam, with confidence level

## Model Performance

- Accuracy: ~98% on test data
- High precision and recall for detecting spam messages

## Status

Task Completed

## Author

Saranya Srinivas
