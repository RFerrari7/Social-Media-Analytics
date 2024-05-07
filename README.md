# Social Media Analytics project on r/marvelstudios subreddit: Community and Content Analysis after the release of 'Avengers: Endgame'

This repository contains a project developed as part of *Social Media Analytics* course of the [Master's degree in Data Science](https://www.unimib.it/graduate/data-science),
University of Milano Bicocca.

## Description

This project aims to analyze the interactions within the r/marvelstudios subreddit, from the popular social media platform *Reddit*, focusing on the discussion of 'Avengers: Endgame', one of the most popular films in the Marvel Cinematic Universe (MCU). With the objective of identifying relationships, influential users, sentiments, and communities, the research employs three main tools:

* **Social Network Analysis**: it is the process of investigating social structures through the use of network and graph theory, that can capture the dynamic interactions between   commenters and post authors.
* **Sentiment Analysis**: it involves understanding the sentiment of the users about a certain topic through the analysis of the comments' polarity, which can be *positive*, *neutral* and *negative*.
* **Topic Modeling**: topic modeling is an unsupervised Machine Learning technique that automatically identifies and extracts significant topics from a set of documents. By leveraging this technique, it's possibile to determine the optimal way to categorize various comments based on their main topic.

The project’s structure comprehends data collection and exploration, social network analysis, sentiment analysis, and topic modeling. The approach is centered on understanding dynamics within an online community engaged in passionate discussions on a popular topic like 'Avengers: Endgame'.

## Repository structure

This repository is structured as follows:

```
.
├── Presentation.pdf                             # slides presenting the results obtained
├── README.md
├── Report.pdf                                   # detailed project report
├── data                                        # data used for the analysis
│   ├── avengers.csv                             # just the raw dataset extracted from Reddit
│   ├── avengers_pre.csv                         # dataset resulting from preprocessing.ipynb
│   ├── avengers_sentiment.csv                   # dataset containing the results from the sentiment analysis
│   └── topic_terms.json                         # obtained from topic_modeling.ipnyb and necessary to compute the WordClouds
└── source code                                 # folder containing the notebooks
    ├── 1.data_extraction.ipynb                  # data extraction from reddit using praw
    ├── 2.preprocessing.ipynb                    # preprocessing phase
    ├── 3.exploratory_data_analysis.ipynb        # exploratory operations with plots
    ├── 4.sentiment_analysis.ipynb               # sentiment analysis on the comments using VADER, with preprocessed dataset
    ├── 5.topic_modeling.ipynb                   # LDA + results 
    └── 6.WordCloud_for_topic_modeling.ipynb     # WordClouds corresponding to the topics obtained through topic modeling
```

All packages and libraries are loaded at the beginning of the notebooks. In case they are not already installed, they can be installed using the standard procedure.








