# News Recommender

## Overview
This repository contains the python code for a News Recommender that recommends news stories based on user personal history. The recommendations are based on the pair-wise 
Euclidean distance between the TFID vectors of news titles in the dataset and a one from the reading history of the user. 

## Dataset
UCI News aggregator uci-news-aggregator.csv having 422,937 news stories collected by a web aggregator between March 10th, 2014 and August 10th, 2014. 
The dataset is available on Kaggle at https://www.kaggle.com/datasets/uciml/news-aggregator-dataset

## Requirements
If running in a local environment, the following command can be used to install the required packages:

pip install -r requirements.txt


## Sections
This repository is divided into the following sections:

- Load Data and perform EDA
- Perform Natural Language Processing
- Vectorize using TFID Vectorizer
- Define Recommender
- Test Recommender
