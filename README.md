#### Task-Aryaai

#### **problem Statement** 
- Perform Binary Classification on given train/test data which have 57 feature and Target variable

#### **EDA**
- I have performed some descriptive statistics to get a proper understanding of data which shows data have sparse columns and features are heavily Skewed. 

#### **Feature selection**
- I have used a tree-based embedded algorithm and mutual information as a measure of feature importance. Ranked them accordingly which feature affects the target variable most.

#### **Preprocessing**
- Data provided does not have any missing value. I have tried various models on data for classification in which  Decision trees and ensemble methods perform best so I have skipped Scaling as They do not require feature scaling to be performed as they are not sensitive to the variance in the data.

#### **Final Model**
I have selected XGBoost Algorithm as it performs well from other algorithms for this problem.
Result for XGBoost Model :  
- Accuracy: 95%
- AUC: 0.98
 
