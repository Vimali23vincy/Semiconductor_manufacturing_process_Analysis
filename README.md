
# Semiconductor Manufacturing Process - Pass/Fail Prediction

## 📌 Project Overview
This project aims to **predict the yield outcome (Pass or Fail)** of a semiconductor manufacturing process using machine learning.  
By analyzing high-dimensional sensor data, we identify the most important factors that influence the final product quality.  
The project involves **data cleaning, visualization, preprocessing, model building, and evaluation**.

---

## 🎯 Objective
To build and compare multiple supervised learning models to accurately predict whether a product will **Pass (-1)** or **Fail (1)** during the manufacturing process.  
The final best-performing model is saved and can be deployed for future predictions.

---

## 🛠 Steps Performed
### 1. **Data Cleaning**
- Handled missing values and removed irrelevant attributes.
- Corrected data inconsistencies to ensure quality.

### 2. **Exploratory Data Analysis (EDA)**
- Univariate, bivariate, and multivariate analysis to understand patterns.
- Visualized target distribution and feature relationships.

### 3. **Data Preprocessing**
- Separated features (**X**) and target (**y**).
- Balanced target classes using **SMOTE**.
- Performed **train-test split** (80-20).
- Standardized features for consistency.

### 4. **Model Building**
Trained and tuned multiple models:
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Naive Bayes

Used **GridSearchCV** for hyperparameter tuning and cross-validation.

### 5. **Model Evaluation**
- Compared models based on **training and testing accuracy**.
- Selected the **best-performing model (SVM)** for deployment.
- Saved the final model as `best_model.pkl`.

---

## 📊 Results
| Model              | Train Accuracy | Test Accuracy |
|--------------------|---------------|---------------|
| Logistic Regression| 0.90          | 0.88          |
| Random Forest      | 0.99          | 0.94          |
| SVM (Best Model)   | 0.95          | **0.96**      |
| Naive Bayes        | 0.85          | 0.83          |

**SVM** achieved the highest test accuracy, making it the most reliable model for predicting product quality.

---

## 🚀 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/semiconductor-yield-prediction.git
   ```
2. Navigate to the project folder:
   ```bash
   cd semiconductor-yield-prediction
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## 📂 Project Structure
```
├── Semiconductor_Manufacturing_Process.ipynb   # Main notebook
├── signal-data.csv                              # Dataset 
├── best_model.pkl                               # Saved best model (SVM)
└── README.md                                    # Project documentation
```

---

## 👨‍💻 Author
- **Name:** Vimali vincy M
- **Email:** vincymicheal123@gmail.com  
- **LinkedIn:** https://www.linkedin.com/in/vimalivincy-m

