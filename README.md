# priyanka-midterm-m04

### Midterm Project: Classification Analysis

Submission:
 GitHub Repository :https://github.com/Priyankanaskar/priyanka-midterm-m04

 Jupyter Notebook :classification-priya.ipynb
 
 Date :4/4/25

### Introduction:

This project aims to classify mushrooms as edible or poisonous based on various features using machine learning classification algorithms. We explore multiple models, including Logistic Regression and Random Forest, and evaluate their performance using various metrics such as accuracy, precision, recall, and F1-score.:

### Overview
The primary goal of this project is to predict whether a mushroom is edible or poisonous based on its attributes. The dataset includes various features like color, size, and habitat, which are used to classify mushrooms.

I use Logistic Regression and Random Forest classifiers to train the models and assess their performance. The models' results are compared based on accuracy, precision, recall, F1-score, and other metrics to determine the most effective model for this task.

#### Data set:

Mashroom Data set(keggle)

The dataset used in this project is a mushroom classification dataset, which contains features describing the physical characteristics of mushrooms, such as:

### Assignment Requirements:

To run this project, you'll need to have the following Python libraries installed:

pandas

numpy

scikit-learn

matplotlib

seaborn

##### You can install the required libraries using pip:

``
pip install pandas numpy scikit-learn matplotlib seaborn
``
##### Section 1. Installation

Clone the repository to your local machine:

git clone https://github.com/yourusername/mushroom-classification.git


#### Navigate to the project directory:
``
cd mushroom-classification
``

### Model Implementation

Logistic Regression:

Logistic Regression was used as the first model to predict whether a mushroom is edible or poisonous. We tuned the hyperparameters like C, max_iter, and solver to improve convergence. Although Logistic Regression had a good performance, the model struggled with convergence for certain configurations.

Random Forest:

The Random Forest classifier was implemented as an alternative model. It performed better due to its ability to handle complex, non-linear relationships in the data. Hyperparameters like n_estimators, max_depth, and min_samples_split were tuned to optimize the model and avoid overfitting.

Performance Metrics:
I evaluated both models using the following performance metrics:

Accuracy: 
The percentage of correctly predicted mushrooms (edible/poisonous).

Precision:
 The ratio of true positive predictions to all positive predictions.

Recall: 
The ratio of true positive predictions to all actual positives.

F1-score: 
The harmonic mean of precision and recall.

Model Comparison:

Model	Accuracy	Precision	Recall	F1-score
Logistic Regression	95.28%	0.95	0.95	0.95
Random Forest	98.56%	0.98	0.99	0.98

#### Challenges

Data Scaling: Logistic Regression had convergence warnings due to unscaled data. This required normalization and adjusting the number of iterations.

Hyperparameter Tuning: Finding the optimal parameters for both models took significant time. Random Forest required careful tuning to avoid overfitting.

Model Selection: Deciding between classifiers and understanding how their strengths and weaknesses apply to the dataset was challenging.

#### Reflection
The project provided an opportunity to compare the performance of different classifiers and understand their underlying mechanics. The Random Forest classifier outperformed Logistic Regression, but both models provided high accuracy and precision.

#### Future Work
If more time were available, the following improvements could be made:

Experiment with additional models, such as Gradient Boosting or XGBoost.

Explore feature engineering to generate new features or transform existing ones.

Implement cross-validation to improve model evaluation and performance.

Further fine-tune the hyperparameters of Random Forest and Logistic Regression to see if performance can be improved.