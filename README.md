# capstone

Technical Report

1. I acquired my data from https://www.kaggle.com/zynicide/wine-reviews. The data were mostly cleaned but I realized (albeit a bit too late) that they could stand to be a bit more cleaned. I will clean it this weekend.

2. The data needs to be  NLP'd using tokenization, lemmatization, punctuation and stop words removal'd as well as vectorized. This way it can be fed into a classification model.

3. My outcome variable is the type of wine (variety). The idea being that varieties have certain characteristics (flavors, aromas) and those characteristics could lead you to the variety.

4. I used a kNN model and ran a for loop on the number of neighbors to determine the optimal amount.

5. I plan to attempt several more models including a Naive Bayes Classifier and a LogReg. I'd like to try and get above 50% accuracy.