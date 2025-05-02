# task6
Step 1: Understand the Problem

Goal: Use the K-Nearest Neighbors (KNN) algorithm to classify data points (predict categories).

Dataset: Use the Iris dataset, which contains features of 3 types of flowers: setosa, versicolor, virginica.

Step 2: Load and Explore the Dataset

Load the Iris dataset using a data analysis tool like Pandas or directly using Scikit-learn.

The dataset has:

Features: sepal length, sepal width, petal length, petal width

Target/Labels: flower species

Step 3: Normalize the Features

Why? KNN uses distance to classify. If features have different scales (e.g., one is 0–1 and another is 0–100), results will be biased.

How? Use normalization techniques like StandardScaler to bring all features to a similar scale (mean 0, variance 1).

Step 4: Split the Data

Split the dataset into:

Training set: used to train the model (usually 70–80%)

Test set: used to test the model's performance (remaining 20–30%)

Step 5: Train the KNN Model

Use KNeighborsClassifier from scikit-learn.

Set a value for K (number of neighbors), such as K=3, K=5, etc.

Fit the model using the training data.

Step 6: Make Predictions

Use the trained model to predict the labels (species) for the test set.

These are the model’s guesses based on the nearest neighbors in training data.

Step 7: Evaluate the Model

Use metrics to check how well the model performed:

Accuracy: how many predictions were correct.

Confusion Matrix: shows true vs predicted labels.

Classification Report: includes precision, recall, F1-score.

Step 8: Choose the Best K

Repeat the training and testing steps for multiple K values (e.g., from 1 to 20).

Plot K vs Accuracy to find the value of K that gives the highest accuracy.

Step 9: Visualize the Decision Boundary

Choose 2 features (like petal length & petal width).

Plot the decision regions that show how the model classifies the input space.

Use color to show boundaries and classes.

Step 10: Finalize and Submit

Choose the best model (best K).

Save your code, results, and graphs.

Upload everything to a GitHub repo.

Submit the repo link using the provided Google Form.

