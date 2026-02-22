# House-Price-Prediction
**🏠 House Price Prediction**

**📌 Project Overview**

The House Price Prediction project focuses on estimating house prices based on key property features such as area, number of bedrooms, and age of the house. Accurate price prediction is crucial for buyers, sellers, and real-estate businesses to make informed decisions.

This project follows an end-to-end machine learning workflow including data cleaning, exploratory data analysis (EDA), regression modeling, and price prediction.

**📂 Dataset Description**

The dataset consists of multiple house records with the following features:

- area – Total area of the house (square feet)

- bedrooms – Number of bedrooms

- age – Age of the house in years

- price – House price (target variable)

**🧹 Data Cleaning & Preprocessing**

- Checked and handled missing values

- Verified data types and consistency

- Removed invalid or unrealistic entries

- Prepared data for regression modeling
  

**📊 Exploratory Data Analysis (EDA)**

EDA was performed to understand how different factors influence house prices. Key observations include:

- Strong positive relationship between area and price

- Houses with more bedrooms generally have higher prices

- Older houses tend to have lower prices

- Area shows the highest correlation with price


**Key Visualizations**

**Area vs Price**

<img width="776" height="537" alt="image" src="https://github.com/user-attachments/assets/7b98461f-ce62-429f-962d-2cb07617ed42" />

Larger house area is associated with higher property prices, indicating area as a primary pricing factor.

**Bedrooms vs Price**

<img width="782" height="537" alt="image" src="https://github.com/user-attachments/assets/21900c0c-17a3-4813-8095-0df2b77fadac" />


Properties with a higher number of bedrooms generally command higher prices.

**Feature Correlation Heatmap**

<img width="693" height="537" alt="image" src="https://github.com/user-attachments/assets/0dea615e-35fc-4478-b405-b0815cc845e6" />


The heatmap highlights area as the most influential feature for predicting house prices.


**🤖 Model Building & Evaluation**

The following regression models were implemented:

- Linear Regression

- Multiple Linear Regression

- Evaluation Metrics:

- R² Score

- Mean Absolute Error (MAE)

- Root Mean Squared Error (RMSE)

- Multiple Linear Regression performed better by capturing the combined impact of multiple features.
  

**📈 Prediction Results**
- Actual vs Predicted House Prices

- The predicted prices closely follow actual prices, indicating good model accuracy.

**💡 Business Use Case**

This model can be used by:

- Real-estate agents for price estimation

- Property platforms for automated valuation

- Buyers and sellers to assess fair market value
  

**🛠 Tools & Technologies Used**

- Python

- Pandas, NumPy

- Matplotlib, Seaborn

- Scikit-learn

- Jupyter Notebook
  

**🚀 Future Enhancements**

- Feature scaling and transformation

- Advanced regression models

- Model deployment using Streamlit
