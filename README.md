This repository is for an svm analysis I did on the digits data from sklearn. In this analysis, I used svm to predict numbers based on images, then I plotted those images and their classifications. Then I used trained some Keras neural networks to compare to svm. The basic Keras neural network was outperformed by the convolutional neural network I created, which was outperformed by the original optimal svm that used grid search. I also utilized functions and callbacks to make the process more smooth. For simple problems such as these, svm seems to be more applicable than the neural networks I created.

Data set from:
https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification.html#sphx-glr-auto-examples-classification-plot-digits-classification-py
