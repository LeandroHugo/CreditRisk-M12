# Module-12-Challenge

# 📈💳 Credit Risk Classification: Unraveling the Mysteries of P2P Lending 🚀
Welcome aboard as we delve into the fascinating realm of peer-to-peer lending and the inherent credit risks! Our quest? To harness the predictive power of machine learning to identify borrower creditworthiness, helping to navigate the often unpredictable seas of financial lending. 🌊

## 🎯 The Objective:
Our journey involves splitting our data into training and testing sets, creating a Logistic Regression Model with the original data, and making predictions with a Logistic Regression Model utilizing resampled training data. The ultimate goal is to accurately predict credit risk, ensuring a safer lending journey.

## 📝 Your Tasks:
### 1️⃣ Split the Data into Training and Testing Sets
**Task 1:** 
- Load the historical lending dataset.

**Task 2:** 
- Divide the data into features (X) and the target label (y), with the "loan_status" column as our target. This indicates whether a loan is healthy (0) or high-risk (1).
  
**Task 3:** 
- Check the balance of the labels variable (y) using the value_counts function.
  
**Task 4:** 
- Use train_test_split to split the data into training and testing sets.

### 2️⃣ Create a Logistic Regression Model with the Original Data
**Task 5:** 
- Fit a logistic regression model using the training data.
  
**Task 6:** 
- Make predictions on the testing data using the model.
  
**Task 7:** 
- Evaluate the model's performance by calculating the accuracy score, generating a confusion matrix, and printing the classification report.
  
**Task 8:** 
- Reflect on the model's predictions on both 0 (healthy loan) and 1 (high-risk loan) labels.
### 3️⃣ Predict a Logistic Regression Model with Resampled Training Data
**Task 9:** 
- Resample the training data using the RandomOverSampler module from the imbalanced-learn library
  
**Task 10:** 
- Fit a Logistic Regression classifier to the resampled data and make predictions.
Task 11: Evaluate the model's performance as we did previously.

**Task 12:** 
- Reflect on how well the model with resampled data predicts both 0 (healthy loan) and 1 (high-risk loan) labels.
### 📄 Write a Credit Risk Analysis Report
**Task 13:** 
- Consolidate your findings into a brief report.
  
**Task 14:** 
- Summarize the performance of both machine learning models.

**Task 15:** 
- Compare the predictions made on the original and resampled data.

**Task 16:** 
- Provide recommendations based on your analysis.


We're thrilled to have you with us on this data-driven odyssey! Together, we'll decipher the riddles of credit risk classification and uncover hidden insights that lead to more accurate predictions. 🏝️

All Aboard! ⛵️🌅

🎉🚀🤖