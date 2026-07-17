# 📚 Student Performance Tracker

A Machine Learning project that predicts a student's final academic performance using the **UCI Student Performance Dataset**. The project performs data preprocessing, exploratory data analysis (EDA), model training, evaluation, and generates performance reports for students.

---

## 🚀 Features

- Uses the **UCI Student Performance Dataset**
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation analysis
- Performance category generation
- Multiple regression models comparison
- Automatic best model selection
- Student performance prediction
- Cross-validation
- Feature importance analysis
- Tracker report generation
- Model serialization for future use

---

## 📂 Dataset

Dataset Source:
- **UCI Machine Learning Repository**
- Student Performance Dataset

The dataset is automatically downloaded using the `ucimlrepo` package.

Target variable:

- **G3** (Final Grade)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- UCI ML Repository API

---

## 📊 Workflow

### 1. Data Collection

- Load Student Performance dataset
- Create DataFrame

### 2. Data Preprocessing

- Handle missing values
- Separate numerical and categorical features
- Standardize numerical features
- Encode categorical variables

### 3. Exploratory Data Analysis

- Final grade distribution
- Correlation analysis
- Performance category visualization

### 4. Model Training

The following regression algorithms are trained and compared:

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

### 5. Model Evaluation

Models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model with the highest R² score is automatically selected.

---

### 6. Cross Validation

5-Fold Cross Validation is performed to evaluate model robustness.

---

### 7. Student Prediction

The notebook includes a function to predict the final grade of a new student by providing their academic and demographic information.

Example output:

- Predicted Final Grade
- Predicted Performance Category

---

### 8. Feature Importance

If the selected model supports feature importance (such as Random Forest), the project visualizes the most influential features affecting student performance.

---

### 9. Tracker Report

A complete performance tracker is generated for test students containing:

- Actual Final Grade
- Predicted Final Grade
- Actual Category
- Predicted Category

---

## 📁 Project Structure

```
Student_Performance_Tracker.ipynb
README.md
student_performance_uci_model.pkl
student_performance_tracker_report.csv
model_comparison_results.csv
```

---

## 📦 Installation

Clone the repository

```bash
git clone https://github.com/your-username/Student-Performance-Tracker.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

or install manually

```bash
pip install pandas numpy matplotlib scikit-learn joblib ucimlrepo
```

---

## ▶️ Run the Project

Open the notebook

```bash
jupyter notebook Student_Performance_Tracker.ipynb
```

Run all cells sequentially.

---

## 📈 Performance Metrics

The project compares multiple machine learning models and selects the best-performing model based on:

- Highest R² Score
- Lowest MAE
- Lowest RMSE

---

## 📤 Generated Outputs

The notebook saves:

- Trained Machine Learning Model (`student_performance_uci_model.pkl`)
- Student Tracker Report (`student_performance_tracker_report.csv`)
- Model Comparison Results (`model_comparison_results.csv`)

---

## 🎯 Future Improvements

- Deploy using Streamlit or Flask
- Add interactive dashboard
- Support real-time student data
- Early warning system for at-risk students
- Hyperparameter tuning
- Explainable AI (SHAP/LIME)

## Intern_ID: CITS5093

---

## ⭐ If you found this project useful, consider giving it a star!
