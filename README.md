### Classifying Songs

Using a dataset comprised of songs of two music genres (Hip-Hop and Rock), we trained a classifier to distinguish between the two genres based only on track information derived from Echonest (now part of Spotify). 

First, we made use of pandas package in Python for subsetting the data and aggregating information for exploring obvious trends or factors we should consider when doing machine learning. Next, we used the scikit-learn package to apply dimension reduction technique Principal Components Analysis to create a new set of features to use for predicting whether you can correctly classify a song's genre. We then created a decision tree classifier and compared its performance to that of a simple logistic regression.
