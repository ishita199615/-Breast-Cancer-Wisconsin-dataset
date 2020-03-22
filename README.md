# -Breast-Cancer-Wisconsin-dataset

BREAST CANCER WISCONSIN
(DIAGNOSTIC) DATA SET
(https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

Exploratory data analysis (EDA)
Data Loading & Data visualization
I began my project my downloading the data set from the UCI Machine Learning Library.
I have mentioned the link in the heading,
I got the data file as the .data extension. So, while reading it using the panda’s data frame, I was not able to get the whole data information. 
Therefore, I converted the file into csv and the file has been attached in the submission.
First step:
Loading the file (using both pandas and sklearn dataset)
(Libraries – pandas, sklearn)
Second Step 
Converting the diagnosis (column to be int data type)
Third step
Some related exploratory analysis
(Libraries used – matplotlib and seaborn)
Heatmaps showing the correlation
Outlier plot 
Plot showing if there is null value 
Violin plot – This is something new which I learnt about. This graph I have used to analyze that which features can be used for the classification and which are not good to use.
Box plot – This is another visualization which has been used to study the outliers in the data
Fourth step (Applying model)
Then after this I used various classifiers and applied many machine learning algorithms to it like
Support Vector Machine (kernels – linear and rbf)
RandomForest Classifiers
Decision Tree Classifiers
After fitting the train data to with different classifiers in the model, I calculated the accuracy score for each model.
I also took out the confusion matrix so as to check the accuracy from it.
Fifth step
I found that random forest is the one which has the best accuracy score.
I then did feature selection with the RandomForest.

Conclusion
I found that the accuracy of the RandomForest Classifier is the best on application of the training data to the model.
Therefore, I did my prediction of the model using test data with the Random Classifier.
Noticing the good accuracy of the RandomForest Classifier, I did my feature selection considering some of the features.

Improvements and Plan
I used sklearn libraries in the project. Definitely I want to try applying each classifier with hand.
Also, I want to make recommendation system for the breast cancer by trying to combine this data and some data related to medicine and cure.
Off course I want to explore the data even more by using other machine learning algorithms.












