# Analyzing-My-Spotify-Data
Analyzing my spotify data for different time periods. This project focuses on analyzing and visualizing Spotify listening habits using Python and various data science tools. The project includes several scripts for data processing, analysis, and visualization.

# Table of Contents
Data Collection

Audio Features Analysis

Time-based Analysis

Listening Patterns during Exam Periods

Playlist Creation

HTML Data Extraction

Common Song Analysis

Future Listening Prediction

# Data Collection
The project starts by collecting Spotify streaming history data from two JSON files using pandas. It combines the data, extracts relevant columns, and displays the first few rows of the new DataFrame.

# Audio Features Analysis
The script utilizes the Spotify API to fetch audio features for a subset of songs from the streaming history. It demonstrates how to authenticate with the Spotify API, extract track IDs from URIs, and retrieve audio features.

# Time Based Analysis
This script focuses on time-based analysis, converting timestamps, extracting month and year, and visualizing monthly listening time trends.

# Listening Patterns During Exam Periods
Examining listening habits during exam periods, the script calculates total listening time, daily averages, and creates a bar chart comparing daily average listening time during exam and non-exam periods.

# Playlist Creation
These scripts demonstrate how to create Spotify playlists based on listening habits. One script creates playlists for songs listened to during exam periods, and the other creates playlists for non-exam periods.

# HTML Data Extraction
The project includes a script for extracting data from an HTML file containing information about Spotify tracks. It uses BeautifulSoup to scrape data from a playlist table.

# Common Song Analysis
This script analyzes common songs between exam and non-exam periods, calculating Jaccard similarity and visualizing the overlap using a Venn diagram.

# Future Listening Prediction
The final script uses a linear regression model to predict future listening minutes during a specified exam period based on historical data. It demonstrates data preprocessing, model training, and prediction.

Feel free to explore each script for detailed explanations and adjust the parameters to suit your own Spotify listening history data.

# My Hypothesis and Purpose 
I wanted to find out if I'm listening to different songs when I'm studying for my exams. 
Null Hypothesis (H0): There is no significant difference in the songs I listen to when studying for exams compared to other times.
Alternative Hypothesis (H1): I listen to different songs when studying for exams compared to other times.

# Conclusion
Exam Songs and Non-Exam Songs datasets have a similarity of 8%, this supports the H1.
In conclusion, H0 is rejected.
