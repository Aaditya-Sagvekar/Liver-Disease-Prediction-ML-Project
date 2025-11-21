# 🩺 Liver Disease Prediction Using Machine Learning

This project builds a machine learning model to predict the presence of **liver disease** based on patient medical attributes. Using classification algorithms and data preprocessing techniques, the model assists in early disease detection and decision support.

---

## 📁 Dataset

The dataset typically contains patient medical test results such as:

- **Age**
- **Gender**
- **Total Bilirubin**
- **Direct Bilirubin**
- **Alkaline Phosphatase (ALP)**
- **Alanine Aminotransferase (ALT)**
- **Aspartate Aminotransferase (AST)**
- **Total Proteins**
- **Albumin**
- **Albumin/Globulin Ratio**
- **Target Label (Liver Disease: 1 or 0)**

The goal is to classify whether the patient is **likely to have liver disease**.

---

## 🚀 Project Workflow

### **1. Data Preprocessing**
- Handling missing values  
- Label encoding categorical features  
- Scaling numerical features  
- Removing outliers (if required)

### **2. Exploratory Data Analysis (EDA)**
- Distribution plots  
- Correlation heatmap  
- Feature relationship analysis  

### **3. Model Building**
Models used may include:
- Logistic Regression  
- Random Forest Classifier  
- Support Vector Machine  
- K-Nearest Neighbors  
- Decision Tree Classifier  

### **4. Model Evaluation**
Performance metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

### **5. Deployment Assets**
The notebook may export:
- Trained model (`model.pkl`)
- Scaler object (`scaler.pkl`)
- Feature metadata  

These can be used in a Flask or Streamlit web app.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  
