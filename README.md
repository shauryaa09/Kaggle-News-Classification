In the notebook, I tried to classify news articles into five categories using various machine learning methods starting from unsupervised learning, to supervised learning, and finally the multilayer perceptron. I joined a kaggle competition to assess the test dataset results. I used the tfidf word processing algorithm to create the feature matrix.

I optimized both the word processing method and the machine learning hyperparameters.

From the word processing optimizations, I found that using word-grams upto pentagrams, from unigrams, and a minimum document frequency for a token, between 6 to 8, gives us the best results. Along with this, using logarithm of the term frequency gives a little better accuracy too.

Among various machine learning methods, I found that Support Vector Classifier and Multilayer Layer Perceptron perform better than others and obtained a test accuracy of 0.99, and, 0.98, respectively.
I also found that unsupervised learning showed a test accuracy of upto 0.97 which can be a useful result, given the fact that labels are not used.

Among the categories, sport was easily distinguished by the classifiers, while business, tech and, entertainment, mixed a little more in the predictions.

