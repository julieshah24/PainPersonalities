# PainPersonalities

This study uses a combination of two text datasets to train and test three types of classifiers for the Myers-Briggs personality traits.
The first train/test dataset is accessible on kaggle here: https://www.kaggle.com/datasets/datasnaek/mbti-type
The second train/test dataset was scraped from Reddit by our team using the PushShift API. The code to do so is included.

Once we trained the classifiers, our goal was to predict MBTI types of users from another collected Reddit dataset.
This dataset contains text written by people experiencing some form of chronic pain. Ultimately, we were interested to look at whether
we could detect personality trait trends in this final dataset. We did not achieve a high enough accuracy in any of our models
to draw any strong conclusions about personality trends in this final dataset.
