# 🚦 Traffic Accident Severity Prediction

An interactive Machine Learning web application that predicts the **severity of traffic accidents** using a **Random Forest Classifier**. The application provides accident severity prediction, dataset exploration, data analytics, and visual insights through an interactive **Streamlit dashboard**.

---

## 📌 Project Overview

Traffic accidents can vary in severity depending on several factors such as road conditions, weather, traffic conditions, and other accident-related features.

This project uses Machine Learning to analyze historical traffic accident data and predict the **severity level of an accident**.

The system provides an easy-to-use web interface where users can explore the dataset, view analytics, and make predictions using the trained Machine Learning model.

---

## 🎯 Objectives

* Predict traffic accident severity using Machine Learning.
* Analyze important factors related to accident severity.
* Provide an interactive Dataset Explorer.
* Visualize accident-related statistics and patterns.
* Build a user-friendly Streamlit web application.
* Demonstrate the practical application of Random Forest classification.

---

## ✨ Key Features

### 🚗 Accident Severity Prediction

Enter accident-related information and get a predicted severity level using the trained Random Forest model.

### 📊 Analytics Dashboard

Explore accident data through interactive statistics and visualizations.

### 🔍 Dataset Explorer

View the available dataset, rows, columns, and basic dataset information directly from the application.

### 🤖 Machine Learning Model

Uses a trained **Random Forest Classifier** for accident severity prediction.

### 📈 Data Visualization

Provides graphical insights into accident patterns and severity distribution.

### 💻 Interactive Web Interface

Built using Streamlit for a simple and user-friendly experience.

### 💾 Saved Model

The trained Machine Learning model is stored using Pickle and loaded by the application for prediction.

---

## 🛠️ Technologies Used

| Technology    | Purpose               |
| ------------- | --------------------- |
| Python        | Programming Language  |
| Pandas        | Data Processing       |
| NumPy         | Numerical Computation |
| Scikit-learn  | Machine Learning      |
| Random Forest | Classification Model  |
| Streamlit     | Web Application       |
| Matplotlib    | Data Visualization    |
| Seaborn       | Data Visualization    |
| Pickle        | Model Serialization   |

---

## 📂 Project Structure

```text
Traffic Accident Severity Prediction/
│
├── Road.csv
│
├── models/
│   ├── traffic_accident_severity_model.pkl
│   └── target_classes.pkl
│
├── traffic_accident_severity_app.py
│
└── README.md
```

---

## 📊 Dataset

The project uses the `Road.csv` dataset containing traffic accident-related information.

The dataset is used for:

* Data exploration
* Data preprocessing
* Feature analysis
* Model prediction
* Analytics and visualization

---

## 🧠 Machine Learning

### Algorithm Used

**Random Forest Classifier**

Random Forest is an ensemble Machine Learning algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

### Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train/Test Split
   ↓
Random Forest Model
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Save Model
   ↓
Streamlit Application
   ↓
Accident Severity Prediction
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Traffic-Accident-Severity-Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd Traffic-Accident-Severity-Prediction
```

### 3. Install Required Libraries

```bash
pip install pandas numpy scikit-learn streamlit matplotlib seaborn
```

### 4. Run the Streamlit Application

```bash
streamlit run traffic_accident_severity_app.py
```

The application will open in your browser.

---

## 🖥️ Application Modules

### 🏠 Home

Provides an overview of the Traffic Accident Severity Prediction project.

### 🔮 Prediction

Allows users to enter accident-related details and receive a predicted accident severity.

### 📊 Analytics Dashboard

Displays statistics, charts, and insights from the accident dataset.

### 🔍 Dataset Explorer

Allows users to inspect the dataset and understand its structure.

### 🤖 Model Information

Provides information about the Machine Learning model used for prediction.

---

## 🎯 Use Cases

This project can be useful for:

* 🚦 Road safety analysis
* 🚗 Traffic accident analysis
* 📊 Accident data visualization
* 🤖 Machine Learning demonstrations
* 🛣️ Intelligent transportation research
* 🎓 Academic Machine Learning projects

---

## 🔮 Future Improvements

* Integrate real-time traffic and weather data.
* Add more Machine Learning algorithms for comparison.
* Improve model accuracy through hyperparameter tuning.
* Add interactive maps for accident locations.
* Deploy the application on Streamlit Cloud.
* Add real-time accident risk prediction.
* Implement advanced explainable AI techniques.

---

## 📸 Project Highlights

The application combines:

**Machine Learning + Data Analytics + Visualization + Interactive Web Application**

to create a complete end-to-end Traffic Accident Severity Prediction system.

---

## 👩‍💻 Author

**Vaishnavi Dawkhar**

Machine Learning & Full Stack Development Enthusiast

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub!

---

## 📜 License

This project is created for educational and demonstration purposes.
