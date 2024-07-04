

## YouTube Data Extraction and Analysis

### Project Overview
This project involved developing a Python script to download and analyze user interaction data from YouTube videos. Given a list of YouTube video IDs in a CSV file, the script extracted various pieces of information and performed sentiment analysis on the comments. The project showcased skills in data extraction, API usage, data analysis, and sentiment analysis.

### Features
1. **Data Extraction**: 
    - Extracted 100 comments for each video.
    - Retrieved video description, view count, like count, dislike count, comment count, duration, and favorite count.
    - Ignored invalid or non-existent video IDs and proceeded with the remaining IDs.

2. **Data Analysis**:
    - Listed the top 10 videos based on total views.
    - Listed the bottom 10 videos based on total views.
    - Identified the most liked and least liked videos.
    - Found the video with the highest duration.
    - Applied sentiment analysis on the comments for each video.

### Tools and Technologies
- **Python**: Core programming language used for the script.
- **YouTube Data API**: Used to fetch video data and comments.
- **Pandas**: For data manipulation and analysis.
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: For sentiment analysis of comments.

### Files
- `vdoLinks.csv`: CSV file containing YouTube video IDs.
- `youtube_data_extraction.py`: Python script for extracting and analyzing data.

### Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/youtube-data-extraction.git
   cd youtube-data-extraction
   ```

2. Install required libraries:
   ```bash
   pip install pandas google-api-python-client vaderSentiment
   ```

3. Set up YouTube Data API:
   - Obtain an API key from the [Google Developers Console](https://console.developers.google.com/).
   - Replace `YOUR_API_KEY` in the script with your actual API key.

4. Run the script:
   ```bash
   jupyter notebook sma.ipynb
   ```

### Results
- The script outputted CSV files containing the extracted data and sentiment scores.
- Provided lists of top and bottom videos based on views, and the most and least liked videos.
- Sentiment analysis results for each video’s comments.

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

### License
This project is licensed under the MIT License.

