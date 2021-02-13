# Machine Learning Homework - Exoplanet Exploration

![Bar Chart](https://github.com/parastoorazavi/machine-learning-challenge/blob/main/image/exoplanets.jpg)

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Resources](#resources)
- [Hints and Considerations](#considerations)
- [Submission](#submission)
- [Report](#report)

## 🧐 About <a name = "about"></a>
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.


In this homework assignment, you will need to:

1. Preprocess the raw data
2. Tune the models
3. Compare two or more models


## 🥶 Getting Started <a name = "getting_started"></a>

### Preprocess the Data: <br>

•	Preprocess the dataset prior to fitting the model.

•	Perform feature selection and remove unnecessary features.

•	Use MinMaxScaler to scale the numerical data.

•	Separate the data into training and testing data.

### Tune Model Parameters: <br>

•	Use GridSearch to tune model parameters.

•	Tune and compare at least two different classifiers.

### Reporting: <br>


•	Create a README that reports a comparison of each model's performance as well as a summary about your findings and any assumptions you can make based on your model (is your model good enough to predict new exoplanets? Why or why not? What would make your model be better at predicting new exoplanets?).


## 🤔Resources: <a name = "resources"></a>

•	Exoplanet Data Source(https://www.kaggle.com/nasa/kepler-exoplanet-search-results)

•	Scikit-Learn Tutorial Part 1(https://www.youtube.com/watch?v=4PXAztQtoTg)

•	Scikit-Learn Tutorial Part 2(https://www.youtube.com/watch?v=gK43gtGh49o&t=5858s)

•	Grid Search(https://scikit-learn.org/stable/modules/grid_search.html)


## 🤩 Hints and Considerations: <a name = "considerations"></a>

•	Start by cleaning the data, removing unnecessary columns, and scaling the data.

•	Not all variables are significant be sure to remove any insignificant variables.

•	Make sure your sklearn package is up to date.

•	Try a simple model first, and then tune the model using GridSearch.

## 😃Submission: <a name = "submission"></a>

•	Create a Jupyter Notebook for each model and host the notebooks on GitHub.

•	Create a file for your best model and push to GitHub

•	Include a README.md file that summarizes your assumptions and findings.

•	Submit the link to your GitHub project to Bootcamp Spot.

## 😃Report: <a name = "report"></a>

For this project I decided to choose these 4 machines learning algorithms:

1.	Decision Trees:

Our Training data score is 1 which means our model is overfit, this is one reason why decision trees tend to overfit, especially on many features or on categorical data with many options. Out testing data score is 0.85. Generally, the accuracy is 88% but I prefer to not use this model which is not perfectly suitable for my dataset.

2.	Random Forest:

In this model, our training and testing data score are in order 0.75 and 0.72 which aren’t high scores but compare decision tree our training score is better and by having 89% accuracy, I prefer to choose this model.

3.	KNN (K- Nearest Neighbors):

I decided to analyze this model in 2 ways, first with ‘err’ columns and second by dropping them the same as other models to see the difference. When we have extra columns in our model, better train/test Scores will be appeared. By keeping ‘err’ columns still I won’t get a good result.

4.	SVM (Support Vector Machine):

This one is the worst one for my dataset, low train and test scores and also just having 60% accuracy, are the reason to put this model out of our competition.
