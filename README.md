
# 🩺 Multiple Disease Prediction System

A **Streamlit web application** that allows users to predict the likelihood of three major diseases using machine learning models:

- Diabetes
- Heart Disease
- Parkinson's Disease

This project includes trained models, datasets, and interactive notebooks used to build and evaluate each disease-specific prediction system.

---

## 🚀 Live Demo

You can run the application locally by following the steps below.

---

## 📁 Project Structure

```
multiple-disease-prediction-streamlit-app/
│
├── app.py                             # Main Streamlit application
├── requirements.txt                  # Required Python libraries
├── README.md                         # Project documentation
│
├── dataset/                          # CSV datasets for training
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
│
├── saved_models/                     # Pre-trained ML models (.sav)
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   └── parkinsons_model.sav
│
└── colab_files_to_train_models/     # Jupyter Notebooks for training models
    ├── Multiple disease prediction system - diabetes.ipynb
    ├── Multiple disease prediction system - heart.ipynb
    └── Multiple disease prediction system - Parkinsons.ipynb
```

---

## ⚙️ How to Run the App

### 🔧 Requirements

- Python 3.7 or later
- Streamlit
- Scikit-learn
- Pandas
- NumPy

### 📥 Installation

1. Clone this repository or download the zip file:
   ```bash
   git clone https://github.com/your-username/multiple-disease-prediction-streamlit-app.git
   cd multiple-disease-prediction-streamlit-app
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:
   ```bash
   streamlit run app.py
   ```

4. The app will open in your default browser.

---

## 💡 Features

- Intuitive UI to select and test each disease prediction model
- Secure and lightweight models trained using real-world datasets
- Quick predictions based on user input via sliders and fields
- Model training notebooks included for transparency and reproducibility

---

## 📊 Model Training

Each disease prediction model was trained using classic ML algorithms (e.g., Logistic Regression, SVM, etc.) using relevant datasets. You can retrain models using the provided Jupyter notebooks under `/colab_files_to_train_models`.

---

## 📚 Datasets Used

- **Diabetes**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Heart Disease**: [Cleveland Heart Disease Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Parkinson's Disease**: [UCI Parkinson’s Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)

---

## 📌 Future Enhancements

- Add more disease prediction modules
- Enhance UI/UX with modern layout
- Deploy the app on a cloud platform (Streamlit Cloud, Heroku, etc.)
- Integrate explainable AI (XAI) for model interpretation

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project, feel free to fork the repository and open a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

**Srishty Kumari** 
Connect on [LinkedIn][((https://www.linkedin.com/in/srishty-kumari-14b56b272/) 
Email: srishty0208@gmail.com
