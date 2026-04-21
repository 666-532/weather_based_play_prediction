# Weather-Based Play Prediction (Machine Learning Project)

## 📌 Project Overview

This project builds a machine learning classifier that predicts whether a game should be **played or not played** based on weather conditions. The model learns patterns from historical weather data to make predictions about the target variable **Play**.

The dataset includes weather-related features such as **Outlook, Temperature, Humidity, and Wind**, which influence the decision of playing an outdoor game.

The trained model achieved an accuracy score of **89.86%**, demonstrating strong predictive capability on the dataset.

---

## 📊 Dataset Features

The dataset contains the following attributes:

* **Outlook** – Weather condition (Sunny, Overcast, Rain)
* **Temperature** – Temperature level
* **Humidity** – Humidity level
* **Wind** – Wind condition
* **Play** – Target variable indicating whether to play or not

The **Day** column was removed during preprocessing because it does not contribute to prediction.

---

## ⚙️ Machine Learning Workflow

The project follows a standard machine learning pipeline:

1. **Data Loading**
2. **Data Preprocessing**

   * Removing unnecessary columns
   * Handling categorical data
3. **Feature Selection**
4. **Splitting Data into Features (X) and Target (y)**
5. **Model Training**
6. **Model Evaluation**

---

## 📈 Model Performance

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC Curve

Final **Model Accuracy: 89.86%**

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```
weather-play-classifier/
│
├── dataset.csv
├── weather_play_classifier.ipynb
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/weather-play-classifier.git
```

2. Navigate to the project folder

```
cd weather-play-classifier
```

3. Install required libraries

```
pip install -r requirements.txt
```

4. Run the Jupyter Notebook

```
jupyter notebook
```

---

## 🎯 Project Goal

The goal of this project is to demonstrate the **basic machine learning workflow for classification problems**, including preprocessing, model training, and evaluation.

---

## 👨‍💻 Author

**Abdullah Satti**
BS Artificial Intelligence Student
