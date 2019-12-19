# IMDB Reviews - Customer Reviews Classification
The Dataset of 25,000 movie reviews from IMDB, labeled by sentiment (positive/negative). Reviews have been
preprocessed, and each review is encoded as a sequence of word indexes (integers). For convenience, the words
are indexed by their frequency in the dataset, meaning the for that has index 1 is the most frequent word. Use the
first 20 words from each review to speed up training, using a max vocab size of 10,000.
As a convention, "0" does not stand for a specific word, but instead is used to encode any unknown word.

### Overview
1. Import test and train data
2. Import the labels
3. Get the word index and then Create a key-value pair for word and word_id
4. Build a Sequential Model using Keras for the Sentiment Classification task
5. Report the Accuracy of the model
6. Retrieve the output of each layer in Keras for a given single test sample from the trained model
