# News-Virality-Likelihood-Prediction
# Problem Statement (option 1) :
Crawl news & information websites & anticipate the likelihood of its virality.

# Approach :
I have scrapped the news headlines from a media website. I chose this website, because it shows trending news from the past week, with telecasting of current news.It provides relative ease for scraping headlines.
I changed the regression problem of likelihood estimation into a classification problem of trending/normal news follewed by predicting probability of trending classification.
I scrapped 480 datapoints in total for training & validation - 240 trending news + 240 normal news. 
I scrapped 120 current news headlines to make predictions.
Then, after pre-processing the news headlines (methods of pre-processing are mentioned in the notebook), trained a  simple 'Logisic Regression' model with 0.75:0.25 training/validation split.
Achieved a validation f1-score and accuracy of 0.9831 and 0.9833 respectively.
Finally, using the trained model predicted the probability of a news (current news) becoming viral.
