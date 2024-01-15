![a](https://api.groupdocs.app/conversion/v1/download?folderName=d28af398-665d-4c5f-ae7e-7079fa0e9f06&fileName=finallinkedin.png)
# SentimentInsight: Analyzing Public Perceptions of COVID-19 Vaccination through NLP

## Overview

This project aims to analyze sentiment in tweets related to the COVID-19 vaccine. By employing Natural Language Processing (NLP) techniques, we explore the sentiments expressed in the text data, categorizing them as positive, negative, or neutral. The sentiment analysis is conducted using the VADER sentiment analysis tool.

## Data

We utilized a dataset of tweets related to COVID-19 vaccination. The dataset includes information such as tweet text and date of posting.

## Preprocessing

To prepare the text data for sentiment analysis, several preprocessing steps were undertaken:

- Lowercasing: All text converted to lowercase.
- Removal of Twitter Handlers: Twitter handles (@username) were removed.
- Removal of Hashtags: Hashtags were excluded from the text.
- Removal of URLs: Any URLs present in the text were eliminated.
- Removal of Special Characters: Special characters were removed from the text.
- Removal of Single Characters: Single characters not forming meaningful words were removed.
- Consolidation of Spaces: Multiple spaces were replaced with a single space.

## Sentiment Analysis

The sentiment analysis was conducted using the VADER sentiment analysis tool, which provides polarity scores for each sentiment (positive, neutral, negative). We further engineered features such as Positive Sentiment, Neutral Sentiment, and Negative Sentiment based on these scores.

## Exploratory Data Analysis (EDA)

EDA was performed to understand the distribution and cumulative distribution of sentiments across the dataset. Kernel Density Estimation (KDE) plots and Cumulative Density Function (CDF) plots were employed for visualization.

## Sorting and Feature Engineering

The data was sorted by date, and additional time-related features such as year, month, day, day of the year, quarter, and season were engineered for further analysis.

## Visualizing Positive and Negative Sentiments

We identified the most positive and negative sentiments based on our analysis. Word clouds were generated to visually represent common words in the most positive and negative tweets.

## Top Words Analysis

We further analyzed the most common words in the most positive and negative tweets, excluding stopwords. Word clouds for the top 10 words in each category were generated.

## Conclusion

This project provides insights into the sentiments expressed in COVID-19 vaccine-related tweets. The analysis can be valuable for understanding public sentiment and perceptions surrounding the vaccine on social media platforms.

