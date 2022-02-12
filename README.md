### NLP Predicting Disaster Tweets Competition
Our goal here to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.

What's in the notebook?

    Exploratory Data Analysis (EDA)
    Text Prosessing & Data Cleaning
    Evaluation

## Data analysis
In the following we're going to see some data analysis on the corpus.

Specifically:

    General dataset infos
        Number of samples
        Data Columns
        Class Label Distributiom

    Text analysis
        Top words in positive & negative tweets
        Hashtag Analysis
        The word cloud
        

## Text Processing and Data Cleaning
Here we clean our dataset. Specifically, we clean:

    URLs
    HTMLs
    punctuations
    whitespaces
    stopwords
    
and apply following ideas:

    convert text to lower
    replace emoji and smileys by their corresponding text
    Chatwords conversion
    correct spellings
    lemmatizing
    stemming
    
    
    
### Evaluation:

    tfidf & Classic ml classifiers like SVC, LogisticRegression... (score = 81%)
    Voting classifier  (score = 81%)
    Simple LSTM Model (score = 78%)
    Glove Bi-LSTM (score = 81%)
    BERT  (score = 83%)
