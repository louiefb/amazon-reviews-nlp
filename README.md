# amazon-reviews-nlp
Classifying Amazon reviews based on customer ratings using NLP

Louie Balderrama<br>
Springboard Data Science Career Track, January 2019 cohort<br>
<h1 align="center">Capstone Project II</h1>

**Problem Statement**: Classifying Amazon reviews based on customer ratings using NLP

<h4 align="center">Impact</h4>

Reviews provide objective feedback to a product and are therefore inherently useful for consumers. These ratings are often summarized by a numerical rating, or the number of stars. Of course there is more value in the actual text itself than the quantified stars. And at times, the given rating does not truly convey the experience of the product – the heart of the feedback is actually in the text itself. The goal therefore is to build a classifier that would understand the essence of a piece of review and assign it the most appropriate rating based on the meaning of the text.

<h4 align="center">Background</h4>

Though product ratings on Amazon are aggregated from all the reviews by every customer, each individual rating is actually only an integer that ranges from one star to five stars. This reduces our predictions to discrete classes totaling five possibilities. Therefore what we'll have is a supervised, multi-class classifier with the actual review text as the core predictor.

This study is an exploration of Natural Language Processing (NLP). The goal of predicting the star rating given a piece of text will take on different NLP topics including word embedding, topic modeling, and dimension reduction. From there, we'll arrive at a final dataframe and we'll be employing different machine learning techniques in order to come up with the best approach (i.e. most accurate estimator) for our classifier.

<h4 align="center" id="Datasets">Datasets</h4>

The [Amazon dataset](http://jmcauley.ucsd.edu/data/amazon/index.html) contains the customer reviews for all listed *Electronics* products spanning from May 1996 up to July 2014. There are a total of 1,689,188 reviews by a total of 192,403 customers on 63,001 unique products. The data dictionary is as follows:

*  **asin** - Unique ID of the product being reviewed, *string*
*  **helpful** - A list with two elements: the number of users that voted *helpful*, and the total number of users that voted on the review (including the *not helpful* votes), *list*
*  **overall** - The reviewer's rating of the product, *int64*
*  **reviewText** - The review text itself, *string*
*  **reviewerID** - Unique ID of the reviewer, *string*
*  **reviewerName** - Specified name of the reviewer, *string*
*  **summary** - Headline summary of the review, *string*
*  **unixReviewTime** - Unix Time of when the review was posted, *string*

<h4 align="center">Reports</h4>

**a. Amazon Reviews NLP**

This is the Jupyter notebook that contains the entire study along with the source code. The dataset is too large to upload for the free LFS but the code references the link to the original dataset.

**b. Capstone Project II - Final Report**

This is the condensed presentation slides that summarizes the whole study in slides.

**c. Capstone Project II - Milestone Report 1**

This is the interim report submitted prior to applying actual machine learning techniques. This includes:
1. Data Wrangling
 - NLP Pre-Processing
 - Tokenization
 - Phrase Modeling
 - Count-based Feature Engineering
 - Word Embedding for Feature Engineering
 - Final Dataframe
 - Principal Component Analysis
2. Exploratory Data Analysis
 - More on Word2Vec
 - Named Entity Recognition
 - Dependency Tree
 - Topic Modeling

**d.  Capstone Project II - Milestone Report 2**

The is the report that includes the Machine Learning and the Conclusion sections.
