# 📊 Sales Prediction Using Python

## 📌 Project Overview

This project predicts product sales based on advertising expenditure on **TV**, **Radio**, and **Newspaper** using **Linear Regression**, a supervised machine learning algorithm.

The objective is to analyze the impact of different advertising channels on sales and build a predictive model that helps businesses estimate future sales.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Explore and visualize the dataset.
- Analyze relationships between advertising channels and sales.
- Build a Linear Regression model.
- Predict future sales based on advertising budgets.
- Evaluate the model using performance metrics.
- Generate business insights for decision-making.

---

## 📂 Project Structure

```
Sales_Prediction_Using_Python/
│
├── data/
│   └── Advertising.csv
│
├── notebooks/
│   └── Sales_Prediction.ipynb
│
├── images/
│
├── report/
│   └── Project_Report.pdf
│
├── README.md
│
└── requirements.txt
```

---

## 📊 Dataset

The dataset contains **200 records** with the following features:

| Feature | Description |
|----------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspaper |
| Sales | Product sales (Target Variable) |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Machine Learning Algorithm

- Linear Regression

---

## 📋 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Correlation Analysis
7. Feature Selection
8. Train-Test Split
9. Train Linear Regression Model
10. Predict Sales
11. Evaluate Model
12. Business Insights
13. Conclusion

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| MAE | **1.4608** |
| MSE | **3.1741** |
| RMSE | **1.7816** |
| R² Score | **0.8994** |

The model explains approximately **90%** of the variation in sales, indicating excellent predictive performance.

---

## 💡 Business Insights

- TV advertising has the strongest influence on product sales.
- Radio advertising also contributes significantly to sales.
- Newspaper advertising has the least impact on sales.
- Increasing investment in TV and Radio advertising is likely to improve sales.
- The model can help businesses estimate future sales before launching advertising campaigns.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Sales_Prediction_Using_Python.git
```

### 2. Navigate to the project folder

```bash
cd Sales_Prediction_Using_Python
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebooks/Sales_Prediction.ipynb
```

Run all cells to reproduce the analysis and predictions.

---

## 📷 Visualizations

The project includes:

- Correlation Heatmap
- Pairplot
- Histograms
- Boxplots
- Scatter Plots
- Actual vs Predicted Sales Plot
- Residual Plot

---

## 🔮 Future Improvements

- Develop a Streamlit web application.
- Compare multiple regression algorithms.
- Perform hyperparameter tuning.
- Deploy the model online.
- Add model serialization using Pickle.

---

## 👩‍💻 Author

**laxmi sihag**

B.Tech – Computer Science Engineering (Artificial Intelligence & Machine Learning)

---

## ⭐ If you found this project useful, please consider giving it a star on GitHub!