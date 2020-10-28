# Predict The News Category Hackathon[:link:](https://www.machinehack.com/hackathons/predict_the_news_category_hackathon/overview)

## Overview
From the beginning, since the first printed newspaper, every news that makes into a page has had a specific section allotted to it. Although pretty much everything changed in newspapers from the ink to the type of paper used, this proper categorization of news was carried over by generations and even to the digital versions of the newspaper. Newspaper articles are not limited to a few topics or subjects, it covers a wide range of interests from politics to sports to movies and so on. For long, this process of sectioning was done manually by people but now technology can do it without much effort. In this hackathon, Data Science and Machine Learning enthusiasts like you will use Natural Language Processing to predict which genre or category a piece of news will fall in to from the story. Size of training set: 7,628 records Size of test set: 2,748 records FEATURES: STORY:  A part of the main content of the article to be published as a piece of news. SECTION: The genre/category the STORY falls in. There are four distinct sections where each story may fall in to. The Sections are labelled as follows : Politics: 0 Technology: 1 Entertainment: 2 Business: 3

## Evaluation
The leaderboard is evaluated on the standard accuracy_score metric from sklearn

## Models Implemented
- [TFIDF-Stacking Classifier](https://github.com/anshulp2912/Machine-hack-Codes/blob/main/source/Predict%20The%20News%20Category/Notebooks/TFIDF_Stacking_PTNC.ipynb)
- [TFIDF-Smote-Stacking Classifier](https://github.com/anshulp2912/Machine-hack-Codes/blob/main/source/Predict%20The%20News%20Category/Notebooks/TFIDF_SMOTE_Stacking_PTNC.ipynb)
- [BERT Classifier](https://github.com/anshulp2912/Machine-hack-Codes/blob/main/source/Predict%20The%20News%20Category/Notebooks/BERT_PTNC.ipynb)
- [DistilBERT Classifier](https://github.com/anshulp2912/Machine-hack-Codes/blob/main/source/Predict%20The%20News%20Category/Notebooks/DistilBERT_PTNC.ipynb)
- [Fasttext Classifier](https://github.com/anshulp2912/Machine-hack-Codes/blob/main/source/Predict%20The%20News%20Category/Notebooks/FastText_PTNC.ipynb)
- [Naive Bayes-SVM Classifier](https://github.com/anshulp2912/Machine-hack-Codes/blob/main/source/Predict%20The%20News%20Category/Notebooks/NBSVM_PTNC.ipynb)
