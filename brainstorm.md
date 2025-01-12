# DevOp plan

## Description
Making a machine learning model to take a text input and determine the sentiment and emotion.

Key Highlights:
1. Emotion Analysis: Over 422,000 sentences, labeled with six distinct emotions:

    Joy: 143,067 samples

    Sadness: 121,187 samples

    Anger: 59,317 samples

    Fear: 49,649 samples

    Love: 34,554 samples

    Surprise: 14,972 samples


2. Sentiment Analysis: A supplementary set of 3,309 sentences, categorized into two primary sentiments:

    Positive: 1,679 samples

    Negative: 1,630 samples

## Flow

### Training
text input -> pre-processing (TextVectorization probably) -> Train Recurrant Neural Network


### Model Flow

text input -> pre-processing -> Recurrant Neural Network model -> % likelyhood of each emotion / sentiment

## Tasks
- Investigate the dataset and data form
- Investigate data pre-processing techniques for RNN
- Work out how to split dataset into training and test data
- Create the pre-processing steps
- Create RNN architecture
- Training the RNN on the dataset
- World dominance
- Test the model
