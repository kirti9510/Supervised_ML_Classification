# Supervised_ML_Classification
# **Course Project | Heart Disease Prediction**
![image.png](https://static.vecteezy.com/system/resources/previews/018/244/237/original/3d-illustration-of-heart-disease-warning-png.png)

**In this Project we will cover following sections**
* **Main Objectiive**
* **Description and summary of the Dataset**
* **Data Cleaning and feature engineering**
* **Model building**
* **Analyzing the best model**
* **Key findings and insights**
* **Conclusion**

* ## <font color=#dd3558> Main objective


Patients were classified as having or not having heart disease based on cardiac catheterization, the gold standard. If they had more than 50% narrowing of a coronary artery they were labeled as having heart disease.

Its diagnoses is important, which includes analysis of various factors that are present in the dataset used in this project.

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them.  In particular, the Cleveland database is the only one that has been used by ML researchers to date.  The "goal" field refers to the presence of heart disease in the patient.  It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).  

* ## <font color=#dd3558> Description of the Dataset

 **About the data:**
* This dataset contains all physical and clinical parameters to determine Heart disease. There are a total of 13 parameters. 
* This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V.
* It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them.
* The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

* ## <font color=#dd3558> Preprocessing
    
**Steps involved in Data Preprocessing:**
* Dropping the repeated features
* Encoding categorical variables (dtype objects)
* Dealing with missing values

* ## <font color=#dd3558> Exploratory Data Analysis
    
**Steps involved:**
* Studying correlations between features 
* Patterns of most significant features

* ## <font color=#dd3558> Conclusion
* SVC performance was not as good as KNN but accuracy was acceptable with 93%.
* Overall, KNN gave the best results from the different machine learning algorithms used here.
