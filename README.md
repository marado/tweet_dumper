# tweet dumper
A tool to retrieve all possible tweets from an user. 

# How to use it
Download the zip file from this repository to your computer and unzip it. 

Open the file `tweet_dumper.py` and insert the following information:

```
# EDIT THIS!
# Twitter API credentials - https://apps.twitter.com/
consumer_key = ""
consumer_secret = ""
access_key = ""
access_secret = ""`
```

You will need to create an app, with your Twitter credentials, at https://apps.twitter.com to get this information.

Open a console in your computer, go to the directory of the file `tweet_dumper.py`, and write `python tweet_dumper.py twitter_handle"`. A CSV with all possible tweets should be created in the same directory of your unzipped folder.

# Dependencies 
* tweepy - If you don't have in installed in your system, you can do it (as root) by doing `easy_install tweepy`
