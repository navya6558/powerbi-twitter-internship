# Power BI Internship Project — Twitter Analysis Dashboard

**Name:** Macharla Navya Anjali
**Track:** Power BI / Data Visualization

## About this project

This repository is for my Power BI internship submission. The challenge was to develop six visualizations with some filters, aggregation logic and for some of the visualizations with visibility conditions with time (e.g., visible only during specific hours in IST).

The files in this repo contain the following information:

- The finished Power BI Desktop file:
-  **project1.pbix** – This file includes all six of the visuals created in the tasks above on top of the starter dashboard Power BI file provided by my trainer.
- **`Tweet.xlsx`** — Original data of the Twitter engagements that were used for all six tasks.
- **Navya_Anjali_Internship_Report.docx** — my internship report which includes the following sections: Introduction, Background, Learning Objectives, Activities and Tasks, Skills and Competencies, Feedback and Evidence, Challenges and Solutions, Outcomes and Impact, and Conclusion.

## Tasks completed

1.This will be a clustered bar chart of clicks from the URL/profile/hashtag that the tweet links to, by tweet category and with only even dates (shown only 3-5 PM IST) and a word count of > 40.

2.Engagement Rate Comparison: Average engagement rate of tweets with app opens compared to tweets without app opens, both over two separate IST windows.

3.Media views and engagements by day of week (DOW) — dual-axis chart of media views and engagements for each day of the week in Q4 2020, with conditional formatting highlighting days with above-average views.

4. Replies, Retweets & Likes Comparison — simple SUM-based bar chart for June-August 2020.
  
6. Monthly Engagement Rate Trend — Line chart of average engagement rate for tweets with media compared to those without media through the month.
7. 
6.Top 10 tweets by Engagement – Top N chart (exclude weekend tweets), only visible during 3–5 PM IST.

## How to view

Open up the report `project1.pbix` in Power BI Desktop (which you can download free from Microsoft) and see all six report pages fully interactive.
The internship report is in .docx which contains the full write-up of the process, DAX formulas used and problems encountered.

## Notes on the dataset

Even if the visualization is built correctly, some of the visuals have no data or have incomplete data — this occurs because the source dataset does not contain rows that meet all of the filtering criteria (for example, there are no tweets in the dataset with a word count of more than 40). This is shown and explained in the section "Challenges and Solutions" of the report.
