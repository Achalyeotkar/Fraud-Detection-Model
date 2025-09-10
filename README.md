# Fraud Detection Using Machine Learning  

## 📌 Project Overview  
This project was completed as part of my **Internship at Accredian (27th August 2025)**.  
The task was to build a **Fraud Detection Model** that can classify fraudulent vs. legitimate transactions using machine learning.  

The notebook walks through:  
- Data cleaning & preprocessing  
- Outlier detection  
- Exploratory data analysis (EDA)  
- Model training & evaluation  

---

## 📂 Dataset  
- **Source**: Provided during the internship (financial transactions dataset)  
- **Target Variable**:  
  - `0` → Legitimate transaction  
  - `1` → Fraudulent transaction  

---

## ⚙️ Methodology  
1. **Data Cleaning**  
   - Removed missing values  
   - Handled duplicates and inconsistent entries  

2. **Outlier Detection**  
   - Visualized distributions using histograms & boxplots  
   - Detected anomalies with statistical methods  

3. **Exploratory Data Analysis (EDA)**  
   - Distribution of fraud vs. non-fraud  
   - Correlation heatmaps  
   - Transaction amount analysis  

4. **Model Building**  
   - Logistic Regression  
   - Decision Tree / Random Forest  
   - Comparison of models  

5. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - ROC-AUC  

---

## 🛠️ Tools & Libraries  
- **Python**  
- **NumPy, Pandas** → Data processing  
- **Matplotlib, Seaborn** → Visualization  
- **Scikit-learn** → ML models & evaluation  

---

## 📊 Results  
- Logistic Regression achieved high recall (~92%) on fraud detection.  
- Random Forest provided better precision but required more computation.  
- Overall, the models highlight the challenge of **class imbalance** in fraud datasets.  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/fraud-detection.git
   cd fraud-detection

## 📂 Dataset  
Due to file size limitations, the dataset is stored externally.  

- [📥 Download Dataset (Google Drive)](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0-link-here)  
- Place the file inside the `data/` folder before running the notebook.  


