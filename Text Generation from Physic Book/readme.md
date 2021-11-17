## LSTM RNN for text generation with Keras

	- here we will split the book text up into subsequences with a fixed length of 100 characters, an arbitrary length 
	- LSTM layers with 300 memory units
	- used dropout at 20
	- output layer is dense layer using softmax activation
	- we are modeling the training dataset to learn the probability of each chracter in dataset
	- there is no testing dataset
	- network is slow to train, so we would use checkpoints to record all network weights to a file each time an improvement is observed
