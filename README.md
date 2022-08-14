# Toxic comments classification challenge

### Problem statement

Discussing things you care about can be difficult. Many people stop expressing their minds online due to the fear of abuse and harassment, and give up on seeking different opinions. Platforms struggle to facilitate conversations effectively, which forces many communities to restrict or disable user comments. In this context, the majority of platforms and parties have developed methods to identify and categorise different types of talks according to their level of toxicity. The study of harmful online behaviours, such as toxic remarks, is one area of emphasis (i.e. comments that are rude, disrespectful or otherwise likely to make someone leave a discussion). Different models have so far been developed to manage the degree of toxicity in talks. The existing models, however, continue to have flaws and don't let consumers choose the forms of toxicity in which they're most interested in finding(e.g. some platforms may be fine with profanity, but not with other types of toxic content).

### Objectives
This challenge aims to  build a multi-headed model that is capable of detecting different types of toxicity like threats, obscenity, insults, and identity-based hate better than previous models. The model’s  goal is to predict a probability of each type of toxicity for each comment.

### Data
The data used includes a large number of Wikipedia comments which have been labelled by human raters for toxic behaviour. The target toxicity level is divided into toxic, severe toxic, obscene, threat, insult, and identity hate for various comments in the data. The task is to model the data so that we can categorise each comment and assign a probability to each level of toxicity for the particular comment. The data is divided into training and test data. While the test data predicts the toxicity probability for these comments, the training data comprises comments with their binary labels. Some remarks in the test set are not scored in order to deter hand labelling and are assigned a value -1 to differentiate them.


