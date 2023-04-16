#Python FC
This is just a toy example. 

FetchQuotes.ipynb is the code I use to talk to the API and get historical data. There are 3 levels of historical data : 
- Free : 1 update every 1min. Seems not very robust + NO volume data.
- 40£/month : every second AND volume data.
- 80£/month : tick-data (50ms) AND volume data. 
I stuck w free plan + only got data for GB and France. Still have to go through data cleaning etc.

Data is all available in data (parquet files + original json files under "raw")

IsFavoriteTheWinner : simple code to see what's the frequency of the time where the favorite is the winner. Multiple ways to look at this, just did something easy for now.