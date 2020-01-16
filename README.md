# Plagiarism-Detector

## Short Description

Text Plagiarism Detector created for Udacity Machine Learning Engineer Nanodegree.

## Aim

This project aims to build a plagiarism detector that examines an answer text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided, source text.

## Steps

The process can be broken down into a few discrete steps:

*Clean and pre-process the data.
*Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
*Select "good" features, by analyzing the correlations between different features.
*Create train/test .csv files that hold the relevant features and class labels for train/test data points.


## Libraries

The libraries required for this project are:

*Numpy
*Panda
*Scikit-learn
*boto3
*sagemaker


## Note

This project is built on Udacity Plagiarism Detector's initial code, as provided in this repository: 

https://github.com/udacity/ML_SageMaker_Studies

