# Support Vector Machine (SVM) Classification

This project demonstrates the implementation of a **Support Vector Machine (SVM)** classifier using Python. The notebook walks through the process of training an SVM model on a dataset, visualizing the results, and evaluating the performance using standard metrics.

## Project Overview

The SVM model is used for binary classification based on two features from the dataset. The implementation involves data preprocessing, feature scaling, model training, prediction, and visualization of the decision boundary.

### Key Concepts:

- **Support Vector Machine (SVM):** A powerful supervised learning algorithm used for classification and regression tasks. SVM finds the hyperplane that best separates the data into different classes.
- **Feature Scaling:** Essential for SVM to ensure that each feature contributes equally to the decision boundary.
- **Decision Boundary Visualization:** Visual representation of the classification regions created by the SVM model on both the training and test datasets.

## Dataset

The dataset used contains two features: `Age` and `Estimated Salary`, and the target variable is binary (`Purchased` or not). The SVM classifier is used to predict whether a customer made a purchase based on these features.

## Workflow

### 1. Data Preprocessing

- **Importing Libraries:** Essential libraries such as `numpy`, `pandas`, `matplotlib`, and `sklearn` are imported.
- **Loading the Dataset:** The dataset is read into a pandas DataFrame.
- **Feature Scaling:** Features are scaled using `StandardScaler` to standardize the values for better model performance.

### 2. Training the SVM Model

- The `SVC` class from `sklearn.svm` is used to create the SVM classifier.
- The kernel used is linear (`kernel='linear'`).
- The model is trained on the training dataset using the `fit()` method.

### 3. Making Predictions

- Predictions are made on the test dataset using the `predict()` method.
- A confusion matrix is created to evaluate the performance of the model.

### 4. Visualization

- The decision boundary created by the SVM is visualized using a contour plot.
- Separate visualizations are generated for both the training and test sets.
- The decision regions are color-coded, and the support vectors are highlighted.

## Results

- **Confusion Matrix:** A confusion matrix is used to evaluate the accuracy of the model's predictions. It shows the true positives, true negatives, false positives, and false negatives.
- **Decision Boundary:** The decision boundary clearly separates the two classes (`Purchased` and `Not Purchased`), and the support vectors are displayed in the plot.

## Conclusion
This project demonstrates the implementation of a Support Vector Machine (SVM) for binary classification using Python and sklearn. It includes data preprocessing, model training, prediction, and visualization of the decision boundary. The project also highlights the importance of feature scaling in SVM models for effective classification.
