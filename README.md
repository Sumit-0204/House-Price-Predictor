# House Price Predictor

## 📌 Project Overview
This project aims to predict house prices based on various features such as location, size, number of bedrooms, and more. The model utilizes machine learning techniques to analyze historical data and generate accurate price predictions.

## 📜 Motivation
House prices fluctuate based on multiple factors, making it crucial for buyers and sellers to have an estimate before making financial decisions. This project provides a predictive model that helps stakeholders understand market trends.

## 🚀 Features
- Predict house prices using machine learning algorithms
- Supports multiple regression models
- Visual representation of dataset insights
- Model performance evaluation using statistical metrics

## 🛠 Tools & Technologies Used
- **Programming Language**: Python  
- **Libraries & Frameworks**:  
  - **Pandas** – Data manipulation and preprocessing  
  - **NumPy** – Numerical computations  
  - **Matplotlib & Seaborn** – Data visualization  
  - **Scikit-Learn** – Machine learning models and evaluation metrics  
  - **XGBoost** – Gradient boosting algorithm for better accuracy  
- **Data Handling**: CSV files (Kaggle dataset)  
- **Model Evaluation**: MAE, MSE, R² Score  
- **Version Control**: Git & GitHub  
- **Development Environment**: Jupyter Notebook and Google Colab  

## 📂 Dataset
The dataset used in this project is sourced from Kaggle, containing features like:
- **Size (sq ft)**: The total area of the house
- **Number of bedrooms**
- **Location**: Categorical variable indicating the city or neighborhood
- **Year Built**: Age of the property
- **Price**: Target variable

## 🛠 Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Sumit-0204/House-Price-Predictor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd House-Price-Predictor
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the project:
   ```bash
   python app.py
   ```

## 📊 Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Correlation heatmap of features
- Distribution of house prices
- Feature importance analysis

**Example Visualization:**
![Correlation Heatmap](https://github.com/Sumit-0204/House-Price-Predictor/blob/main/corelation%20atributes.PNG)

## 🏗 Model Selection & Training
The project implements multiple regression models, including:
- **Linear Regression**
- **Random Forest Regressor**
- **XGBoost Regressor**

Model evaluation is performed using:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-Squared Score (R²)**

## 📈 Results & Performance
The model achieved an R² score of **X.XX**, indicating a strong correlation between input features and predicted prices.

**Sample Prediction:**
```
Input: {"size": 1500, "bedrooms": 3, "location": "New York", "year_built": 2005}
Predicted Price: $320,000
```

## 🎯 Future Improvements
- Implement deep learning models for better accuracy
- Include additional features like crime rate and school ratings
- Deploy the model as a web application

## 🤝 Contributing
Feel free to fork this repository and submit pull requests for improvements.


## 🙏 Acknowledgments
- Kaggle for the dataset
- Scikit-Learn, Pandas, Matplotlib, and Seaborn for data analysis

---
📌 **GitHub Repository:** [House Price Predictor](https://github.com/Sumit-0204/House-Price-Predictor)
