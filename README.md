## As part of Sentiment Analysis

### Sentiment-Analysis - Data Preprocessing using NLTK

#### Pre requests:
1. Python 3  -  [Mac/Linux: sudo apt-get install python3] [Windows: https://www.python.org/]
2. Jupyter Notebook - Its better to install Anaconda, it will come as package which can be helpful for further process.
                      [https://conda.io/docs/user-guide/install/index.html]

#### NLTK Instalation:
1. NLTK: <<https://pythonprogramming.net/tokenizing-words-sentences-nltk-tutorial/>>

#### NLTK An Intro:
1. What is NLTK?
   The Natural Language Toolkit (NLTK) is a platform used for building Python programs that work with human language data for applying in statistical natural language processing (NLP).
   It contains text processing libraries for tokenization, parsing, classification, stemming, tagging and semantic reasoning. It also includes graphical demonstrations and sample data sets as well as accompanied by a cook book and a book which explains the principles behind the underlying language processing tasks that NLTK support.

2. Most commonly used NLTK terms:
   1. Remove Stop Words
   2. Tokenize Text
   3. Word Lemmatization & Stemming
   4. Part of Speech (POS) Tagging
   5. BOW - Bag OF Words
   6. Sentence Parsing
   7. Corpora and lexical resources
   
#### Tips for SA data preprocessing: 
we have few dataset and we will clean the dataset to implement SA, below are some tips for cleaning or preprocessing the dataset:
1. Retweets, which starts with “RT” are eliminated.
2. User names preceded by ‘@' and external links are eliminated.
3. Hashtag ‘#' (used to point subjects and phrases that are currently in trending topics) is removed from the tweet.
4. Emoticons 1 are replaced by its equivalent meaning because these can serve as a useful feature to detect senti-
ments.
5. “Stemming” is done to reduce each word to its root word.
6. Slangs are converted to words with equivalent meaning.
7. Stop-words or useless words are removed from the tweet.


#### Note: NLTK - Cheetsheet available in repository  
