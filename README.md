# 📢 Validating-Model-ad-sale-prediction using Logistic Regression

This project predicts whether an **existing customer** will purchase a product after viewing a **digital advertisement** using **Logistic Regression**.

---

## ❓ Why This Project
- Advertising companies want to maximize ROI by targeting **the right customers**.  
- Not every customer shown an ad will make a purchase.  
- By building a prediction model, businesses can:  
  - Reduce advertising costs  
  - Improve targeting efficiency  
  - Increase conversion rates  

This project shows how machine learning can help businesses **predict customer behavior**.

---

## ⚙️ How It Works
1. **Data Loading** – Import the dataset (`DigitalAd_dataset.csv`) with customer demographics and ad-click behavior.  
2. **Exploratory Data Analysis (EDA)** – Visualize patterns like age vs purchase, income vs purchase.  
3. **Preprocessing** – Clean dataset, select relevant features.  
4. **Model Training** – Train a **Logistic Regression classifier** using scikit-learn.  
5. **Prediction** – Predict whether a customer buys a product after viewing an ad.  
6. **Evaluation** – Measure accuracy, precision, recall, and confusion matrix.  

---

## 📂 Dataset
- **File:** `DigitalAd_dataset.csv`  
- Contains customer information and ad-purchase behavior.  
- Example features:
  - `UserID`
  - `Age`
  - `EstimatedSalary`
  - `Purchased` (target variable – 0 = No, 1 = Yes)

---

## 🛠️ Technologies & Libraries
- Python 3.x  
- [pandas](https://pandas.pydata.org/) – Data handling  
- [numpy](https://numpy.org/) – Numerical computations  
- [matplotlib](https://matplotlib.org/) – Data visualization  
- [seaborn](https://seaborn.pydata.org/) – Statistical visualization  
- [scikit-learn](https://scikit-learn.org/stable/) – Logistic Regression model  

---

## 📊 Project Workflow
1. Import required libraries.  
2. Load and explore dataset.  
3. Visualize dataset distributions.  
4. Train Logistic Regression model.  
5. Make predictions.  
6. Evaluate performance metrics.  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sachin-183/Validating-Model-ad-sale-prediction.git
   cd Validating-Model-ad-sale-prediction
