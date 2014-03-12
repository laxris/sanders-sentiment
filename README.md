This is an update for the Twitter Sentiment Corpus installation/download script, originally compiled and published by Sanders Analytics at
> http://www.sananalytics.com/lab/twitter-sentiment/
to use the API 1.1 and respect the new rate limits.

To use the script:

1)	download the original zip file from http://www.sananalytics.com/lab/twitter-sentiment/ 
	and place the corpus.csv into the same directory as the install.py file

2)	Make sure to install twython (e.g. via "pip install twython" or "easy_install twython". 

3)	Create an app at http://dev.twitter.com and generate a set of tokens. Replace the tokens in the script, as indicated by the following lines:

	APP_KEY = "abcdefghijklmn"
	APP_SECRET= "abcdefghijklmnabcdefghijklmnabcdefghijklmn"
	OAUTH_TOKEN = "012345679-abcdefghijklmnabcdefghijklmnabcdefghijklmn"
	OAUTH_TOKEN_SECRET = "abcdefghijklmnabcdefghijklmnabcdefghijklmnabcdefghijklmn"

4)	Run the script. It will take a while.

Please refer to the original readme.pdf, distributed with the original script, and refer to its licensing information.


Licensing
---------
All of the data from Twitter (tweets, creation dates, tweet ids) is covered by Twitter’s Terms of
Service:
https://dev.twitter.com/terms/api-terms

The sentiment classifications themselves are provided free of charge and without restrictions.
They may be used for commercial products. They may be redistributed. They may be modified.
THEY COME WITH NO WARRANTY OF ANY SORT.

If you use this corpus, attribution and acknowledgements are appreciated but not required.
Buying the author a beer is, likewise, appreciated but not required.