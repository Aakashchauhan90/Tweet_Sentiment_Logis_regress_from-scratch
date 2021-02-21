# Tweet_Sentiment_Logis_regress_from-scratch


# Logistic regression

# Supervised Machine Learning & Sentiment Analysis

In supervised machine learning you have input features X and a set of labels Y.

The goal is to minimize your error rates or cost as much as possible.

To do this, run the prediction function which takes in parameters data to map your features to output labels Ŷ.

The best mapping from features to labels is achieved when the difference between the expected values Y and the predicted values Ŷ hat is minimized.

The cost function F does this by comparing how closely the output Ŷ is to the label Y.

Update the parameters and repeat the whole process until your cost is minimized.

# Preprocessing
Use of stemming and stop words for text pre-processing

First, I remove all the words that don't add significant meaning to the tweets, aka. stop words and punctuation marks.
In some contexts you won't have to eliminate punctuation. So you should think carefully about whether punctuation adds important information to your specific NLP task or not.
Stemming in NLP is simply transforming any word to its base stem
