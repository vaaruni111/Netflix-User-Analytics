# Netflix User Analytics 

## Student Information

* **Student Name**: Vaaruni Gupta
* **Enrollment Number**: 07401222025
* **College Name**: Indira Gandhi Delhi Technical University For Women(IGDTUW)
  
## Project Overview

This project analyzes Netflix user behavior using Machine Learning techniques namely Decision Tree, K-Nearest Neighbour and Linear Regression.
The objective is to explore user behavior, predict subscription renewal, and estimate monthly spending using different machine learning algorithms.

---

## Tasks Taken

### 1. Exploratory Data Analysis (EDA)

* Understand dataset structure
* Identify numerical and categorical features
* Check for missing values
* Analyze user demographics and viewing behavior

### 2. Preprocessing data

* Preparing data by converting categorical features into numerical features using encoding.
* Splitting the dataset into train and test.
* Setting feature set and target variable

### 3. Decision Tree Classification

* Training a Decision Tree model
* Finding it's accuracy and confusion matrix
* Finding factors affecting subscription renewal

### 4. K-Nearest Neighbors (KNN)
* Training a KNN model with K=5
* Comparing accuracy
  
### 5. Linear Regression

* Predict a user's monthly spending using Linear Regression.

---

## Results

### Classification Results

| Model         | Accuracy |
| ------------- | -------- |
| Decision Tree | 56.00%   |
| KNN           | 63.33%   |

### Regression Result

Predicted Monthly Spending for a New User:

₹ 358.87

---

## Business Insights

### 1. Which factors influence subscription renewal?

Based on Decision Tree feature importance analysis, the most influential factors were:

* MonthlySpend
* AdClicks
* Age
* WatchHoursPerWeek
* FavoriteGenre


### 2. Why is subscription renewal a classification problem?

Subscription renewal has two possible outcomes: Yes or No. As there are discrete categories, it is a classification task.A new user can only
attain these 2 values.

### 3. Why is monthly spending a regression problem?

Monthly spending is a continuous numerical value not a category, making it suitable for regression analysis.

### 4. Which algorithm performed better?

The KNN model with the higher accuracy score(63.33%) as compared to Decision Tree Model's accuracy score(56.00%) is the better performer for renewal prediction.

### 5. How can Netflix use these predictions?

* Identify users likely to cancel subscriptions 
* Improve customer retention strategies
* Offer personalized recommendations
* Create targeted marketing campaigns
* Increase customer engagement
* Revenue Forecasting by predicting monthly spending of the users

---

## Repository Structure

```text
Netflix-User-Analytics/
│
├── netflix_UserData.csv
├── Netflix_User_Analytics.ipynb
├── README.md
└── description.md   

```

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset file.
3. Run all cells.
4. Review the outputs and model results.

---



