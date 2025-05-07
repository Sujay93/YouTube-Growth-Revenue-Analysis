
## Business Problem

This project delivers a comprehensive exploratory data analysis (EDA) of a large-scale YouTube dataset with the goal of uncovering actionable insights into content trends, channel performance, and geographic patterns. 
The analysis is aimed at identifying key drivers of channel growth and revenue, helping stakeholders understand which content strategies and market segments contribute most to success on the platform.

## Quick summary

**Objective :** The analysis is aimed at identifying key drivers of channel growth and revenue, helping stakeholders understand which content strategies and market segments contribute most to success on the platform

**Insights and Recommendations :**
* “Gaming”, “Music”, and “Entertainment” emerged as the most active and highly subscribed categories, but also show high           competition.
* Certain categories like “Education” or “How-to & Style” show promising subscriber counts with relatively fewer channels —        indicating lower saturation.
* Channel types such as “Entertainment” and “Gaming” have the highest monthly earnings, while How-to and News channels often       have steady but lower revenue.
* Channels in “Entertainment”, “Music”, “Tech”, and “Animals” can boost earnings by maintaining consistent content and forming     brand partnerships
* YouTubers can expand their reach by targeting countries beyond the US, India, and the UK, where digital literacy and             infrastructure are improving
* Creators can expand globally by producing multilingual content or localizing videos for regions with growing digital access,     particularly outside top markets like the US, India, and the UK
* Creators can optimize content strategies by leveraging performance data, such as top-performing video types and viewer           demographics, to boost engagement and audience retention.

## Dataset

[https://github.com/Sujay93/YouTube-Growth-Revenue-Analysis/blob/main/Global%20YouTube%20Statistics.csv]

## Data cleaning

* Imported the dataset using Python libraries to prepare for analysis.
* Identified and removed duplicates to maintain data accuracy.
* Handled missing values through appropriate replacement strategies to ensure completeness.
* Eliminated irrelevant columns not aligned with the analysis objectives.
* Validated and corrected data types for consistency and analytical accuracy.
* Standardized formatting to enhance data usability for analysis

## Exploratory data analysis

This interactive dashboard presents key insights from a comprehensive YouTube dataset, focused on analyzing creator performance, content trends, and geographic influence. The visuals below highlight the most impactful findings:

1. **Category wise Average subscribers**
   
   ![image](https://github.com/user-attachments/assets/26f787c3-2f1c-4d86-9721-94664bbf2bab)

* The bar chart represents the average number of subscribers across different YouTube categories.
* The "Shows" category has the highest average number of subscribers, exceeding 40 million, making it the most popular category.
* The "Trailers" category also boasts a significant average subscriber count, likely reflecting the broad interest in movie and     TV trailers.
* "Film and Animation" maintains a solid average of over 30 million subscribers, highlighting the appeal of creative and visual     content.
* "Nonprofits and Activism" follows with a respectable average of around 30 million subscribers, despite its focus on social        causes and activism.
* The "Education" category closely follows, suggesting that educational content maintains strong demand among audiences.

2. **Average Uploads**

   ![image](https://github.com/user-attachments/assets/6699ecff-edda-46b6-85df-4aaa7aa1964d)

* The bar chart represents the total subscribers for each country
* **Dominant Country:** The United States has the highest number of total subscribers, significantly more than any other country.     Its bar is much taller than the others, indicating a very large subscriber base
* **Top Countries:** After the United States, the countries with the highest subscriber counts are India, Brazil, and the United       Kingdom. These countries have a noticeable drop in subscriber numbers compared to the United States but still stand out           among the rest
* **Other Countries:** The remaining countries have relatively small numbers of subscribers, as indicated by the short bars.       These include a wide range of countries from different regions, such as Indonesia, Mexico, and South Korea, among others.
   
3. **Category with the Highest Yearly earnings**

  ![image](https://github.com/user-attachments/assets/b5d2a0ca-84a6-4c80-b847-d2c5af69fe1f)

* The violin plot represents the category wise highest yearly earnings.
* Categories such as “Music”, “Film & Animation”, and “Entertainment” show a broad distribution with several high-earning           outliers. The “Shows” category has the widest spread, indicating a highly variable range of earnings.
* Categories like “How to & Style” and “Nonprofits & Activism” have a more concentrated distribution, suggesting consistent         earnings among these channels.
* “Gaming” and “Education” categories also show a fairly concentrated earnings range with fewer      outliers.
* **Outliers:** Several categories, such as “Music”, “Film & Animation”, and “Shows”, have significant outliers. The “Pets &        Animals” and “Autos & Vehicles” categories also show some variability but with fewer extreme outliers.

4. **Channel type distribution**

![image](https://github.com/user-attachments/assets/e8d33e68-d22f-4c57-ab4c-c84a24131985)

* The pie chart shows the distribution of different channel types.
* **Dominant Channel Type:** “Entertainment” channels have the largest share, making up 41.7% of the total distribution. This       suggests that entertainment is the most popular channel type in this dataset.
* **Significant Channel Types:** “Music” channels are the second most common type, constituting 29.6% of the total. “Games” channels account for 12.4% of the distribution.
* **Smaller Categories:** “People” channels make up 9.0% of the distribution. “Comedy” channels have the smallest share at 7.3%

5. **YouTubers with the Highest Yearly earnings**

   ![image](https://github.com/user-attachments/assets/507dfc0c-cb92-4968-baf3-d34bfe7f26f2)

* The above line chart represents the YouTubers with highest yearly earnings.
* **Highest Earner:** “DaFuq!?Boom!” appears to have the highest yearly earnings, exceeding 1.0 x 10^8 (100 million) in the             represented currency
* **Top Contenders:** “T-Series” closely follows, with earnings nearly equal to DaFuq!?Boom!. “Cocomelon - Nursery Rhymes” is the       third highest, with earnings slightly below T-Series
* **Other Significant Channels:** “SET India” and “Zee TV” are fourth and fifth, respectively. Their earnings are lower than the     top three but still substantial.

6. **Correlation between Subscribers, Views and Earnings**

   ![image](https://github.com/user-attachments/assets/0c3cb1eb-c53a-4f6b-86e5-6efdedc6d696)

* This visual is a correlation matrix, which shows the relationships between different variables using correlation coefficients.
* **Subscribers & Video Views:** Correlation of 0.79. This is a strong positive correlation, indicating that as the number of      subscribers increases, the number of video views also tends to increase. 
* **Video Views & Monthly Earnings:** Correlation of 0.64. This suggests a moderate positive relationship,   meaning that         higher video views are associated with higher monthly earnings.
* **Subscribers & Monthly Earnings:** Correlation of 0.5. This indicates a moderate positive relationship,   suggesting that an   increase in subscribers is moderately associated with an increase in monthly earnings. 
* **Lowest & Highest Monthly Earnings:** Correlation of 1













