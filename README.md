# YouTube_Data_Analysis
YouTube Data Analysis with python.

>>> To collect data from YouTube, you need to set up an API. Here are the steps you can follow:

    Go to Google Cloud Console.
    Click on the project drop-down at the top, then “New Project”.
    Enter a project name and click “Create”.
    In the Google Cloud Console, navigate to “APIs & Services” > “Library”.
    Search for “YouTube Data API v3” and click on it.
    Click “Enable”.
    Go to “APIs & Services” > “Credentials”.
    Click “+ CREATE CREDENTIALS” and select “API key”.
    Copy the generated API key.

>>> Now, let’s get started with YouTube data collection using Python. I’ll collect data about the top 200 trending videos on YouTube:

  Use "Fetch_data.ipynb" to fetch data from youtube using api key. Remember to add your API KEY in the code.

>>> Running the code fron "Fetch_data.ipynb" will genrate a csv file containg data from the youtube.

>>> now we analyze this data using python.

>>> use "Data_Analysis.ipynb" for the analysis. and remember to replace yor api_key in the code.

>>> the analysis includes:

  look at what the data looks like.
  look at the missing values and data types.
  Filling missing values and updating data types.
  quick look at the descriptive statistics.
  look at the distribution of views, likes and comments of all the videos in the data.
  look at the correlation between likes, views, and comments.
  collect the category names as well to analyze the categories of the trending videos.
  analyze the number of trending videos by category.
  look at the average engagement metrics by category.
  convert the duration from ISO 8601 format to seconds.
  analyze the content and the duration of videos.
  analyze the relationship between views and number of tags used in the video.
  impact of the time a video is posted on its views.
  

Conclusion:

So, here’s my conclusion on what makes a video trend on YouTube:

1) Encourage viewers to like and comment on videos to boost engagement metrics.
2) Aim to create shorter videos (under 5 minutes) for higher engagement, especially for categories like Music and Entertainment.
3) Schedule video uploads around peak times (6 AM – 4 PM) to maximize initial views and engagement.
