Worked on this for about 4 hours.

Done:
Data read in and split into train/test.
Data exploration to see some of the variances and extremes.
Pre-processing to remove stop words and less valuable characters.
Apply stemming and lemmatisation to create 3 separate versions of the training data to compare the extracted features.
TF-IDF was applied to each dataset to vectorise
Fitted an SVM to the base dataset and saved it. But not eval
Build and configured hyper-parameters for a small neural net using pytorch.

TODO:
I could not get to evaluating the SVM or training the neural net.

I was trying to create the train/val splits and train the neural net.
At the same time I was try to pre-process the test set for SVM eval but didn't get far enough.

After that I would have run the lemmatised and stemmed datasets to see if performance was any different.
I suspect lemmatisation would have been better because I used part of speech tagging for informed shortenings.

This was fun!