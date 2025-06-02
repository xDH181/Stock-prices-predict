# 📈 Stock Price Prediction using Machine Learning

## 🔍 Objective  
This project is part of my final report for machine learning course, aims to predict stock prices for four companies from different sectors:

- **UBER** *(Transportation)*  
- **INTEL** *(Semiconductors)*  
- **NETFLIX** *(Entertainment)*  
- **NVIDIA** *(Technology)*  

We apply and compare several machine learning models to evaluate their prediction performance across different types of stocks and market conditions.

---

## 🧠 Machine Learning Models Used  
- Long Short-Term Memory (**LSTM**)  
- Feedforward Neural Networks (**FFNN**)  
- **Linear Regression**  
- **Support Vector Machines (SVM)**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**

---

## 📊 Features & Macroeconomic Indicators  
To improve accuracy and capture broader market influences, the models incorporate macroeconomic indicators, such as:

- **Interest Rates**  
- **Inflation**  
- **GDP Growth**  
- **Industry Type (Encoded & Scaled)**  

---

## 🗂️ Dataset  
- Dataset file: `market_stocks_new.csv`  
- Includes historical stock prices, company sector (`industry_type`), and macroeconomic features.  
- Target variable: future stock prices (regression task).  

---

## ⚙️ Data Preprocessing  
- Missing values are handled using **SimpleImputer**.  
- Categorical data (`industry_type`) is processed using **LabelEncoder** and normalized using **MinMaxScaler**.  
- The dataset is split by company for individualized modeling and evaluation.  
- Standardization is applied where appropriate.

---

## 🧪 Model Evaluation Metrics  
Each model is evaluated using:

- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  
- **R² Score**

These metrics help assess both the accuracy and robustness of each approach.

---

## 💻 Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn keras
```

---

## 📎 Project Structure

```
📦 Stock Price Prediction
├── Stock_prices_predict.ipynb    # Main notebook with all model code
├── market_stocks_new.csv         # Dataset file
├── README.md                     # Project description
```

---

## 🚀 Future Improvements
- Hyperparameter tuning via Grid Search or Bayesian Optimization  
- Use of more advanced models like Transformers or Attention-based architectures  
- Integration of real-time data API for live prediction

---

## 📬 Contact  
For questions or suggestions, feel free to open an issue or contact the project maintainer.

Email : haidangforworks@gmail.com
