# Sentiment-Classification-Amazon-Food-Reviews
## Natural Language Processing(NLP)
### Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews
## About Project
#### This Case Study focuses on sentiment classification of Amazon Food Reviews.
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
Number of reviews: 568,454 Number of users: 256,059 Number of products: 74,258 Timespan: Oct 1999 - Oct 2012 Number of Attributes/Columns in data: 10

Attribute Information:

1.  Index
2.  Id
3.  ProductId - unique identifier for the product
4.  UserId - unqiue identifier for the user
5.  ProfileName
6.  HelpfulnessNumerator - number of users who found the review helpful
7.  HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
8.  Score - rating between 1 and 5
9.  Time - timestamp for the review
10. Summary - brief summary of the review
11. Text - text of the review
12. ProcessedText - Cleaned & Preprocessed Text of the review
## Flow of Project
We have applied almost all of the possible Machine Learning Algorithms in the classfication of polarity of Reviews. We have also applied T-SNE which is a dimensionality reduction algorithm to visualize our data from higher dimension into 2-D.
Since, a review is nothing but a sequence of characters and we know that LSTM process sequence information very well so we have also used LSTM which is a deep learning technique and as expected, we got the best accuracy on LSTM among all the algorithms that we have tried.
All of the algorithms are segregated in separate files, so it is easy to find different algorithms in separate files.
## How to Run the Project
Just download the data from the above mentioned source then run "1_DataCleaning_TextPreprocessing_AmazonFoodReviews.ipynb" in the folder "T-SNE_Amazon_Food_Reviews". This files will do the cleaning and initial pre-processing of all of the reviews and create a new database altogether. Save this new database with the name "FinalAmazonFoodReviewsDataset.sqlite". Then simply run any algorithm file you want.
## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
* Python 3
* Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
* XGBoost
## Installing
* Python 3: https://www.python.org/downloads/
* Anaconda: https://www.anaconda.com/download/
* XGBoost: conda install -c conda-forge xgboost
## Authors
Gaurav Sharma - Complete work
## Acknowledgments
Applied AI Course
