# The Art of storytelling -  Summative Assessment

# Instagram Data Visualization in Tableau for GramGaze

## Project Overview

**Title:**  Likes, Comments, and Aesthetics - Analysing Instagram Trends and Engagement Metric\
**Purpose:** To analyze Instagram engagement metrics and trends to gain actionable insights.\
**Target Audience:** Social media marketers, data analysts, and content creators seeking to optimize engagement strategies of INSTAGRAM.\
**Key Objectives:**

- Understand engagement patterns across posts.
- Identify top-performing content types and hashtags.
- Analyze follower growth trends and interactions.
- Provide interactive dashboards for better data exploration.

---

## Data Summary

**Data Source:** Instagram CSV dataset containing metrics on posts, engagement, followers, and content types.\
**Cleaning Steps:**

- Removed duplicates and irrelevant columns.
- Standardized date formats and missing values.
- Filtered out anomalies (e.g., extreme outliers in likes/comments).

**Key Variables Analyzed:**

- **Post Metrics:** Likes, Comments, Shares, Impressions, Saves.
- **Home%/ Explore%/ Hashtag%/ Others%:**([From Explore or Home or Hashtags or Others] / [Impressions]) * 100
- **Engagement Rate:** (Likes + Comments + Saves) / Impressions.
- **Follower Conversion rate:** IF [Profile Visits] > 0 THEN [Follows] / [Profile Visits] ELSE NULL END

---

##  Key Insights

- **Peak Engagement Times:** Posts published in the evening (6-9 PM) received the highest interaction rates.
- **Best Performing Content:** Carousel posts had the highest engagement rates compared to single images and videos.
- **Hashtag Effectiveness:** Posts with 5-10 hashtags performed better than those with excessive or no hashtags.
- **Follower Growth Trends:** Spikes in followers were observed during giveaways and collaborations.
- **User Interaction Patterns:** Videos had higher reach but lower engagement compared to carousels.

---

## Dashboard Features

**1️ Top Performing Hashtags**
* The most engaging hashtags include #python, #pythonprogramming, #artificialintelligence, and #deeplearning.
* Hashtags play a crucial role in boosting engagement across likes, shares, and follows.

**2️ Audience source analysis**

* The Home Feed generates the highest impressions, followed by Hashtags and Explore Page.

**3️ Follower conversion rate**

* There are spikes in the follow conversion rate on specific days, indicating that certain posts perform exceptionally well in converting viewers into followers

**4️ Engagement metrics**

- Likes are the highest engagement metric, significantly outperforming other interactions.

**Interactive Features:**

- **Date Selector:** Allows users to filter data by specific time ranges.
- **Drill-Down Functionality:** Click on visual elements to view post-specific details.

---

## 📷 Relevant Screenshots

![image](https://github.com/user-attachments/assets/9587c33c-b6f0-4f9c-8fbe-e43ec687ee6d)
(Interactive filter)

![image](https://github.com/user-attachments/assets/13dfcbbd-5dea-4c32-b009-50613f4f7f78)
(Engagement metrics)

![image](https://github.com/user-attachments/assets/605bcf13-a105-47e7-9858-0b325d85823c)

![image](https://github.com/user-attachments/assets/3d51e1eb-184a-4ecd-95f9-1dfd7f0df475)

![image](https://github.com/user-attachments/assets/4d38a2b8-5681-4a25-8222-c8f9195ac2da)
(Dasboard)




---

##  Conclusion & Future Improvements

**Summary:** This Tableau visualization helps marketers and analysts understand Instagram engagement trends, optimize content strategies, and improve audience reach.

**Potential Improvements:**

* Optimize hashtag strategy by leveraging high-performing tags while experimenting with new trending hashtags.
* Improve content discoverability on the Explore Page by enhancing post timing and engagement strategies.
* Increase interactive elements (polls, questions, engaging captions) to boost comments and shares.
* Identify and replicate the content strategy of high-converting posts to maintain steady follower growth.
* Integrate real-time Instagram API for live tracking.
* Explore sentiment analysis using captions and comments.

---



