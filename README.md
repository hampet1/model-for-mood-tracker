<h1 align="center">model for mood tracker app<h1>
  
## Description
  
Neural network model based on LSTM (long-short term memory) technology takes care of your rating based on your daily mood description. Your message is evaluated either as negative (0) or positive (1). The model itself is a basic mathematical model that evaluate probability of each sentence whether it's positive or not, the input is our description that is translated into numbers using one hot encoding technique. The model was trained originally on annotated tweet messages originally collected and annotated by Saravia et al. in the paper: Contextualized Affect Representations for Emotion Recognition viz: [paper](https://aclanthology.org/D18-1404.pdf). The authors constructed a set of hashtags to collect a separate dataset of English tweets from the Twitter API belonging to eight basic emotions: anger, anticipation, disgust, fear, joy, sadness, surprise, and trust. For simplicity's sake of this app, all emotions were grouped only into two groups (positive, negative)

* natural language processing
* LSTM (long-short term memory) is a model using deep network for training


## Check out the app and the repo

* the repo is available [here](https://github.com/hampet1/moodtracker)
* check out the app [here](https://trackmood.herokuapp.com/)
