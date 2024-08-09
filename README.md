# Parkinsons_Disease_Pred
**ABSTRACT:**
Parkinson's disease (PD) is a progressive neurodegenerative disorder that impacts motor function, and early and accurate diagnosis is crucial for effective management. This report presents a detailed analysis of Parkinson's disease classification using a dataset consisting of various clinical and physiological features. The dataset includes attributes such as motor symptoms (e.g., tremor, rigidity), speech features (e.g., voice frequency, amplitude), and demographic information (e.g., age, gender). The target variable for classification is the presence or absence of Parkinson's disease, categorized as binary outcomes.
We employ several machine learning techniques to develop predictive models, including logistic regression, decision trees, and support vector machines etc. Performance metrics such as accuracy, precision, recall, and F1-score are utilized to evaluate the effectiveness of each model. The results demonstrate that advanced classification methods can achieve high accuracy in distinguishing between patients with Parkinson's disease and healthy controls. This analysis not only highlights the importance of specific features in the classification process but also offers insights into optimizing diagnostic strategies for early detection of Parkinson's disease.


**Introduction**
Parkinson's disease (PD) is a progressive neurological disorder characterized by a gradual decline in motor function and quality of life. Affecting millions worldwide, PD presents a significant challenge to healthcare systems due to its complex symptomatology and the need for early intervention to manage disease progression effectively. Early diagnosis is crucial for implementing timely treatment strategies and improving patient outcomes.
Advances in data science and machine learning offer promising avenues for enhancing diagnostic accuracy and early detection of Parkinson's disease. By analysing datasets that include various clinical, physiological, and demographic features, researchers can develop predictive models to differentiate between patients with Parkinson's disease and those without.
This report focuses on the classification of Parkinson's disease using a comprehensive dataset that includes features such as motor symptoms, speech characteristics, and demographic variables. The objective is to explore and evaluate different machine learning techniques to build robust classification models. Through this analysis, we aim to identify the most significant features contributing to the diagnosis of Parkinson's disease and to assess the performance of various predictive algorithms.
The following sections will detail the methodology employed, the results obtained from different classification models, and the implications for improving diagnostic practices in Parkinson's disease.
The project is sub-divided following section. These are: 
1.	Loading Necessary Libraries.
2.	Loading Dataset from a CSV File or from a Table.
3.	Summarization of Data to Understand Dataset (Descriptive Statistics).
4.	Visualization of Data to Understand Dataset (Plots, Graphs, etc.).
5.	Data Pre-processing Imbalanced Learn Techniques, Data Transformation, Cross Validation.
6.	Hyper parameter Tuning to Find the Optimal Parameters for the Classification Models.
7.	Applying Different Learning Algorithms on the Training Dataset.
8.	Applying the AUC and ROC Curves for the best three models.

   **Procedure**
Step 1: Finding out the null values.

 
No null values present in the data.

Step 2: Checking whether the data is balanced or imbalanced .
 
Imbalanced Data

Step 3: Deletion of unnecessary columns manually and assigning the features and target variables to x and y.
 
Step 4: Plotting graphs for the data distribution and finding out the existence of outliers.
 
Histplot

 
Density graph 
 
Distribution Graph

 
Boxplot

 
Pairplot
 

Step 5: Converting the data from imbalanced to balanced using imblearn library involving Undersampling, Oversampling and Combination techniques.

 

Step 6: Train Test Split and Resampling the imbalanced data into balanced data.
 

RESULTS:
Step 7: Predicting the accuracies using all the classification models and Resampling Techniques using imblearn.
Models:  Logistic Regression, Decision Tree Classifier, Random Forest Classifier,
Bagging Classifier, Support Vector Machine and Gaussian Naive Bayes.
Resampling Techniques: 
RandomOverSampler, RandomUnderSampler, SMOTE, ADASYN, TomekLinks, SMOTEENN, SMOTETomek.
 
Using for loop and finding the accuracy score and classification report

 
Classification Report
Best accuracies found using Random Forest Classifier along with Tomek Links as an Under Sampling Technique with 97.43% accuracy.

Step 8: AUC and ROC Curve
AUC and ROC Curve is plotted for the best models with high accuracy score prediction.
Those models are Bagging Classifier using SMOTE, Bagging Classifier using SMOTEENN, Random Forest Classifier using Random Over Sampler.
 
AUC and ROC Curve
 
AUC Scores


**CONCLUSION:**
In this study, we applied various machine learning algorithms to classify Parkinson's disease based on a dataset of vocal features and physiological measurements. The primary goal was to assess the effectiveness of these models in distinguishing between individuals with Parkinson's disease and healthy controls.





