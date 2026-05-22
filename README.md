# ❤️ Heart Disease Prediction System

A Machine Learning project that predicts the likelihood of heart disease based on patient health parameters. This project uses data preprocessing, exploratory data analysis (EDA), feature selection, and multiple machine learning algorithms to determine the most accurate prediction model.

---

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help reduce risk and support preventive healthcare decisions.

This project analyzes patient medical data and predicts whether a person has heart disease using machine learning techniques.

The workflow includes:

- Data collection and preprocessing
- Exploratory Data Analysis (EDA)
- Feature analysis and visualization
- Training multiple ML models
- Comparing model performance
- Predicting heart disease from user input

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- StatsModels
- FancyImpute

---

## 📂 Dataset Information

The dataset contains patient health information such as:

| Feature | Description |
|-----------|-------------|
| Age | Age of patient |
| Sex | Male = 1, Female = 0 |
| Chest Pain Type | Different chest pain categories |
| Resting Blood Pressure | Blood pressure at rest |
| Cholesterol | Serum cholesterol level |
| Fasting Blood Sugar | Blood sugar > 120 mg/dl |
| Rest ECG | Electrocardiographic results |
| Maximum Heart Rate | Maximum heart rate achieved |
| Exercise Induced Angina | Presence of exercise-induced chest pain |
| ST Depression | ST depression induced by exercise |
| ST Slope | Slope of peak exercise ST segment |
| Number of Major Vessels | Number of vessels detected |
| Thalassemia | Blood disorder category |
| Target | Heart Disease (1 = Yes, 0 = No) |

---

## 📊 Exploratory Data Analysis (EDA)

Several visualizations were performed to understand patterns in the dataset:

- Distribution of heart disease cases
- Age vs heart disease frequency
- Gender-based analysis
- Cholesterol analysis
- Fasting blood sugar analysis
- Correlation heatmaps
- Thalassemia relationships

---

## 🤖 Machine Learning Models Used

The project trains and compares multiple algorithms:

### 1. Naive Bayes
- Gaussian Naive Bayes classifier
- Fast and simple probabilistic model

### 2. Decision Tree
- Entropy-based Decision Tree
- Easy interpretation of predictions

### 3. Logistic Regression
- Binary classification model
- Used for heart disease prediction

---

## 📈 Model Evaluation

Performance metrics used:

- Accuracy Score
- Confusion Matrix
- False Negative Rate (FNR)

Final model comparison is visualized using bar charts.

Example:

| Algorithm | Accuracy |
|------------|-----------|
| Logistic Regression | Best Performing |
| Naive Bayes | Moderate |
| Decision Tree | Moderate |

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Heart-Disease-Prediction.git
```

Move into project directory:

```bash
cd Heart-Disease-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
HeartDiseasePred.ipynb
```

---

## ▶️ How to Run

1. Open the notebook
2. Execute cells sequentially
3. Train models
4. Compare model performance
5. Enter patient details when prompted
6. Receive prediction output

Example user input:

```text
Enter age: 45
Male=1 Female=0: 1
Chest Pain Type: 2
Resting Blood Pressure: 130
Cholesterol: 250
...
```

Prediction Output:

```text
Heart Disease Detected
```

or

```text
No Heart Disease Detected
```

---

## 📁 Project Structure

```text
Heart-Disease-Prediction/
│
├── HeartDiseasePred.ipynb
├── heart.csv
├── user_input.csv
├── heartDiseaseAndAges.png
├── pt.dot
├── README.md
└── requirements.txt
```

---

## 🔮 Future Improvements

- Build a web application using Flask or Django
- Add real-time prediction interface
- Improve model accuracy using ensemble techniques
- Hyperparameter tuning
- Deploy model using cloud services
- Add feature importance visualization

---

## ⚠ Disclaimer

This project is developed for educational and research purposes only. It should not be used as a replacement for professional medical diagnosis.
