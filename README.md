# PROJECT 1

## INTRODUCTIONS
In this project, I chose to analyze tweets using the Sentiment140 dataset. My goal is to understand patterns in how the wording and or the way text is framed a certain way text can express sentiment on whether it can have positive or negative emotions.

My Research Questions
- Pattern Focused: What are the most common words and phrases in positive tweets versus negative tweets?
- Length of Message Focused: Does the length of a tweet correlate with its sentiment? Such as are shorter tweets more often positive or negative?
- Day of Time Trends Focused: Are there specific times or days when positive or negative tweets are more common? 

## THE DATASET
The data I chose to use is a file found from Kaggle called https://www.kaggle.com/datasets/kazanova/sentiment140. I chose this dataset because it has many columns, which gives me more ways of analyzing the data to answer my questions, as it contains 1.6 million tweets labeled for sentiment (positive or negative), along with other information such as timestamps.

## PREPROCESSING
Some steps I took for preprocessing my data were to:
- Remove Irrelevant Columns - Doing this step allowed me to use data that was relevant to answer my questions and focus on columns that will contribute to my analysis and visualizations.
- Cleaning Up Data of Text Data - This step allows the tweets to be cleaned and more readable, so I can focus on the text that will help answer my questions. Which included URLs, mentions, hashtags, special characters, etc.
- Renaming Columns - This allows the dataset to have better readability to understand not just the code but the dataset itself.
- Changing Text to Lowercase - This allowed the text not to differentiate the same word when doing frequency counts, along with it making it more readable.
- Adding Columns - This allowed me to describe and find something specific that will help me any my questions and so I can be able to work with that specific data.

## VISUALIZATION/DATA UNDERSTANDING
To explore the data, I plan to use
- Bar Charts: Ideal to show frequent words for positive and negative tweets.
- Box Plots: Allow to show tweet length for each sentiment, as well as the range and any outliers.
- Line Graph: to be used to plot the number of positive and negative tweets over time, such as by hour of the day, to show patterns of tweet amounts for that specific time.

## STORY
When I was exploring this dataset, my thoughts were on how the length of a tweet can have a positive or negative sentiment, or whether it was the specific wording of the tweet that gave it that specific sentiment. The bar chart showed the distribution level of specific words that are frequent based on sentiment, which were labeled as either positive, negative, and it showed how tweets were based on it at the start with generic words, but as I analyzed to find unique words it showed a level frequency but not really a story behind the tone of so the prominent words on the bar chart are just words that can be associated with sentiment. The box plot compared tweet lengths across sentiment types. There were noticeable outliers on the longer end of the spectrum for positive sentiment. These outliers can suggest that when there is expression, it can skew positively. The line graph tracked sentiment trends over time of the day. It revealed spikes at the end of the day and during the day was a its lowest, meaning this could suggest that users have time to express during certain points of the day.

## IMPACT
- Overall, I think analyzing the tweets of this sentiment could provide a level of observations based on the visualizations themselves. The lack of perspective could probably skew the sentiment the and the charts can not tell the whole story of a message. Along with that, there is bias in sentiment as it associates certain words with positive or negative emotions, but based on the tone of the message, it can miss parts. Such as one of the top ten unique positive words I got was "thanks," but that word can also be used in other tones, such as sarcasm, so it lacks textual context, but that word makes the tweet itself skew positively despite a lack of context.


## REFERENCES
- This project was used using Jupyter Notebooks and was coded in Python with libraries such as Pandas, Matplotlib, and Seaborn.
- The dataset used was [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140) and The overall structure of this project should be
  *  `PROJECT1.ipynb`: My main code that has the data preprocessing, analysis, and visualization information.
 `training.1600000.processed.noemoticon.csv`: The raw dataset file.

## TO VIEW VISUALIZATIONS 
- Click on the file `PROJECT1.ipynb` and Preview and scroll to see visualizations.

## TO RUN THIS PROJECT
- Download Zip Locally
- Download the raw dataset file from [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
- Open Zip
- Move the raw dataset file you got from the [Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
to the Project1-main folder
- Open Visual Studio Code
- Download the extensions Python, Jupyter if you don't have it already installed
- Open the file using Visual Studio Code
- Run the Code to View the Visualizations



