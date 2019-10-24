# Lambda-Build-One

This project uses a dataset of China's 新闻联播 articles to train a model to predict whether or not an article will be about Xi Jinping. 

Version 3 uses a Bag of Words approach and then trains various classifier models on it (with a 75% shuffled training set, tested on 25% of data). Their accuracy scores are:

Multinomial Naive Bayes: 92.646%

Bernoulli Naive Bayes: 85.953%

Logistic Regression: 95.904%

Support Vector Clustering (SVC): 93.883%


Version 2 has various bits of code with LDA classification, and is uploaded more as a playground for various experiments in NLP at a time during which I am very unfamiliar with the NLP process, rather than as an example of good code. It has not been uploaded due to filesize constraints.
