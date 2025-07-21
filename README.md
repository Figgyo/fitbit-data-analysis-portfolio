# fitbit-data-analysis-portfolio
Project Background
Bellabeat is a health-focused technology company that designs smart wellness products for women, including activity trackers and a comprehensive wellness app. As Bellabeat seeks to grow in the competitive smart device market, it wants to better understand how people use wearable fitness technology in their daily lives.

This project analyzes publicly available Fitbit data to uncover trends in activity, sleep, and overall smart device usage. The goal is to generate actionable insights that Bellabeat can use to enhance its marketing strategy and further develop products that meet user needs.

**Insights and recommendations are provided on the following key areas:**

- **User Activity Trends:** Evaluation of daily steps, activity intensity, and overall movement patterns among users.
- **Sleep Behavior Analysis:** Assessment of user sleep duration and quality, and its relationship to activity levels.
- **Device Engagement:** Analysis of how consistently users interact with their fitness trackers.
- **Correlation Analysis:** Investigation of the relationships between physical activity, sleep, and calories burned.
- **Marketing Opportunities:** Recommendations for leveraging user behavior insights to inform product messaging and user engagement strategies.

The complete data cleaning, processing, and exploratory analysis workflow is documented in the following Jupyter notebooks:

- [Data Cleaning and Processing](Fitbit_Process_Phase.ipynb)
- [Exploratory Data Analysis](Bellabeat_Fitbit_Analysis.ipynb)

 ## Data Structure & Entity Relationship Diagram (ERD)

The Fitbit dataset is organized into several related tables, each capturing different aspects of user activity, biometrics, and wellness data. The core tables and their relationships are:

- **dailyActivity:** Main table capturing each user’s daily totals for steps, distance, activity intensity, and calories burned.
- **weightLogInfo:** Records of user weights, BMI, and body fat percentages over time.
- **hourlySteps / hourlyCalories / hourlyIntensities:** Hourly summaries of steps, calories burned, and physical activity intensity.
- **heartrate:** Heart rate measurements at specific timestamps for each user.
- **Merged_Sleep_and_Activity:** Combines daily activity data with total daily sleep minutes for each user.

All tables are linked by the `Id` field (the unique user identifier), which enables integrated analysis of activity, sleep, weight, and heart rate patterns.





