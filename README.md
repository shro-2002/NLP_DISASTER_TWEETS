# NLP_DISASTER_TWEETS

Twitter has become a vital communication channel, particularly during emergencies. The widespread use of smartphones allows people to report emergencies in real-time. Consequently, many organizations, such as disaster relief agencies and news agencies, are interested in programmatically monitoring Twitter for such announcements.

However, it is not always easy for machines to determine whether a tweet is actually announcing a disaster. For example, a tweet may use words related to disasters but in a metaphorical or non-literal sense. This ambiguity poses a challenge for automated classification.

In this competition, participants are provided with a dataset of 10,000 tweets that have been manually classified as either describing a real disaster or not. The task is to develop a machine learning model that can accurately predict the classification label for new, unseen tweets.

## Dataset
The dataset for this competition consists of 10,000 labeled tweets. Each tweet is represented as a text string, and the corresponding label indicates whether it is a real disaster tweet (1) or not (0).

The dataset is divided into two subsets: a training set and a test set. The training set is provided along with the labels, while the labels for the test set are not disclosed. Participants can use the training set to train their models and evaluate their performance using appropriate metrics. The final predictions for the test set should be submitted in the specified format.

## Evaluation
The performance of the machine learning models will be evaluated using accuracy, which is the proportion of correctly predicted tweets out of the total number of tweets in the test set.

Participants can submit their predictions for the test set to the competition platform, and the platform will calculate the accuracy of the predictions against the true labels.
