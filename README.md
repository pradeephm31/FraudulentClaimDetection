# FraudulentClaimDetection
# FraudulentClaimDetection
> Global Insure, a major player in the insurance industry, is experiencing substantial financial losses due to a high volume of fraudulent claims. The existing fraud detection system relies heavily on manual inspections, which are not only time-consuming and labour-intensive but also inefficient. As a result, many fraudulent claims are detected only after payouts have been made, limiting the company's ability to prevent losses and straining operational resources.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Problem Statement
	-  &nbsp;&nbsp;&nbsp;&nbsp;Global Insure, a major player in the insurance industry, is experiencing substantial financial losses due to a high volume of fraudulent claims. The existing fraud detection system relies heavily on manual inspections, which are not only time-consuming and labour-intensive but also inefficient. As a result, many fraudulent claims are detected only after payouts have been made, limiting the company's ability to prevent losses and straining operational resources.


- Data Set
	- insurance_claims set was considered which has all the attributes contributing to the fraudulent insurance claims 
	 
- Approach for analysis
1. Data Preparation and Cleaning	
	- This step involves handling missing , datatypes

2. EDA
	- This step involves reading and understanding the dataset via Visualization

3. Feature Engineering
	- This part focuses on selecting and creating the relevant set of features for Model
   
4. Model Building
	- This part focuses on building model Logistic Regression and Random Forest Models.

5. Predictions and Model Evaluation
	- Model Predictions with Test Set and Evaluation.




## Conclusions	
- Outcome of Predictions and Model Evaluation
	### 🔹 Probability Cutoff Chosen
- **0.565**

---

### 📊 Logistic Regression Model

#### 🧪 Training Set Metrics
- **Accuracy**: 0.8766  
- **Sensitivity (Recall)**: 0.8777  
- **Specificity**: 0.8755  
- **Precision**: 0.8758  
- **F1 Score**: 0.8767  

#### 🧪 Validation Set Metrics
- **Accuracy**: 0.8388  
- **Sensitivity (Recall)**: 0.8194  
- **Specificity**: 0.8458  
- **Precision**: 0.6556  
- **F1 Score**: 0.7284  

---

### 🌲 Random Forest Model

#### 🔧 Best Hyperparameters Found
- `max_depth`: 10  
- `max_features`: 12  
- `min_samples_leaf`: 10  
- `min_samples_split`: 20  
- `n_estimators`: 20  

#### 🧪 Training Set Metrics
- **Accuracy**: 0.8863  
- **Sensitivity (Recall)**: 0.9206  
- **Specificity**: 0.8519  
- **Precision**: 0.8614  
- **F1 Score**: 0.8900  

#### 🧪 Validation Set Metrics
- **Accuracy**: 0.8388  
- **Sensitivity (Recall)**: 0.8889  
- **Specificity**: 0.8209  
- **Precision**: 0.6400  
- **F1 Score**: 0.7442  


## Technologies Used
- pandas - version 2.2.2
- numpy - version 1.26.4
- matplotlib - version 3.8.4
- seaborn - version 0.13.2
- scikit-learn - version 1.4.2
- statsmodels - version 0.14.2



## Acknowledgements
Give credit here.
- This project was inspired by Machine Learning Course and Lecture Notes as part of IIIT-B PG Program in a ML and AI


## Contact
Created by [@pradeephm31] - feel free to contact me!