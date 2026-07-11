# 🚗 Car Price Prediction Using Machine Learning

## 📌 Project Overview

This project predicts the selling price of a used car using Machine Learning. It analyzes various factors such as the present price, age of the car, fuel type, transmission, kilometers driven, seller type, and ownership history to estimate the selling price.

The project follows the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Encode categorical features.
- Build a Linear Regression model.
- Predict the selling price of a used car.
- Evaluate model performance.
- Generate business insights.

---

## 📂 Project Structure

```
Car_Price_Prediction/
│
├── data/
│   └── car_data.csv
│
├── notebooks/
│   └── Car_Price_Prediction.ipynb
│
├── images/
│   ├── heatmap.png
│   ├── selling_price_distribution.png
│   ├── present_vs_selling.png
│   ├── actual_vs_predicted.png
│   └── residual_plot.png
│
├── report/
│   └── Project_Report.pdf
│
├── README.md
└── requirements.txt
```

---

## 📊 Dataset Information

The dataset contains information about used cars.

### Features

| Feature | Description |
|---------|-------------|
| Car_Name | Name of the car |
| Year | Manufacturing year |
| Selling_Price | Selling price (Target Variable) |
| Present_Price | Current showroom price |
| Driven_kms | Distance driven |
| Fuel_Type | Petrol / Diesel / CNG |
| Selling_type | Dealer / Individual |
| Transmission | Manual / Automatic |
| Owner | Number of previous owners |

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

## 🤖 Machine Learning Algorithm

- Linear Regression

---

## 📈 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Feature Selection
7. Train-Test Split
8. Train Linear Regression Model
9. Predict Selling Price
10. Model Evaluation
11. Business Insights
12. Conclusion

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 📷 Visualizations

The project includes:

- Correlation Heatmap
- Selling Price Distribution
- Present Price vs Selling Price
- Actual vs Predicted Price
- Residual Plot

---

## 💡 Business Insights

- Newer cars generally have a higher selling price.
- Cars with a higher present price tend to sell for more.
- Lower mileage often contributes to a better resale value.
- Fuel type and transmission influence the selling price.
- The model can help estimate a fair selling price for used cars.

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/your-username/Car_Price_Prediction.git
```

### Install Libraries

```bash
pip install -r requirements.txt
```

### Open Notebook

```bash
jupyter notebook
```

Run all notebook cells to reproduce the analysis.

---

## 🔮 Future Improvements

- Compare Linear Regression with Random Forest Regressor.
- Hyperparameter tuning.
- Deploy using Streamlit.
- Add model serialization using Joblib.
- Improve prediction accuracy with ensemble models.

---

## 👩‍💻 Author

**laxmi sihag**

B.Tech Computer Science Engineering (Artificial Intelligence & Machine Learning)

---

⭐ If you found this project useful, consider giving it a star on GitHub.