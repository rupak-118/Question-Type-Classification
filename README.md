# Question-Type-Classification

## Problem statement :
Question-type classification into Coarse and fine labels (6 coarse classes, 50 fine classes)

## Dataset :
The training and test datasets can be downloaded from here : http://cogcomp.cs.illinois.edu/Data/QA/QC/

## Approach and methods/experiments :
* Text pre-processing (exploration, cleaning, stemming, lemmatization, stopword removal etc.)
* Word embeddings (CountVectors, TF-IDF, word2vec, GloVe)
* Linear ML models (Logistic Regression, SVM)
* Non-linear and Tree models (Gaussian Naive-Bayes, Multinomial NB, Bernoulli NB, LightGBM, XGBoost)

## Future steps/experiments :
* Ensembles
* RNNs/LSTMs
* Implementing state-of-the-art papers in the QC domain
* Better feature extraction (e.g. using only first few words/keywords from each question, or, deriving word2vec embeddings weighted by tf-idf values etc.) 
* Manual inspection of examples which the model is getting wrong to derive insights and improve precision/recall
