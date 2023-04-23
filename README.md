# song-analysis

## About

Song Analysis Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on songs and tracks from a database that was retrieve by the Spotify API. Please view the source code in order from:

1. [Data Extraction](https://github.com/De-Zato/song-analysis/blob/main/data-extraction.ipynb)
2. [Data Visualisation](https://github.com/De-Zato/song-analysis/blob/main/data-visualisation.ipynb)
3. [Machine Learning Models](https://github.com/De-Zato/song-analysis/blob/main/MachineLearningModels.ipynb)

## Contributors
- @De-Zato - Data Extraction, Data Visualisation
- @YashJain14 - Machine Learning Models, README

## Problem Definition
- Are we able to predict if a song/track will be popular based on its attributs?
- Which model would be the best to show and predict it?

## Models Used
- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors Classifier
- Decision Tree Classifier
- Linear Support Vector Classification
- XGBoos

## Conclusion
- After analyzing the numerical and categorical data in the dataset, we can conclude that there exists a non-linear relationship between the numerical features and the popularity of songs. This suggests that the relationship between these features and popularity may not be straightforward and may require more complex models to accurately predict popularity.
On the other hand, the categorical features such as key and mode appear to have similar relationships with popularity, indicating that they may not have a significant impact on predicting song popularity.
However, our analysis does suggest that songs released in later years and songs with explicit language tend to be more popular among listeners.

- We can conclude that the Random Forest Classifier is the best fit for predicting the popularity of songs. The Random Forest Classifier is able to model complex interactions between different features, which is important given the non-linear relationships between the features and popularity in this dataset. Furthermore, the Random Forest Classifier achieved the highest accuracy of 78% and AUC of 64.2% among the evaluated machine learning models. The AUC value indicates that the Random Forest Classifier has good performance in distinguishing between positive and negative classes in the binary classification problem.

## What we learned
Throughout the data science project, we learned a number of important skills and techniques related to understanding the data, cleaning and preprocessing the data, and selecting and evaluating machine learning models.

We learned how to thoroughly explore and understand the data, including its structure, features, and distributions. This involved using various visualization and exploratory data analysis techniques to gain insights into the relationships between different features and the target variable.

Next, we learned how to select and evaluate the performance of various machine learning models, including logistic regression, random forest classifier, K-nearest neighbors classifier, decision tree classifier, linear support vector classification, and XGBoost. We used performance metrics such as accuracy, and ROC AUC to compare the performance of these models and select the best fit for the problem at hand.

## References
Dataset: https://www.kaggle.com/datasets/yamaerenay/spotify-dataset-19212020-600k-tracks
