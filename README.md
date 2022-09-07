
# Project: Data Analysis of  <i>WeRateDogs</i> Twitter Account

![project_image](project_image.jpeg)

**Name of Datasets:** <br/>
- Twitter Archive Enhanced
- Image Predictions
- Tweet Json
**Description of Datasets:** <br/>
- Twitter Archive Enhanced: This data set contains the basic tweet data for all 5000+ of their (WeRateDogs) tweets as of the time it was extracted, but not everything. However, from the first column, records for the rest columns were extracted to make it enhanced.
- Image Predictions: This data set contains a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images). Gotten via a neutral network.
- Tweet Json: This data set contains addtional information related to enhanced twitter data set such as; tweet ID, retweet count, and favorite count which will aid the overall data analysis process.

> *social media/project image credit: https://50nerdsofgrey.com/* 

# Data Wrangling Overview

The three data sets were gathered via download using Python's *requests* module and Twitter API (application programming interface) using *Tweepy*. After gathering, each data sets now dataframes were assessed visually and programmatically (with focus primarily on the columns of interest relative to the questions of the analysis) to identify tidiness and quality issues. Finally, employing the *define-code-test* technique, each identified issue from the assessment was cleaned to improve the quality of the dataframe and stored for easy reference.

# Summary of Key Insights

The following insights were discovered upon completion of the exploratory analysis: <br/>
- The dog named Bo, had the highest rating and number of counts for with known dog stage and breed.
- Alhough the Pomeranian, have the highest confidence level by AI picture prediction to be the top most rated dog breed, the Standard_Poodle, by verifiable data prove to be the top rated breed.
- Majority of the dogs in the dataframe were not classified. However, Doggo, is the most prevalent stage for the top rated dogs.
- A no-brainer, there exists a significant correlation that suggests dogs with high ratings have a greater chance of being retweeted or marked as favourites.

> *More details of the insights from this analysis can be found in the project files*





























