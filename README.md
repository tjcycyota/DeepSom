# DeepSom
An exploration of wine review data.

## Overview
Let's admit it: wine is confusing. There are so many varietals, so many regions, and so many words floating around to describe it. As of June 2018, Wine Enthusiast Magazine (winemag.com) has over 240,000 wine reviews. 

In an effort to better understand the swirling vortex of words being used to describe the drink of the gods, and perhaps to further improve my own vocabulary, I've put together this repo that uses several approaches and algorithms to analyze samples of these reviews. 

The files in this repo are structured as follows:

| Purpose | Files of Relevance | Notes |
| ------- | ------------------ | ----- |
| Data Acquisition & Manipulation | scrape-winemag.py, 00_WineReviews_JSONtoCSV.ipynb | Output file stored as winemag-data* files |
| Exploratory Data Analysis | 01_DeepSom_XplrtryDataAnalysis.ipynb | |
| Clustering with t-SNE | 02_DeepSom_Clustering.ipynb | |
| WordCloud, tf-idf, t-SNE | 03_DeepSom_Visualization.ipynb | |

## Outputs
### Plot of common words used in wine reviews
![tSNE varietals](https://github.com/tjcycyota/DeepSom/blob/master/visuals/tSNE_varietals.png)

### Bokeh plot of reviews, dots colored by varietal
![bokeh clustering plot](https://github.com/tjcycyota/DeepSom/blob/master/visuals/Bokeh_plot.png)

### Word Cloud of most common words used in reviews of Cabernet Sauvignon
![word cloud for cabernet sauvignon](https://github.com/tjcycyota/DeepSom/blob/master/visuals/wordcloud.png)

