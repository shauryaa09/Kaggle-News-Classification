The notebook A4W4-unsup-learning-UCB.pdf contains the pdf of the code. It uses the tfidf text vectorizer on the BBC news classification data set, which is obtained from: http://kaggle.com/competitions/learn-ai-bbc/.
This notebook constructs tfidf vectors and then uses unsupervised learning, including non-negative matrix factorization, to get the results. It also compares the results from supervised learning methods.
Then, finally, training data is split into various splits, and the supervised learning methods are compared.
In the notebook nmf_mov_rating, it is shown how the movie ratings are predicted using NMF, and the RMSE is better than traditional methods. The RMSE using NMF ~0.96 and using traditional
methods like predicting to average or 3 is ~1.2. Even Jaccard similarity predicts ~0.95 at best. All of this is shown to be possible using NMF. The other results are not present in 
that notebook, but are present over here in the Readme file.

