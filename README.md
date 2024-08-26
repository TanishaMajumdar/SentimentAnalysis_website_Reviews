#Sentiment Analysis for Amazon reviews (H1)
This repository contains code to analyze sentiment in Amazon reviews using different sentiment analysis techniques. The primary goal is to understand customer sentiments and compare the results of different models.
The dataset used in this project is the Reviews.csv file containing Amazon product reviews. We use a subset of 500 reviews for analysis to demonstrate the process. The dataset is assumed to be in the same directory as the script.

##Visualization (H2)
The project includes visualizations to compare sentiment scores across different star ratings:

1) Count of Reviews by Stars: A bar plot showing the distribution of review scores.
2) Sentiment Scores by Review Rating: A series of bar plots comparing positive, neutral, and negative scores for each rating.

##Results (H2)
The results show that different models can yield varying sentiment scores. The VADER model tends to have quicker inference but may not always be as nuanced as RoBERTa, which is a more sophisticated deep learning model.

