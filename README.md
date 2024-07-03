# YouTube-Data-Extraction-and-Analysis
Project Overview
Developed a Python script to download and analyze user interaction data from YouTube videos based on a list of video IDs in a CSV file. Extracted key information, including comments, description, view count, like count, dislike count, comment count, duration, and favorite count. Applied sentiment analysis on the comments using VADER, showcasing skills in data extraction, API usage, data analysis, and sentiment analysis.

Features
Data Extraction:

Extracted 100 comments per video.
Retrieved video description, view count, like count, dislike count, comment count, duration, and favorite count.
Ignored invalid video IDs and continued processing remaining IDs.
Data Analysis:

Listed the top 10 videos based on total views.
Listed the bottom 10 videos based on total views.
Identified the most liked and least liked videos.
Found the video with the highest duration.
Performed sentiment analysis on comments for each video.
Tools and Technologies
Python: Main programming language.
YouTube Data API: For fetching video data and comments.
Pandas: For data manipulation and analysis.
VADER: For sentiment analysis of comments.
