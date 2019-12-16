## Classifying NBA Games Based on Team Stat Lines

I looked at NBA Team Stats for every game from the 2014-15 season through the 2017-18 season to see if it was possible to classify a game as a win or loss based on one team's final stat line. 

## Contributor 
 -Christopher Shaw ([github](https://github.com/JackBurton11/))

## Background
This was our first solo project at the Flatiron School (NYC Data Science)

## Project Purpose and Description
 - The goal of this project was to work with real world datasets and experiment with different types of classification models(Logistic Regression, K Nearest Neighbors, Decision Trees, Random Forests, Support Vextor Machines).
 
## Python Tools:
   - pandas
   - sklearn
   - Seaborn/Matplotlib
   - SciPy/NumPy
   - statsmodels
   - XGBoost
   - pydotplus

## Process
I experimented with several different models after separating the data into training and test sets to see which model could best classify the Team Stats data. The Dataset had 41 columns and 9840 rows prior to data cleaning and feature selection. I ended up with 14 features, all continuous with the exception of Home or Away.

## Conclusion
After the model experiments and extensive feature selection, I found the best results with SVM and Logistic Regression as they performed comparably to the training set.
