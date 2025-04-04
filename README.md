# 🫀 Cardio Disease Prediction using Deep Learning

This project uses a cleaned cardiovascular dataset and a deep learning model built with TensorFlow/Keras to predict whether a patient is likely to have a cardiovascular condition.

## 📊 Dataset
- **Source**: [Kaggle - Cardiovascular Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
- **Format**: CSV
- **Features**: Age, Height, Weight, BP, Cholesterol, Glucose, Lifestyle, etc.
- **Target**: `cardio` (1 = Disease, 0 = No Disease)

## 🚀 Features
- End-to-end pipeline (Cleaning → Feature Engineering → Scaling → Modeling)
- Deep Neural Network with BatchNorm & Dropout
- Accuracy over 70% on test data
- Correlation Heatmap for feature analysis

## 🧠 Tech Stack
- Python, Pandas, NumPy
- TensorFlow / Keras
- Seaborn / Matplotlib
- Scikit-learn

## 🛠️ Folder Structure
cardio-disease-prediction/ │ ├── data/ │ └── cardio_train.csv │ ├── notebooks/ │ └── EDA_and_Modeling.ipynb │ ├── model/ │ └── cardio_model.h5 │ ├── static/ │ └── styles.css │ ├── app.py ├── requirements.txt├── README.md 

## 📈 Model Performance
- Validation Accuracy: ~XX% (update based on result)
- Loss curves & accuracy plots provided

## 🔍 How to Run
1. Clone the repo:
```bash
git clone https://github.com/yourusername/cardio-disease-prediction.git

pip install -r requirements.txt
python app.py
