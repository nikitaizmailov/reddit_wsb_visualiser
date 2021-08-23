# reddit_wsb_visualiser
## Run the below link to access the jupyter notebook globally without the need to install the dependencies.
https://mybinder.org/v2/gh/nikitaizmailov/test_web_notebook/74dce2065bef936edefef2c6b8140c8964c80682?filepath=main_final_version.ipynb

Analysing trends and insights of WallStreetBets community on reddit.

The application allows you to retrieve comments from any subreddit and any subreddit's submission. Also you can just view the last 1000 comments published on any subreddit

Below are the pictures of GUI and how to use it.

You will also need to create a Reddit Developer's API token to access PRAW library so that you can send Reddit API requests.


Functionalities:
1) Select Subreddit -> Select Submission/Post -> Input a Regex pattern -> Press button "Analyse Submissions" -> Retrieves all comments from the submission -> Searches for Regex Pattern in each comment and displays that comment and also creates a BarChart graph with amount of mentions for each ticker.
<img width="815" alt="Screenshot 2021-07-21 at 00 43 27" src="https://user-images.githubusercontent.com/42198709/126401885-62db84d8-3b85-4164-b5d4-932249160e7e.png">

2) Select Subreddit -> Input a Regex pattern -> Press button "Display Last 1000 Comments" -> Retrieves the last 1000 comments -> Displays the comments first that matched the Regex pattern then all the comments retrieved.
<img width="804" alt="Screenshot 2021-07-21 at 01 11 08" src="https://user-images.githubusercontent.com/42198709/126401878-14fccb75-f4f3-4fde-a72e-2253aa45e51e.png">
