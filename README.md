# accedent-prediction-using-machine-learning
### **Accident Prediction Using Machine Learning**
Author: Usha rahul
Date: 05/01/2025
company: CodeTech IT Solutions
inturn ID: CT0806HT
Domain: Machine Learning
Batch duration: december 30th 2024 to February 14th 2025
Mentor name:Neela Santhosh Kumar
#### **Table of Contents**
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [Key Results](#key-results)
5. [Technologies Used](#technologies-used)
6. [Future Scope](#future-scope)
7. [How to Use](#how-to-use)

---

### **Overview**
This project involves building a machine learning model to predict road accidents based on traffic, vehicle, and driver-related attributes. The goal is to identify patterns that could help in reducing road accidents and improving safety measures.

---

### **Dataset**
- **Source**: Simulated or real-world accident dataset.
- **Features**:
  - Traffic Density
  - Speed Limit
  - Number of Vehicles
  - Driver Alcohol Consumption
  - Driver Age
  - Driver Experience
- **Target Variable**: 
  - `Accident` (0 = No Accident, 1 = Accident)

---

### **Project Workflow**
1. **Exploratory Data Analysis (EDA)**:
   - Statistical summary and visualizations to understand the dataset.
2. **Data Preprocessing**:
   - Addressed class imbalance using SMOTE.
   - Encoded categorical variables.
3. **Model Building**:
   - Built and visualized a Decision Tree Classifier.
   - Tuned hyperparameters using GridSearchCV.
4. **Model Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score.
   - Analyzed confusion matrix for minority and majority classes.

---

### **Key Results**
- **Accuracy**: 66.67%
- **Precision (Minority Class)**: 26.92%
- **Recall (Minority Class)**: 9.72%
- **F1-Score (Minority Class)**: 14.29%
- The model performed well for the majority class but struggled to identify accident cases due to class imbalance.

---

### **Technologies Used**
- **Python Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Imbalanced-learn
- **Tools**:
  - Jupyter Notebook
  
---
-**images
![image](https://github.com/user-attachments/assets/32173f77-0589-42be-95a6-73d7d0b85273)
![image](https://github.com/user-attachments/assets/6b1bbdac-35d2-4d57-91b2-cc4f2e3334a0)
![image](https://github.com/user-attachments/assets/9b122b78-6e8b-4b88-911f-bf2187b4d2ae)
![image](https://github.com/user-attachments/assets/690d62b9-aa11-4e58-b903-f53ea7b50826)
![image](https://github.com/user-attachments/assets/c9e37cc9-176e-4487-8f09-11a5a7cea567)


### **Future Scope**
1. Experiment with advanced models like **Random Forest**, **XGBoost**, or **LightGBM**.
2. Add features like weather conditions and road infrastructure details.
3. Develop a real-time prediction system integrated with GPS and traffic data.

---


