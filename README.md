<h1 align="center">Twitter Retweet Bot using Python:</h1>


A Python built twitter retweet bot using Tweepy. Searches and retweets based on hashtag or keyword. Can do for multiple keywords, or hashtags. It can be used for **automation and marketing purposes**.

## What You Need 

-   [Tweepy](http://www.tweepy.org/)  - An easy-to-use Python library for accessing the **Twitter API**.

    `pip install tweepy`
-	Make a [Twitter Developer Account](https://developer.twitter.com/en).
-   Make sure you fully understand  [Twitter's Rules on Automation](https://support.twitter.com/articles/76915). Play nice. Don't spam!
- And you need to have [Heroku Account](https://dashboard.heroku.com/).

## Instructions

-   Create a new directory to contain all of your retweet bot files.

	`mkdir TwitterBot`

-   Create a new  [**Twitter Application**](https://apps.twitter.com/app/new). This is where you'll generate your keys, tokens, and secrets.
-   Fill in your keys, tokens, and secrets in the credentials.py file.
-   Check comments in bot.py to tweak the retweet bot to your liking.
-   The example demonstrates a single hashtag value, but you can tweak the code to search multiple hashtags. Example:

	`q= #thinkbig`

-   Run your bot.py script.

	`python bot.py`
-	If it runs without any errors it can be deployed on [**Heroku**](https://dashboard.heroku.com/).
-	Once deployment is done you're good to go you !Sit back and relax have successfully created a twitter bot.

## For deployment on Heroku 
You need to make three differnt files :
- runtime.txt (Includes Python Version `python-3.8.1`)
- requirements.txt (`pip freeze > requirements.txt`)
- Procfile (`worker: python bot.py`)

## Additional Information 

-   **Note**: Make sure that your bot.py and credentials.py files are, obviously, in the same directory.


