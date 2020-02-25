# :trophy: Using Spark for Machine Learning :trophy:
## Topic Modelling LDA ##

![science and tech](https://media.giphy.com/media/ize2r20ICQONq/giphy.gif)

## Introduction 

In this project, we are using spark to do machine learning. Our dataset is  `Amazon Product Review Dataset` and analyze reviews using natural language processing (NLP).Here we are using  algorithm "Topic Modeling " is a type of statistical modeling for discovering the abstract “topics” that occur in a collection of documents. Latent Dirichlet Allocation (LDA) is an example of topic model and is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.


## About Data  :shipit:

We are using dataset `Amazon's Magazine Subscription` and here is the link of dataset http://deepyeti.ucsd.edu/jianmo/amazon/index.html.


## Instructions For Running the Project:

For our project, Here we are trying to implement NLP on the dataset, in order to do that,we will follow the following machine learning steps:

1. Exploratory Data Analysis (EDA)
2. Data Processing 
3. Implementing Algorithms(Topic Modelling LDA)
4. Validation
5. Testing your Model

### How can I run spark?

For running the Spark here is the list of options:

1. Google Colab
2. Databricks
3. Spark on Docker on your own computer
4. Install Spark Locally


### 1. EDA 

In this part, We did the following steps:

1. Prepare graphical representation of `overall`
2. Get the count of most common words
3. Categorize the length of reviews
4. Find the total number of words in the whole dataset
5. Find the total number of characters in the whole dataset
6. Find the total numbers of special characters (punctuations, numbers, etc) over all words

### 2. Data Processing

Data Processing is the most important part of the project is to apply text processing to the dataset. 

Here are the following list for processing step:

1. Removing punctations.
2. Lowercasing words
3. Removing stopwords
4. Lemmatization
5. Stemming
6. Removing top n% and lowest n% most used words from dataset
7. Correcting spelling for words
8. Tokenizing review into sentences
9. Tokenizing review into words
10. Removing short words (len(word) > n)

### 3. Machine Learning





