# Predicting Political Ideology of Twitter Users

## Problem Statement

Given a text (single/multiple documents), figuring out the political ideology of the person to which the text belongs to.

**Dataset**: Social Network Data - Twitter

## Methodology

● This would be a supervised classification problem. We aim to classify active user and not so active user who supports one or another political ideology.
● First, we’ll extract the dataset from Twitter to form the initial seed data set (which we can filter out in later steps).
● The dataset is cleaned by removing the stopwords and lower-casing the tweet text.
● Naive Bayes, MaxEnt and Decision Tree are used for classification.

## Dataset

We acquired data from the author Lyle Ungar and received the Twitter IDs of the users which were annotated in the range
of (1-7).

As of now, I have collected the data from the given Twitter ids by them and from the Twitter Lists which we had seen that
day (MBFC - Media Bias / Fact Check Twitter Lists).

A brief overview of the data:

● 3130 Tweet ID objects from the Lyle Ungar Team- Annotated 1-7.
● 368 Left Leaning and 164 Right Leaning Tweet ID objects.
● Most of the Tweet IDs from the Lyle Ungar team are by actual users as such whereas the Tweet IDs from the MBFC lists are of influencers as in the newspaper press, news website or so.

## Results

Used a tool called MALLET for the data cleansing and classification task.

![alt text](https://github.com/shrebox/Political-Ideology-Detection-on-Twitter/blob/master/images/binary_new.png?raw=true)

<!-- ![alt text](https://github.com/shrebox/Political-Ideology-Detection-on-Twitter/blob/master/images/senti_multi.png?raw=true) -->

## References

1. Predicting the Political Alignment of Twitter Users(20111) - https://ieeexplore.ieee.org/document/6113114
2. Ideology Detection for Twitter Users with Heterogeneous Types of Links(2016) - https://arxiv.org/abs/1612.08207
3. Beyond Binary Labels: Political Ideology Prediction of Twitter Users(2017) - https://aclanthology.coli.uni-saarland.de/papers/P17-1068/p17-1068, Slides - http://anthology.aclweb.org/attachments/P/P17/P17-1068.Presentation.pdf
