# LinkedIn Profile Comments Crawler

## Overview

This repository contains a Python-based program that retrieves **comments from a LinkedIn profile** using the **LinkedIn API** provided by **RapidAPI**. The script collects profile comments based on specified parameters, saving them in a CSV file for easier analysis and review. Using the LinkedIn API from RapidAPI ensures efficient and compliant data retrieval.

### Key Features
- **Retrieve Profile Comments**: Collects comments from a specified LinkedIn profile.
- **Save Data to CSV**: Saves retrieved comments in a CSV file for easy access and analysis.
- **Customizable Parameters**: Allows you to specify which profile to target and filter parameters.

### Technologies Used
- **Python**: Primary programming language for the script.
- **Requests**: Library used for making HTTP requests to the API.
- **Pandas**: Library used for data manipulation and exporting to CSV.
- **LinkedIn API on RapidAPI**: API used to fetch LinkedIn profile comments in a structured and legal way.

## Setup

### 1. Prerequisites
Make sure you have **Python** installed on your system. Additionally, install the following Python libraries:
```bash
pip install requests pandas
```

### 2. Obtaining an API Key from RapidAPI

To access the LinkedIn API, you’ll need an API Key from RapidAPI:
1. Register or log in to [RapidAPI](https://rapidapi.com/).
2. Search for “LinkedIn” and look for an API that provides profile comment retrieval (for example, `LinkedIn Profile Scraper` or similar).
3. Subscribe to the API, noting any usage limits.
4. Obtain your **API Key** from the RapidAPI dashboard.

### 3. Configuring the Code

After you have your API Key:
1. Open the Python script and insert your API Key in the `API_KEY` variable like so:
    ```python
    API_KEY = "e7cfca7086mshb39f9ddd43d29b7p10bd20jsn2f950456dda8"
    ```
2. Set the **LinkedIn Profile ID** or **Profile URL** of the user whose comments you want to retrieve in the code (the exact parameter may vary depending on the API).

### 4. Running the Program

Run the script using the command:
```bash
python linkedin_profile_comments.py
```
The comments data will be saved in a CSV file called `linkedin_comments.csv`.

### Note

Please respect LinkedIn’s privacy policies and usage restrictions. This tool should be used only for personal or authorized research purposes.
