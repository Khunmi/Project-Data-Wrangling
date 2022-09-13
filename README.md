
# Project- DATA WRANGLING
## by Bukunmi Adebanjo


## Dataset

Data used for this project was sourced from three different files types namely:
1. twitter-archive-enhanced.csv - Contains tweets from WeRateDogs twitter handle and the respective
properties of each tweet such as ratings, dog name, time stamp of tweets, dog stages and source. This file
was sourced by manual download.
2. image-predictions.tsv - This file is a neural network prediction of images found in tweets made by the
WeRateDogs twitter handle. This file was sourced using programtic download method by using the
requests.get() method.
3. tweet-json.txt - This is a TXT file with JSON contents extracted from Twitter(via API) and provided by
Udacity. Contains tweet properties just like the first file on the list but having more details. This files helped
me generate the favorite counts and retweet counts. Two needed columns from this file were extractd using
the .readlines() , pd.DataFrame() and .append() methods.

