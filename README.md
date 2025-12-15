# Titanic Survived Prediction
 
 
## 1. Project Overview
This project aims to build a machine learning model that predicts which passengers survived the Titanic shipwreck. By analyzing the famous Kaggle Titanic dataset,
the project identifies patterns in passenger data (such as age, gender, ticket class, and fare) to classify survival outcomes.

The goal is to demonstrate the end-to-end data science workflow, from data cleaning and exploratory analysis to model training and evaluation.

## 2. Technologies & Tools Used
This project was developed using **Python** and its data science ecosystem.

* **Language:** Python 3.x
* **IDE:** Google Colab
* **Data Manipulation:**
* `Pandas`: For data loading, cleaning, and manipulation.
* `NumPy`: For numerical computations and matrix operations.


* **Data Visualization:**
* `Matplotlib`: For basic plotting.
* `Seaborn`: For statistical data visualization (heatmaps, distribution plots).


* **Machine Learning:**
* `Scikit-Learn`: For model building, preprocessing, and evaluation.


## 3. Dataset
The dataset used is the **Titanic: Machine Learning from Disaster** competition dataset from Kaggle.

**Train.csv:** Used to train the model (contains features + survival label).

## 4. Methodology
The project follows a standard Data Science lifecycle:

1. **Data Acquisition:** Loading the train and test datasets.
2. **Exploratory Data Analysis (EDA):**
* Analyzed survival rates based on Gender, Pclass, and Embarked locations.
* Visualized correlation between features using heatmaps.
* Handled missing values in `Age`, `Cabin`, and `Embarked` columns.


## 3. Data Preprocessing:
* **Feature Engineering:** Created new features like `FamilySize` (SibSp + Parch) and extracted `Title` from names.
* **Encoding:** Converted categorical variables (Sex, Embarked) into numerical values using One-Hot Encoding/Label Encoding.
* **Scaling:** Standardized numerical features like `Fare` and `Age`.


## 4. Model Selection:
Tried multiple algorithms to find the best fit:
* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)
 



## 5. Results & Evaluation
The models were evaluated based on **Accuracy Score** and **Confusion Matrix**.

* **Best Model:** [Random Forest Classifier]
* **Accuracy:** [82.5%]

| Model | Accuracy Score |
| --- | --- |
| Logistic Regression | [79%] |
| Decision Tree | [76%] |
| **Random Forest** | **[82%]** |

> **Key Insight:** Gender and Passenger Class were the most significant factors in predicting survival. Women and 1st-class passengers had a much higher chance of survival.

 
## 6. Author **Syed Mehdi Shah**
 
