# Understanding-Search-Interest-with-Google-Trends
This project explores time series data to analyze and compare the popularity trends of three prominent AI tools: ChatGPT, Gemini, and Microsoft Copilot. The project focuses on processing and visualizing the interest over time for these AI tools, using real-world data from Google Trends, to uncover patterns, trends, and insights. By performing these analyses, the goal is to help make data-driven decisions about where to focus marketing efforts, predict future trends, and identify areas for improvement in these tool
## Acknowledgements
This project was originally created as part of a course on [DataCamp](https://www.datacamp.com). The original content and structure were provided by DataCamp.
## Project Overview
The global interest in AI tools is rapidly evolving. This analysis focuses on understanding which of the three major AI tools — ChatGPT, Gemini, and Microsoft Copilot — is gaining the most traction over time. By examining time series data from Google Trends, we can identify key insights such as:
- Which tool has the most consistent growth in interest.
- When ChatGPT experienced its largest decline in interest.
- Which month had the highest average interest across all tools.

## Tools and Libraries
- Python: Used for data processing and analysis.
- Pandas: For manipulating and analyzing the time series data.
- Matplotlib: For visualizing trends and patterns.
- Google Trends Data: The Google Trends data is available as a CSV file `ai_tools_comparison.csv`. The data contains the number of worldwide searches for chatGpt, Gemini, and Microsoft Copilot over the past 12 months as of September 2024.
    - Link to query: https://trends.google.com/trends/explore?q=chatgpt,gemini,%2Fg%2F11tsqm45vd&hl=en-US
  
## Key Analysis
1. Consistent Growth in Interest
This analysis calculates the weekly percentage change in interest for each tool, then determines which tool has shown the most consistent growth over the observed period. Consistency is measured using the standard deviation of the growth rates.

2. Largest Decline in Interest for ChatGPT
By analyzing the time series data, we can identify the month and year when ChatGPT experienced its largest decline in search interest. This is done by finding the lowest point in the ChatGPT data.

3. Month with the Highest Average Interest
This analysis examines the monthly average search interest across all tools to determine which month had the highest combined interest for ChatGPT, Gemini, and Microsoft Copilot.
