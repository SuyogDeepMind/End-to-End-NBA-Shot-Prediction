# 🏀 NBA Shot Predictor

An interactive Streamlit app to predict whether Kobe Bryant's shot will be **Made** or **Missed** using real historical game features.

## 📦 Features
- Inputs: shot distance, quarter, clutch moment, shot zone, and more.
- Model: XGBoost Classifier.
- Live prediction with confidence score.
- Fully responsive UI.

## 🚀 How to Run (Locally)
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🌐 Deployment (Streamlit Cloud)
1. Push this repo to GitHub.
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud).
3. Connect your GitHub and select the repo.
4. Make sure `app.py` is the entry file and `requirements.txt` is added.

## 📁 File Structure
```
app.py
xgboost_model.pkl
X_test.pkl
y_test.pkl
data.csv
requirements.txt
README.md
```

Enjoy predicting Kobe’s legendary shots!