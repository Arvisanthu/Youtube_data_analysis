YouTube - Text Data Analysis:

YouTube is the 2nd most visited site in the world with more than 1 billion hours of the content is watched per day, attracts about 44% of all internet users also 37% of all mobile internet traffic belongs to YouTube.

Project process:

1) Understand the Use-Case data.

2) Run ETL pipeline
   
   a)Extract: To read the raw data.
   
   b)Transform: Remove Duplicate rows, Remove irrelavent rows, Fix errors, Check Missing values & data types etc., Deal with Outliers.

   c)Load: To load the featurized/formatted data.

3) EDA: Exploratory Data Analysis, to perform data analysis and visualize the data.


5 key modules/packages used for the Data Analysis project process:

1) Pandas: To read, modify & maniplate the data.

2) NumPy: To perform numerical computations of the data like Mean, Median, Varience & Percentile of the data.

3) Matplotlib: Data visualization, to generate basic plots.

4) Seaborn: Used for beautiful looking plots with fast & quick Data visualization.

5) Plotly: Used for dynamic plots data visualization.



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


