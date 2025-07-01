Social Media Engagement Analytics with Python & Power BI
Project Overview
This project is a deep dive into Instagram and Facebook performance data, combining Python and Power BI to analyze real-world social media metrics. The objective was to uncover insights about what drives engagement and help inform data-driven content strategies.

The project includes:

End-to-end data cleaning and preprocessing in Python

Power BI dashboards with interactive visualizations

Insight-driven written reports

Simulated A/B testing using text-based classification

Tools & Technologies
Python (Pandas, Matplotlib)

Power BI

Excel

Jupyter Notebook

Project Structure
css
Copy
Edit
Instagram_Analytics/
├── Instagram_Analytics.ipynb
├── Cleaned_Instagram_Analytics.xlsx
├── Instagram_Task.pbix
├── Social Media Performance Report.pdf (Instagram section)

Facebook_Analytics/
├── Facebook_Analytics.ipynb
├── Cleaned_Facebook_Analytics.xlsx
├── Facebook_Task.pbix
├── Social Media Performance Report.pdf (Facebook section)

README.md
Instagram Report Summary
Engagement rate averaged around 4.68%.

Engagement steadily increased from September to December 2024, peaking during the holiday period.

Feed posts outperformed Reels in total engagement, suggesting user preference for static content.

Emotional or motivational captions with strong calls to action performed best.

A rule-based model using median engagement was implemented to classify posts as "High" or "Low" performing.

Facebook Report Summary
Cleaned and analyzed two datasets: Profile Overview and Post Engagement.

Created a normalized Post Engagement Score combining likes, shares, comments, views, and clicks.

Simulated A/B testing using a text classification approach to group captions into campaign types.

"Masterclass CTA" posts had the highest engagement, outperforming all other categories.

Bar, line, and pie charts in Power BI showed trends across formats, themes, and time.

Power BI Visuals
Engagement trends over time (line chart)

Post type breakdown and performance (stacked bars and pie charts)

Top performing posts ranked by engagement

High vs Low engagement distribution (scatter plot)

Ad creative performance (bar chart by message type)

KPI cards summarizing engagement per 100 views

Opportunities for Extension
If the datasets had more granularity or linkages, the following analyses could be added:

Time-of-day and day-of-week performance analysis

Demographic and geographic segmentation

Follower growth vs. content engagement correlation

Sentiment analysis on post captions

Funnel analysis from impressions to clicks

