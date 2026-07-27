# Power BI Internship Project — Twitter Analysis Dashboard

**Name:** Macharla Navya Anjali
**Track:** Power BI / Data Visualization

## About this project

This repository contains my completed Power BI internship submission. The task was to build six visualizations on a Twitter engagement dataset, each with specific filtering rules, aggregation logic, and in some cases, time-based visibility conditions (visible only during certain hours in IST).

## Files in this repo

- **`project1.pbix`** — the completed Power BI Desktop file with all six task visuals, built on top of the starter dashboard file provided by my trainer.
- **Tweet.xlsx`** — the source Twitter engagement dataset used for all six tasks.
- **`Navya_Anjali_Internship_Report.docx`** — my Internship report covering Introduction, Background, Learning Objectives, Activities and Tasks, Skills and Competencies, Feedback and Evidence, Challenges and Solutions, Outcomes and Impact, and Conclusion.

## Tasks completed

1. **Tweet Interaction Breakdown by Category** — clustered bar chart of URL/profile/hashtag clicks by tweet category, filtered to even dates and word count > 40, visible only 3–5 PM IST.
2. **Engagement Rate Comparison** — average engagement rate for tweets with vs. without app opens, restricted to weekday 9 AM–5 PM tweets, visible during two IST windows.
3. **Media Interaction by Day of Week** — dual-axis chart of media views and engagements by day of week for Q4 2020, with conditional formatting highlighting above-average days.
4. **Replies, Retweets & Likes Comparison** — simple SUM-based bar chart for June–August 2020.
5. **Monthly Engagement Rate Trend** — line chart comparing average engagement rate for tweets with vs. without media, by month.
6. **Top 10 Tweets by Engagement** — Top N chart by combined retweets + likes, excluding weekend tweets, visible only 3–5 PM IST.

## How to view

- Open `project1.pbix` in **Power BI Desktop** (free download from Microsoft) to see all six report pages with full interactivity.
- The full write-up of my process, DAX formulas used, and challenges faced is in the internship report (`.docx`).

## Notes on the dataset

Some of the visuals return empty or partial results even when built correctly — this is because the underlying dataset doesn't contain rows matching every filter condition (for example, no tweet in the dataset has a word count above 40). This is documented and explained in the "Challenges and Solutions" section of the report.
