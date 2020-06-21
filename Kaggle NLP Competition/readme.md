# Kaggle NLP Competition

This is a in-class Kaggle competition for my Applications of Deep Neural Networks class. The objective is to use deep learning models to predict if two randomly selected sentences are from the same Wikipedia page. Our team achieved a log loss of 0.2 (Top 10%) by combining more than 40 features extracted from the sentence pairs and XGBoost model. Packages used include NumPy, pandas, XGBoost, sklearn, NLTK, Matplotlib, Pylab, fuzzywuzzy, tqdm, SciPy, gensim.

### Dataset:

The training dataset includes 100,000+ pairs of randomly selected sentences from Wikipedia, as well as a column called "same_source" indicating if the two sentences are from the same Wikipedia page. The testing dataset includes 10,000+ pairs of randomly selected sentences from Wikipedia. 
