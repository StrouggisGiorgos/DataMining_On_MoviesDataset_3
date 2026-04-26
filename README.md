# Contributors
* Georgios Dimoudis
* Georgios Strouggis

# Important
.csv files were too big for GitHub, so please download the data_train and data_test files from this here drive link: https://drive.google.com/drive/folders/1Cg-PbSwRN_Igi8uq_oBI_xbHCqjgLS1k?usp=drive_link

# Steps for 3_2
* Step 1: Loads data and creates a sparce matrix with the ratings given by users to various movies.
* Step 2: Uses K-means algorithm to compute Sum of Squares Error and Silhoutte Coefficient for K = 2 to 20.
* Step 3: Plots the SSE and Silhouette Coefficient to determine the best K value for both of them.
* Step 4: Performs Agglomerative Clustering for the same K values as Step 2.
* Step 5: After selecting the ideal number of clusters, we check the frequency of each movie genre in each cluster.
* Step 6: We calculate the lift values of the top three genres per cluster.
* Step 7: We repeat steps 1-7 while utilizing PCA.

# Steps for 3_3
* Step 1: Loads data and keeps movies with exactly one of 3 desires categories (War, Music, Animation) as well as a collection of keywords for all of them.
* Step 2: Creates a tf-idf + decision tree pipeline, runs cross validation and computes accuracy, precision and recall to see how accurately a movie could be predicted by its keywords.
* Step 3: Creates confusion matrix for the above.
* Step 4: Repeats Steps 2-3 but using a word2vec + decision tree pipeline.
* Step 5: Repeats Steps 2-3 but using tf-idf + kNN for each iteration of the five fold cross validation, computes accuracy, precision and recall, then when we find the best value for kNN we create the confusion matrix for it.
* Step 6: Repeats Step 5 except uses word2vec + kNN.
* Step 7: Repeats Steps 5 except uses tf-idf + logistic regression.
* Step 8: Repeats Step 7 except uses word2vec + logistic regression.
* Step 9: Repeats Step 5 except uses tf-idf + SVM.
* Step 10: Repeats Step 9 except uses word2vec + SVM.
* Step 11: Repeats Step 5 except uses tf-idf + MLP.
* Step 12: Repeats Step 11 except uses word2vec + MLP.
* Step 13: Compares the scores for all of the above.

# Steps for 3_4
* Recreation of https://github.com/StrouggisGiorgos/DataMining_On_MoviesDataset_2/tree/main Steps 4-5 implementing pagerank algorithm.
