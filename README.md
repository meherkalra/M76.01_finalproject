# M76.01_finalproject

## Saksham A., Meher K., Cody T. 
## Math 76.01 Network Science, Final Project

**GitHub username:**  saksham324, meherkalra, codytheobald

*Project submitted for course Math 76.01 at Dartmouth College, Spring 2023.*

This repository includes the code, in the form of python scripts and jupyter notebooks, for the analysis conducted for the final project titled, *''The Impact of User Interaction on College
Subreddits on Mental Health''*. 

The code is organized into subdirectories described below: 
* `data`: contains all the raw data files scraped from the Berkeley, Cornell, Harvard, UIUC college subreddits. 
* `processed_data` : contains processed data files used for conducting the regression analysis and training for comment sentiment classification 
* `reddit_scraping.ipynb` : Python script used for scraping data from Reddit using PRAW
* `create_network.ipynb` : Python script used to create networks using scraped Reddit data 
* `network_centrality.ipynb` : Python script to compute centrality measures for created networks for regression analysis. 
* `sentiment_calculation.ipynb `: Python script to conduct sentiment analysis on scraped data. 
* `comment_sentiment_classification.ipynb`: Python script used to train and test machine learning models for multi-class classification of comment sentiment. 
* `regressions`: subdirectory containing python scripts corresponding to the regression analysis conducted. The subdirectory is further organized into subfolders `h1`, `h2` and `h3` corresponding to the regressions conducted for each of the three hypotheses tested respectively. 
* `Final Project Manuscript` : More information about the motivation, data source, methodology, results and discussion is included in the manuscript.
