# Module14

### Save a PNG image of the cumulative return plot that shows the actual returns vs. the strategy returns

![Actual Returns vs. Strategy Returns (Baseline)](Actual_Returns_vs_Strategy_Returns.png)

Based on the above image showing the actual returns versus the strategy returns, the strategy has produced better results than the actual MSCI-based emerging markets ETF. From mid-2018 onwards, the strategy has consistently produced better returns regardless of market environment. During the COVID crash in early 2020, the ETF and the algorithm saw a downturn but the algorithm saw a less severe downturn. In the run up following the March 2020 lows, the algorithm clearly outperformed the ETF.

Note that this serves as a baseline against which to compare the effects of tuning the trading algorithm. 

## Tune the Baseline Trading Algorithm

### Tune the training algorithm by adjusting the size of the training dataset. Use a different 'DateOffset' value (6 months)

![Actual Returns vs. Strategy Returns (6 months)](DateOffset_6_months.png)



