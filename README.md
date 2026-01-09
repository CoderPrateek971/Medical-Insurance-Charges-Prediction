# Medical Insurance Charges Prediction 📊

## 📌 Project Overview
This project is a **Data Analytics Using Python (DAP) mini project** focused on analyzing and predicting **medical insurance charges** based on personal and lifestyle attributes. The project combines **Exploratory Data Analysis (EDA)**, **statistical hypothesis testing**, and **machine learning (Linear Regression)** to identify key cost-driving factors.

---

## 🎯 Objectives
- Analyze the Medical Insurance Charges dataset to identify important factors affecting insurance costs  
- Statistically validate differences in charges between smokers and non-smokers  
- Build a Linear Regression model to predict insurance charges  
- Evaluate model performance using standard regression metrics  

---

## 📂 Dataset Description
- **Total records:** 1,337 (after cleaning)
- **Target variable:** `charges`
- **Features used:**
  - age
  - sex
  - bmi
  - children
  - smoker  
- The `region` feature was excluded to keep the baseline model focused.

---

## 🛠️ Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- SciPy
- Scikit-learn

---

## 🔍 Methodology
1. **Data Cleaning & Preprocessing**
   - Removed duplicate records
   - Converted categorical variables using mapping
   - Feature scaling using StandardScaler

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis of insurance charges
   - Correlation heatmap
   - Scatter plots for multivariate analysis

3. **Statistical Analysis**
   - Independent Two-Sample T-Test
   - Compared insurance charges between smokers and non-smokers

4. **Predictive Modeling**
   - Linear Regression model
   - 80/20 train-test split
   - Model evaluation using R², MAE, and RMSE

---

## 📈 Key Findings
- **Smoker status** is the strongest predictor of insurance charges  
- Charges increase significantly faster with age for smokers  
- Statistical tests confirmed a highly significant difference between smokers and non-smokers  
- Linear Regression model explained **~80% of the variance** in insurance charges  

---

## 📊 Model Performance
- **R² Score:** 0.8046  
- **Mean Absolute Error (MAE):** ~$4,198  
- **Root Mean Square Error (RMSE):** ~$5,991  

---

## 🧠 Conclusion
Lifestyle choices, particularly **smoking**, along with **age and BMI**, play a dominant role in determining medical insurance costs. The statistical evidence strongly supports the visual patterns observed in EDA and directly contributes to the predictive power of the regression model.

---

## 🤖 Use of AI Tools
- Tool Used: Gemini 2.5 Pro  
- Purpose: Minor language refinement and code verification  
- AI Usage: ~3% (as per Quillbot)  

---

## 👨‍💻 Author
**Prateek Garg**  
CSE (V)  
Data Analytics Using Python  

---

## 📜 License
This project is intended for academic and learning purposes.
