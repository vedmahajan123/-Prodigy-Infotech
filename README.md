Decision Tree Classifier – Bank Marketing Dataset
📌 Overview

This project uses a Decision Tree Classifier to predict whether a customer will subscribe to a bank term deposit based on their demographic and behavioral data.
The dataset is from the UCI Machine Learning Repository (Bank Marketing dataset).

📂 Dataset

File used: bank-full.csv

Records: 45,211

Features: 16 input attributes (age, job, marital status, education, balance, loan info, etc.)

Target: y → whether the customer subscribed (yes / no)

⚙️ Steps in the Project

Load dataset from CSV.

Preprocess data: Encode categorical variables using Label Encoding.

Split dataset into training (70%) and testing (30%).

Train a Decision Tree using entropy (information gain).

Evaluate model using Accuracy, Confusion Matrix, and Classification Report.

Visualize the tree with decision rules.

📊 Results

Accuracy: ~89%

The model predicts non-subscribers (no) very well.

It struggles with subscribers (yes) due to class imbalance.
