# Predicting-Ad-Click-using-Logistic-Regression
Machine Learning Project: Predicting if the user will click on the Ad using Logistic Regression. 

#### The dataset consists of the following features:
 'Daily Time Spent on Site': consumer time on site in minutes
 'Age': cutomer age in years
 'Area Income': Avg. Income of geographical area of consumer
'Daily Internet Usage': Avg. minutes a day consumer is on the internet
'Ad Topic Line': Headline of the advertisement
'City': City of consumer
'Male': Whether or not consumer was male
'Country': Country of consumer
'Timestamp': Time at which consumer clicked on Ad or closed window
'Clicked on Ad': 0 or 1 indicated clicking on Ad  ..(Target)

### Steps:

1. Loading the dataset.
2. Analyzing the dataset.
3. Exploring the dataset.
4. Performing Logistic Regression.


### 4) Conclusion


#### 1. Confusion Matrix

Each row: actual class

Each column: predicted class


First row: Non-clicked Ads, the negative class: 

. 348 were correctly classified as Non-clicked Ads. True negatives.

. Remaining 6 were wrongly classified as clicked Ads. False positive


Second row: The clicked Ads, the positive class:

. 18 were incorrectly classified as Non-clicked Ads. False negatives.

. 328 were correctly classified as clicked Ads. True positives.


#### 2. Precision

Precision measures the accuracy of positive predictions. Also called the precision of the classifier ==> 96.57 %


#### 3. Recall

Precision is typically used with recall (Sensitivity or True Positive Rate). The ratio of positive instances that are correctly detected by the classifier ==> 94.8 %


#### 4. F1

F1 score is the harmonic mean of precision and recall. Regular mean gives equal weight to all values. Harmonic mean gives more weight to low values ==> 96.47 %
