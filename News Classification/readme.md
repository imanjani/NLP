# News Classifier Using Bidirectional LSTM RNN

---
_**Fake or Real!!!**_

Dataset: https://www.kaggle.com/c/fake-news/data#

![Fake](https://user-images.githubusercontent.com/68546391/97145655-91912180-178c-11eb-925d-1347dca903ff.jpg)

**What does it mean by Fake News??**<br/>
Many people have been using the term fake news for the last few years, but do they actually know what it looks like? The term has been used so amorphously that it begs a more direct examination. Sensationalist fake news is often used to generate clicks onto a webpage to improve ad revenue. It has also been used to influence public thought.

_The concepts used to predict whether the news is fake or not:_

**### LONG SHORT- TERM MEMORY (LSTM)**<br/>
LSTM is a recurrent neural network (RNN) architecture that REMEMBERS values over arbitrary intervals. LSTM is well-suited to classify, process and predict time series given time lags of unknown duration. Relative insensitivity to gap length gives an advantage to LSTM over alternative RNNs, hidden Markov models and other sequence learning methods.

![LSTM1](https://user-images.githubusercontent.com/68546391/97147145-0b2a0f00-178f-11eb-9562-05553182afb9.png)

Math Behind it : https://colah.github.io/posts/2015-08-Understanding-LSTMs/

**### Bi-directional LSTM**<br/>
![Bidirect](https://user-images.githubusercontent.com/68546391/97147474-94414600-178f-11eb-9952-78bc76c8e2e7.png)

Bidirectional LSTMs are an extension of traditional LSTMs that can improve model performance on sequence classification problems.
In problems where all timesteps of the input sequence are available, Bidirectional LSTMs train two instead of one LSTMs on the input sequence. The first on the input sequence as-is and the second on a reversed copy of the input sequence. This can provide additional context to the network and result in faster and even fuller learning on the problem.


