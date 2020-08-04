# Sentiment-Analysis-of-IMDB-Movie-Reviews-
## Table of Contents
* [Problem Statement](#Problem-Statement)
* [Approach](#Approach)
 * [Data Preprocessing](#Data-Preprocessing)
   * [Importing the data and taking a first look at it.](#Importing-the-data-and-taking-a-first-look-at-it)
   * [Exploratory Data Analysis.](#Exploratory-Data-Analysis)
   * [Splitting the dataset.](#Splitting-the-dataset)
   * [Text Normalization.](#Text-Normalization)
   * [Removing html strips and noise text.](#Removing-html-strips-and-noise-text)
   * [Removing special characters.](#Removing-special-characters)
   * [Removing Stopwords.](#Removing-Stopwords)
   * [Normalizing the Train and Test data.](#Normalizing-the-Train-and-Test-data)
   * [Bag of Words.](#Bag-of-Words)
   * [TFIDF.](#TFIDF)





## Problem Statement:
In this, we have to predict the number of positive and negative reviews based on sentiments by using different classification models.

![image](https://user-images.githubusercontent.com/55452866/89191685-ec1d4600-d5c0-11ea-94be-de8793258b00.png)

## Approach:

## Data Preprocessing:
In this section I am doing all the Data cleaning and analysis.

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

### Removing html strips and noise text:
By using Beautiful soup I am removing the url and I am removing some noising text by defining a function which will remoe the noise.

### Removing special characters:
While going through the data i find out that it contains some special characters which i thought which was not important so I removed those special characters.

### Removing Stopwords:
There are words in the reviews which does not give us the sentiment of the sentence hence they are useless for us hence I removed that. 

### Normalizing the Train and Test data:
Here I am normalizing the train and test data.

### Bag of Words:
It is used to convert text documents to numerical vectors or bag of words.

![image](https://user-images.githubusercontent.com/55452866/89327711-ef403100-d6a9-11ea-9488-9772f7c5b418.png)

### TFIDF:
It is used to convert text documents to matrix of tfidf features.


