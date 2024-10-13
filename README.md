# Custom-NER-Assignment-on-Health-Care-Data
**Problem statement:** This repository contains a machine learning project that focuses on building a custom Named Entity Recognition (NER) model to identify Diseases and Treatments from medical text data. The objective is to extract all predicted treatments corresponding to diseases using a Conditional Random Fields (CRF) model.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
The dataset contains 2599 sentences for training and 1056 sentences for testing. The objective of this assignment is to build a custom NER model on this data sentence to identify the disease and thier treatment patterns. The dataset consists of medical text, where:

Each word is represented on a separate line.
Sentences are separated by blank lines.
Labels include:

- O (Other)

- D (Disease)

- T (Treatment)

The provided dataset includes:

- `train_sent`: Training sentences.

- `train_label`: Labels corresponding to the training sentences.

- `test_sent`: Test sentences.

- `test_label`: Labels corresponding to the test sentences.

## Technologies Used
- spacy
- sklearn_crfsuite
- pandas

## Conclusions
After building the model the f1-score on train and test set are as follows:

- f1 score of train data: 0.9471

- f1 score of test data: 0.9165

## Contact
Created by [@shootingStar10](https://github.com/shootingStar10) - feel free to contact me!
