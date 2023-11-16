# twittersentimentanalysis

This project is a good starting point for those who have little or no experience with Kafka & Apache Spark Streaming.

![image](https://user-images.githubusercontent.com/57892314/153753329-a49ef16f-37c5-43fd-8d24-312ae4c59803.png)

Input data: Live tweets with a keyword
Main model: Data preprocessing and apply sentiment analysis on the tweets
Output: Text with all the tweets and their sentiment analysis scores (polarity and subjectivity)

We use Python version 3.7.9 and Spark version 3.2.1 and Kafka 3.1.0.

## Part 1: Ingest Data using Kafka 

This part is about sending tweets from Twitter API. 


## Part 2: Tweet preprocessing and sentiment analysis
In this part, we receive tweets from Kafka and preprocess them with the pyspark library which is python's API for spark. We then apply sentiment analysis using textblob; A python's library for processing textual Data. 
After sentiment analysis, we write the sentiment analysis scores in the console. We have also the possibility to store in a parquet file, which is a data storage format.
