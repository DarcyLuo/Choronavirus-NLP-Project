# Choronavirus-NLP-Project
This project aims to analyze text samples from Douban Goose Group using NLP and Word Cloud technology.

This preject aims to analyze how the public attitude changed during the past 2 weeks after Wuhan being locked down. As a Wuhan local who has been retained as home for more than one month (and will be retained for longer), I can only obtain most updated information about other people's lives from the internet. However, we should notice that most of the internet users are young people age from 15 to 45 years old and analyzing their posts can investigate into how young people are living and what problems they took attention to during this special period of time.

Douban Goose Club was chosen because it is a very influential forum with over 600,000 active members. Most of the members are born from 1980s to 2000s and they are open-minded to information worldwide. The topics of their posts could reflect their comments and attitudes towards one single event (such as the death of Doctor Li Wenliang and the Misbehave of Wuhan Red Cross Organization). Most of the posts are closely related to the most trending events with vivid expression of their attitudes. Furthermore, unlike Weibo and other social network, there is no official accounts on Douban. In this case, all the posts gathered from Douban represent different personal thoughts not official information without any emotion. So, we can analyze the emotion scores based on these posts.

The project will be divided into three parts:

1. Web Crawler: grab all the information (post dates, author ID and topics) from Douban Goose Group official website.
2. Data Preprocessing: use Jieba and Word Cloud library to cut words, visualize the word frequencies and propare for emotion dictionaries for later analysis.
3. Sentiment Analysis: use emotion dictionaries modified based on the data preprocessing results, calculate the emotion scores and discover how public attitutes changed as time passed by.
