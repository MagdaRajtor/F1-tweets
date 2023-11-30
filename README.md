# F1-tweets
Predicting Formula 1 race winners based on drivers tweets

The project consists of two parts: 1) gathering and cleaning data, and 2) training and comparing different classifiers on it.

**Dataset**: Twitter data from seasons 2017-2023 (still ongoing at that point) was collected using a module from snscrape library. Detailed instructions for the chosen drivers, races and date windows are given in the first part of the notebook. Tweets are cleaned from handles and links - however, emojis are retained (in the form of their description).

**Models**: Using BOW encoding or TF-IDF, a simple neural network, Naive Bayes, and logistic regression models were tested. Additionally, a Transformer model was trained (although not quite fitting for a problem of this magnitude). An evaluation report is provided, as well as a word cloud analysis for two drivers with most wins.

What I learned:
- scraping data from Twitter (with given constraints)
- preparing evaluation functions for custom data
- keras, sklearn, transformer libraries
- identifying overfitting and training problems
