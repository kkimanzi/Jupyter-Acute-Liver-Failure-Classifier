# Jupyter-Acute-Liver-Failure-Classifier
**Introduction**
Acute liver failure (ALF) is a sudden and rare illness that occurs in patients who previously didn’t have existing liver disease (Bernal & Wendon, 2013). ALF mostly occurs in adults over the age of 30. The disease is much rare in the developed world compared to developing nations, where viruses such as hepatitis A and E have been attributed to more than 50% of the deaths of individuals from the illness (Hoofnagle, Nelson, & Purcekk, 2012). The diseases possess a high fertility rate of between 65% to 85% (Batra & Acharya, 2003). With advances in liver transplant technology and intensive care, the fatalities possed by the disease have been reduced. This, however, is a costly treatment.
Prediction of ALF can be useful for patients to take corrective action in the face of the illness. Also, caregiving institutions can benefit from this prediction in enabling them to mobilize the resources needed to mitigate the illness in time.
This assessment aims at building a classifier using machine learning algorithms to help in the prediction of acute liver failure.

**Conclusion**
The purpose of this assessment was to build a classifier to predict acute liver failure (ALF). The raw data imported into the Jupyter environment was cleaned to remove rows where ALF was missing. The missing values in the data set were filled using the median strategy to avoid skewing the data. Feature selection was accomplished using the Pearson correlation. The feature chosen had an absolute correlation of greater than two. The data was found to be skewed with the ALF results having more negative cases than positive ones. To handle this, random oversampling was done on the minority class. XGBoost, Search Grid, and Random Forest were investigated as machine learning algorithms for the classifier. Recall was chosen to be the most important metric due to the skew in the data and to since false negatives were seen to have a high consequence in the setting. It was found that Search Grid offered the best solution with a recall of 0.833.

**Data Source**
https://www.kaggle.com/datasets/rahul121/acute-liver-failure
