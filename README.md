# Restaurant_Reviews_Analysis
For any restaurant manager it is essential to know feedbacks from customers (are they satisfy with service? what they feel about
food? are they really like that? if not then what is the reason? is there any scope of improment?) Each owner wants a 
happy customer.
 The aim of this project is to build prediction model to predict whether a review on the restaurant is positive or negative.

 # To build a model following steps are followed:
1)Importing Dataset
2)Preprocessing Dataset
3)Vectorization
4)Training and Classification
5)Analysis Conclusion

# Exploratory Data Analysis:
1)N-grams: Unigrams, Bigrams, Trigrams
2)Wordcloud: Graphical representation of a text data
3)Checking the length of document

# Data Preprocessing :
1)Pandas function info() helps us to check data types and non null count 
2)checked missing value count
3)checked data balancing
4)remove extra spaces,newlines
2)Contraction Mapping-Here we are expanding the join words
3)Handling accented character
4)Cleaning text : Tokenization,lowercase conversion,remove punctuation,remove stopwords
5)Lemmatization:Here we are finding root words 

# Feature Engineering :
From the cleaned dataset, potential features are extracted and are converted to numerical format.
1)Countvectorizer
2)TFIDF
3)Word2Vec
All above techniques are used to convert textual data to numerical format.

# Model Building and Evaluation:
The data is splitting into train test format with 80% -20%.
Algorithms like Decision tree, KNN, Logistic Regression, Naive Bayes were implemented and on comparing the accuracy score, precision and recall.

