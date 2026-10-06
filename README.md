# Iris Flower Classification

## Introduction

Iris Flower Classification is a machine learning project developed using Python. The project classifies iris flowers into three different species based on their measurements.

## Objective

The main objective of this project is to use machine learning to predict the species of an iris flower from its physical measurements.

## Dataset

The Iris dataset contains measurements of iris flowers.

The four features are:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The three flower species are:

- Setosa
- Versicolor
- Virginica

## Algorithm Used

K-Nearest Neighbors (KNN) is used for classification.

## Technologies Used

- Python
- Scikit-learn
- Machine Learning

## Working

First, the Iris dataset is loaded using Python. The dataset is divided into training and testing data. The KNN algorithm is trained using the training data. The trained model then predicts the species of iris flowers in the test data.

## Sample Prediction

The model predicts the species of a new iris flower using its sepal and petal measurements.

## Conclusion

This project demonstrates how machine learning can be used to classify iris flowers based on their physical measurements. It provides a simple introduction to supervised machine learning and classification.

## How to Run

Install the required library using:

pip install -r requirements.txt

Then run:

python iris_classification.py
## Results

The K-Nearest Neighbors (KNN) model was trained and tested using the Iris dataset.

The model achieved an accuracy of **100% (1.0)** on the test data.

For the sample input, the model predicted the flower species as **Setosa**.