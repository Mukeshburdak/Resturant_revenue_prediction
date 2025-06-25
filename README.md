# Resturant_revenue_prediction

🍽️ Predict Restaurant Ratings
📌 Objective
The objective of this project is to develop a machine learning model that accurately predicts the aggregate rating of a restaurant based on various features such as location, cuisine, cost, online delivery options, and more. This helps platforms and businesses in providing better recommendations and gaining deeper insights into customer preferences.

📊 Problem Statement
Restaurant reviews and ratings provide valuable information to users. However, many new or less-reviewed restaurants lack sufficient ratings. This project aims to predict the restaurant's aggregate rating using its metadata, offering useful insights even before reviews accumulate.

📁 Dataset
The dataset contains multiple attributes of restaurants including:

Name

Location

Approximate cost for two

Online delivery availability

Table booking availability

Cuisines

Type of restaurant

Votes

Listed dish likes

And more...

⚙️ Features Used
Categorical and numerical data preprocessing

Feature engineering (e.g., encoding, imputation)

Exploratory Data Analysis (EDA)

Correlation & feature importance analysis

🧠 ML Models Applied
Linear Regression

Decision tree

Logistic Regression

Final model chosen based on RMSE and R² score performance on the validation set.

📈 Evaluation Metrics
Root Mean Squared Error (RMSE)

R² Score

Mean Absolute Error (MAE)

🏁 Results
Achieved an R² score of XX.XX on the test set

Feature importance indicated cost for two, votes, and online delivery as major predictors

🛠️ Installation
bash
Copy
Edit
git clone https://github.com/Mukeshburdak/restaurant-rating-prediction.git
cd restaurant-rating-prediction
pip install -r requirements.txt
🚀 How to Run
bash
Copy
Edit
# Run the notebook or script
python model_train.py
# or open in Jupyter
jupyter notebook Restaurant_Rating_Prediction.ipynb
📌 Future Work
Incorporate sentiment analysis from customer reviews

👨‍💻 Author
Mukesh Burdak
GitHub | LinkedIn

