# sentiment-annalysis
In this work, we aim to predict the intensity of user emotion (anger, fear, sadness and joy) contained in a sentence. This problem is more challenging than the task of classification into sentiment categories as the degree of emotion extraction needs deeper level of granularity. We have approached the solution with various techniques such as tfidf, lexicon based approaches, Word embeddings and LSTM networks. In this process, we found a few interesting observations regarding the behavior of different approaches. Word embedding approaches perform better with the inclusion of sentiment lexicon knowledge and also the results obtained from the experiments show the inefficiency of tfidf approach for regression tasks. The observation that the emotion learning is not independent, has motivated us to develop a new architecture for leveraging the power of shared learning. The shared- LSTM architecture developed in this work eliminates the problem of insufficient data to train a particular emotion category by exploring mutual and interactive learning among the emotion categories. Shared- LSTM outperforms the other approaches significantly and also can be extended to various other tasks where there is a need to explore the dependencies among different categories.