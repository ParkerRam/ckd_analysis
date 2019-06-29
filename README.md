# CKD Analysis
Term project for DSCI 100 at UBC. Data wrangling, EDA and classification exercise on the [UCI Chronic Kidney Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Chronic_Kidney_Disease#). It was found that hemoglobin, packed cell volume, red blood cell count, Diabetes mellitus, hypertension, albumin, and specific gravity are all strong predictors, these were confirmed through EDA and recursive feature elimination. A simple KNN model used to perfectly classify our test set using only the above predictors, however the dataset is rather small and these results may be misleading.

# What I learned
* Basics of tidyverse and caret
* Proper EDA and model fitting work flow
* Utilising cross-validation while fitting models

