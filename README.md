# CEO-Tweets-Analysis---Natural-Language-Processing
Analyzed the impact of CEO tweets on stock market and made recommendations to make them more influential


## Project Title:

Top Company CEO tweets Analysis- Sentiment analysis, topic modeling and driver analysis - Natual Language Processing 

## Motivation:

The marketing strategies are shifting to social media platforms. CEOs like Elon Musk, depend highly on social networking platforms like twitter. In this project, I analyzed CEO tweet's sentiment, topic they usually tweet about, and tweet's impact on the company stock market. 
For companies like Tesla, where the marketing is solely based on the social media platforms, we found out that CEO's tweets make a huge impact on the stock market. Soon other company CEOs should also adopt this platform for their marketing strategies. 
So how can these tweets impact the stock market? How can these tweets be more influential?


## Data Source:

Twitter data is scraped for ~20 CEOs for their tweets from year 2016 using Twitter API


## Analysis Steps:

- Scrape the tweets for these CEOs
- Remove stopwords, special characters and clean the tweets (lower case etc.)
- Sentiment Analysis- Check the distribution of the positive, negative and neutral tweets by the CEO
- Topic Modeling (manual and using LDA): Check what are the topics CEOs are tweeting about. Create buckets of these topics
- Linear regression (driver analysis) : Check what are the influencing factor on stock market data.   
    Note: I included company related finance data, CEO attributes and tweet attributes for this analysis to make sure the significant factors are not by chance
- Driver analysis to analyze what makes a tweet influential. For this, I calculated engagement score by taking weighted average of likes and retweets (retweets were given higher weightage). By bucking these scores in high and low buckets, I built a logistic regression model as a driver analysis model


## Findings and Recommendations:

- With sentiment analysis, Aaron Levie turned out to be CEO with the most negative tweets, but with topic modeling he is actually a very generous and positive person on Twitter. Hence, sentiments should be analyzed along with topics in any analysis
- I found out that twitter followers, sentiment scores, technology related tweets, emotional tweets and business related tweets influence the stock market 
- So, to make these tweets more influential a CEO should talk about social, technology, product related topics. Additionally, she should express her emotions to showcase the human side of her. Also, employee perception (Glassdoor CEO approval) also influences the effectiveness of the CEO's tweet
