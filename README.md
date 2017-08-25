## Inspiration
Python program is built to build a collection of tweets library. 

The inspiration for this project was to create a simple method to pull all tweets from user "X" and write & save them as a collection into a text file.  

    1) the creation of a Twitter application, or
    2) any log on information.  I therefore aimed to pull all of user X's tweets by scraping them directly from the user's profile using Selenium.

## How to Use twitterUserScraper.py
- Simply type: python twitterUserScraper.py twitterUsername outputFileName.txt 
- The outputFileName.txt will be saved to the "twitterHistories" folder.

## Down Sides
While twitterUserScraper.py works well as a tweet scraper, it has two major downsides:

- 1) It is slow.  I am not sure how much slower it is than if Tweepy were used, but this is a common problem when scraping with Selenium.  Additionally, my code could probably be optimized further.

- 2) It only scrapes the latest ~800 tweets.  That is because Twitter will only display the user's latest ~800 tweets on their webpage.  
