# SVM Classification and Grid Search Optimization for Iris Prediction

## Project Overview
This project uses Support Vector Machine (SVM) classification and Grid Search optimization to predict the species of Iris flowers based on their physical characteristics. The dataset contains measurements for various flower attributes, such as sepal length, sepal width, petal length, and petal width. By applying an SVM model, the goal is to classify the flowers into one of three species: Setosa, Versicolor, and Virginica. Grid Search is used to fine-tune the hyperparameters of the SVM model to achieve the best classification performance.

## Methods
 - Data Exploration: The Iris dataset is initially explored using visual tools like pair plots and histograms to understand the distribution of features and their relationships with the target variable (species). These visualizations help in identifying patterns and the separability of the species based on the given attributes.

 - Feature Selection: All four features (sepal length, sepal width, petal length, and petal width) are used for classification as they are highly relevant to distinguishing between the three Iris species. The dataset is split into features (X) and target (y) variables for model training.

 - Model Training: A Support Vector Machine (SVM) classifier is trained on the dataset to learn the relationship between the features and the Iris species. Grid Search is applied to optimize the SVM model by testing different values for hyperparameters like C and gamma to find the best configuration for accuracy.

 - Model Evaluation: The model’s performance is evaluated using classification metrics such as accuracy, precision, recall, F1-score, and a confusion matrix. These metrics help in assessing how well the model distinguishes between the different Iris species and its ability to predict the correct species for unseen data.


