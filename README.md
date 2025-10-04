<p align="center">
  <img src="banner.png" alt="Sentiment Analysis Banner" width="800">
</p>


# Sentiment-Analysis-on-IMDB-Reviews

## Run to Colab
[open in Google Colab](https://colab.research.google.com/drive/1u2cuXZ6TYqwuvZg_W5_iPxE1YOSHrQ9W?usp=sharing)

## Overview
This project focuses on analyzing IMDB movie reviews to determine whether each review expresses a positive or negative sentiment.
The process involves:
	•	Cleaning and preprocessing the text data using NLTK
	•	Applying sentiment polarity analysis with TextBlob
	•	Visualizing the overall sentiment distribution with Matplotlib
	•	(Optional) Creating a Power BI Dashboard for better insight visualization

  Objective

To demonstrate Natural Language Processing (NLP) and Data Analysis skills by building a mini end-to-end project — from text cleaning to insight visualization.

⸻

## Technologies Used
•	Python (Pandas, NLTK, TextBlob, Matplotlib)

⸻

## Dataset

The dataset used is the IMDB Dataset of 50,000 Movie Reviews, containing text reviews and sentiment labels.
Only a random sample of 500 reviews was used for this project to improve processing speed.

⸻

## Data Cleaning & Preprocessing
1.	Convert text to lowercase
2.	Remove punctuation and special characters
3.	Tokenize the text
4.	Remove English stopwords
5.	Join the tokens back into cleaned text

⸻

## Sentiment Analysis

Each cleaned review is passed through the TextBlob sentiment analyzer to calculate polarity:

Polarity > 0: Positive

Polarity < 0: Negative

Polarity = 0: Neutral (counted as Negative for simplicity)

## visualization
The results are visualized using Matplotlib to show the distribution of positive vs. negative reviews.
![chart](Screenshot%202025-10-05%20004132.png)

	
