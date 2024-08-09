# Text to Emoji Predictor

## Overview

The Text to Emoji Predictor is a machine learning project that converts a given text input into an appropriate emoji based on the sentiment and context of the text. 
It uses LSTMs and GLove word embeddings to predict 99 different emojis. This model is designed to understand the nuances in written language and predict the most suitable emoji to convey the intended emotion or sentiment.

## Pre-requisites

1. Download the 'emojitweets-01-04-2018.txt' file from [Data](https://www.kaggle.com/datasets/rexhaif/emojifydata-en?select=emojitweets-01-04-2018.txt) and store it in 'Data' folder.
2. Download Glove word embeddings using
   ```
   !wget http://nlp.stanford.edu/data/glove.840B.300d.zip
   !unzip glove.840B.300d.zip
   ```
## Some predictions made by the model

![image](https://github.com/user-attachments/assets/1081ce47-8cc0-4a76-9af4-c23e9edecb5f)

## Performance
Due to hardware constraints, the model was trained on 750,000 data points for 15 epochs. Despite these limitations, the model shows promising results in predicting relevant emojis.
However, you can achieve better accuracy by training on more data points and increasing the number of epochs.

Run all the notebooks to create the model and play around😉
