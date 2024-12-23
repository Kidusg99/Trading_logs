- The objective of this logging tool is to gather data to of all the trades 
- Based on self defined criterias each trade will be graded based on if they followed the trading plan 
 
    - What is the trading plan?
        - 3 trades max a day 
        - market has to be trending in one direction
        - enter after consildation has been broken
        - wait for retest
        - 3 to 1 risk to reward ratio
        - volume has to be good
        - trade only new york session and asian session
        - trade must close after an hour max or hitting TP
        - After hitting TP1 75% of the position is closed and move stop loss to break even. When it hits half way up to TP2 move stop loss to TP1 and let it run until it hits TP2 or
        - No news days
    
    -what pairs will be traded?
        - GBPUSD, USDJPY, GBPJPY, XAUUSD

- It will analyse the trades and sort through it to define which entry models do the best and what does the worst
    and calculate the win rate and profitability 

    - What are the entry models?
        -

- The google sheets will contain the statistics of all trading account and consolidate it into one workbook labeling each sheet based on the account

- It will showcase what times and intervals I make the most money
- it will indicate whether I overleveraged or stayed with in a defined risk tolerance
    + Sees how much margin is being used based on each symbol/pair (marginused)
    + Calculate the pip value to enusre only 1% of account is risked per trade

-What are the criterias?
    - 
    - 
    -
    -
    -


- With the data gathered I will then create a "Trading buddy" which will scan the market and notfiy me if a high probability/profitable trading model appears
    - I will begin to let it paper trade to see if the trading model still holds true and notfiy me if it falls under 65% win rate 
    - It will identify the trading condition whether the day was within a certain price range
        -whether the market had high volume 
        - whether the market was trending in a downward direction for the week 
        - or if the entry was to early or late 
- once its been tested I will then allow it to trade based on that  

- Add a feature that reviews the charts for pairs and identify key areas of support and resistance/ what price the pair experiences the most volitilty in one direction

GAMEPLAN
[] phase 1
+ Connect the tradelocker to googlesheets

[] phase 2
+ once information can be pulled from tradelocker and translated to googlesheets ensure it can track trades taken

[] phase 3
+ Once the data is tracked create code to organize the data and fil  ter through it 

[] phase 4
+ Creating trading models

[] phase 5
+ Test trading models

[] phase 6
+ automate the process 