# subreddit downloader

This subreddit downloader downloads all posts and comments in a subreddit

For a ***tutorial to use this program*** please follow this medium article - https://medium.com/@guneet.android/download-subreddit-data-for-nlp-projects-c8fa85c0df87

This script makes use of the pushshift API ( https://github.com/pushshift/api ) to download the entire dump of posts and comments in a specific subreddit

Simply replace the subreddit name in the fourth line of code and run the script

It will download two files one for all the posts and one for all the comments 

***Patched UTF-8 encoding****

***Please note pushshift has rate limitations -***

repeated 429 error codes will result in blocklisting of IP



***If your data format is in single quotes***

Please use this JSON fixer by @mbrzusto

https://gist.github.com/mbrzusto/23fe728966247f25f3ec
