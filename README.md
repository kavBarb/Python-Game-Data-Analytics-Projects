# Python-Game-Data-Analytics-Projects
Book Keeping on Major Models I used during my job as a product analyst in a game company start up 

# Overview
This project explores user retention and segmentation using cohort analysis techniques in SQL, and clustering and regression modeling in Python. It focuses on player behaviors in a mobile game app, with attention to ad viewers, conversion, and retention.

## Goals
Identify behavioral cohorts (e.g., ad viewers vs. non-viewers)

Segment players by conversion, country, platform

Build regression models to estimate LTV

Apply unsupervised learning to identify hidden user clusters

## Tools & Technologies
SQL (BigQuery) for querying event data

Python (Pandas, Scikit-learn, Matplotlib) for analysis

Jupyter Notebook for prototyping

Looker Studio for dashboarding (not shown here)

📊 Key Analyses
sql/cohort_analysis.sql: Tracks 30-day retention by cohort

sql/segment_query.sql: Segments by conversion and platform

notebooks/cohort_clustering.ipynb: K-Means for behavioral clusters

notebooks/ltv_regression.ipynb: Regression for predicting LTV

📷 Sample Visuals

🧠 Insights
Ad viewers have 3x retention compared to non-viewers

Behavioral clusters revealed a distinct group of high-LTV low-conversion users

Regression models achieved R² of 0.71 on predicting 30-day LTV

📝 Blog Post
Read the full write-up on Medium: [Link to article]

📁 How to Use
Clone repo

Open SQL files for queries (use BigQuery or similar)

Run notebooks in Jupyter or Google Colab

📩 Contact
Want to collaborate or hire me? Reach out on [LinkedIn](your link) or visit my website: [livewildbarefoot.com]
