# :two_hearts: Using Spark for Machine Learning :stuck_out_tongue_winking_eye::dog:

![science and tech](https://media.giphy.com/media/ize2r20ICQONq/giphy.gif)

## Introduction 

In this project, we will use spark to do machine learning. We will use `Amazon Product Review Dataset` as our data and analyze reviews using natural language processing (NLP).

Natural Language Processing is the field of computer science to process languages to be able to extract usable information, extract contexts, etc. NLP is used for various ways, some of them goes like in the following list:

- Speech recognition
- Speech Segmentation
- Automatic Summarization
- Word Sense Disambiguation
- Sentiment Analysis
- Question Answering
- Named Entity Recognition (NER)
- Machine Translation
- Part of Speech Tagging (POS)
- Abbreviation Detection

## About Data  :shipit:

This Dataset is an updated version of the Amazon review dataset released in 2014. As in the previous version, this dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs). In addition, this version provides the following features

The data is maintained by [Jianmo Ni](https://nijianmo.github.io/) and the [Amazon Product Review Data](https://nijianmo.github.io/amazon/index.html) is available after completing the form.

The data is 34 GB, in total of 233.1 million reviews.

The sample of a review is of the following shape.

``` json
{
  "reviewerID": "A2SUAM1J3GNN3B",
  "asin": "0000013714",
  "reviewerName": "J. McDonald",
  "vote": 5,
  "style": {
    "Format:": "Hardcover"
  },
  "reviewText": "I bought this for my husband who plays the piano.  He is having a wonderful time playing these old hymns.  The music  is at times hard to read because we think the book was published for singing from more than playing from.  Great purchase though!",
  "overall": 5.0,
  "summary": "Heavenly Highway Hymns",
  "unixReviewTime": 1252800000,
  "reviewTime": "09 13, 2009"
}
```

**For our purpose**, we are only interested in `reviewText`, `summary`, and `overall` parts of the data. We may use these columns for the project.

Column| Usage
------ | --------
reviewText | Will be the used to derive X.
summary | May be used along with reviews.
overall | It will be used as ground truth for machine learning. Will be used to create y.







## Project Information

For our project, Here will try to do implement NLP on the dataset, in order to do that,we will follow the following machine learning steps:

1. Exploratory Data Analysis (EDA)
2. Data Processing 
3. Implementing Algorithms
4. Validation
5. Testing your Model

### How can I run spark?

As you already know from previous classes, we have multiple options.

1. Google Colab
2. Databricks
3. Spark on Docker on your own computer
4. Installing Spark Locally
5. SPU [Data Science Lab](dsl.saintpeters.edu) (DSL) (Thanks to @SaintPeters)
6. [Apache Zeppelin](https://dsl.saintpeters.edu:8443) Notebooks available in SPU DSL.


### 1. EDA 

In this part, We did the following steps:

1. Prepare graphical representation of `overall`
2. Get the count of most common words
3. Categorize the length of reviews
4. Find the total number of words in the whole dataset
5. Find the total number of characters in the whole dataset
6. Find the total numbers of special characters (punctuations, numbers, etc) over all words

### 2. Data Processing

Second, and the most important part of the project is to apply text processing to the dataset. 

Again,Here are the following list for processing step:

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

In this part, we will create our X and y matrices and apply some algorihms to do NLP tasks. In order to do that,here are the following list :

1. Create [TF-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) matrix.
2. Create [Bag of Words](https://en.wikipedia.org/wiki/Bag-of-words_model) model with Count
3. Create Bag of Words model with Normalized Count
4. Create Doc2Vec representations
3. Create [Word Embeddings](https://en.wikipedia.org/wiki/Word_embedding)




