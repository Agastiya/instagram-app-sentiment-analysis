# Sentiment Analysis on the Instagram Application 

<p align="center"><a href="/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/2048px-Instagram_logo_2016.svg.png" width="200"></a></p>

## Table of Contents

- [Overview](#overview)
- [Data Source](#data-source)
- [Preparing and Installation](#preparing-and-installation)
  - [Preparing Dataset](#preparing-dataset)
  - [Installation](#Installation)
- [References](#references)

## Overview
The aim of this project is to analyze sentiment regarding the use of the Instagram  application to understand people's views and responses. This sentiment analysis process uses machine learning techniques which are carried out using a set of datasets. This project is designed to classify Instagram-related public comments into two categories, namely positive and negative sentiment.

## Data Source
This project uses a dataset sourced from the kaggle.com site, where the dataset contains user data, ratings and comments on Instagram application from Google Playstore. Initial data used in this project amounting to around 3,080,209 data
    
    https://www.kaggle.com/datasets/bwandowando/3-million-instagram-google-store-reviews

## Getting Started
We will prepare this project, starting from getting the dataset, installation, and running the code.

### Preparing Dataset
If you want to get the entire dataset, you can download it from the link below.
    
    https://drive.google.com/file/d/1TA4kfdNGZVA3xDl_cEshSXoYZZQwXGd5/view

If you want to download dataset manually, you can download and get the link from the data source section. After that you can follow this steps :

- Clone this repository.
        
        https://github.com/Agastiya/instagram-app-sentiment-analysis.git

- Create a directory called *dataset*.

        mkdir Dataset

- Extract dataset from download and put the **INSTAGRAM_REVIEWS.csv** into the directory.

### Installation
    pip install -r requirement.txt

After installing all the libraries we need, you can run the block code step by step.

## References
- https://www.kaggle.com/code/ankumagawa/sentimental-analysis-using-naive-bayes-classifier
