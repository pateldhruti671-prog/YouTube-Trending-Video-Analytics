Data Processing
The dataset was cleaned and prepared before analysis. Data preprocessing included handling missing values, standardizing data types, preparing numerical columns, and preparing date and time information for analysis.
Analysis Performed
Category Analysis
Category-wise average views were calculated to identify categories receiving high view counts.
Sentiment Analysis
Sentiment analysis was performed on YouTube video titles using the VADER sentiment analyzer. Titles were classified as Positive, Negative, or Neutral.
Engagement Analysis
Views, likes, comments, and engagement rate were analyzed to understand video performance.
Publishing Time Analysis
Video performance was analyzed according to publishing hour and publishing day.
Trending Analysis
Trending video activity was analyzed over time using time-series visualizations.
Power BI Dashboard
An interactive Power BI dashboard was created to visualize important YouTube trends and performance metrics.
Key Findings
- Gaming recorded the highest average views among the analyzed categories.
- Movies and Music also showed high average views.
- Video titles showed different sentiment patterns.
- Publishing time can be compared with video performance.
- Trending activity changes over the analyzed period.
Project Output
The repository contains:
- Cleaned dataset
- Python analysis scripts
- Generated CSV analysis files
- Data visualizations
- Power BI dashboard
- Project presentation
- Screenshots
Conclusion
This project demonstrates how YouTube trending data can be analyzed using Python and visualized using Power BI to identify patterns in categories, views, engagement, sentiment, publishing behavior, and trending activity.

### Step 2 — `requirements.txt` banao

Project ke main folder me **New File → `requirements.txt`**

Paste:

```text
pandas
matplotlib
seaborn
nltk