# YouTube Trending Analytics Project

This project analyzes trending YouTube videos using AWS and Tableau. It demonstrates an end-to-end pipeline from data ingestion to visual storytelling.

## 🚀 Tools Used
- AWS Lambda: YouTube API extraction every 6 hours
- Amazon S3: Data lake for raw & processed files
- AWS Glue: ETL (JSON → Parquet)
- AWS Glue Crawler: Auto-schema detection
- Amazon Athena: SQL queries on S3
- Tableau: Interactive dashboard

## 📊 Dashboard Highlights
- Top trending videos by views
- Views, likes, comments by country
- Engagement bubble chart
- Publishing activity timeline
- Channel performance leaderboard

## 📁 Files Included
- `code/lambda_function.py` – YouTube API extractor
- `code/glue_job_script.py` – Transformation script
- `YouTube_Trending_Analytics_Project.pdf` – Full project write-up
- (Optional) Dashboard screenshot

## 📸 Screenshot
![Dashboard Preview](dashboard_screenshot.png)

## 📌 Author
Created by [sasank reddy](https://www.linkedin.com/in/sasank reddy) – aspiring data engineer.
