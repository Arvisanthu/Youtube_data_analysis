
### **1. Project Objectives**

* Analyze YouTube text data (comments, feedback, and metadata) to understand user engagement and sentiment.
* Perform **sentiment analysis**, **text mining**, and **exploratory data analysis (EDA)** to identify patterns in user behavior.
* Use data visualization techniques to uncover insights about audience preferences, likes, and trending content.

---

### **2. Methods**

* **ETL Pipeline**:

  * **Extract** → Read raw YouTube data.
  * **Transform** → Clean data (remove duplicates, irrelevant rows, handle missing values, outliers, fix errors).
  * **Load** → Store and use the formatted/featurized dataset for analysis.

* **Exploratory Data Analysis (EDA)**:

  * Analyzed sentiment polarity (positive, negative).
  * WordCloud for frequent words.
  * Emoji usage analysis.
  * Visualization with boxplots, scatterplots, heatmaps, regression plots, and interactive Plotly charts.

* **Libraries Used**:

  * **Pandas** (data manipulation)
  * **NumPy** (statistical computation: mean, median, variance, percentiles)
  * **Matplotlib & Seaborn** (basic + advanced static visualization)
  * **Plotly** (dynamic interactive visualizations)

---

### **3. Dataset**

* Source: YouTube text/comment dataset (with metadata such as likes, views, categories, and trending video details).
* Features included: Comments/feedback, likes, views, category, channel, sentiment polarity, and emoji usage.

---

### **4. Results**

* **Sentiment Analysis**:

  * Positive users emphasized words like *best, awesome, perfect, amazing, look, happy*.
  * Negative users emphasized words like *terrible, worst, horrible, boring, disgusting*.

* **WordCloud**: Highlighted the most frequent positive and negative keywords.

* **Emoji Analysis**:

  * Majority used positive emojis (funny, love, heart, outstanding).
  * Indicated strong positive user engagement.

* **Boxplot Analysis**:

  * Categories with max likes: *Music, Entertainment, People & Blogs, Nonprofit & Activism*.

* **Scatter/Regression (Likes vs Views)**:

  * Linear trend → More views lead to more likes.

* **Heatmap**:

  * Strong correlation between views and likes (0.78).

* **Plotly Visualization**:

  * *Stephen Colbert channel* had the largest number of trending videos.

---

### **5. Insights**

* **YouTube audience sentiment is mostly positive**, with heavy use of positive keywords and emojis.
* **Content categories** like Music and Entertainment dominate user engagement (likes & views).
* **Views and Likes strongly correlate**, meaning popularity and engagement grow together.
* **Channels with consistent trending videos (e.g., Stephen Colbert)** can serve as benchmarks for content strategy.
* **Text and emoji sentiment** provide valuable signals about customer satisfaction and engagement levels.

---


Data Visualizations:

Sentiment Analysis: Analyse sentiments of users (feedback or comments) Polarity-->[-1,1]; -1--> -ve sentiment; 1--> +ve sentiment.

Wordcloud Analysis: Its a graphical representation of Text data or text frequencies to show most important keywords.

EDA for highly +ve sentences i.e., polarity value = 1:

![+ve polarity](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/5fde438d-437c-4b4a-bd09-5b65ea7e6fb5)

Conclusion-->> Positive Users are emphasizing more on best , awesome , perfect , amazing , look , happy  etc..

EDA for highly -ve sentences i.e., polarity value = -1:

![-ve polarity](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/d38d1555-e6a2-4117-850c-28a6e2e4d409)

Conclusion-->> Negative Users are emphasizing more on Terrible , worst ,horrible ,boring , disgusting etc..


Emoji's Analysis:

![Screenshot 2024-04-14 121133](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/9857ab78-823e-4085-9821-c8fd5a3acc58)

Conclusion--> Majority of the customers are happy as most of them are using emojis like: funny , love , heart , outstanding..

Boxplot with max. likes:

![boxplot wit max likes](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/6b25bf64-bd0b-40ff-b2a6-b04e4d675d74)

Conclusion--> Most of the customers likes: Music, Entertainment, people & blogs, Nonprofit & activisum etc..


Scatter/Regression plot for likes vs views: 

![scatterplot](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/76bc3204-ecd8-495a-b361-c683aaaf2379)

Conclusion--> The straight line indecates that if views increases then likes will increase.

Heatmap:

![heatmap](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/c2ff76d6-2bc1-462a-bdde-178a9e4b0ee6)

Conclusion--> views & views are correlated, If views will increase by 1 unit/100 then the likes will increase by number 0.78/factor of 78.


Plotly:

![newplot](https://github.com/Arvisanthu/Youtube_data_analysis/assets/165466685/adbe0253-70b7-48e1-85fc-17efa07ee7c8)

Conclusion--> Stephen Colbert channal has largest number of trending videos.


