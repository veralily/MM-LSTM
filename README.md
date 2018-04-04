# MM-LSTM

1. code
	
	- readWords
		
		It contains functions for reading, splitting and extracting batches of sequences in the datasets. 

	- mmLSTM*

		This kind of files provide the MM-LSTM model for each dataset as the attributes of events vary in different datasets.
2. data
	
	Because the sizes of BPIC17 and ClickTracker are too large, we compressed the datasets into  *rar* format.

	- *_event.txt

		This kind of files provide datasets of event sequences, without attributes information.

	- *_withattributes.txt
	
		The files with suffix of '_withattribute' contain both events and attributes sequences. The words before ":" in each line represent the sequence labels, which are not analyzed in MM-LSTM. We drop these words in preprocessing period.
