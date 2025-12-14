## 🇨🇦 YouTube Trending Data Analysis – Canada



A complete exploratory data analysis (EDA) project exploring trending YouTube videos in Canada using Python and Google Colab.

This project aims to analyze YouTube video performance, understand category trends, and extract insights on engagement patterns.



##### 📌 Project Overview



This project analyzes YouTube trending videos in Canada using the official Kaggle dataset.

It focuses on:



* Understanding which categories dominate trending videos
* Studying engagement metrics such as views, likes, and comments
* Practicing real-world data cleaning and EDA skills
* Building a polished portfolio project suitable for Data Analytics \& BI roles





##### 📁 Dataset



**Source:** *Kaggle – YouTube Trending Dataset*

(YouTube trending video data for multiple countries)



**Files Used**



* CAvideos.csv — Raw dataset for Canada
* CA\_category\_id.json — Category metadata used to decode video categories



##### 

##### 🧪 Project Workflow

###### 1️⃣ Library Setup



Imported essential libraries:

pandas, numpy, matplotlib, seaborn, json



###### 2️⃣ Category Data Processing



* Loaded CA\_category\_id.json
* Extracted category\_id → category\_name
* Built a clean DataFrame (cat\_df) for merging



###### 3️⃣ Video Data Loading



* Uploaded and read CAvideos.csv into df



###### 4️⃣ Data Merging



* Merged video data with category names using category\_id
* Ensured each row had a readable category instead of numeric codes



###### 5️⃣ Data Cleaning



* Removed rows with missing video titles or channel names
* Filled missing comment\_count values with 0
* Removed duplicate entries
* Filtered out rows where views == 0
* Ensured likes <= views logical consistency



###### 6️⃣ Exploratory Data Analysis (EDA)



Created visualizations to explore:



**📌 View Distribution**

**📌 Trending video count by category**

**📌 Correlation between views and likes**

**📌 Average comments by category**



###### 7️⃣ Export Final Data



Saved cleaned file as:

CAvideos\_cleaned.csv





##### 📊 Key Insights



* Top Trending Category: Entertainment
* Highest Average Comment Count: Music videos
* Engagement Pattern: Strong positive correlation between views and likes, with several viral outliers
* Some categories (e.g., Entertainment, Music) dominate the trending list disproportionately
* Many trending videos come from a small number of highly influential channels





##### ⚙️ How to Run This Project



###### 1\. Install Required Libraries

###### 

###### **##Code:**

pip install pandas numpy matplotlib seaborn



###### 2\. Open Notebook



Run youtube\_analysis.ipynb in Google Colab or Jupyter Notebook.



###### 3\. Add Data Files



Make sure CAvideos.csv and CA\_category\_id.json are in the notebook directory.





🛠️ Tools \& Technologies Used



* Python

     - Pandas

     - NumPy

     - Matplotlib

     - Seaborn

     - JSON Parsing

* Google Colab
* GitHub for version control





##### 👤 Author



**Ahmed Taha Idrees**

Data Analyst \& QA Tester

Focused on Business Intelligence, Data Cleaning, and Exploratory Data Analysis.



##### 

##### 📬 Contact



* **LinkedIn:** (www.linkedin.com/in/ahmed-taha-idrees-416705378)
* **GitHub:**   (https://github.com/Hmada777)
