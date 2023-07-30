# CARDIOVASCULAR-RISK-PREDICTION
The Framingham Heart Study dataset is used in this project's machine learning to forecast the risk of cardiovascular disease over the next ten years. Important risk factors are found by using classification algorithms. The approach helps medical practitioners spot high-risk patients and take preventive action.

![Project Logo](https://www.metropolisindia.com/blog/wp-content/uploads/2023/04/Heart-Diseases.jpg)

# Project Overview
The objective of this research is to create a machine learning model that uses a dataset of demographic, clinical, and laboratory data to predict an individual's 10-year risk of cardiovascular disease.

The Framingham Heart Study dataset, a popular dataset for predicting cardiovascular risk, was used in this investigation. It includes information on 3,390 patients who underwent 10 years of cardiovascular event monitoring. 17 different factors, including age, sex, blood pressure, cholesterol levels, smoking status, and diabetes status, are included in the dataset.

Data preparation, which includes managing missing values, encoding category categories, and scaling numerical variables, is the initial phase in this project. 
The dataset is divided into training and testing sets using a 70:20 ratio after preprocessing.

The training data is processed using a number of machine learning methods, such as logistic regression, KNN, XGBoost, SVC, random forest, and Naive Bayes Classifier. These algorithms were chosen since it has been demonstrated that they are effective at predicting cardiovascular risk. The algorithms are trained using the training data, and the testing data is used to assess their performance.

# Evaluation Metrics
Accuracy, precision, recall, and the area under the receiver operating characteristic curve (AUC-ROC) are some of the assessment criteria employed in this research. These indicators aid in evaluating how well the machine learning model is doing.

# Results
The outcomes demonstrate that XGBoost outperforms the other examined algorithms, with accuracy, precision, recall, and AUC-ROC values of 0.89, 0.92, 0.85, and 0.89 respectively. This shows that the model performs well in forecasting cardiovascular risk in general.

# Feature Importance
To determine which features in the dataset are most crucial, additional analysis is conducted. Age, education, prevalentHyp, and daily cigarette consumption are the top factors in predicting cardiovascular risk, according to the feature importance plot. This knowledge may be used to spot high-risk people and put preventative measures in place.

# Conclusion
In conclusion, this effort shows how machine learning methods can accurately estimate cardiovascular risk using the dataset from the Framingham Heart Study. Healthcare providers may identify people with a high risk of cardiovascular disease and take preventative actions to lower that risk using the created machine learning model. Cardiovascular risk may be predicted early, which can help with prompt treatment and better patient outcomes.
