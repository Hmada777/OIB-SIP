## 🛍️ Customer Segmentation using K-Means Clustering



A complete machine learning project for segmenting e-commerce customers based on spending behavior, demographics, and engagement metrics.



#### 

#### 📌 Project Overview



This project performs customer segmentation for an e-commerce company using **K-Means Clustering.**

The aim is to understand customer profiles, identify high-value segments, and support strategic, data-driven marketing decisions.



**By grouping customers into clusters, marketing teams can:**



* Personalize campaigns
* Improve retention
* Increase revenue by focusing on the right audience





#### 🎯 Project Objectives



* Analyze customer demographics, purchases, and online behavior
* Create meaningful customer segments using clustering
* Visualize cluster characteristics
* Translate results into actionable business insights





#### 📁 Dataset



**Source:** Kaggle — *Marketing Analytics by Jack Daoud*



* **File:** ifood\_df.csv



* **Observations:** 2,206 customers



* **Includes:**



&nbsp;   - Income \& demographics

&nbsp;   - Product purchases

&nbsp;   - Marketing campaign responses

&nbsp;   - Website visit patterns





#### 🏗️ Project Structure



📂 customer-segmentation/

│── ifood\_df.csv

│── customer\_segmentation.ipynb

│── README.md

│── segmentation\_visuals/ (optional for charts)





#### 🔧 Workflow Summary



###### 1️⃣ Data Loading \& Exploration



* Loaded dataset
* Checked structure \& summary statistics
* Identified missing values and inconsistent fields



###### 2️⃣ Data Cleaning



* Removed unnecessary or redundant columns
* Handled missing values
* Ensured numerical consistency



###### 3️⃣ Feature Selection



**Picked relevant numerical fields such as:**

* Income
* Spending on product categories
* Web visits
* Campaign responses



###### 4️⃣ Data Scaling



Used StandardScaler for normalization before clustering.



###### 5️⃣ Determining Optimal Clusters



Applied the Elbow Method to select the most stable number of clusters.



###### 6️⃣ Applying K-Means Clustering



* Trained the model
* Labeled each customer with their assigned cluster
* Integrated cluster labels into the dataset



###### 7️⃣ Cluster Analysis \& Visualization

#### 

* Created visualizations to compare clusters based on:
* Income
* Total spending
* Web engagement
* Campaign acceptance





#### 📊 Key Insights



* **Total clusters: 4**



* **Clusters 0 \& 3:**

    High-income, high-spending customers — ideal for premium campaigns



* **Cluster 1:**

&nbsp;  Low-income, low-engagement group — requires cost-efficient targeting



* **Cluster 2:**

&nbsp;  Middle-income customers with mixed spending patterns



* Segmentation results can guide **optimized marketing, budget allocation, and audience targeting** strategies





#### ⚙️ Tools \& Technologies Used



* **Python**

&nbsp;    - Pandas

&nbsp;    - NumPy

&nbsp;    - Scikit-learn

&nbsp;    - Matplotlib

* **Google Colab**





#### 👤 Author



**Ahmed Taha Idrees**

Data Analyst \& QA Tester

Specialized in Data Cleaning, EDA, and Business Intelligence.





#### 📬 Contact



* **LinkedIn:** (www.linkedin.com/in/ahmed-taha-idrees-416705378)
* **GitHub:**   (https://github.com/Hmada777)



