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
* AWS
* Scikit-Learn
* Pyspark
* TensorFlow

## Project Description
We have 5 JSON files from [Yelp](https://www.yelp.com/dataset/documentation/main) representing users, businesses, reviews, checkins, and tips (~ short reviews). We will clean the files we care about and merge them into a master dataset as the basis to conduct our analysis and build machine learning models. 

We will first explore the data more to make sure it's of high quality, run sentiment analysis, examine the impact of COVID on restaurant reviews, and more. Any additional features needed for data will be engineered into the master dataset, using one-hot encoding technqiue. 

Next, we run several machine learning models, both unsupervised and supervised. First we will use k-means clustering to further understand trends in the data. Then we will run a variety of models to determine what is most accurate in predicting the review rating. They include: linear regression, logistic regression, FNN, decision tree, and random forest with hyperparameter tuning.

The predictor columns we use to build the model are:
```"review_count", "price_range", "good_for_groups", "accepts_credit_card", "has_take_out", "has_outdoor_seating", "good_for_kids", "has_reservations", "has_happy_hour", "review_length", "avg_monthly_checkins"```

In the same section, we will implement model evaluation using accuracy, precision, and recall metrics and also confusion matrix with heatmap. 

Lastly, we will implement feedforward deep learning model to test and see if it improves overall accuracy of the model. 

## Getting Started

1. Set up AWS following the instructions in the notebook.

3. Raw Data is being kept [here](https://drive.google.com/drive/folders/1B9sT11g-F-R3ifkLe9rloA4phKzbAO8Z?usp=share_link) through Google Drive.
    
3. Data processing/transformation/EDA/Modeling/Evaluation scripts are being kept in the [NB](https://colab.research.google.com/drive/1uBpqYS_SEux-N97jmCCxvRGMIm-mNctm?usp=share_link)

## Disclaimer
This project utilizes data of ~450MB size. Naturally, it takes a while to execute the codes. We recommend using the finished copy as the true source of information. If you need to run the code, please note that code blocks that utilize extensive memories, such as Random Forests, Hyperparameter Tuning, and Deep Learning might take a few hours. These sections are marked with astericks in the notebook.

## Featured Notebooks/Analysis/Deliverables
* [Google Colab Notebook #1 - data preprocessing, eda](https://colab.research.google.com/drive/1uBpqYS_SEux-N97jmCCxvRGMIm-mNctm?usp=share_link)
* [Google Colab Notebook #2 - modeling, evaluation, summary](https://colab.research.google.com/drive/1ipUpndrpZrtwiM0MhA5tnBkuYdrpPNNm?usp=sharing)

## References
* [Yelp Dataset Documentation](https://www.yelp.com/dataset/documentation/main)
