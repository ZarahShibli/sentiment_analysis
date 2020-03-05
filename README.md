# Sentiment Analysis

1. [Project Overview](#ProjectOverview)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Overview <a name="ProjectOverview"></a> 
This project to build a sentiment analysis for English Movies dataset and Arabic Posts.  


## 2. Installation <a name="installation"></a>

- Python versions 3.*.
- Python Libraries:
    - sklearn.
    - Pandas.
    - string.
    - nltk
    - re.

## 3. Data<a name="data"></a> 
**English**

[IMDB dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) having 50K movie reviews. This is a dataset for binary sentiment classification.

**Arabic**

[BBN Blog Posts Sentiment Corpus](https://saifmohammad.com/WebPages/ArabicSA.html) contains A random subset of 1200 sentences chosen from the BBN Arabic-Dialect–English Parallel Text.


## 4. Implementation <a name="model"></a> 
In this project, we used [Gaussian Naive Bayes from scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html). The data have been split into training and testing with a ratio of 80:20.

**English**

[<img src="https://colab.research.google.com/assets/colab-badge.svg" height = '40px' >](https://colab.research.google.com/github/ZarahShibli/sentiment_analysis/blob/master/notebooks/sentiment_analysis_en.ipynb)
---
**Arabic**

[<img src="https://colab.research.google.com/assets/colab-badge.svg" height = '40px' >](https://colab.research.google.com/github/ZarahShibli/sentiment_analysis/blob/master/notebooks/sentiment_analysis_ar.ipynb)

## 5. Result<a name="results"></a> 
Here some prediction to model.

**English**
---

<img src="https://user-images.githubusercontent.com/42017072/75926120-079dec80-5e7b-11ea-8c2d-6f96d05f2f60.PNG" height = '200px' >

<img src="https://user-images.githubusercontent.com/42017072/75926118-066cbf80-5e7b-11ea-96fa-ac0dacc147a9.PNG" height = '200px' >

**Arabic**
---

<img src="https://user-images.githubusercontent.com/42017072/75987890-c3a1fa80-5f01-11ea-952b-e94ab2b7b577.PNG" height = '200px' >
