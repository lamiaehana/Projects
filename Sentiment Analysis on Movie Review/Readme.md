# Sentiment Analysis on Movie Review
## Team: Lamiae HANA
![feedback](https://user-images.githubusercontent.com/36892795/98424010-b2148200-2090-11eb-9bde-a88f1e253cea.jpg)
## Problem Statement
Movie reviews are an important way to gauge the performance of a movie. While providing a numerical/stars rating to a movie tells us about the success or failure of a movie quantitatively, a collection of movie reviews is what gives us a deeper qualitative insight on different aspects of the movie. A textual movie review tells us about the the strong and weak points of the movie and deeper analysis of a movie review can tell us if the movie in general meets the expectations of the reviewer.
## Significance of the Problem Statement 
Sentiment Analysis[1] is a major subject in machine learning which aims to extract subjective information from the textual reviews. The field of sentiment of analysis is closely tied to natural language processing and text mining. It can be used to determine the attitude of the reviewer with respect to various topics or the overall polarity of review. Using sentiment analysis, we can find the state of mind of the reviewer while providing the review and understand if the person was “happy”, “sad”, “angry” and so on. In this project we aim to use Sentiment Analysis on a set of movie reviews given by reviewers and try to understand what their overall reaction to the movie was, i.e. if they liked the movie or they hated it. We aim to utilize the relationships of the words in the review to predict the overall polarity of the review.

We were eager to try out our own hands with Sentiment Analysis On Movie Review using machine learning.
 
## Project Implementation 
The purpose of this project was for the model to be able to predict the stock price for the next trading day. We have implemented the project in two ways: MS Azure ML implementation in Microsoft Azure ML Studio (Classic) and  Python implementation in Jupyter notebook.

### Dataset
We used dataset from Kaggle : - [Daily News for Stock Market Prediction](https://www.kaggle.com/aaron7sun/stocknews)

### Technologies 
Kaggle, Microsoft Azure ML Studio (Classic), Jupyter Notebook, PyTorch, GitHub

#### Model Architecture
We applied eight regression models: Bayesian linear regression, decision forest regression, boosted decision tree regression, fast forest quantile regression, neural network regression, ordinal regression and Poisson regression. We compared the output for each. See Figure 1. 

#### Model Training
We split the dataset 80% for training, and 20% for testing with the dates column. 

#### Model Metrics
We used RMSE with Bayes Linear Regression and Linear Regression gave the lowest RMSE.
