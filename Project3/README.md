# Project 3: Web APIs & Classification

### Description

In week four we've learned about a few different classifiers. 
In week five we'll learn about webscraping, APIs, and Natural Language Processing (NLP). 
Now we're going to put those skills to the test.

For project 3, your goal is two-fold:
1. Using Reddit's API, you'll collect posts from two subreddits of your choosing.
2. You'll then use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.

Selected Sub-Reddit post : Today I Fucked Up(TIFU)  &   Am I The Asshole(AITA)


### Executive Summary
Reddit is a social news platform that allows users to discuss and vote on content that other users have submitted. There are multiple threads, termed as sub-reddits where people can discuss stuff and post content relevant to the subreddit title. TIFU is a sub-reddit post where people share personal testimonies about how they ruined their day, where AITA is a sub-reddit post where poeple will post their events that may have happened to them to gauge if their actions are deemed as screwed up or not. 

This 2 sub-reddit post have are both contents that people may want to share how screwed up they are, or how they have screwed up by doing some stuffs. There is alot of over-lapping content where reddit-ers may not know which sub-reddit is most appropriate for them to post and share their stories.

This binary classification model will help by evaluating the words used in the content of the post, and is about xx% accurate in recommending the most appropriate sub-reddit post for the user to post at. In this way, this will lessen the sub-reddit moderator's workload, where their job are usually the enforcing the rules and regulation for people that are posting stuffs in the respective threads. 



### Problem Statement
Where to post my stories? 
To help redditors to post their story in the most recommended subreddit thread


### Overview
1) Collecting data by using Reddit's API
2) Cleaning Data
3) Feature Engineering and Preparation of Data
4) Train-Test Split
5) Modelling 
6) Model selection and evaluation 


### Conclusion & Recommendation 
The model is XX % Accurate in recommending the correct sub-reddit thread for the user to post their stories
This model can be further modified with more Subreddits to recommend different Subreddits with similar topics for users to look at and choose from.


---



### Why is this project choosen?
This project covers three of the biggest concepts we cover in the class: Classification Modeling, Natural Language Processing and Data Wrangling/Acquisition.

Part 1 of the project focuses on **Data wrangling/gathering/acquisition**. This is a very important skill as not all the data you will need will be in clean CSVs or a single table in SQL.  There is a good chance that wherever you land you will have to gather some data from some unstructured/semi-structured sources; when possible, requesting information from an API, but often scraping it because they don't have an API (or it's terribly documented).

Part 2 of the project focuses on **Natural Language Processing** and converting standard text data (like Titles and Comments) into a format that allows us to analyze it and use it in modeling.

Part 3 of the project focuses on **Classification Modeling**.  Given that project 2 was a regression focused problem, we needed to give you a classification focused problem to practice the various models, means of assessment and preprocessing associated with classification.   
