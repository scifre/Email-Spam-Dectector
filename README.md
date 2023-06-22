# Spam Email Detection with TensorFlow

This repository contains code for a spam email detection project using TensorFlow. The project demonstrates how to build a sequential model in TensorFlow to classify emails as spam or non-spam based on their text content.

## Dataset

The dataset used for training and testing the model is not included in this repository. However, you can download the dataset from [link_to_dataset] and place it in the `data` directory.

The dataset contains two columns:
- `text`: The text content of the emails.
- `spam`: A binary label indicating whether the email is spam (1) or non-spam (0).

## Files

The repository includes the following Python files:

- `spamdetector.ipynb`: The main script for training and evaluating the spam email detection model. It loads the dataset, preprocesses the text data, builds the sequential model, and trains the model using TensorFlow.

- `model_tester.ipynb`: A module containing functions for testing the model.

## Usage

1. Download all the files and place them in the same directory.

2. Install the required dependencies by running `pip install -r requirements.txt`.

3. Run the `spamdetector.ipynb` script to train and evaluate the model:
