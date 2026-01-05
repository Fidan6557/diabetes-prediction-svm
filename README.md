# 🏥 Diabetes Prediction using Support Vector Machine (SVM)

This project focuses on building a robust Machine Learning model to predict diabetes in patients based on specific medical metrics. It utilizes the **Support Vector Machine (SVM)** algorithm for binary classification.

## 📌 Project Overview
The primary goal is to provide an early-stage diagnostic tool for diabetes using clinical data. By processing features such as Glucose, BMI, and Age, the model can classify whether a patient is diabetic or not.

## 📊 Technologies & Libraries
The following tools and libraries were used to develop this project:
* **Python**: The core programming language.
* **Pandas & NumPy**: For data manipulation and numerical operations.
* **Scikit-learn**: 
    * `svm`: To implement the Support Vector Classifier.
    * `StandardScaler`: For data normalization to improve model performance.
    * `train_test_split`: To create training and evaluation datasets.
* **Matplotlib & Seaborn**: For exploratory data analysis (EDA) and data visualization.

## 🛠️ Project Workflow
1. **Data Preprocessing**: Analyzed the statistical summary and checked the distribution of the outcome.
2. **Standardization**: Since SVM is sensitive to feature scaling, `StandardScaler` was applied to normalize the input data.
3. **Data Partitioning**: The data was split into Training (80%) and Testing (20%) sets using stratified sampling.
4. **Model Training**: A Support Vector Machine classifier with a **linear kernel** was trained on the standardized data.
5. **Prediction System**: Built a logic that allows real-time prediction for individual clinical inputs.

## 📈 Model Evaluation
The model achieved a reliable accuracy on both training and test data:

| Metric | Accuracy Score |
| :--- | :--- |
| **Training Accuracy** | 78.33% |
| **Test Accuracy** | 77.27% |

### Visual Insights


* **Feature Distribution**: The histogram plots visualize the frequency of medical readings across the dataset.
* **Diabetes vs Age**: The analysis shows a significant trend in diabetes outcomes across different age groups.



## 🚀 How to Use the Predictive System
You can input raw medical data to get an instant prediction. 
Input format: `(Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age)`

* **Output 1**: The person is diabetic.
* **Output 0**: The person is not diabetic.
* <img width="989" height="590" alt="download" src="https://github.com/user-attachments/assets/7d667472-9c9c-4a0f-a7ad-f6ebf217a33d" />


## 📂 Dataset
The model is trained on the **Pima Indians Diabetes Dataset**.
