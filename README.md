# Comparison of Scikit-Learn Algorithms
The attached notebook documents observations in the varying strengths and weaknesses of four machine learning algorithms; Decision Trees, K-Nearest Neighbors, Support Vector Machines, and Neural Networks.

We compared the algorithms by testing their performance on classifying results for two unique datasets. By adjusting model hyperparameters, we were able to observe changes in performance using validation curves, learning curves, wall-clock time and loss curves where applicable. The analysis was performed in python 3.7 using the scikit-learn (sklearn) package, version 1.2.1.

db folder contains sqlite database with data for running the code without the time and space complexity of building and testing the models. To build the models instead of reading from database, change "read_db" to False in all calls to plot_validation_curve and plot_learning_curve.
