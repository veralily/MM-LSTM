# MM-LSTM

1. code
	
	- readWords
		
		It contains functions for reading, splitting and extracting batches of sequences in the datasets. 

	- mmLSTM*

		This kind of files provide the MM-LSTM model for each dataset as the attributes of events vary in different datasets.
2. data

	- *_event.txt

		This kind of files provide datasets of event sequences, without attributes information.

	- *_withattributes.txt
	
		The files with suffix of '_withattribute' contain both events and attributes sequences. The words before ":" represent the sequence labels, which are not analyzed in MM-LSTM.
