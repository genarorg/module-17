# Predict if a person will subscribe to a term deposit.

The following is a data analysis and modeling of the "Bank Marketing"
dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

The dataset contains information about a bank's marketing campaign to 
promote term deposits. The goal is to predict if a person will subscribe.

The detailed Notebook can be found here:
[Main](main.ipynb)

## Findings

From the exploratory analysis, we found the following:
* Older customers tend to subscribe more.
* Older customers take less calls before they agree to subscribe.

## Modeling

The following models were tested:

* Logistic Regression
* Decision Tree
* KNNeighbors

Of these models, the Logistic Regression model performed the best, achieving a higher recall score.
