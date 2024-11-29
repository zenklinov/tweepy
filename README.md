# Twitter Data Scraper using Tweepy

This Python script demonstrates how to scrape recent tweets from Twitter using the Tweepy library. The script searches for tweets containing the hashtag `#pepguardiola`, retrieves additional tweet metadata such as context annotations and creation time, and saves the results into an Excel file.

---

## Features

- **Twitter API Integration**: Fetch recent tweets with a specific query using Tweepy.
- **Tweet Metadata**: Retrieve fields such as `context_annotations` and `created_at`.
- **Data Export**: Save the scraped data into an Excel file for further analysis.

---

## Prerequisites

1. **Twitter Developer Account**: 
   - Obtain a **Bearer Token** from the [Twitter Developer Portal](https://developer.twitter.com/).
2. **Python Libraries**:
   - `tweepy`: For accessing the Twitter API.
   - `pandas`: For data manipulation and exporting to Excel.
   - Install dependencies using:
     ```bash
     pip install tweepy pandas
     ```

---
