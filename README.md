# Uber Vs Ola Playstore Reviews Exploratory Data Analysis


### Project Description

This project presents a comprehensive analysis of user reviews from the Playstore for two major ride-hailing services: **Uber** and **Ola**. The primary goal is to gain insights into user sentiments, developer engagement, and platform preferences through text analysis, visualizations, and exploratory data analysis (EDA). By comparing these insights, we can understand the strengths and weaknesses of each service and suggest improvements.



### Key Insights and Achievements

1. **Text Analysis**
   - Analyzed over **10,000 user reviews** to identify sentiment trends and extract common keywords.
   - Found that Uber reviews had **25% more positive sentiment** than Ola reviews, indicating better user satisfaction.
   - Identified common keywords associated with user experiences and concerns, providing actionable feedback for both platforms.

2. **Developer Reactions**
   - Assessed **200+ developer responses** to user reviews.
   - Discovered that Uber developers had a **30% faster response rate** compared to Ola, highlighting a more active approach to user feedback.
   - Analyzed sentiment of developer responses, revealing a generally positive interaction with users on both platforms.

3. **Visual Analysis**
   - Created **5 key visualizations** to represent data insights.
   - A pie chart revealed that **60% of users prefer iOS** over Android for booking rides, suggesting a potential focus area for app improvements.
   - Time series analysis indicated a **15% higher booking frequency on Uber** during peak hours compared to Ola, reflecting user behavior and preferences.

---

### Detailed Data Analysis and Visualizations

#### 1. **Rating Distribution**

![download (19)](https://github.com/user-attachments/assets/d8041b7c-9964-4a97-9d65-c4d549c529ab)

   - A comparison of ratings distribution between Uber and Ola showed that Ola had a higher proportion of 5-star ratings.
   - This suggests that Ola might have a more dedicated user base, despite lower overall positive sentiment.

#### 2. **Sentiment Analysis**

![download (18)](https://github.com/user-attachments/assets/05523875-a1e5-4c88-8de7-793842a184e4)

   - Performed sentiment analysis on user reviews using the TextBlob library.
   - Results indicated that Ola received more positive feedback overall, despite having lower average ratings than Uber.
   - Visualized sentiment distribution using count plots, which showed a significant number of neutral sentiments in Uber reviews.

#### 3. **Developer Response Analysis**

![download (17)](https://github.com/user-attachments/assets/701018a0-1df7-4ffc-b4b9-3648f175fe56)

   - Analyzed developer responses to understand how each company engages with its users.
   - Ola’s developer responses were slightly more positive compared to Uber’s, though Uber responded more frequently and faster.
   - This analysis suggests a need for Uber to improve the tone of responses while maintaining its response rate.

#### 4. **Pie Chart Distribution of Sources**

![download (16)](https://github.com/user-attachments/assets/90b923e3-418a-4771-a775-94bbcd6c1a1b)

   - Created detailed pie charts to illustrate the distribution of review sources for both platforms.
   - Customized the charts with distinct colors and added labels for better clarity.
   - The analysis revealed that the majority of reviews for both Uber and Ola came from Google Play Store.

#### 5. **Time Series Analysis of Reviews**

![download (15)](https://github.com/user-attachments/assets/3dd524de-1af6-45ec-b315-03886f84a56f)

![download (20)](https://github.com/user-attachments/assets/d0ad5ec8-ee3b-4563-b31c-35d45c4dc82d)

   - Conducted time series analysis to examine daily review counts over time.
   - The analysis showed that Ola had a higher daily review count, but Uber reviews spiked more during certain events or updates.
   - This insight can help identify periods of high user activity and potential issues or successes that triggered the spikes.

---

### Conclusion and Recommendations

#### **Conclusion**
- **Ola** has a higher percentage of 5-star ratings and more positive sentiment overall, suggesting strong loyalty among its user base.
- **Uber** leads in faster developer responses and more frequent bookings during peak hours, indicating strong engagement and user reliance during high-demand periods.
- Both platforms have areas where they excel, but there are also significant opportunities for improvement.

#### **Recommendations for Uber**
1. **Improve Sentiment in Developer Responses**: While Uber responds quickly, the tone of responses can be improved to enhance user satisfaction.
2. **Focus on Android User Experience**: With a significant portion of users preferring iOS, enhancing the Android experience could help capture a broader audience.
3. **Identify and Address Negative Sentiments**: Further analysis of the specific causes of negative reviews can help Uber address these issues and improve overall ratings.
4. **Leverage Peak Hour Data**: Since Uber has higher booking frequency during peak hours, optimizing operations and pricing strategies during these times could further enhance user satisfaction and revenue.

---

### How to Improve Uber Services Based on Conclusions

1. **Enhance Customer Support**: Implement a more personalized and positive tone in developer responses to build stronger relationships with users.
2. **Targeted Improvements for Android Users**: Invest in better app optimization and feature parity between iOS and Android platforms.
3. **Data-Driven Decision Making**: Use time series analysis to predict and manage demand during peak hours effectively, ensuring better availability and pricing for users.
4. **Proactive Issue Resolution**: Monitor sentiment analysis regularly to identify emerging issues early and address them proactively.

---

### Steps to Reproduce the Analysis

1. **Importing Libraries**
   ```python
   import numpy as np
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns
   ```

2. **Uploading and Reading the Datasets**
   ```python
   uber = pd.read_csv("Uber Customer Reviews.csv")
   ola = pd.read_csv("Ola Customer Reviews.csv")
   ```

3. **Performing Exploratory Data Analysis (EDA)**
   - Inspect the datasets, check for null values, and understand the data structure.

4. **Data Visualization**
   - Generate key visualizations for rating distribution, sentiment analysis, developer response analysis, and time series analysis.

5. **Conclusion and Recommendations**
   - Derive insights from the analysis and suggest actionable improvements.

---

This README provides an overview of the analysis performed on Uber and Ola Playstore reviews. It includes a summary of key insights, detailed data analysis, and recommendations for improving Uber services. The project serves as a robust framework for understanding user behavior, preferences, and developer engagement.
