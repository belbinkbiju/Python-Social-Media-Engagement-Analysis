# 📊 Social Media Engagement Analysis

A Python-based data analysis project exploring social media engagement patterns across content types, categories, countries, demographics, devices, verification status, and sentiment.

## 🎯 Objective

The objective of this project is to analyze social media data and identify patterns and factors that influence user engagement. The analysis covers content types, post categories, countries, age groups, devices, verification status, and sentiment.

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** for data manipulation and analysis
- **NumPy** for numerical operations
- **Matplotlib** for data visualization
- **Seaborn** for statistical visualizations
- **Plotly** for interactive visualizations
- **Jupyter Notebook / Google Colab**

## 📂 Dataset

The dataset contains **5,000 social media records** with information about users, posts, engagement metrics, posting dates, devices, verification status, and sentiment.

### Key Features

- User demographics: age, gender, country
- Post information: post type and category
- Engagement metrics: likes, comments, shares, watch time, and impressions
- User information: follower count and verification status
- Device type and sentiment
- Hashtags and hashtag count
- Engagement rate

## 🧹 Data Cleaning & Preparation

The dataset was cleaned and prepared for analysis using Pandas and NumPy.

Key preprocessing steps included:

- Checked and handled missing values using mean and mode imputation
- Checked for duplicate records
- Validated categorical values for consistency
- Converted `posted_at` to datetime format
- Checked for unrealistic or negative values in engagement metrics
- Created `hashtag_count` from the hashtags column
- Converted relevant numerical columns to appropriate data types
- Created `engagement_score` using likes, comments, and shares
- Applied log transformation to `engagement_rate` to reduce the impact of extreme values

## 📊 Analysis & Visualization

The cleaned dataset was explored using descriptive statistics, group-by analysis, correlation analysis, and visualizations.

The analysis focused on:

- Engagement patterns across different post types and categories
- Average engagement rates across countries
- Engagement differences between age groups
- Verified vs. non-verified users
- Watch time across different device types
- Engagement patterns based on sentiment
- Relationships between numerical variables using correlation analysis
- Trends in average engagement over time
- Distribution of engagement metrics and user demographics

The project includes **10 visualizations** using Matplotlib, Seaborn, and Plotly, including scatter plots, line charts, bar charts, pie charts, histograms, box plots, violin plots, correlation heatmaps, and an interactive Plotly chart.

## 🔍 Key Findings

- **Video posts** recorded the highest average engagement score among the different post types, although the differences were relatively small.
- **Music** was the highest-performing post category based on average engagement score.
- **Brazil** recorded the highest average engagement rate among the countries analyzed, while the **USA** recorded the lowest.
- Users aged **26–40** had the highest average engagement score, while engagement was lowest among the **56–65** age group.
- **Verified users** had a slightly higher average engagement rate than non-verified users.
- **Mobile users** recorded the highest average watch time, although the difference between devices was small.
- Posts with **negative sentiment** recorded the highest average engagement rate and engagement score.
- Most numerical variables showed **weak correlations** with each other. Likes and impressions, in particular, showed almost no linear relationship.

## 📁 Project Files

| File | Description |
|---|---|
| `Social_Media_Engagement_Analysis.ipynb` | Jupyter Notebook containing the complete data cleaning, analysis, statistical exploration, visualizations, and insights |
| `social_media_engagement_5000.csv` | Dataset containing 5,000 social media records used for the analysis |

## ▶️ How to Run

1. Download or clone this repository.
2. Keep the notebook and CSV file in the same folder.
3. Open `Social_Media_Engagement_Analysis.ipynb` using Jupyter Notebook or Google Colab.
4. Run the cells sequentially to reproduce the analysis.
