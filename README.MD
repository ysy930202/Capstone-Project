# Data Scientist Nanodegree

## Project: Capstone Project

## Table of Contents

- [Project Overview](#overview)
- [Conclusion](#Conclusion)
- [Credits and Acknowledgements](#credits)

***

<a id='overview'></a>

## 1. Project Overview

Credit default is important for credit card bank to manage users. In this project, I use a dataset detailing personal and payment information of credit card owners to predict whether someone will default in the future. The dataset is from a foreign bank that experiences a high level of credit card defaults.

The goal of this project is to use a dataset detailing personal and payment information of credit card owners to predict whether someone will default in the future. I explored the dataset and applied 4 different models to build a binary classifier in Python.

In this report, I first describe the dataset, how I preprocess and analyze it. Then, I use hyperparameter optimization to configure the best model from logistic regression, decision tree, neural network, and random forest. At the end, I test the results by 70/30 training/validation split.


<a id='Conclusion'></a>

## 2. Conclusion

Up to now, we have already got the best models. Obviously, the random forest performs best in Python on the validation data, except a lower specificity. As we have discussed before, what we care most in this problem is the recall rate, so that we can choose the model that is able to find as many potential default behaviors as possible. 

<a id='credits'></a>

## 3. Credits and Acknowledgements

Thanks tutor taught me skills regarding data science and providing such a cool project to practice my skills. Appreciate all the teaching and help!


