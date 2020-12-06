# Project Nvidia - Real or Not? NLP with Disaster Tweets

## Data Mining and Machine Learning - University of Lausanne

### :pencil: Project description

In this project we are challenged to build a Machine Learning model that can predict which tweets are about real disasters and which are not. The
project topic is based around a Kaggle competition. We have a training set with 6471 tweets and the information of it is a real disaster or a fake news. The goal is to train this model to have the best accuracy we can on the test set that is located on [AICROWD](https://www.aicrowd.com/challenges/final-project-of-the-data-mining-and-machine-learning-course). Each teams can make up to 5 submission a day and then see it's accuracy and it's ranking. We can see the results of our fellow and makes the challenge even more competitive!


### :books: Data
You can find the training data and the unlabelled test data under the Resources tab.
Submissions
As you build your model and train it on the training data, you can generate predictions for the
(unlabelled) test data. Make sure that your submission file has the same format as the example
submission file on the Resources tab. Once you are sure about your model and satisfied with the
prediction accuracy you got (on your own test data), you can try to generate predictions for the
actual test data and submit in the compet


### :calendar: Weekly project progress

- Week 1 
  - Created the GitHub repository
  - Created the colab project linked to the GitHub repository
  - Cleaned a first time the dataframe
  - Visualization of the dataframe with some EDA functions
  - Trained the dataframe
  - Submited our 1st prediction on AICrowd

- Week 2: 
  - Calculated the base rate
  - Further cleaning and merging of keywords with the text
  - Calculated optimal Logistic regression parameters without the merged keywords
  - Calculated optimal Logistic regression parameters with the merged keywords
  - Updated the readme file
  
- Week 3:
  - Calculated optimal TFID - vector -> Overfitting
  - Merged optimal Log regression and tfidf parameters -> Overfitting
  - Pipeline function with standardization
  - Completed the readme file
  - Arranged and cleaned our code on colab

- Last Week:
  - Regex function - removed hyperlinks, removed special characters
  - Final Version of the readme file
  - Final Version of the code

### :bulb: Results

- 1st Week:  0.81
- 2nd Week:  0.823
- 3rd Week:  0.8169
- Last Week: 0.8185

:chart_with_upwards_trend: Best results was obtained during Week 2, with the accuracy of 0.823 :white_check_mark:

