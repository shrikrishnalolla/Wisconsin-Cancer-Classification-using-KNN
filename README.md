# Classification using K Nearest Negihbours 

This is a quick implementation of KNN from scratch on Wisconsin breast cancer dataset. The model classifies the tumor as either Benign or Malignant. 

The dataset can be previewed and downloaded from the link given below :

https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

KNN is a simple algorithm that assumes that similar points must be located at similar (close-by) locations in a vector space of N-dimesions (N is the number of parameters). The algorithm takes minkowski distance as the distance metric. Here, the minkowski parameter is taken as 2 which reduces the metric to Euclidean distance. The model returns an accuracy of 95.6% on test for K = 5. Further, an accuracy plot is made for all K from 1 to 100. The plot is available in the jupyter notebook.

The code has been written in Python.

![KNN](https://miro.medium.com/max/650/1*OyYyr9qY-w8RkaRh2TKo0w.png)
