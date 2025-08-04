# IRIS-flower-prediction
my first machine learning model

This project demonstrates a simple machine learning classification task using the famous Iris flower dataset. It uses the K-Nearest Neighbors (KNN) algorithm from the scikit-learn library to classify the flowers into one of three species based on their sepal and petal measurements.

Description
The Iris dataset contains 150 samples of iris flowers, with four features measured for each sample: sepal length, sepal width, petal length, and petal width. The goal of this project is to build a model that can accurately predict the species of a new iris flower based on these four features.

The project follows a standard machine learning workflow:

Data Loading: The Iris dataset is loaded directly from scikit-learn.

Data Splitting: The data is split into training and testing sets to evaluate the model's performance on unseen data.

Model Training: A K-Nearest Neighbors classifier is instantiated and trained on the training data.

Prediction: The trained model is used to make predictions on the test data.

Evaluation: The model's accuracy is calculated to see how well it performed.

Technologies Used
Python: The core programming language for the project.

scikit-learn: A popular machine learning library in Python used for the dataset, model, and metrics.

NumPy: A fundamental package for numerical computation in Python, used by scikit-learn.

Installation
To run this project, you need to have Python and the necessary libraries installed. You can install scikit-learn which includes the other dependencies, using pip.

pip install scikit-learn

Usage
You can run the Python script to see the model in action. The script will load the data, train the model, make predictions, and print the model's accuracy score.

To run the script, save the code provided as a Python file (e.g., iris_classifier.py) and execute it from your terminal:

python iris_classifier.py

The output will be the accuracy score of the model on the test data.

Code
You can find the complete, runnable Python code for this project in the repository. It is designed to be straightforward and easy to understand for beginners.
