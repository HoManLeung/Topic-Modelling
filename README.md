#  Topic Modeling LDA Using Spark for Machine Learning 




## Introduction 

In this project, we are using spark to do machine learning. Our dataset is  `Amazon Product Review Dataset` and analyze reviews using natural language processing (NLP).Here we are using  algorithm "Topic Modeling " is a type of statistical modeling for discovering the abstract “topics” that occur in a collection of documents. Latent Dirichlet Allocation (LDA) is an example of topic model and is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.


## About Data 

We used Amazon raw review dataset that was 34gb in zipped format and 120gb otherwise. We did EDA, DataProcessing along with Count vectorizer(files in Topic modeling folder) on that data but after that as data is too big and we were performing analysis on personal computer it stopped working when we tried to fit model. We thought to proceed with department's Datascience lab but we only have access on Tuesdays. Therefore we choose Amazon Magazine_Subscription data to proceed with.
`Amazon's Magazine Subscription dataset's online link is here http://deepyeti.ucsd.edu/jianmo/amazon/index.html.

## Topic Modeling:

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





