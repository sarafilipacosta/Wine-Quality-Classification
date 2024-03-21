# About Dataset

## Context

The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

*This repository focuses on applying machine learning techniques to a dataset containing information wine quality, provided by the Kaggle website.
https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009*

## Content
For more information, read [Cortez et al., 2009].

Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10)

## Tips

What might be an interesting thing to do, is aside from using regression modelling, is to set an arbitrary cutoff for your dependent variable (wine quality) at e.g. 7 or higher getting classified as 'good/1' and the remainder as 'not good/0'.

# What was done in this project?

In this project, we have implemented basic stat, correlation, information about missing values, visualization as boxplot, histplot, scatterplot. Here we apply the model random Forest, logistic regression, support vector machine, decision tree, K neighbours, and gaussian naive bayes






