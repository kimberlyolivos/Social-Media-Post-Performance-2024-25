# Project Background
The collected data centered around different posts made in Facebook, Instagram, LinkedIn, YouTube, X and TikTok from January 1st 2024 to May 1st 2025 for an IT company actively running content campaigns across multiple social media platforms. The goal for this project is to analyze what kind of content is succesful on different platforms and explain regional trends in engagement to inform better content and platform strategy decisions.

An interactive Power BI dashboard can be downloaded [here](Social_Media_Post_Performance_2024_2025.pbix).

The R script utilized to review the null values and find missing patterns can be found [here](Preparing_Data.R).

# TikTok posts performance from January 2024 to May 2025 
Although the report includes data from various social media platforms, TikTok was one of the only two platforms that provide complete information on the CTR for all posts.

# Insights deep dive

## Content categories and format performance
Over 2024 and the beginning of 2025 (from January 1st until May 1st) the content categories that have driven the **highest level of engagement** are **educational and product promotion**, reaching a total of around 40 million engagements in 2024. 

Although **Customer Story** content didn’t reach a high total engagement, possibly due to the limited number of posts made, it does have the **highest average engagement rate** (between 20 and 21%) among all categories for both years. Educational content also is the second content category with one of the highest average engagement rate. On the other hand, the average engagement rate for product promotion content is one of the lowest, at 12%.

An important fact to highlight is the **user preference for organic content**. Since early last year, this type of content has consistently driven the highest engagement across categories.

In regards to content format, during 2024, videos and live streams showed a **similar average engagement rate across the categories of Customer Story** (19–20%), Educational (20%), and Product Promotion (11–12%). In 2025, this similarity has maintained for **Customer Story and Product Promotion**, but for Educational content, **videos have shown a 2% increase in their average engagement rate**.

Across the three categories, videos were posted more than live streams. In 2024, videos also had a higher CTR for educational and product promotion content, however live streams performed better in terms of CTR for Customer Story content with an average of 1.75%.

In early **2025**, 
-	**Customer Story** videos have a higher CTR (1.89%) than live streams in contrast to 2024 (1.75%).
-	For **Educational content**, live streams are ahead in CTR, but videos still continue to bring in more interactions overall.
-	In **Product Promotion**, videos clearly lead in average CTR for both 2024 (1.76%) and 2025 (1.74%), but there aren't as many videos posted as for the other two categories.

![](data_viz/customer_story_breakdown.png)
![](data_viz/educational_breakdown.png)

## Hashtags that reach higher level of impressions
Since the beginning of 2024, the hashtags that have constantly driven the highest reach are:
-	**#CustomerStory** for Educational and Customer Story content
-	**#ProductDemo** for Product Promotion
-	**#TrendingNow** for Entertainment
-	**#EventRecap** for the Event/Webinar category
  
## Best times and days to post to generate more engagement
Overall, the main best times to post based on 2025 trends are:
-	For **Product Promotion content**: Thursdays at 12 p.m. and 5 p.m.
-	For **Educational content**: Tuesdays at 8 a.m., Wednesdays at 5 p.m., and Sundays at 7 p.m.
-	For **Customer Story content**: Tuesdays to Fridays between 4 and 5 p.m., Wednesdays at 12 p.m., Fridays at 8 a.m., Saturdays at 3 p.m., Sundays between 9 and 10 a.m.
1[](https://github.com/kimberlyolivos/Social-Media-Post-Performance-2024-25/blob/main/data_viz/product_promotion_posting_times.png)
  
## Top Regions by Engagement
In 2024, the USA led with 17 million engagements. But from January 1st to May 1st of 2025, **Japan is leadin in engagement levels with 7 million engagements**. During this period, the **USA dropped six positions**, now generating only about half the engagement Japan is getting.

## Best Posting Times for Japan and the USA
For the **Japanese audience**:
-	In **2024**, the best times were on Saturdays at 8 a.m. and 1 p.m.  
-	In **2025**, better results come from posting on Thursdays at 5 p.m., Fridays at 8 a.m., and Saturdays at 8 a.m. and 4 p.m.
  
![](https://github.com/kimberlyolivos/Social-Media-Post-Performance-2024-25/blob/main/data_viz/japan_2025_posting_times.png)

To reach the **USA audience**:
-	In **2024**, peak times were Mondays at 9 a.m. and Fridays at 5 p.m.
-	In **2025**, engagement is highest when posting on Mondays at 4 p.m., Tuesdays at 2 p.m., Thursdays at 10 a.m., and Fridays at 3 p.m.
  
![](https://github.com/kimberlyolivos/Social-Media-Post-Performance-2024-25/blob/main/data_viz/usa_2025_posting_times.png)

## Recommendations
Some recommendations that would be introduced to the marketing team are the following:
-	Increase the production of Customer Story content in video format in 2025, since they have the highest engagement rate as well as a high average CTR. 
-	Implement strategies to re-engage the U.S. audience by adjusting posting schedules and content formats to align with their current content preferences and behavior patterns.

