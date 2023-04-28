# Yelp-Data-Analysis
With trusted local business information, photos and reviews, Yelp provides a one-stop platform for consumers to discover local businesses. For business owners, it’s a critical marketing platform to generate buzz. A business thrives when they receive high user ratings, high number of reviews, and positive reviews, to name a few. 

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to use Yelp data to model and predict if overall rating of the business are affected by certain predictors like the length of the review texts they received, price range of the items they sell, whether they are good for groups or kids, accept credit cards, have take-outs, happy-hour outdoor seatings. 

The predictor columns are:
```"review_count", "price_range", "good_for_groups", "accepts_credit_card", "has_take_out", "has_outdoor_seating", "good_for_kids", "has_reservations", "has_happy_hour", "review_length"```

### Partner
* Matt Ordway, Phong Le, Lin Price

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
gist: conducted modeling to test ~~~ 


## Getting Started

1. Set up AWS following the instructions in the notebook.

3. Raw Data is being kept [here](https://drive.google.com/drive/folders/1B9sT11g-F-R3ifkLe9rloA4phKzbAO8Z?usp=share_link) through Google Drive.
    
3. Data processing/transformation/EDA/Modeling/Evaluation scripts are being kept in the [NB](https://colab.research.google.com/drive/1uBpqYS_SEux-N97jmCCxvRGMIm-mNctm?usp=share_link)

## Disclaimer
This project utilizes data of ~450MB size. Naturally, it takes a while to execute the codes. We recommend using the finished copy as the true source of information. If you need to run the code, please note that code blocks that utilize extensive memories, such as Random Forests, Hyperparameter Tuning, and Deep Learning might take a few hours. These sections are marked with astericks in the notebook.

## Featured Notebooks/Analysis/Deliverables
* [Google Colab Notebook](https://colab.research.google.com/drive/1uBpqYS_SEux-N97jmCCxvRGMIm-mNctm?usp=share_link)

## References
* [Yelp Dataset Documentation](https://www.yelp.com/dataset/documentation/main)
