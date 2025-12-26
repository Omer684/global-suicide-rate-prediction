# Global Suicide Rate Analysis & Prediction
### Introduction To Data Science (IDS) Project

---

## 📌 Project Overview
This project performs a comprehensive analysis of global suicide rates to identify key socio-economic and demographic drivers. By utilizing various machine learning models, we developed a system capable of predicting death rates with high accuracy and identifying the most significant influencing factors.

## 👥 Contributors
* **Muhammad Omer**
* **Muddasar Ishtiaq**
* **Instructor:** Jawad Safdar

---

## 🚀 Technical Highlights
* **Data Source:** Global suicide statistics (1985–2016).
* **Exploratory Data Analysis (EDA):** Visualized trends across gender, age groups, generations, and GDP per capita using `Seaborn` and `Matplotlib`.
* **Preprocessing:** Handled missing values, performed label encoding for categorical features (Age, Sex, Generation), and applied feature scaling to optimize model performance.

## 📊 Model Performance
We evaluated multiple regression models to determine the best fit for our non-linear dataset. The results are summarized below:

| Model | R² Score | Note |
| :--- | :--- | :--- |
| **Random Forest** | **0.997** | **Best Performance** |
| **Decision Tree** | 0.995 | High Accuracy |
| **Gradient Boosting** | 0.993 | Robust Prediction |
| **Linear Regression** | 0.440 | Baseline Model |



## 📈 Key Insights
* **Demographics:** Higher suicide rates were observed in specific age cohorts, requiring targeted mental health interventions.
* **Economic Factor:** We analyzed the correlation between **GDP per capita** and suicide rates to understand how economic stability impacts mental health.
* **Model Selection:** Tree-based ensemble methods significantly outperformed linear models, proving that the relationship between socio-economic factors and suicide rates is highly complex and non-linear.

## 🛠️ Built With
* **Python** (Pandas, NumPy)
* **Scikit-Learn** (Machine Learning)
* **Matplotlib & Seaborn** (Data Visualization)

---

## 📂 Project Structure
```text
├── death rate.csv        # Dataset used for analysis
├── ids_project.py        # Main Python script/Notebook
├── README.md             # Project documentation
