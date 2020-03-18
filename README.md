# Handwritten Digit Classifier

I created a model to classify handwritten digits. I used a data set which is obtained from scikit-learn. Scikit-learn copies the data set from UCI. I explored the data set by using pandas and matplotlib. I did not do any change on the data because the data set is clean and ready to implementation. 
I have started to set my models to find the fittest way. I have created functions which get the data set, train and test the model on it. I have used knn classification, neural networks and random forests.  I have tested my models by calculating their accuracies. For this purpose, I have created cross validation function to test my models by getting accuracies.

## Conclusion

With 4-fold cross validation function, I have got approximately 96% accuracies for my knn classification model.

The accuracy has started with 86% for neural networks. I have used different hidden layers and neurons to see accuracies. I have obtained 95% accuracy with two hidden layers. And I have got 96% accuracy with three hidden layers. When I have used more hidden layers and more neurons, my accuracies was going to be higher. 

Lastly I have used random forests. And my highest accuracy is approximately 94%.

As a conclusion, I can say that I have got the highest accuracy score with nueral networks with three hidden layers.








