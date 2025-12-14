## 🏠 House Price Prediction using Linear Regression



A complete machine learning project for predicting real estate prices using classical regression techniques.

This project demonstrates the full pipeline: **data cleaning → preprocessing → encoding → model training → evaluation → insights.**



#### 📌 Project Overview



The goal of this project is to estimate house prices based on property characteristics such as area, bedrooms, bathrooms, amenities, and furnishing status.

Linear Regression is used as a baseline model to understand feature influence and build an interpretable predictive system.



This project is part of a professional Data Analytics \& Machine Learning portfolio.



#### 📂 Dataset



File: **Housing.csv**

Target Variable: **price**



###### **Features Included**



* **Numerical:** area, bedrooms, bathrooms, stories, parking
* **Binary (yes/no):** mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea
* **Categorical:** furnishingstatus



The dataset contains structured housing information suitable for regression modeling.



#### 🧠 Project Workflow

###### 1️⃣ Data Preparation



* Loaded the dataset and inspected structure
* Cleaned and formatted binary values
* One-hot encoded the furnishingstatus category
* Verified data integrity \& ensured no missing values



###### 2️⃣ Feature Engineering



* Correlation analysis to identify influential features
* Numerical and binary feature separation
* Prepared final feature matrix for model training



###### 3️⃣ Model Training



* Trained a LinearRegression model
* Fitted model using all selected features



###### 4️⃣ Model Evaluation



Using standard regression metrics:



* R² Score: 0.546
* MSE: 2.29 trillion
* MAE: 1.12 million



###### 5️⃣ Visualization



* Correlation Matrix: Identifies key price drivers
* Actual vs Predicted Plot: Evaluates prediction spread and accuracy



#### 📈 Key Insights



* **Area, bathrooms, and number of stories** strongly influence property price.
* Amenities such as **air conditioning, hot water heating, and guestroom** significantly increase value.
* Baseline Linear Regression explains ~54.6% of price variation.
* Average price prediction error is around **1.12M**, reasonable for large-scale real estate markets.



#### 🚀 Future Improvements



To enhance performance and reduce error:



* Implement **Random Forest, XGBoost, or Gradient Boosting**
* Apply feature scaling \& normalization
* Use **k-fold cross-validation** for more stable results
* Incorporate geographic/location-based features
* Perform hyperparameter tuning



#### 🛠️ Tools \& Technologies



* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook



#### 👤 Author



**Ahmed Taha Idrees**

Data Analyst \& QA Tester

Focused on Machine Learning, Data Cleaning, and Business Intelligence.



#### 📬 Contact



* **LinkedIn:** (www.linkedin.com/in/ahmed-taha-idrees-416705378)
* **GitHub:**   (https://github.com/Hmada777)
