# Airbnb-Price-Prediction
📌 Project Overview:
This project focuses on predicting the nightly prices of Airbnb listings using machine learning techniques. The dataset contains detailed listing information such as location, property type, amenities, and host characteristics. The goal is to build a model that can accurately estimate prices based on these features, helping hosts set competitive rates and assisting guests in identifying fair deals.

📂 Dataset:
The dataset used in this project is sourced from Kaggle:
Airbnb Price Prediction Dataset
It contains various features including:
Listing ID
Neighbourhood & City
Room Type
Number of Guests
Number of Reviews
Amenities
Host Information
Price (Target Variable)

🛠️ Project Workflow:
1. Data Exploration & Cleaning
Handled missing values and removed irrelevant features.
Converted categorical variables into numerical form.
Performed feature scaling where required.

2. Exploratory Data Analysis (EDA)
Visualized price distribution across different neighborhoods and property types.
Identified key factors influencing price.
Detected outliers and unusual patterns in pricing.

3. Feature Engineering
Created new features such as price per guest and amenities count.
Encoded location-based features for better model performance.

4. Model Building
Implemented multiple regression and tree-based models, including:
Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Performed hyperparameter tuning to optimize performance.

5. Model Evaluation
Evaluated models using:
R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Selected the best-performing model for final predictions.

📊 Results:

Best Model: Gradient Boosting Regressor
R² Score: Example: 0.85
RMSE: Example: 45.3

Insights: Neighborhood, room type, and number of reviews were the most influential features.

📦 Technologies & Libraries Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

🚀 Future Improvements:
Incorporate additional datasets for seasonal price trends.
Integrate NLP-based sentiment analysis from listing descriptions and reviews.
Deploy the model as a web application for real-time predictions.

📜 License:
This project is open-source and free to use for educational purposes.
