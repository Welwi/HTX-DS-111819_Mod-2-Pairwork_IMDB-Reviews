# Module 2 Paired Exercise - Classifying IMDB Movie Reviews

## Goal

Goal of this exercise is to use a naive version of Bayes' Theorem to classify IMDB movie reviews as either positive (1) or negative (0).

## Data 

Data sourced from [Kaggle](https://www.kaggle.com/iarunava/imdb-movie-reviews-dataset). Positive reviews gave scores greater than or equal to 7, negative reviews gave scores less than or equal to 4, on a scale of 1-10. For cleaned CSVs provided in this repository, there are no reviews included that gave neutral scores of 5-6.

Code to clean and sample down the CSVs can be found in the `Preparing_CSVs` notebook, which used some code from [this notebook by Praveen Kotha](https://www.kaggle.com/praveenkotha2/end-to-end-text-processing-for-beginners).

Samples for the train and test sets, without duplicates and fairly evenly distributed between positive and negative reviews, are provided in the main directory as `clean_train_sample` and `clean_test_sample`. There are 5000 samples in both the train and the test sample CSVs.