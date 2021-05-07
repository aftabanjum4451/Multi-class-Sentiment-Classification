# Movie Review Sentiment Analysis 
Movie reviews help users decide if the movie is worth their time. A summary of all the reviews for a movie can help users make their decision by not wasting their time reading all the reviews on different source webistes. Movie-rating websites are often used by critics to post comments and rate movies which help viewers decide if the movie is worth watching. Sentiment analysis can determine the attitude of critics depending on their reviews. Sentiment analysis of a movie review can rate how positive or negative a movie review is, and hence the overall rating for a movie. Therefore, the process of understanding if a review is positive or negative can be automated as the machine learns through training and testing the data.

![](images/SENTIMENT.jpg)

 This project is about kaggle competition of movie reviews dataset, The data set link is provided below.

## Dataset
The Rotten Tomatoes movie review dataset is a corpus of movie reviews used for sentiment analysis, originally collected by Pang and Lee. In their work on sentiment treebanks, Socher et al. used Amazon's Mechanical Turk to create fine-grained labels for all parsed phrases in the corpus. This competition presents a chance to benchmark your sentiment-analysis ideas on the Rotten Tomatoes dataset. You are asked to label phrases on a scale of five values: negative, somewhat negative, neutral, somewhat positive, positive. Obstacles like sentence negation, sarcasm, terseness, language ambiguity, and many others make this task very challenging.

(https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews/data)

The sentiment labels are:
- 0 -- negative
- 1 -- somewhat negative
- 2 -- neutral
- 3 -- somewhat positive
- 4 -- positive

## Project Highlights
- Load the data from kaggle  
- Data Cleaning
  - Remove unwanted text, hyperlink, punctuations,Stop word removal, lemmatization 
- Data Exploratory analysis
- class imbalnce  
- Build and train the Model
- Evaluate the model on the test set

## Embedding 
- Bage of Words
- TFIDF
- Glove pre-trained

## Model
The listed model has been implemented for this projects.
- ML Model
  - **Random Forest**
  - **Naive bayes**
- Deep Learning Models
  - **CNN classifier**
  - **LSTM**


## How to Run The Code
All the code and comments are listed the jupyter notbook (Sentiment Analysis of Movies Reviews.ipynb)


