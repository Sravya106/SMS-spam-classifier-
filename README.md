# SMS-spam-classifier-
Model to classify spam and not spam messages. Naïve Beyer's Model. 

- [Spam Classification](#spam-classification)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Features](#features)
  - [Getting Started](#getting-started)
  - [Data Pre-processing](#data-pre-processing)
  - [Visualizations](#visualizations)
  - [Model Building](#model-building)
  - [Model Analysis and Improvements](#model-analysis-and-improvements)


## About

The Spam Classification project aims to build a machine learning model for accurately classifying emails as spam or non-spam. This project is motivated by the need to enhance email filtering systems and reduce the impact of unwanted communication.

## Features

- Machine learning-based spam classification
- Data cleaning and preprocessing techniques
- Visualizations to better understand the dataset
- Model analysis and techniques for improvement
- Best performance model with precision value of 1

## Getting Started
Importing the libraries and choosing a dataset 

## Data Pre-processing
Cleaning text data involves removing the words that are used to form a sentence(eg: is, am, of etc). You can also perform one hot encoding or Label encoding on data at this point. Libraries such as nltk(natural language tool kit) are handy while making these changes on text data.

## Data Visualizations
Visualizing data can provide ud useful insight on data. In this case we observe that spam messages usually thve higher number of charecters used in them. Aslo extracting the most used words and other visualizations would be useful to have as well.

## Model Building
Naive Bayers models are known for their comparitively highrt performance with textual data. As we are us sure about the data distributtions at this point comparing all the models would be preferable.

## Model Evaluation and Improvements
Hyperparameter tuning or Fine tuning hels us determining best parameters for our model. Confusion Matrics and the precision and accuracy values are taken into consideration for selection the best model. In this case precision is the key value for determining best model.


