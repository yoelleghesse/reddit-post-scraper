This script uses PRAW to connect to Reddit and retrieve new posts from a specified subreddit. It filters the posts to include only those submitted within the last 24 hours and saves the titles and self-texts of these posts to an output file (output.txt).

Install PRAW:

``pip install praw``

Create a Reddit app on the Reddit website to obtain the required credentials (client ID, client secret). 

Replace placeholders YOUR REDDIT APP ID, YOUR REDDIT APP SECRET, YOUR REDDIT USERNAME, and YOUR REDDIT ACCOUNT PASSWORD with your Reddit app ID, app secret, Reddit username, and account password, respectively.

Run the script:

``python reddit_post_scraper.py``
