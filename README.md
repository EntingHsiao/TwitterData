# TwitterData

The dataset that I wrangled and analyzed is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog, and it has over 4 million followers.
Using Python and its libraries (pandas, numpy, matplotlib, etc), I gathered data from a variety of sources and in a variety of formats, assessed its quality and tidiness, then cleaned it. I also analyzed and visualized the cleaned data using Python.


The tasks in this project are as follows:

## Gathering data
* The twitter_archive_enhanced.csv is given by Udacity.
* The image_predictions.tsv is hosted on Udacity's servers and downloaded programmatically using the Requests library
* The twitter_archive_enhanced.csv contains tweet IDs for each tweet. With those IDs, I queried the Twitter API for each tweet's favorite count and retweet count using Python's Tweepy library and stored the entire set of tweet JSON data in a file called tweet_json.txt file. Each tweet was written to its own line.

## Assessing data
Assess the data programmatically for quality and tidiness issues in wrangle_act.ipynb

## Cleaning data
Clean each of the issues I detected above. Perform this cleaning in wrangle_act.ipynb as well. The result is a clean master pandas DataFrame and it is stored in a CSV file named twitter_archive_master.csv.

## Analyzing and visualizing data
Use numpy and matplotlib to analyze and visualize the wrangled data in the wrangle_act.ipynb. The analysis and insights into final data can also be read in the act_report.pdf, which also displays the visualizations produced from the wrangled data.

[Link to the PDF report](https://github.com/EntingHsiao/TwitterData/blob/master/act_report.pdf)

