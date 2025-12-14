### 🍷 Wine Quality Prediction – Enhanced Machine Learning Project

#### 

#### 📌 Project Overview



This project predicts wine quality based on chemical properties using multiple machine learning classification models. It includes professional-grade preprocessing, binary target transformation, model comparison, feature importance analysis, and performance visualization.

The project is structured for portfolio presentation and technical evaluation.



#### 📂 Dataset Description



**Source:** *WineQt.csv*

**Original Target:** *quality (scores 3–8)*

**Transformed Target:**



* 1 → Good quality (≥ 6)
* 0 → Bad quality (< 6)



**Feature Groups:**



* **Chemical Properties:** fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, sulphates, alcohol, etc.
* **Additional Attributes:** density, pH, free \& total sulfur dioxide



#### 🧠 Key Concepts



* Binary classification transformation
* Data cleaning \& preprocessing
* Feature scaling (StandardScaler)
* Multi-model training \& evaluation
* Confusion matrix visualization
* Feature importance extraction (Random Forest)



#### 🔧 Tools \& Libraries



* Python
* Pandas, NumPy - data handling
* Scikit-learn - modeling, scaling, evaluation
* Matplotlib, Seaborn - visualizations



#### ⚙️ Workflow Summary



1. Load \& inspect dataset

2\. Clean missing/non-numeric values

3\. Transform ***quality → quality\_binary***

4\. Scale features (StandardScaler)

5\. Stratified train-test split

6\. Train the following models:

    - Random Forest Classifier

    - Support Vector Classifier (SVC)

    - SGD Classifier

    - Gradient Boosting Classifier

    - Generate confusion matrices

    - Evaluate metrics \& compare results

    - Extract and visualize feature importance



#### 📈 Model Performance (Binary Classification)



**Model		  	Accuracy**

Random Forest	  	71.1%

SVC	  	  	67.2%

SGD		  	58.0%

Gradient Boosting	Pending evaluation



**Best Model:** Random Forest

**Challenge:** Mild class imbalance affecting low-frequency quality scores.



#### 📊 Visualizations



* **Quality Distribution:** Frequency of original quality labels
* **Confusion Matrices:** Comparison of prediction correctness per model
* **Feature Importance:** Ranking of top predictors (e.g., alcohol, sulphates, volatile acidity)



#### ✅ Final Insights



* Alcohol and sulphates are the most influential indicators of high-quality wine.
* Converting the problem to binary classification improves interpretability.
* Random Forest delivers the most stable and accurate predictions.
* Scaling substantially improves SVC and SGD performance.
* 

#### 🚀 Future Enhancements



* Hyperparameter tuning (GridSearchCV)
* Address class imbalance using SMOTE or class weighting
* Build an interactive dashboard (Streamlit / Power BI)
* Deploy as API or lightweight web application



#### 📦 Project Files



* Wine\_Quality\_Prediction.ipynb
* WineQt.csv
* README.md
* Final\_Report.pdf



#### 👤 Author



**Ahmed Taha Idrees**

Data Analyst \& QA Tester

Focused on Machine Learning, EDA, and Business Intelligence.



#### 📬 Contact



* **LinkedIn:** (www.linkedin.com/in/ahmed-taha-idrees-416705378)
* **GitHub:**   (https://github.com/Hmada777)
