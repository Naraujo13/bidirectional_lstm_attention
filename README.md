# bidirectional_lstm_attention

This implemmentation uses a Bi-Directional LSTM with attention and glove embeddings in an attempt to solve Quora Insincere Questions Kaggle challenge.
https://www.kaggle.com/c/quora-insincere-questions-classification/data

## Problem:
The attacked problem here is the classifify a Quora quesation as sincere or not.
In this competition you will be predicting whether a question asked on Quora is sincere or not.

Quora define 'insincere' as 'a question intended to make a statement rather than look for helpful answers', giving the following characteristics to describe them:
    - Has a non-neutral tone
        - Has an exaggerated tone to underscore a point about a group of people
        - Is rhetorical and meant to imply a statement about a group of people
    - Is disparaging or inflammatory
        - Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
        - Makes disparaging attacks/insults against a specific person or group of people
        - Based on an outlandish premise about a group of people
        - Disparages against a characteristic that is not fixable and not measurable 
    - Isn't grounded in reality
        - Based on false information, or contains absurd assumptions
    - Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers

## Dataset:
The dataset used was the one provided by Quora with over a million questions classified as sincere or not, containing the question that was asked, and whether it was identified as insincere (target = 1). 
The labeling of the dataset is not guaranteed to be 100% accurate, with some noise to be expected.

## Results
This model achieved the following results:

**Precision**: 0.603

**Recall**: 0.6245

**F1**: 0.6137
