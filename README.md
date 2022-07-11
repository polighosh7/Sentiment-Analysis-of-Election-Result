# Sentiment-Analysis-of-Election-Result

Users obtain texts in unstructured form from various sources such as financial and business reports, news articles, books, blog posts, messages or posts from social networking
and other social media sites in ever increasing amounts. Therefore, there is a need to extract the information from these texts. 

In this paper, we calculate sentiment analysis of the election data collected from twitter before as well as after the election using R infrastructure. 
The results of the sentiment analysis will help us understand people's opinion before and after the election.

Greater the positive value of sentiment analysis, greater the positive attitude of the people. Similarly a negative value of the sentiment analysis shows a negative 
attitude and a zero value shows neutral attitude of the people. 

Firstly, the tweets of the people before and after the election are collected. These tweets are then converted into two text files, one containing the tweets before the election and the other after the
election. Each of these text files are then imported into R. These files are then cleaned with the help of text mining package in R. Sentiment analysis is then calculated by
comparing the positive and negative terms. 

Lastly, each text document is represented by wordcloud. Wordcloud is the graphical representation of the text which gives the user a quick visualization of the important terms used in the text.
Wordcloud is implemented by using the wordcloud package available in R.
