# Predictive Modelling and Classification of Parkinson's Disease: A Comprehensive Data Analysis

**Overview:**

This project focuses on the classification of Parkinson's disease (PD) using machine learning techniques applied to a dataset of vocal features. Parkinson's disease is a neurodegenerative disorder that affects motor function, and early detection is crucial for effective management. By leveraging data-driven approaches, this project aims to build and evaluate models that can accurately distinguish between individuals with Parkinson's disease and healthy controls.

**Dataset:**

The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains vocal features extracted from audio recordings of patients with Parkinson's disease and healthy individuals. The dataset includes 22 features and a target variable status, where:

'1' indicates the presence of Parkinson's disease.
'0' indicates a healthy control.

**Some important Features:**

MDVP
(Hz): Average vocal fundamental frequency
MDVP
(%), MDVP
(Abs): Measures of variation in fundamental frequency
MDVP
, MDVP
, Jitter
: Various jitter measurements
MDVP
, Shimmer
: Measures of variation in amplitude
NHR, HNR: Noise-to-harmonics and harmonics-to-noise ratios
RPDE, DFA: Signal fractal scaling exponent and signal smoothness
spread1, spread2: Two nonlinear measures of the fundamental frequency variation
D2: Another nonlinear measure
PPE: A measure of vocal pressure


**Installation**


Install Jupyter Notebook : Make sure you have Python installed on your computer.

Install Required Packages: Install the necessary Python packages. You can do this using your preferred method (e.g., via Anaconda, or directly using pip). The key packages you might need are:

numpy

pandas

scikit-learn

matplotlib

seaborn

imblearn

seaborn

These packages are commonly used for data analysis and machine learning.

**Usage**


**Download the Dataset**: Obtain the Parkinson's disease dataset from the UCI Machine Learning Repository.

**Run the Analysis**: Follow the steps in the project to explore the data, train the model, and evaluate its performance.

**Review Results**: Check the model's accuracy and other performance metrics to understand how well it classifies Parkinson's disease.



**Results**

The trained model achieves high accuracy in classifying Parkinson's disease based on the vocal features provided in the dataset.

**License**

This project is licensed under the MIT License.
