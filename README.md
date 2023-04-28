# Yelp-Data-Analysis

With trusted local business information, photos and reviews, Yelp provides a one-stop platform for consumers to discover local businesses. For business owners, it’s a critical marketing platform to generate buzz. A business thrives when they receive high user ratings, high number of reviews, and positive reviews, to name a few. 


#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to use Yelp data to model and predict the types of restaurants that are likely to succeed based on their business and review attributes.


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


### Technologies
* AWS
* Scikit-Learn
* Pyspark

## Project Description

## Getting Started

### 1. Set up AWS

Steps to Set up AWS

Reference: Getting Started with AWS Doc

Summary of Steps from Doc Above:

Go to AWS Academy Learner Lab
Click Start Lab
When AWS light (upper left corner) is green, click on it
Now we are on AWS Main Page:

Select Cloud Formation
Selete Create Stack (w/ new resources - standard)
S3 link is: https://penn-cis545-files.s3.amazonaws.com/emr-course.yml
Next. Stack Name is: CIS545-1
Iterate stack name each time you do this (so can increae # at end)
For the Parameters related to Amazon EMR Cluster Configuration, drop down the VpcId, VPC Public SubNet, and EC2 Key Pair and choose the first item in the list
Livy Proxy Credentials - fill out your own password. Can use 545GroupMCIT as Pass if you want.
Keep hitting next and click create stack.
Stack is set up. Will take a while to run, and then will see "CREATE_COMPLETE".
Go to Outputs, and copy the URL there.
Past in the URL and password you set below.
when done working: Click END LAB on Learner Lab. Otherwise $$$.
[One-time for Entire Team] Create S3 Bucket w/ Data

Select S3 (from Storage Services)
Click create bucket. Name it 545-project. Create it.
Go to Google Drive, and download the yelp_dataset. If not already downloaded locally.
It will download as zip and may download in multiple files. Unzip on your computer and combine into one folder. Delete the PDF file.
Upload folder to S3 Bucket
Make S3 bucket public (and files within it). Also add Canonical user ID of teammates to Access Control List for read/write privileges.
3. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)

## References
* [Yelp Dataset Documentation](https://www.yelp.com/dataset/documentation/main)
