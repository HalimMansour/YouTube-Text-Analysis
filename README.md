# Analyzing YouTube Comments with Python 

 I hope you're all doing well. Today, I want to share an exciting project I've been working on - Analyzing YouTube Comments using Python. 📈

In this project, I used various Python libraries such as TextBlob, WordCloud, and emoji to gain insights from a dataset of YouTube comments. Here's a brief overview of what I did:

### 1. Data Preparation 
I started by installing the necessary libraries, including TextBlob, WordCloud, and emoji, to perform Natural Language Processing (NLP) on the comments.

I loaded a YouTube comments dataset and conducted some initial data exploration to check for missing values, dropping any rows with missing comments.

### 2. Sentiment Analysis 
Next, I performed sentiment analysis on the comments. I calculated the polarity of each comment using TextBlob, classifying them as either:
- Positive Sentiment (polarity > 0)
- Neutral Sentiment (polarity = 0)
- Negative Sentiment (polarity < 0)

I visualized the distribution of sentiments within the dataset, providing valuable insights into the audience's reactions.

### 3. Wordcloud Analysis 
To gain a better understanding of the most prominent words used in the comments, I created word clouds for both positive and negative comments. This helped highlight the most frequently occurring words in each category.

### 4. Tags Analysis 
I also explored the tags associated with YouTube videos to identify common words. I cleaned the tags data and created a word cloud to visualize frequently used terms in video tags.

### 5. Data Visualization 
I used seaborn and matplotlib to create visualizations that showcase the relationship between views, likes, and dislikes of YouTube videos. This provides insights into user engagement and preferences.

### 6. Emoji Analysis 
Lastly, I conducted an analysis of emojis used in the comments. I identified the most commonly used emojis and visualized the top 5 emojis in a bar chart.


