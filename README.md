# Heart-Disease-Prediction-ML-System

##  Project Overview  
This project develops a machine learning system to predict the likelihood of heart disease using patient health data. The goal is to support early detection and assist healthcare providers in identifying individuals at risk, enabling more proactive and preventative care.

The system uses supervised learning models to analyze patterns in clinical features such as age, cholesterol levels, blood pressure, and heart rate.

---

##  Objectives  
- Predict the presence of heart disease (binary classification)  
- Compare performance of multiple machine learning models  
- Identify the most effective model based on evaluation metrics  
- Demonstrate a complete ML workflow from data processing to prediction  

---

##  Machine Learning Models  
The following models are implemented and compared:

- Logistic Regression (baseline)  
- Random Forest (primary model)  
- Support Vector Machine (SVM)  

---

##  Dataset  
- Source: UCI Heart Disease Dataset  
- Includes features such as:
  - Age  
  - Sex  
  - Cholesterol  
  - Resting blood pressure  
  - Maximum heart rate  
  - Other clinical indicators  

---

##  Project Structure  

project/
├── data/
│   ├── raw/
│   └── processed/
├── models/
├── notebooks/
├── app/              # optional (Streamlit or FastAPI)
├── mlruns/           # if using MLflow
├── README.md
└── requirements.txt

---

##  How to Run the Project  

### 1. Clone the Repository  
git clone [[https://github.com/new ](https://github.com/kelseyjhock-svg/Heart-Disease-Prediction-ML-System  ) ](https://github.com/kelseyjhock-svg/Heart-Disease-Prediction-ML-System  )

### 2. Install Dependencies  
pip install -r requirements.txt  

### 3. Run Model Training  
python train.py  

### 4. (Optional) Run the App  

If using Streamlit:  
streamlit run app/app.py  

If using FastAPI:  
uvicorn app.main:app --reload  

---

##  Evaluation Metrics  
Model performance is evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

Recall is emphasized due to the importance of identifying high-risk patients.

---

##  Experiment Tracking  
Experiments track:
- Model type  
- Hyperparameters  
- Preprocessing steps  
- Evaluation metrics  

This ensures reproducibility and allows comparison across runs.

---

##  Model Versioning  
Trained models are saved and versioned (e.g., model_v1.pkl, model_v2.pkl) to track improvements and maintain reproducibility.

---

##  System Workflow  

Raw Data → Preprocessing → Feature Engineering → Model Training → Evaluation → Saved Model → Prediction  

---

##  Challenges  
- Limited dataset size  
- Class imbalance  
- Model tuning complexity  

---

##  Future Improvements  
- Use larger and more diverse datasets  
- Improve model interpretability (e.g., SHAP)  
- Deploy model in a real-world healthcare environment  
- Integrate real-time prediction capabilities  

---

##  Team Members  
- Kelsey Hock — [https://github.com/new ](https://github.com/kelseyjhock-svg/Heart-Disease-Prediction-ML-System  ) 

---

## 📎 Repository Link  
https://github.com/new  
