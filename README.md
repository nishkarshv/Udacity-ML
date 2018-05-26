# Machine Learning Engineer Nanodegree
# Capstone Project
## Project: Toxic Comment Classification of Wikipedia Comments

### Install

This project requires **Python 3.5+** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project. 

### Code

Template code is provided in the `ToxicLogisticReg.ipynb` and `ToxicLSTMwithGLOVE.ipynb` notebook file. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project.

### Run

In a terminal or command window, navigate to the top-level project directory `finding_donors/` (that contains this README) and run one of the following commands:

```bash
ToxicLogisticReg.ipynb
```  
or
```bash
jupyter notebook ToxicLSTMwithGLOVE.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

Please follow the link :- 
https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data

You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

toxic
severe_toxic
obscene
threat
insult
identity_hate
You must create a model which predicts a probability of each type of toxicity for each comment.

File descriptions
train.csv - the training set, contains comments with their binary labels
test.csv - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
sample_submission.csv - a sample submission file in the correct format
test_labels.csv - labels for the test data; value of -1 indicates it was not used for scoring; (Note: file added after competition close!)


**Features**
You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

toxic
severe_toxic
obscene
threat
insult
identity_hate

