# Predict Clicked Ads Customer Classification by Using Machine Learning
A company in Indonesia wants to know the effectiveness of an advertisement that they display, this is important for the company to be able to find out how much the advertising attracts the market.
By processing historical advertisement data and finding insights and patterns that occur, it can help the company determine marketing targets. The focus of this case is to create a machine-learning classification model to identify customers who are likely to click on the ads displayed by the marketing team.

### Dataset Overview
<hr>
Data contains 1000 rows with 10 features. <br/> 
Terminologies: <br/>  
- Daily time spent on site: Daily time spent on site <br/>
- Age: Age  <br/>
- Area income: Income <br/>
- Daily internet usage: Daily internet usage  <br/>
- Male: jenis kelamin  <br/>
- Timestamp: Time when the customer decides to click or not click <br/>
- Clicked on ad: Did the customer click on the ad <br/>  
- City: City  <br/>
- Province: Province  <br/>
- Category: Category looked by the customer  <br/>

## Exploratory Data Analysis<br/>
1. Statistical Descriptive <br/>
2. Univariate Analysis <br/>
3. Bivariate Analysis <br/>

## Data Preprocessing and Modelling</br>
1. Feature Engineering
2. Hypotesis Testing
3. Split test dan train
4. Pipeline

## Result
- Tried 3 algorithms: Random Forest, XGBoost, and Gradient Boosting.
- Scoring: Accuracy because of a balanced target, and Precision to minimalize false positive.
- Hasil: The best algorithm is XGBoost with 0.95 Accuracy and 0.96 Precision.
- Most Important Feature: Daily internet usage.

Business simulation using CLICK PER IMPRESSION as the advertisement method could give potential income up to **44%**.
