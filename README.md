
# Aircraft Engine Remaining Useful Life (RUL) Prediction

### 🎓 Data Science Graduation Project

A data-driven predictive maintenance framework for estimating the Remaining Useful Life (RUL) of aircraft turbofan engines using Machine Learning and Deep Learning techniques.

The project uses NASA's C-MAPSS dataset to investigate engine degradation patterns and support proactive maintenance decisions.

## 📌 Project Overview

Predictive maintenance plays an important role in improving aircraft safety, reducing unexpected failures, and optimizing maintenance schedules.

This project focuses on estimating the remaining operational cycles of turbofan engines based on historical sensor measurements.

## 🎯 Project Objectives

- Predict aircraft engine Remaining Useful Life (RUL).
- Analyze engine degradation using sensor data.
- Apply data preprocessing and feature engineering.
- Explore Machine Learning and Deep Learning approaches.
- Evaluate prediction performance using regression metrics.
- Support data-driven maintenance planning.

## 📊 Dataset

**NASA C-MAPSS Turbofan Engine Degradation Dataset**

The dataset contains simulated engine degradation trajectories and includes four subsets:

| Dataset | Operating Conditions | Fault Modes |
|---------|----------------------|-------------|
| FD001 | 1 | 1 |
| FD002 | 6 | 1 |
| FD003 | 1 | 2 |
| FD004 | 6 | 2 |

Each engine contains multivariate time-series measurements, including 21 sensor readings and operational settings.

## 🧠 Methodology

The project follows a data science workflow:

1. Data collection and exploration
2. Data cleaning and preprocessing
3. Sensor analysis and feature selection
4. Data normalization
5. RUL target calculation
6. Model development and evaluation
7. Comparison and interpretation of predictions

## 🛠️ Technologies & Tools

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- PyTorch

## 📈 Model Evaluation

The project examines regression performance using metrics such as:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Detailed implementation and evaluation are available in the project notebook.


## 📊 Experimental Results

The following table summarizes the best-performing models identified for each evaluated NASA C-MAPSS subset.

| Dataset | Best Model | MAE | RMSE |
|---------|------------|-----|------|
| FD002 | Ensemble (Average) | 14.36 | 18.62 |
| FD003 | GRU + Attention | 7.18 | 11.85 |
| FD004 | Ensemble (Average) | 10.51 | 17.44 |

### Key Findings

- GRU with Attention achieved an RMSE of 11.85 on FD003.
- The averaging ensemble achieved an RMSE of 17.44 on FD004.
- The averaging ensemble achieved an RMSE of 18.62 on FD002.
- Results demonstrate the application of deep learning and ensemble approaches to aircraft engine RUL prediction.

**Note:** Results are reported from the saved notebook outputs. Performance comparisons across different subsets should be interpreted carefully.


## 📂 Repository Contents

- `README.md` — Project documentation
- `RUL_Prediction_Framework_FD001_FD004.ipynb` — Project notebook
- Graduation Project Report (PDF) — Research and methodology documentation

## 👨‍🎓 Graduation Project Team

- Abdulaziz Alsaidalani
- Omar Daffa
- Ahmed Babader
- Firas Matari
- Bandar Farhan

**Supervisor:** Dr. Tariq Alsahfi

## 🚀 Future Improvements

- Improve model robustness across operating conditions.
- Explore explainable AI for model interpretation.
- Develop an interactive maintenance assistant.
- Investigate deployment for practical maintenance support.

## 📬 Contact

**Firas Matari**

Data Science Graduate | Jeddah, Saudi Arabia

GitHub: [FerasMatari](https://github.com/FerasMatari)
