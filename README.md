# AI Crypto Bot

## Crypto Bot Idea

The idea was to programm a bot which gets 
real life Crypto data and predicts the next half and hour or day. 
It's trained with data from the last year and predicts the next 
half an hour with the last one.

## Input-Data

We shape the input data and drop the useless parts. 
We also change little things to make the data trainabel 
such as drop "NA" and change the index.

## Shaping Data/Training:

We shape the data int X and Y arrays. The X-Data array takes
20 Inpur-data/time per Output Data. Then we compile and
train a LSTM Neural network width a batch size of 10 and for
the the best results with a epoch over 1000 iterations

## Output Data

## Notes:
The script, once startet will run every 30min and give a prediction for the next half an hour. It will also save the data for the data for further enhancements on the algo. 
