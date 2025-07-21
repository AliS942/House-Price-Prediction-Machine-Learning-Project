# House-Price-Prediction-Machine-Learning-Project
This project is a machine learning regression model that predicts housing prices based on real-world data from Kaggle. Using Python and scikit-learn, the model learns to estimate home prices from features like square footage, number of rooms, and location.

The dataset was cleaned by handling missing values—numerical columns were filled with the median, and categorical columns were filled with the mode. One-hot encoding was used to convert categorical data into numerical format. The model was trained using Linear Regression, and its performance was evaluated with the R² score and Mean Squared Error. A scatter plot was also created to visualize predicted vs actual house prices.

This project was developed in Google Colab, making it easy to run without any local setup. You can try it out by opening the notebook directly in Colab using the link below.


Future improvements could include using more advanced models like Random Forest or XGBoost, and building a simple web interface with Streamlit or Flask to make predictions interactively.


Tools & Libraries
Python, Pandas, NumPy
scikit-learn (Linear Regression)
Matplotlib & Seaborn
Google Colab


Run It Yourself
On Google Colab:

Locally:
Install Python 3.x

Install packages:

pip install numpy pandas scikit-learn matplotlib seaborn joblib

Run:

python house_price_prediction.py
