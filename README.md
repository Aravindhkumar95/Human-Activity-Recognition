# Human-Activity-Recognition
## Objective

In this project will try to predicts the human activity such as (1-Walking, 2-Walking upstairs, 3-Walking downstairs, 4-Sitting, 5-Standing or 6-Laying). This data collected by the sensors which embedded in smartphone to detect the human activities and sensors were used to collect data from 30 different people performing a set of activities. But the accuracy of prediction though is questionable. Thus, a multi classification model that could determine the accuracy of this prediction.

## Dataset

A single Dataset splitted into 5 parts of Dataset (X_train, X_test, y_train, y_test, features) downloaded from analyticsvidhya used in this project. Link to access the datasets - https://www.analyticsvidhya.com/blog/2018/05/24-ultimate-data-science-projects-to-boost-your-knowledge-and-skills/

A datasets has 10,299 rows, there are 561 different variables and one target variable that holds the activity performed. 

## Modelling

Three different classification algorithm were used to analyse and predict the Human Activity. 
  1. Naive Bayes Classifier
  2. Random Forest Classifier
  3. Support Vector Machine

### Naive Bayes Classifier

Naive bayes Classifier is based on Bayes Therom. It works fast and accurate when the dataset is huge and provides high accuracy. Naive Bayes works by assuming that features in a class is independant of the other features. Thus called Naive.

### Random Forest Classifier

Random Forest is nothing but comprised of Decision trees. It can be used for both Classification and Regression problems.If the decision trees in random forest is more than the quality of forest will be robost. The trees are generated based on random selected data samples, once the tree constructed, it will get the predicted result from each tree and choose the most popular class as the final result.

### Support Vector Machine


