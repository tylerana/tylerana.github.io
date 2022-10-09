
# Project Description

The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. Using a dataset of IMDB moview reviews with polarity labeling, train a model to automatically detect negative reviews. The model will need to have an F1 score of at least 0.85.
## Table of Contents:

1. Initialization
2. Load Data
3. Exploratory Data Analysis
4. Evaluation Procedure
5. Normalization
6. Train/ Test Split
7. Reviews
8. Conclusion



## Data
* review: the review text
* pos: the target, `0` for negative and `1` for positive
* ds_part: `train`/`test` for the train/test part of the dataset

## Goal:
Train a model to automatically detect negative movie reviews. 

## Libraries Used:
tensorflow, sklearn, matplotlib, seabron, tqdm, lightgbm, nltk, spacy