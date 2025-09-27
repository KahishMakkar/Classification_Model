# Loan Prediction Case Study

## 📌 Project Overview
This project focuses on building machine learning models to predict **loan approval status** based on applicant details.  
The goal is to assist financial institutions in identifying eligible applicants efficiently using data-driven approaches.

## 📊 Dataset
- **Train file (`train.csv`)**: Contains applicant features and the loan approval status (target).
- **Test file (`test.csv`)**: Contains applicant features without the target (used for final predictions).
- **Target variable**: `Loan_Status` (1 = Approved, 0 = Not Approved)

### Key Features
- Applicant income  
- Co-applicant income  
- Loan amount  
- Loan term  
- Credit history  
- Gender, marital status, dependents, education, employment type, property area  

---

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy (data handling)  
- Matplotlib, Seaborn (visualization)  
- Scikit-learn (model building & evaluation)  

---

## 🚀 Approach
1. **Data Preprocessing**
   - Handled missing values
   - Encoded categorical variables
   - Scaled numerical features
   - Split data into train and validation sets  

2. **Exploratory Data Analysis (EDA)**
   - Distribution of loan approval by applicant characteristics
   - Correlation between numerical variables
   - Impact of credit history on loan status  

3. **Model Training**
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  

4. **Evaluation Metrics**
   - Accuracy Score  
   - Confusion Matrix  
   - Precision, Recall, F1-Score  

---

## 📈 Results
| Model                  | Accuracy |
|-------------------------|----------|
| Logistic Regression     | 81%      |
| Decision Tree Classifier| 79%      |
| Random Forest Classifier| 78%      |

> 🔑 **Final Model Chosen**: **Logistic Regression** (due to its simplicity, interpretability, and strong performance).  

---


