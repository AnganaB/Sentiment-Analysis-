Sentiment Analysis:

Dataset used: IMDB large movie review dataset

1. Preprocessing
	- Encoded the text
	- Split dataset into training and testing
	- Used padding for standardizing the review sizes
	- Used masking (to ignore the required pads)
2. Model Creation
	- Embedding layer (word embedding)
	- 2 LSTM layers
	- ReLU activation layer
	- Added Dropout=0.5
	- Output layer
3. Training
	- Used Binary Cross Entropy loss
	- Used Adam optimizer
	- No of epochs = 10, validation steps = 30
4. Testing
	- Calculated accuracy on testing set 
	- Calculated loss on testing set

Test set accuracy = 85.17%
Test set loss = 48.3% 
