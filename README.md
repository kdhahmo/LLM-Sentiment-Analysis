# LLM Project

## Project Task

A sentiment analysis tool that determines the rating of a yelp review based on the review text.
## Dataset

I used the [YelpReviewFull](https://huggingface.co/datasets/Yelp/yelp_review_full) dataset, which has english reviews from Yelp extracted from the Yelp Dataset Challenge 2015 data.

## Pre-trained Model

I chose the [ElizaClaPa/SentimentAnalysis-YelpReviews-OptimizedModel from HuggingFace](https://huggingface.co/ElizaClaPa/SentimentAnalysis-YelpReviews-OptimizedModel) because it's a sentiment analysis model that is trained on the yelp review data I was provided with.
## Performance Metrics
              precision    recall  f1-score   support

           0       1.00      0.00      0.00        10
           1       0.25      0.23      0.24        13
           2       0.00      0.00      0.00         5
           3       0.18      0.18      0.18        11
           4       0.29      0.20      0.24        10
           5       0.00      1.00      0.00         0

    accuracy                           0.14        49
   macro avg       0.29      0.27      0.11        49
weighted avg       0.37      0.14      0.15        49

## Hyperparameters

I chose a lower learning rate for smoother adjustment. 
I didn't want to overfit the model so I used a lower number of training epochs.
I used a lower weight decay in order to keep from overfitting.

## Links

[![A screenshot of my Sentiment Analysis Model on HuggingFace](/images/MyHuggingFaceModel.PNG)](https://huggingface.co/KelseyHahmo/Yelp-Review-Sentiment-Analysis)
[KelseyHahmo/Yelp-Review-Sentiment-Analysis](https://huggingface.co/KelseyHahmo/Yelp-Review-Sentiment-Analysis)
[YelpReviewFull Dataset](https://huggingface.co/datasets/Yelp/yelp_review_full)