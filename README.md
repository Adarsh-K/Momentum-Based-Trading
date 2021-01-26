# Momentum Based Trading using Hurst Exponent

In the Notebook I've implemented a Trading Strategy based on Momentum using Hurst Exponent. I've used it to trade APPL stocks. I've build the model using the Auquan Toolbox. 

Please see the file- **Momentum Based Trading.ipynb** for the complete implementation & the results.

## My Trading Strategy

I'm going long if the Hurst Exponent is > 0.5 (which shows a stronger trend) and both long (30 days) & short (10 days) term momentum are positive. Similarly I'm going short when the Hurst Exponent is > 0.5 and both long & short term momentum are negative.

When Hurst Exp is < 0.5 I'm using the Mean Reverting Strategy.

## Results

I've managed to get a 6% PnL along with the Sharp ratio of 1.42.
