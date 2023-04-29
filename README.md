# Yelp-Data-Analysis
#### -- Project Status: [Completed]

## Project Intro & Objective
With trusted local business information, photos and reviews, Yelp provides a one-stop platform for consumers to discover local businesses. For business owners, it’s a critical marketing platform to generate buzz. A business thrives when they receive high user ratings, high number of reviews, and positive reviews, to name a few. The purpose of this project is to use Yelp data to model and predict if overall rating of the business are affected by certain restaurant features like the price range of the items, accept credit cards, have take-outs, happy-hour, and outdoor seatings, etc.


### Partners
* Matt Ordway
* Phong Le
* Lin Price

### Methods Used
* Inferential Statistics
* Data Visualization
* Unsupervised Machine Learning: K-Clusters and PCA
* Supervised Machine Learning: Linear Regression, Logistic Regression, Decision Tree, and Random Forests
* Regularization
* Hyperparameter tuning
* Machine Learning Model Evaluation - Accuracy, Precision, Recall, Confusion Matrix, and ROC curve [AUC]
* Deep Learning - FNN


### Technologies
* Scikit-Learn
* Pyspark
* TensorFlow

## Project Description
We have 5 JSON files from [Yelp](https://www.yelp.com/dataset/documentation/main) representing users, businesses, reviews, checkins, and tips (~ short reviews). We will clean the files we care about and merge them into a master dataset as the basis to conduct our analysis and build machine learning models. 

We will first explore the data more to make sure it's of high quality, run sentiment analysis, examine the impact of COVID on restaurant reviews, and more. Any additional features needed for data will be engineered into the master dataset, using one-hot encoding technqiue. 

Next, we run several machine learning models, both unsupervised and supervised. First we will use k-means clustering to further understand trends in the data. Then we will run a variety of models to determine what is most accurate in predicting the review rating. They include: linear regression, logistic regression, FNN, decision tree, and random forest with hyperparameter tuning.

The predictor columns we use to build the model are:
```"review_count", "price_range", "good_for_groups", "accepts_credit_card", "has_take_out", "has_outdoor_seating", "good_for_kids", "has_reservations", "has_happy_hour", "review_length", "avg_monthly_checkins"```

In the same section, we will implement model evaluation using accuracy, precision, and recall metrics as well as confusion matrix with heatmap. 

## Getting Started

1. Our team leveraged Google Drive to store the Yelp dataset; stored in the yelp_dataset folder of a folder called [545_Group_Project](https://drive.google.com/drive/folders/1B9sT11g-F-R3ifkLe9rloA4phKzbAO8Z?usp=share_link). Should you not be able to access this link, download the dataset from [Yelp](https://www.yelp.com/dataset/documentation/main), and add it into a folder on your Drive called 545_Group_Project.

2. All imports and additional steps to follow are in our Google Colab Notebook #1 [here](https://colab.research.google.com/drive/1uBpqYS_SEux-N97jmCCxvRGMIm-mNctm?usp=share_link).

## Disclaimer
This project utilizes starting data of close to 10GB (in JSON files), thought we pare it down for our final models. Naturally, it can take a while to execute the code. We recommend using the finished (fully executed) notebooks linked below as the true source of information. 

In order to decrease the run-time, we have separated the code into two notebooks (NBs). NB#1 does all the data transformations, and then writes the final dataframe back to our yelp_dataset folder on Drive. NB#2 reads that dataframe back into memory, and then runs all the machine learning models. We realized this at the tail end of the project - likely since there is less stored in RAM, models like k-means clustering decreased from 7 hours to minutes.

## Featured Notebooks/Analysis/Deliverables
* [Google Colab Notebook #1 - Data Preprocessing, EDA](https://colab.research.google.com/drive/1uBpqYS_SEux-N97jmCCxvRGMIm-mNctm?usp=share_link)
* [Google Colab Notebook #2 - Modeling, Evaluation, Summary](https://colab.research.google.com/drive/1ipUpndrpZrtwiM0MhA5tnBkuYdrpPNNm?usp=sharing)

## References
* [Yelp Dataset Documentation](https://www.yelp.com/dataset/documentation/main)
