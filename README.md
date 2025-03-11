# **💳 Credit Card Approval Prediction**

## 📌 Overview  
### **🎯 Objective: Business-Oriented Problem Statement**  

In today’s **fast-paced financial industry**, credit card companies face **increasing challenges** in accurately assessing **creditworthiness** while minimizing **default risks**. Traditional credit evaluation models often **fail to incorporate non-traditional data** and **struggle with imbalanced datasets**, leading to **higher rejection rates for eligible customers** and **increased financial risk due to misclassification**.  

This project aims to **bridge the gap** by leveraging **machine learning** to develop a **robust, data-driven credit approval system** that enhances **accuracy, fairness, and efficiency** in decision-making.  

---

### **📌 Business Problem Statement**  

💼 **Financial institutions** process **millions of credit card applications** annually. A poor credit evaluation system can result in:  

🔴 **High default rates** due to incorrectly approved applications  
🔴 **Lost revenue** from rejecting eligible customers  
🔴 **Customer dissatisfaction** and **regulatory compliance issues**  

To solve these challenges, this project introduces a **machine learning-based Credit Card Approval Prediction System**, designed to:  

✅ **Reduce default rates** by accurately classifying high-risk applicants  
✅ **Increase approval rates** for **creditworthy** individuals, boosting customer acquisition  
✅ **Enhance decision-making speed** and minimize manual processing  
✅ **Ensure fairness & compliance** with responsible AI practices  

By implementing **Gradient Boosting Classifier** and **SMOTE techniques**, this model **outperforms traditional rule-based credit scoring** and provides **scalable, real-time insights** for financial decision-makers. 🚀  

---

This version **positions your project as a real-world business solution**, making it attractive to potential **investors, banks, fintech companies, and data science teams** looking for **better credit risk management strategies**.  

Would you like me to refine it further with **industry stats** or **ROI benefits**? 📊💰


## 🚀 Key Features  
✔ **End-to-End ML Pipeline** (Preprocessing → Training → Deployment)  
✔ **Feature Engineering** (Outlier Removal, Encoding, Normalization)  
✔ **Gradient Boosting Classifier + SMOTE for Imbalance Handling**  
✔ **AWS S3 for Secure Model Storage**  
✔ **Interactive Streamlit Web App for Predictions**  

---

## 📂 Project Structure  
```
vivek12367-creditcard_approval/
│── app.py                # Streamlit web app
│── CC_approval.ipynb     # Jupyter Notebook (EDA & Model Training)
│── Data/
│   ├── train.csv         # Training dataset
│   ├── test.csv          # Testing dataset
│── Models/
│   ├── model.sav         # Trained model stored in AWS S3
```

---

## 📊 Dataset Overview  
The dataset consists of **demographic, financial, and employment details**.

| Feature               | Description                                      |
|----------------------|------------------------------------------------|
| **Gender**            | Applicant's gender (Male/Female) |
| **Age**               | Age in years |
| **Marital status**    | Married, Single, Civil Marriage, etc. |
| **Income**            | Applicant's monthly income (USD) |
| **Employment length** | Duration of employment (years) |
| **Education level**   | Highest qualification attained |
| **Has a car**        | Owns a car (Yes/No) |
| **Has a property**   | Owns property (Yes/No) |
| **Family size**      | Number of family members |
| **Has phone/email**  | Contact details presence |

---

## 🛠 ML Pipeline & Feature Engineering  
The **end-to-end pipeline** is built using **Scikit-Learn Pipelines** to ensure efficiency and automation.

### ✅ **1. Data Preprocessing**  
- **Outlier Removal** (IQR-based filtering)  
- **Missing Value Imputation**  
- **Categorical Encoding** (OneHotEncoder & OrdinalEncoder)  
- **Feature Scaling** (MinMaxScaler)  

### ✅ **2. Model Training**  
- **Algorithm**: Gradient Boosting Classifier  
- **Class Imbalance Handling**: SMOTE oversampling  
- **Feature Selection**: Based on SHAP importance  

### ✅ **3. Deployment**  
- **Model stored in AWS S3**  
- **Predictions served via Streamlit Web App**  

---

## 🖥️ How to Use the Web App  
### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your_username/vivek12367-creditcard_approval.git
cd vivek12367-creditcard_approval
```
### 2️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt
```
### 3️⃣ **Run the Streamlit App**  
```bash
streamlit run app.py
```
🔹 Open the link displayed in your **browser** and **start making predictions**!  

---

## 🎯 Future Improvements  
✅ Add **XGBoost & Random Forest Models**  
✅ Implement **Explainability (SHAP, LIME)**  
✅ Improve **UI/UX Styling** in Streamlit  

---

## 🤝 Contributing  
**Want to improve this project?** Follow these steps:  
1. **Fork** the repo  
2. **Create a new branch** (`git checkout -b feature-branch`)  
3. **Commit** changes (`git commit -m "Added feature X"`)  
4. **Push** and **Create a Pull Request** 🚀  

---

## 📜 License & Credits  
📌 **License**: MIT  
📌 **Author**: Vivek Chatla  
📌 **Reference**: [Credit Card Approval Prediction Blog](https://semasuka.github.io/blog/2022/10/12/credit-card-approval-prediction.html)  

🚀 **Star this repo if you find it useful!** ⭐  
