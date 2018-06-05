# Classifying-20-news-group-dataset-using-support-vector-machine and NLP
This is the code for classifying 20 news group dataset using support vector machine and natural language processing.

## Overview

Basically we create a data clean function using nltk which removes non-alpha words (like abc1234) or characters, punctuatons and popular names(like John, James using nltk.corpus.names). And then each word is lemmatized ({close, closely, closed, closer} => close ) using WordNetLemmatizer. 

## Dependencies
* nltk
* sklearn
* numpy

## Usage
Just run the given jupyter notebook in your browser.
