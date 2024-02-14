# Add-one-smoothing-Laplace-law-

MLE(Maximum likelihood estimator) is usually unsuitable for NLP because of the sparseness of the data.

We must allow for the possibility of seeing events not seen in training. 

We decrease the probability of previously seen events to leave a little bit of probability for previously unseen events.

In Add-one smoothing we Pretend we have seen every n-gram at least once 

**Formula used:**
 p(w1,w2..wn) = c(w1,w2..wn)+1 / c(w1,w2...wn-1)+V

# p(w1,w2..wn) -> probability of the given n-gram
# c(w1,w2..wn) -> no of time the n-gram appeared in the given data
# V -> no of unique words in given data (Vocabulary)
