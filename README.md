# WSBAI

Stock predictor trained off of public discourse scraped from the r/WallStreetBets subreddit.

This agent uses multivariate linear regression to build the model and has live scraping capabilities along with using the linked dataset.

## How To Run

https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts

The model trains off of the dataset linked above.
The .csv file in data.zip should be in the same folder as the .ipynb file.

Other than this, the .ipynb file is mostly self-contained within its
folder, meaning there should be no outside dependencies outside of
Google Colab. The .ipynb file will also create additional .csv files to reduce
code block dependencies.

Runtime -> Run All will not work due to asynchronous constraints from the PRAW scraping code cell.
So long as the reddit_wsb.csv file is in the same folder as the  WSBAI.ipynb file, training and evaulating should run smoothly.
