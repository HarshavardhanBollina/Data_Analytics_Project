# Data_Analytics_Project

Context According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient.


Heart strokes are quite common in our daily life. Majority of the people prone to heart attacks because of their smoking habits. Despite knowing the consequences of the smoking, Nowadays many people are addicted to it and are unable to quit it. In this context, robust countermeasures must be developed in order to keep track of their health. This is where the machine learning comes into picture to predict the effect of heart disease by considering some important features. In this brief, a novel approach for heart stroke detection that considers features from the dataset by integrating with the algorithms is proposed. Experiments on the Healthcare dataset indicate that such algorithms like logistic regression and Naive Bayes algorithm outperform other state-of-the-art algorithms, presenting great results in terms of attack detection.


In this study, we are using healthcare datasets with stroke data to build an effective model that can predict a person's propensity for a heart attack.
Here, let's provide a summary of the steps taken to get the desired results.
loading the data is the first stage, and then To explore the loaded data, we'll utilize the pandas library. To establish if a certain variable is discrete (categorical) or continuous, we will first check the data type for each variable. The cardinality of the categorical variables should be noted, as well as any columns with blank values.
The data will subsequently undergo preprocessing.
Here, we can easily remove some of the data and continue working with the remaining data. Filling in missing values, normalizing continuous variables, and serializing categorical variables are all phases in the preparation of data. Simply creating two lists—one for continuous variables and the other for categorical data—is all that is required and then we select any two of the machine learning algorithms and we train the models and the accuracy of the models will be evaluated based on the metrics like accuracy score, standard deviation, AUC score, precision, recall, f1 score etc.


Among many algorithms that can be used to solve this problem these are most efficient ones

* Logistic Regression
* SVM
* KNearestNeighbors
* GaussianNB
* BernoulliNB
* DecisionTree
* RandomForest
* AdaBoostClassifier
* Naive-Bayes




Attribute Information

id: unique identifier
gender: "Male", "Female" or "Other"
age: age of the patient
hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
ever_married: "No" or "Yes"
work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
Residence_type: "Rural" or "Urban"
avg_glucose_level: average glucose level in blood
bmi: body mass index
smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
stroke: 1 if the patient had a stroke or 0 if not *Note: "Unknown" in smoking_status means that the information is unavailable for this patient
Data files included:

healthcare-dataset-stroke-data.csv
