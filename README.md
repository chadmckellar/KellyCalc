# KellyCalc

A web-based tool for calculating the Kelly Criterion, helping traders optimize their position sizing for maximum growth while managing risk.

## What is the Kelly Criterion?

The Kelly Criterion, developed by John L. Kelly Jr. in 1956, is a formula used to determine the optimal size of a series of bets or investments to maximize long-term growth. It balances the trade-off between risk and reward, ensuring you don't overexpose yourself to potential losses while still capitalizing on favorable opportunities.

The criterion is widely used in financial markets, sports betting, and gambling, and it is praised for its mathematical rigor and effectiveness in maximizing portfolio growth under ideal conditions.

## The Math Behind the Kelly Criterion

The Kelly Criterion formula for a single trade or bet is:

`
f^* = \frac{bp - q}{b}
`

Where:  
- \(f^*\): The fraction of your capital to wager/invest.  
- \(b\): The odds received on the wager (e.g., \(b = 1\) for even money).  
- \(p\): The probability of a win.  
- \(q\): The probability of a loss (\(q = 1 - p\)).

For financial markets, where returns are often continuous rather than discrete, the generalized Kelly Criterion formula is:

`
f^* = \frac{\mu - r}{\sigma^2}
`

Where:  
- \(\mu\): The expected return of the investment.  
- \(r\): The risk-free rate (can be assumed 0 in many cases).  
- \(\sigma^2\): The variance of returns.

These formulas help calculate the optimal fraction of capital to allocate to maximize growth over the long run.

## Key Considerations

While the Kelly Criterion is mathematically sound, it assumes perfect knowledge of probabilities and outcomes, which is often unrealistic. Overestimating probabilities or underestimating risk can lead to overexposure. Traders may use a fractional Kelly approach (e.g., half-Kelly) to reduce risk and volatility.

## Credits

The Kelly Criterion was first introduced in John L. Kelly Jr.'s groundbreaking paper, *"A New Interpretation of Information Rate"* (1956). Kelly was a physicist and researcher at Bell Labs, and his work laid the foundation for modern portfolio theory and betting strategies.

## Features

- Calculate the Kelly Criterion for discrete trades or continuous investments.
- Intuitive, user-friendly interface.
- Instant results with clear breakdowns.

## How to Use

1. Enter the trade parameters, including odds, win probability, and/or expected return.  
2. The tool calculates the optimal position size for maximizing growth.  
3. Use the results to inform your trading or betting strategy.

## Disclaimer

This tool is for informational and educational purposes only. It does not constitute financial advice. Always perform your own due diligence and consult with a financial advisor before making investment decisions.
