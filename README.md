# 🩺 Multiple Disease Prediction System

A **Streamlit web application** that predicts the likelihood of three major diseases from user inputs using machine learning models:

- Diabetes
- Heart Disease
- Parkinson's Disease

The project includes the trained models, datasets and Jupyter notebooks used to build and evaluate each prediction model.

🔗 **Live Demo:** [https://multiple-disease-prediction-web-app-yhwy.onrender.com/](https://multiple-disease-prediction-web-app-yhwy.onrender.com/) 

---

## 🛠️ Tech Stack

| Area | Technology |
|---|---|
| Language | Python |
| Machine Learning | Scikit-learn, NumPy |
| Web App | Streamlit, streamlit-option-menu |
| Notebooks | Jupyter / Google Colab |
| Deployment | Render |

---

## 💡 Features

- Simple interface to switch between the three disease prediction models
- Quick predictions from values entered in input fields
- Models trained on real-world, publicly available datasets
- Training notebooks included so the models can be retrained and reproduced

---

## 📁 Project Structure

```
Multiple-Disease-Prediction/
│
├── app.py                             # Main Streamlit application
├── requirements.txt                   # Required Python libraries
├── README.md                          # Project documentation
│
├── dataset/                           # CSV datasets for training
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
├── saved_models/                      # Pre-trained ML models (.sav)
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   └── parkinsons_model.sav
│
└── colab_files_to_train_models/       # Jupyter notebooks for training models
    ├── Multiple disease prediction system - diabetes.ipynb
    ├── Multiple disease prediction system - heart.ipynb
    └── Multiple disease prediction system - Parkinsons.ipynb
```

---

## 🚀 Run Locally

```bash
git clone https://github.com/srishty02/Multiple-Disease-Prediction.git
cd Multiple-Disease-Prediction
pip install -r requirements.txt
streamlit run app.py
```

The app opens in your default browser.

---

## 📚 Datasets Used

- **Diabetes:** [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Heart Disease:** [Cleveland Heart Disease Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Parkinson's Disease:** [UCI Parkinson's Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)

---

## 📌 Future Enhancements

- Add more disease prediction modules
- Improve the UI/UX with a more modern layout
- Integrate explainable AI (XAI) for model interpretation

---

## ⚠️ Disclaimer

This project is for learning and demonstration purposes only. It is not a medical tool and should not be used for diagnosis. Please consult a doctor for any health concern.

---

## 👩‍💻 Author

**Srishty Kumari**
[LinkedIn](https://www.linkedin.com/in/srishty-kumari-14b56b272/) · [GitHub](https://github.com/srishty02) · srishty0208@gmail.com
