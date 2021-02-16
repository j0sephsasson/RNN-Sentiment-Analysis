# RNN Sentiment Analysis
Build a RNN to extract sentiment from tweets to assist in predicting market movements.

# Purpose
It is no secret that markets react to the news. What if you could track news sentiment for your portfolio? That is exactly the function of this project. Using deep learning, and stocktwits, we can train a neural network to extract sentiment. 

# Technologies Used
Python -- PyTorch, Numpy, Pandas, NLTK

# Features
This notebook has a fully functional RNN for sentiment analysis, ready for deployment. All that is needed is access to a stocktwits API, or a stocktwits webscraper.

# Usage
Example Output:

```{'symbol': '$AAPL',
 'score': tensor([[ 0.0882,  0.0927,  0.2245,  0.2279,  0.3667]]),
 'timestamp': '2018-11-01T00:00:18Z'}
 ```

The model returns a score from very negative to very positive.  
