# Exoplanet_Exploration_Machine_Learning

![](Images/exoplanets.jpg)

## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

Machine learning models were created to classify candidate exoplanets from the raw dataset.

## Models
-Logistic Regression (LR)
-Random Forest Classifier (RF)
-SVM

## Design Approach
- Build a base model using the original dataset 
- Use the base model to evaluate feature importance, filter the data to include relevant features only.
- A second model (select features model) using the filtered data.
- Tune the model parameters using GridSearch.
- final model using the tuned parameters.

## Findings

- SVM, With a linear kernal, obtained a testing accuracy of 88.9 %. few different kernals were attempted but best amongst them was the Linear Model
- with LR 88.1 % accuracy was achieved
- with RFC 89.3 % accuracy was seen so the this model was the best amongst the three tried for priction of exoplanet candidacy.

## next steps to try
- model with deep learning techniques might prove better


