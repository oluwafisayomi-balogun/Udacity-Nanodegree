# WeRateDogs

## Introduction
The project focuses mainly on Data Wrangling of a twitter account ‘WeRateDogs’ and the analysis, visualization of the data gotten. WeRateDogs is a twitter account which goes by the username ‘dog_rates’ with a whopping followers of ‘9.3 million’ as at the time of this report. They basically rate dogs (**extremely cute** dogs) over 10.


The catch – ratings are usually above 10. I think that’s just the cutest thing ever. If you want to be attacked with lots of cuteness and love check the account [here](https://twitter.com/dog_rates?s=20&t=poMe1HF2-fYb5uOpx5nNkg).


## Data Used
Got my data from 3 different sources
1. A csv file 'twitter-archive-enhanced.csv' - WeRateDogs Twitter archive which contained basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
2. A tsv file which contained the image predictions. This file (image_predictions.tsv) is present in each tweet according to a neural network. Was downloaded programmatically using the Requests library and this [URL](https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv)
3. Twitter API. Where I gathered each tweet's retweet count and favorite ("like") count using the tweet IDs in the twitter-archive-enhanced.csv & storing in a file called tweet_json.txt file.


## Files
1. Wrangle act shows all my codes and visualizations
2. Act report communicates all the insights and displays the visualization(s) produced from your wrangled data
3. Wrangle report briefly describes your wrangling efforts
4. Twitter-archive-master stores the cleaned master DataFrame in a CSV file 
