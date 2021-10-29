# subredditdownloader

This subreddit downloader downloads all posts and comments in a subreddit

Using the reddit API is extremely challenging after the update as there is no way to download the entire subreddit contents

For people working on NLP projects wasting a lot of time on the data collection process is not really worth it 

This script makes use of the pushshift API ( https://github.com/pushshift/api ) to download the entire dump 

Simply replace the subreddit name in the fourth line of code and run the script

It will download two files one for all the posts and one for all the comments 

Please note pushshift has request limitations -

repeated 429 error codes will result in blocklisting of IP
