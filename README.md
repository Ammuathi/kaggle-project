Online Shoppers Purchasing Intention Prediction
Project Overview

This project aims to predict whether an online shopper will generate revenue (make a purchase) based on their browsing behavior on an e-commerce website.
Machine learning techniques are used to analyze user session data and classify the purchase intention of visitors.

The dataset contains information about user behavior such as page visits, session duration, and traffic source.

Dataset

Dataset used: Online Shoppers Purchasing Intention Dataset

It contains information about website visitor sessions, including:

Administrative pages visited

Informational pages visited

Product related pages visited

Bounce rate

Exit rate

Page value

Month

Operating system

Browser

Region

Traffic type

Visitor type

Weekend activity

Revenue (target variable)

Target Variable:

Revenue

True → Customer made a purchase

False → Customer did not make a purchase

Technologies Used

Python

Pandas

Scikit-learn

Kaggle Notebook / Jupyter Notebook

Libraries used:

pandas

sklearn

LabelEncoder

RandomForestClassifier

train_test_split

accuracy_score

Project Workflow
1. Data Collection

The dataset is obtained from Kaggle and loaded into the Python environment.

2. Data Preprocessing

The dataset is cleaned and categorical variables are converted into numeric form using Label Encoding.

Categorical columns encoded:

Month

VisitorType

Weekend

Revenue

3. Feature Selection

The Revenue column is used as the target variable, while the remaining columns are used as input features.

4. Train-Test Split

The dataset is split into training and testing data:

80% Training Data

20% Testing Data

5. Model Training

A Random Forest Classifier is used to train the model and learn patterns from the training data.

6. Model Evaluation

The trained model is evaluated using accuracy score.

Model Accuracy

The Random Forest model achieved an approximate accuracy of:

90% – 93%

This means the model can correctly predict the purchasing intention of online shoppers in most cases.

How to Run the Project
Step 1

Install required libraries:

pip install pandas scikit-learn
Step 2

Load the dataset:

df = pd.read_csv("online_shoppers.csv")
Step 3

Run the preprocessing and model training code.

Step 4

Check the model accuracy.

Applications

This project can help e-commerce businesses:

Understand customer behavior

Predict purchase intention

Improve marketing strategies

Increase conversion rates

Future Improvements

Possible improvements include:

Using advanced algorithms like XGBoost

Feature importance analysis

Hyperparameter tuning

Visualization of results

Conclusion

The project demonstrates how machine learning can be used to analyze user behavior and predict online purchasing intentions. The Random Forest model provides a reliable classification with high accuracy.
