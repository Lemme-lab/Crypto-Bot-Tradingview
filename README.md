# AI Crypto Bot

## Crypto Bot Idea

The idea was to programm a bot which gets 
real life Crypto data and predicts the next half and hour or day. 
It's trained with data from the last year and predicts the next 
half an hour with the last one.

## Input-Data
![Screenshot_54](https://user-images.githubusercontent.com/71924682/149637613-4ee43c99-5019-4d66-b098-21d79172f8bf.png)
We shape the input data and drop the useless parts. 
We also change little things to make the data trainabel 
such as drop "NAN" and change the index.

## Shaping Data/Training:
We shape the data int X and Y arrays. The X-Data array takes
20 Inpur-data/time per Output Data. 
![Screenshot_56](https://user-images.githubusercontent.com/71924682/149637652-62413a7f-2572-4fea-a823-6fd915c1813f.png)

Then we compile and train a LSTM Neural network with a 
batch size of 10 and for the the best results with a 
epoch of over 1000 iterations


## Output Data
![Screenshot_55](https://user-images.githubusercontent.com/71924682/149637612-1b4e7f75-7044-4670-8d4e-2f08e4a64756.png)

## Notes:
The script, once startet will run every 30min and give a prediction for the next half an hour. It will also save the data for the data for further enhancements on the algo.
Visit my Website to see more informations about this project. 
https://lemme.one/Crypto_Index.html
