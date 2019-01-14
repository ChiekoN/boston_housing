# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

## Project Overview
In this project, I apply basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. I first explore the data to obtain important features and descriptive statistics about the dataset. Next, I properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. Then I analyze performance graphs for a learning algorithm with varying parameters and training set sizes. This enables me to pick the optimal model that best generalizes for unseen data. Finally, I test this optimal model on a new sample and compare the predicted selling price to my statistics.

## Goal
The aim of this project is being used to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Analyzing and interpreting the performance of my model is always necessary to use many of the avalable algorithms in the sklearn library.

Things I learn in this project:

- How to use NumPy to investigate the latent features of a dataset.
- How to analyze various learning performance plots for variance and bias.
- How to determine the best-guess model for predictions from unseen data.
- How to evaluate a model's performance on unseen data using previous data.


## Description
The Boston housing market is highly competitive, and I want to be the best real estate agent in the area. To compete with my peers, I decide to leverage a few basic machine learning concepts to assist me and a client with finding the best selling price for their home. Luckily, I've come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. My task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for my clients' homes.


### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included.


### Run

In a terminal or command window, go to this repositry, and run the following command:

```bash
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes
