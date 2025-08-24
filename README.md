# 🏥 Healthcare Cost Prediction

This project is part of the **FreeCodeCamp Machine Learning curriculum**.  
It predicts a person’s **medical expenses** using demographic and lifestyle information with a regression model built in **TensorFlow/Keras**.

---

## 📌 Dataset
- Dataset: [Medical Cost Personal Dataset](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv)  
- Features:
  - `age`: Age of the person  
  - `sex`: Male/Female  
  - `bmi`: Body Mass Index  
  - `children`: Number of children covered by health insurance  
  - `smoker`: Yes/No  
  - `region`: US region (northwest, southwest, southeast, northeast)  
- Target:
  - `expenses`: Annual medical costs (USD)  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn (train/test split, preprocessing)  
- TensorFlow / Keras (Deep Learning Model)  

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/healthcare-cost-prediction.git
   cd healthcare-cost-prediction
   pip install -r requirements.txt
   jupyter notebook healthcare_cost_prediction.ipynb
