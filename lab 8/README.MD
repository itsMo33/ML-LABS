KNN Classification Project

In this project, I applied the K-Nearest Neighbors (KNN) algorithm using Python.

I started with basic exploratory data analysis (EDA) to understand the dataset. After that, I standardized the features since KNN is sensitive to the scale of the data.

Then, I split the dataset into training and testing sets using train_test_split. I first trained the model with K = 1, but the performance was not optimal.

To improve the model, I used the elbow method to test different values of K and find the best one. Based on the results, I selected a better K value (around 30).

Finally, I retrained the model using the chosen K value and evaluated it using a confusion matrix and classification report.

The model achieved an accuracy of about 84%, with balanced performance across both classes.

Conclusion

Choosing the right value of K significantly improves model performance, and feature scaling is an important step when using KNN.