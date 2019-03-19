# Project Submission for COMPSCIX433.3-007 Python for Data Analysis and Scientific Computing

Project Name: Wine classification using custom PCA

Group Members: Sushil Garg, Aparna Vaidya, Sravani Gunti

Platform Used: Jupyter Notebook

Python Version: 3.7

Packages Used: Numpy, Scipy, Matplotlib, Pandas, Scikit-learn

Dataset Used: Wine dataset from kaggle [here](https://www.kaggle.com/akram24/wine-pca). 

Additional Instructions: Copy wine.csv file to your current working directory and run the notebook.

Final presentation slides [here](https://docs.google.com/presentation/d/1OM2gzzMCiYebUFN3bcFwzm9gp22KTKnbA6_UEK_4HyE/edit#slide=id.p).

## Overview of the project

We applied PCA to select the optimal number of component automatically based on explained variance. We did PCA using just numpy and scipy libraries instead of using any in-built class. Result was then comapred to sklearn's inbuilt PCA class. 

Then we built multiple machine learning models for classification of wine class. Different ML models are used - 

1. Logistic Regression
2. Linear Discriminant Analysis
3. K-Nearest Neighbors
4. Decision Tree Classifier
5. Gaussian Naive Bayes
6. Support Vector Machines

All above 6 models were applied on both original dataset (without PCA) and transformed dataset (with PCA) and results were compared. 



