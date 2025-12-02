# Spam Classifier

This is a simple machine learning project that classifies text messages as Spam or Not Spam using Python and scikit-learn.

The dataset is loaded from: 'https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv' and combined with a self made dataset for more types of SPAM messages.
It contains:
label → spam or ham
message → SMS text

## What the Project Does

Loads and inspects the dataset
Cleans text (lowercase, remove punctuation, remove stopwords)
Creates bag-of-words features using CountVectorizer
Splits data into train/test sets
Trains a Multinomial Naive Bayes classifier
Predicts spam/ham for example messages

And here we also Checked the model performance with a new unseen dataset from Kaggle and our model performed well on this dataset too (Accuracy: 98.79%)

## Technologies Used

Python,
Pandas,
NumPy,
NLTK,
Scikit-learn,
