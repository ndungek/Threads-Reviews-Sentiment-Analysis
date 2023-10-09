# **Threads-Reviews-Sentiment-Analysis**
-----
## Introduction
In the fast-paced world of social media and messaging apps, Threads emerged as a new contender, gaining popularity since its launch in July. As it navigates its way through the ever-changing landscape, we embarked on a journey to analyze the sentiments of Threads app users through an extensive sentiment analysis project.

This repository contains the code and resources for the Threads Reviews Sentiment Analysis project. Our goal is to predict sentiment – whether it's positive, negative, or neutral.

## Project Overview
In this project, we performed the following tasks:

* Imported necessary libraries and tools for data analysis and natural language processing.
* Loaded and examined the dataset.
* Cleaned and preprocessed the data to prepare it for analysis.
* Explored the data through visualizations to gain insights.
* Built machine learning models to predict sentiment.
* Evaluated the models using cross-validation.

## Data Understanding
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/saloni1712/threads-an-instagram-app-reviews). It has 40435 rows and 4 columns.
The dataset consists of the following columns:

* `source`: Indicates the source of the review, such as "Google Play" or "App Store."
* `review_description`: Contains the text of the reviews.
* `rating`: Represents the rating given by the users.
* `review_date`: Shows the date when the review was posted.
## Data Cleaning
Data cleaning involved the following steps:

* Checking for missing values (there were none).
* Handling duplicate rows.
* Removing special characters, and numbers, and converting text to lowercase.
* Removing emoticons.
* Tokenizing text data.
* Removing stopwords.
* Lemmatizing words.
## Data Preprocessing
The cleaned data was split into training and testing sets.
Various vectorization techniques were applied, including Count Vectorization, TF-IDF at the word level, N-gram TF-IDF, and Character Level TF-IDF.
## Modeling
We implemented several machine learning models, including:

* Logistic Regression
* K-Nearest Neighbors (KNN) Classifier
* XGBoost Classifier
We evaluated these models using cross-validation and assessed their performance with different vectorization methods.

## Conclusion
This project provides valuable insights into the sentiment of Threads app users. The analysis reveals trends in user reviews and highlights areas for improvement. By understanding user sentiments, app developers can make informed decisions to enhance the user experience.

Feel free to explore the Jupyter notebooks in the notebooks/ directory for a detailed step-by-step analysis of the project.

If you have any questions or feedback, please don't hesitate to reach out @ndungek66@gmail.com.
