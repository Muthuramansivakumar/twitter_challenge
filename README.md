# EdgeTier-ML-Challenge

Welcome to the EdgeTier machine learning and data science code challenge!

You are required to read the challenge below, and submit a Jupyter notebook (or similar) with your analysis and output in answer to each part of the challenge.

# Challenge

SomeAnalytics Company are a fictional company who specialise in analysing, and classifying social media data related to a particular topic and sell insights on to businesses who may be interested.

You have been hired by SomeAnalytics to analyse 500,000 tweets related to ChatGPT between January and March 2023 and help them with the following three asks they are seeing demand for among their clients:

### Key Players and hashtags

SomeCompany want you to identify who are the most 10 mentioned Twitter accounts in the dataset and what are the 20 most used hashtags in the dataset.

The output here should visualise the top handles and hashtag by the number and % of tweets they appear in.

### Technical issues detection

A core part of SomeCompany's product offering is the training of custom models to detect sub-topics in social media data relating to a particular topic.

To get started, SomeCompany want to train a model to detect when people on twitter mention general technical issues related to ChatGPT. The issues people mention can vary and include (but are not limited to) issues such as:

- Login issues
- Timeouts when using ChatGPT
- Blank pages

Your job is to train a binary classifier capable of analysing a tweet related to ChatGPT and determining if it is related to a general technical issue or not.

### Recommendations for additional topics

In addition to the ask in part 2, SomeCompany are interested in training additional models on this data in the future. Before they do this however, they want to get an idea of what are the 3 most common things users speak about when tweeting about ChatGPT.

To achieve this you should perform some analysis on the content of each tweet (or a subset of them) and identify the 3 largest meaningful topics SomeCompany could go after next and roughly what % of the data these topics.

# The dataset

The dataset supplied for this task is based on the ["500k ChatGPT-related Tweets Jan-Mar 2023" Kaggle dataset](https://www.kaggle.com/datasets/khalidryder777/500k-chatgpt-tweets-jan-mar-2023?resource=download) and can be found in `gpt_mentions.zip`. The data contains the following columns:

- *Date*: The date and time when the tweet was posted.
- *ID*: A unique identifier for each tweet.
- *Content*: The text content of the tweet including any mentions or hashtags.

# Submission

Please submit your code along with a presentation of your results with some discussion on your approach to each task as a **private** git repository that we can clone.

Please note that there is a vast number of messages in this dataset, if processing time becomes an issue, feel free to use a subset of the data to reduce the time required.