# 📱 Cellphone Price Prediction

## 📌 Description
This project predicts **cellphone prices** using **Linear Regression** with **RAM** as the primary predictor variable.  
The dataset (`Cellphone.csv`) is preprocessed to ensure clean and consistent data. Outliers are handled using **Winsorization**, and exploratory analysis is performed with **boxplots** and statistical summaries.  

---

## ⚙️ Workflow
1. **Data Import & Exploration**
   - Loaded dataset using Pandas
   - Performed `.head()`, `.tail()`, `.describe()`, `.info()`, `.shape`, `.size`
   - Checked for missing values

2. **Data Preprocessing**
   - Outlier handling with **Winsorization**
   - Boxplot visualization for feature distribution

3. **Model Training**
   - Feature: `RAM`
   - Target: `Price`
   - Train-test split (80/20)
   - Trained **Linear Regression model**

4. **Model Evaluation**
   - Mean Absolute Error (MAE): `≈ 223`
   - Mean Squared Error (MSE): `≈ 74,607`
   - R² Score: `≈ 0.68`

5. **Visualization**
   - Relationship between **RAM vs Price** plotted for train and test sets

---

## 📊 Results
- **MAE:** 222.73  
- **MSE:** 74,607.26  
- **R² Score:** 0.68  

This demonstrates a **moderate correlation** between RAM and Price, showing that preprocessing and feature selection significantly impact prediction accuracy.

---

## 🛠️ Technologies Used
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Scikit-learn**  
- **SciPy (Winsorization)**  

---

# Run the script
python main.py
