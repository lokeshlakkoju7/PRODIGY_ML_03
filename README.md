# PRODIGY_ML_03
# Cat vs Dog Image Classification using SVM

This project implements a Support Vector Machine (SVM) model to classify images of cats and dogs.

The main goal is to build an image classification system that can distinguish between cat and dog images using machine learning techniques.

## Dataset

The dataset used in this project is the Dogs vs Cats dataset from Kaggle.

It contains:

- Cat images
- Dog images
- Labeled training data for classification

The dataset is widely used for image classification tasks and beginner computer vision projects. :contentReference[oaicite:0]{index=0}

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Load the dataset
2. Resize all images to a fixed size
3. Convert images into numerical arrays
4. Flatten image data into feature vectors
5. Split the dataset into training and testing sets
6. Train the SVM model
7. Predict image labels
8. Evaluate model accuracy

## Model Used

This project uses the Support Vector Machine (SVM) algorithm for image classification.

SVM works by finding the optimal decision boundary that separates different classes.

:contentReference[oaicite:1]{index=1}

Where:

- \( w \) = Weight vector  
- \( x \) = Input feature vector  
- \( b \) = Bias term  

For classification, SVM tries to maximize the margin between the two classes.

## Features

- Binary classification of cat and dog images
- Image preprocessing using resizing and flattening
- Model training using Scikit-learn
- Accuracy evaluation on test data
- Easy-to-understand workflow for beginners

## Results

The model predicts whether an image belongs to a cat or a dog.

Performance can be evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report

A higher accuracy score indicates better classification performance.

## How to Run

1. Clone the repository

```bash
git clone https://github.com/lokeshlakkoju7/PRODIGY_ML_03.git
