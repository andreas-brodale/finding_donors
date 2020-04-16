Intro to machine learning nanodegree
## Supervised Learning
## Project: Finding donors for "CharityML".
#Aim:
Identification of suitable donors for a charity organization based on data of US census

In this project, I employed several supervised algorithms to accurately model individuals' income using data collected from the 1994 U.S. Census. I chose the best candidate algorithm from preliminary results and further optimize this algorithm to best model the data. The goal with this implementation is to construct a model that accurately predicts whether an individual makes more than $50,000. This sort of task can arise in a non-profit setting, where organizations survive on donations. Understanding an individual's income can help a non-profit better understand how large of a donation to request, or whether or not they should reach out to begin with.  

The dataset for this project originates from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Census+Income). The datset was donated by Ron Kohavi and Barry Becker, after being published in the article _\"Scaling Up the Accuracy of Naive-Bayes Classifiers: A Decision-Tree Hybrid\"_. The data I investigate here consists of small changes to the original dataset, such as removing the `'fnlwgt'` feature and records with missing or ill-formatted entries.
 
