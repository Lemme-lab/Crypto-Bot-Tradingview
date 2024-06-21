# Tradingview with integrated AI Crypto Bot

<img width="1728" alt="Screenshot 2024-06-21 at 16 05 46" src="https://github.com/Lemme-lab/Crypto-Bot-Tradingview/assets/71924682/ed1af2e4-a72b-4bd1-bd40-5d8779605429">
<img width="1728" alt="Screenshot 2024-06-21 at 16 05 13" src="https://github.com/Lemme-lab/Crypto-Bot-Tradingview/assets/71924682/9933c72a-f647-4dcb-99ab-ed77a84e57a8">
<img width="1728" alt="Screenshot 2024-06-21 at 16 22 41" src="https://github.com/Lemme-lab/Crypto-Bot-Tradingview/assets/71924682/1be50c85-9d93-4ba9-8dd0-6e8202798094">
<img width="1728" alt="Screenshot 2024-06-21 at 16 21 52" src="https://github.com/Lemme-lab/Crypto-Bot-Tradingview/assets/71924682/de9ac58d-caed-42bf-aa7b-c48ad6679d29">


![Screenshot_92](https://user-images.githubusercontent.com/71924682/149665886-4e786ce6-e325-40be-bb6e-8be2ea8d651a.png)

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
![Screenshot_57](https://user-images.githubusercontent.com/71924682/149637684-4defe038-79b2-4061-8185-fc6eeeba456e.png)



## Output Data
![Screenshot_55](https://user-images.githubusercontent.com/71924682/149637612-1b4e7f75-7044-4670-8d4e-2f08e4a64756.png)

## Output on the Tradingview (Orange prediction)
<img width="1727" alt="Screenshot 2024-06-21 at 16 05 33" src="https://github.com/Lemme-lab/Crypto-Bot-Tradingview/assets/71924682/4de15889-db30-4408-b105-d887131f3c1f">

## Notes:
The script, once startet will run every 30min and give a prediction for the next half an hour. It will also save the data for the data for further enhancements on the algo.
Visit my Website to see more informations about this project. 
https://lemme.one/Crypto_Index.html
