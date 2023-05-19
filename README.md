# Expert-System-Project
The code performs analysis and classification of a dataset using various machine learning algorithms. It loads the dataset from a CSV file and performs exploratory data analysis, including data visualization through graphs. The dataset is then split into training and testing sets, and the performance of different models is evaluated using cross-validation. The code also trains a Support Vector Machine (SVM) model and makes predictions on the validation dataset, followed by evaluating the accuracy of the predictions.


Data Set Information:

This data set was generated to model psychological experimental results. Each example is classified as having the balance scale tip to the right, tip to the left, or be balanced. The attributes are the left weight, the left distance, the right weight, and the right distance. The correct way to find the class is the greater of (left-distance * left-weight) and (right-distance * right-weight). If they are equal, it is balanced.

