# YouTube-Channels-Content-Category-Analysis

# 1. Problem Definition
This project analyses how content categories differ in subscriber counts, total views, and upload volume among the top 500 most-subscribed YouTube channels as of June 2024, aiming to provide content positioning insights for small content creators, new channel operators, and junior MCN teams.

# 2. Target User
Small content creators, new YouTube channel operators, and junior MCN teams who need data-driven guidance for content positioning and channel development.

# 3. Data Source
- Source: Kaggle, "Top 500 Most Subscribed YouTube Channels - June 2024"
- Kaggle link: https://www.kaggle.com/datasets/ritiksharma07/top-500-most-subscribed-youtube-channels-june24
- Access date: 16 April 2026
- Main variables: category, subscribers, views, total_number_of_videos

# 4. Project Objective
The project aims to help users understand which content categories perform best in subscribers, views, and upload frequency. It provides clear, actionable insights to support new creators in choosing sustainable and high-potential content fields.

# 5. Methods / Workflow
1. Data loading: Load the raw YouTube dataset from a local CSV file
2. Column standardization: Convert all column names to lowercase to avoid matching errors
3. Data cleaning: Remove duplicate records, drop rows with missing values, and filter invalid content categories
4. Data transformation: Convert text values with K/M/B units into numeric values for calculation
5. Feature calculation: Compute average views per video to measure content efficiency
6. Exploratory data analysis: Group data by category and calculate key performance indicators
7. Data visualization: Generate bar charts, boxplots, scatter plots, and concentration charts for multi-dimensional analysis
8. Insight generation: Summarise seven evidence-based findings for target users based on analysis results

# 6. Key Findings
1. Music and Entertainment categories have the highest average subscribers, making them ideal for new creators to build an audience quickly.
2. Entertainment and Gaming categories generate the most total views, supported by higher upload frequency.
3. Creators should choose categories based on their ability to post consistently, not just subscriber popularity.
4. The Music category shows scattered subscriber distribution and obvious head effects, while other categories develop more steadily.
5. Several categories gain high views per single video, delivering outstanding content efficiency with low update frequency.
6. Upload and view correlation varies by category, so creators need targeted content update strategies.
7. Categories with high top-10 subscriber share face severe monopoly, leaving limited growth space for new creators.

# 7. Repository Structure
- youtube.csv: Raw dataset of top 500 Most Subscribed YouTube channels
- analysis.ipynb: Jupyter Notebook with complete data analysis code
- README.md: Full project introduction and documentation

# 8. How to Run
- Python version: 3.8 or above
- Required packages: pandas, matplotlib, re
- Open notebook: Open the analysis.ipynb file in Jupyter Notebook
- Additional setup: Place the CSV dataset in the same folder as the notebook

# 9. Demo Video
[Insert 1–3 minute demo video link]

# 10. Limitations
- This dataset only covers the top 500 most-subscribed YouTube channels, so the findings may not represent smaller or newer creators.
- The data is cross-sectional and reflects only one point in time (June 2024), so it cannot show changes over time.
- The dataset includes limited variables and does not capture factors such as engagement rate, audience demographics, language, or content quality.

# 11. Next Steps
- Extend the analysis with a larger and more diverse sample of YouTube channels.
- Add time-series data to explore how category performance changes over time.
- Include more variables, such as engagement metrics, region, and language, to generate deeper insights for creators.
