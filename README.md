# WSBAI

Stock predictor trained off of public discourse scraped from the r/WallStreetBets subreddit.

This agent uses multivariate linear regression to build the model and has live scraping capabilities along with using the linked dataset.

## How To Run

https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts

The model trains off of the dataset linked above. The .csv file is also included in this repository via zip file for ease of use. 

Runtime -> Run All will not work due to asynchronous constraints from the PRAW scraping code cell.
So long as the reddit_wsb.csv file is in the same folder as the  WSBAI.ipynb file, training and evaulating should run smoothly.
