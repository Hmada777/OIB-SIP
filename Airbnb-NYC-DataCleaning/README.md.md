## **Project Overview**



This project focuses on cleaning, preprocessing, and exploring the **Airbnb NYC 2019 dataset**.

The goal is to demonstrate strong data cleaning, **data quality assurance, and exploratory data analysis (EDA)** skills—essential for real-world data analytics and Business Intelligence workflows.



##### The project includes:



* Comprehensive preprocessing (missing values, duplicates, outliers).
* Standardization for consistent analytics.
* Visual exploration of pricing, regions, and reviews.
* A fully reproducible Colab notebook.



##### Files Included



###### **File		                                Description**

AB\_NYC\_2019.csv.zip			Original compressed dataset.

AB\_NYC\_2019.csv	                		Raw dataset after extraction.

AB\_NYC\_2019\_cleaned.csv			Final cleaned dataset ready for analysis.

Airbnb\_Cleaning.ipynb			Google Colab notebook containing full cleaning, preprocessing, and visualizations.





##### 🎯 Purpose \& Motivation



Airbnb datasets are widely used in data analytics due to their complexity and richness.

This project was created to:



\- Practice real-world data cleaning workflows.

\- Prepare a refined dataset suitable for BI dashboards and modeling.

\- Analyze pricing patterns and neighborhood trends in NYC.

\- Build a strong portfolio project demonstrating data cleaning expertise.





##### 🧹 Data Cleaning Steps



###### **1️⃣ Data Integrity Checks**



\- Verified dataset structure with df.info() and df.describe().

\- Ensured consistent formatting for categorical fields (e.g., neighbourhood\_group, room\_type).



###### **2️⃣ Handling Missing Data**



\- Dropped rows missing critical textual fields (name, host\_name).

\- Filled missing reviews\_per\_month values with 0.



###### **3️⃣ Removing Duplicates**



\- Eliminated all duplicate rows using df.drop\_duplicates()



###### **4️⃣ Standardization**



\- Converted text-based columns to lowercase.

\- Stripped leading/trailing whitespace.

\- Ensured consistent formatting for neighborhoods.



###### **5️⃣ Outlier Detection \& Removal**



Removed unrealistic prices:



\- price <= 0

\- price > 1000





##### 📊 Exploratory Visual Analysis



###### **🔹 Price Distribution**



A histogram showing that most listings fall under **$200**, with a long right tail.



###### **🔹 Listings by Region**



Bar plot indicating that **Manhattan and Brooklyn dominate the listing count**.



###### **🔹 Room Type Distribution by Region**



Room types vary by area, with **entire homes/apartments concentrated in Manhattan**.



###### **🔹 Price vs. Number of Reviews**



Scatter plot showing **cheaper listings receive more reviews**, indicating higher demand.





##### 🔍 Key Insights \& Results



 - **Manhattan** has the highest number of listings and the highest average prices.

 - **Private rooms** make up a significant portion of listings, especially in Brooklyn and Queens.

 - The majority of listings receive **less than 10 reviews**, showing a long tail of low-engagement properties.

 - Listings priced under **$150** tend to receive more frequent reviews.





##### ⚙️ How to Run This Project



###### **1. Install Required Libraries**



**## Code:**

pip install pandas numpy matplotlib seaborn



###### **2. Open the Notebook**



You can run the project directly on Google Colab or locally via Jupyter Notebook.



###### **3. Load the Dataset**



Ensure the CSV files are in the same directory as the notebook.



🛠 Tools \& Technologies Used



* **Python**

&nbsp;    - Pandas

&nbsp;    - NumPy

&nbsp;    - Matplotlib

&nbsp;    - Seaborn

* **Google Colab**
* **GitHub for version control**





##### 👤 Author



**Ahmed Taha Idrees**

Data Analyst \& QA Tester

Focused on Business Intelligence, Data Cleaning, and Exploratory Data Analysis.





##### 📬 Contact



Feel free to reach out for collaborations, questions, or suggestions via:



* **LinkedIn:**  (www.linkedin.com/in/ahmed-taha-idrees-416705378)
* **GitHub:**    (https://github.com/Hmada777)
