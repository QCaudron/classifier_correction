# "Correcting" a probabilistic classifier for minority class underprediction

In probabilistic classifiers where one class is a "real" majority (for some definition thereof...), we might see the classifier underpredicts the minority class. If we know the original distribution of our data classes, and can calculate the class-wise recall matrix, we can calculate the post-prediction distribution of our data classes. Can we use these to correct the classifier to some extent ?
