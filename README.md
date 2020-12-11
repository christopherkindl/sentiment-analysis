## Introduction

The aim of this analysis is to understand Apple smartwatches’ market positioning within the ‘runners’ segment compared to established brands, like Garmin, and to guide Apple in its strategy for this product. Therefore, we decide to analyze customers opinions of the brand expressed online, particularly on YouTube, due to its availability, reach of the platform within our target audience, and due to the importance of product videos in purchasing decisions.

To extract new insights from the unstructured data source, namely YouTube’s comments, we apply NLP techniques to extract the main product features of interest from these comments, and categorize the comments based on these features. We then score and label each comment as positive, neutral, or negative based on a sentiment analysis technique using VADER, a lexicon and rule-based sentiment analysis tool that is attuned to sentiments expressed in social media.

All code is shown in the [jupyter notebook](https://github.com/christopherkindl/business-strategy/blob/main/sentiment-analysis-youtube-comments.ipynb).

## Supporting documents in zip folder
- **all_comments.csv:** shows the raw comments extracted from YouTube
- **mapping.csv:** housekeeping file to identify which videos feature which brand
- **2020-12-08_apple_topic_comments.csv:** final output of data cleaning 
- **2020-12-08_garmin_topic_comments.csv:** final output of data cleaning 
- **apple_results.csv:** final output of sentiment scoring
- **garmin_results.csv:** final output of sentiment scoring
