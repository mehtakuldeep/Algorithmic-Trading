Dataset Link : https://drive.google.com/file/d/1pmWHrNwBPky6brIDBAuElNXAaLt3cp0A/view?pli=1

Backtested a Trading Strategy :
      1.	Sell an ATM straddle at 10:30 am by simultaneously selling both an ATM call option and an ATM put option with the same WEEKLY expiry date and strike price.
      2.	Buy 2% away wings for protection by buying both an out-of-the-money call option and an out-of-the-money put option with strike prices 2% higher and lower than the ATM strike, respectively.
      3.  Monitor the position for the rest of the day and exit if either of the following conditions is met:
          o	The 30% stop loss is hit.
          o	The target of 80% is achieved.
      4.  If neither condition is met, hold the position until the expiry time of 3:20 pm and exit all legs of the trade together.

The Results are : 


![Trade_log - Excel 13-04-2024 15_08_54](https://github.com/mehtakuldeep/Algorithmic-Trading/assets/112538022/ac5fb041-7fef-4cab-b2fd-3f8ab5788b8e)


Net Profit Per Month per Lot = Grand_Total of Total_pnl * Lot_Size(25)
The Total Profit for Jan 2019 was : 430*25 = 10,750 Per Lot

