# Sentiment-Analysis-of-IMDB-Movie-Reviews-
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)
  * [Importing the data and taking a first look at it.](#Importing-the-data-and-taking-a-first-look-at-it)
  * [Exploratory Data Analysis.](#Exploratory-Data-Analysis)
  * [Splitting the dataset.](#Splitting-the-dataset)
  * [Text Normalization.](#Text-Normalization)





## Problem Statement:
In this, we have to predict the number of positive and negative reviews based on sentiments by using different classification models.

![image](https://user-images.githubusercontent.com/55452866/89191685-ec1d4600-d5c0-11ea-94be-de8793258b00.png)

## Approach:

### Importing the data and taking a first look at it:
The dataset has two columns review and sentiment.There are 50000 reveiws.

### Exploratory Data Analysis:
The positive and negative sentiment are equal in count.

![image](https://user-images.githubusercontent.com/55452866/89194735-5fc15200-d5c5-11ea-8a28-7e9a8463fcc0.png)

### Splitting the dataset:
The dataset is divided into 80:20 ratio 80% is for training the model and 20% is for testing our model.

![image](https://user-images.githubusercontent.com/55452866/89196336-b596f980-d5c7-11ea-94d6-7c067644dd54.png)


### Text Normalization:
Here I am initiating tokenizer for tokenization and setting English stopwords. 


