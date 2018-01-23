# MyOwnNN
First neural network built in python.

Inside jupyter notebook file, you can find a neural network based on back-propagation algorithm. 
Processed data comes from:

https://www.kaggle.com/c/sentiment-analysis-on-movie-reviews

The dataset is comprised of tab-separated files with phrases from the Rotten Tomatoes dataset. The train/test split has been preserved for the purposes of benchmarking, but the sentences have been shuffled from their original order. Each Sentence has been parsed into many phrases by the Stanford parser. Each phrase has a PhraseId. Each sentence has a SentenceId. Phrases that are repeated (such as short/common words) are only included once in the data.

train.tsv contains the phrases and their associated sentiment labels. We have additionally provided a SentenceId so that you can track which phrases belong to a single sentence.

test.tsv contains just phrases. You must assign a sentiment label to each phrase.

1. Word embeddings is a popular model used in natural language processing, usually as features for deep learning of recurrent neural networks.

2. LSTM is a recurrent neural network architecture commonly used for time series analysis.

It was very difficult to valuate model performance because the lack of test labels. It was decided to evaluate network using train dataset, what is not a common and best approach, but unfortunatelly the only possible one.

Time required to train the network is pretty long and depends on total amount of epochs.
