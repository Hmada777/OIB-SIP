## 📊 Google Play Store Data Analysis



###### **Unveiling the Android App Market Through Data Insights**



##### **📁 Dataset**



* apps.csv — App metadata (name, category, rating, installs, price, etc.)
* user\_reviews.csv — User reviews with sentiment labels



##### **🎯 Objective**



Analyze and visualize Google Play Store data to uncover insights related to:



* App categories
* User ratings
* Pricing models (free vs. paid)
* User sentiment and review patterns



#### 🧹 1. Data Preparation



* Removed unnecessary columns (e.g., Unnamed: 0)
* Cleaned and standardized key fields:
* Installs: removed commas and “+” signs → converted to numeric
* Price: removed “$” → converted to float
* Size: converted consistently to MB using a custom function
* Handled missing values through appropriate filtering



#### 📊 2. Category Exploration



* Counted apps per category
* Visualized Top 10 Categories using a horizontal bar chart with gradient coloring



#### 📈 3. Metrics Analysis



**Category Ratings**

* Calculated the average rating for each category



**Free vs Paid Apps**

* Compared the distribution of free vs paid apps
* Analyzed rating differences between pricing models



#### 💬 4. Sentiment Analysis



* Loaded and cleaned sentiment labels from user\_reviews.csv
* Visualized sentiment distribution (Positive / Neutral / Negative)
* Applied custom ordering and clear color palette



#### 🎨 5. Visualization \& Design



* Used seaborn + matplotlib with custom color palettes:
* viridis, mako, Set2, coolwarm
* Removed deprecated warnings by proper hue/legend usage
* Ensured clean layouts, readable labels, and logical ordering



#### 🧠 6. Skills Demonstrated



* Data cleaning \& preprocessing
* Visualization best practices
* Exploratory data analysis
* Sentiment analysis
* Insights interpretation



#### ✅ Final Outcome



A complete and well-presented analysis of Google Play Store data featuring:

* Clear visualizations
* Clean and optimized Python code
* Actionable insights
* Suitable for portfolio, academic submission, and professional review



### 👤 Author



**Ahmed Taha Idrees**

Law student \& aspiring Business Intelligence Engineer



### 📬 Contact



* **LinkedIn:** (www.linkedin.com/in/ahmed-taha-idrees-416705378)

**GitHub:**   (https://github.com/Hmada777)

