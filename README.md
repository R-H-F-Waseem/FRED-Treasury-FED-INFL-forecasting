# FRED-Treasury-FED-INFL-forecasting
A quick, fun project pulling and playing with the FRED 10-Year Treasury Securities Market Yield, Effective Fed-Funds Rate, and 10-Year Breakeven Inflation Rate.

The point of this project was to showcase the handling of real and current economic data from the FRED. I ended up falling down a rabbit-hole of econometric concepts I had not done before, or had only briefly explored when I took the relevent classes.
The most interesting of which was Granger Causality; assessing for predicive utility from past observations (in one variable) over a different variable's current/future value. It reminded me closely of autocorrelation (AC) concepts, and having researched it further, I found out that Granger Causality is closely linked. As in, in most cases with firm autocorrelation, Granger Causality becomes a likely possibility.

There is also the forecasting of the first differences due to the ADF test rejecting the raw values; this was my first time using the Johansen test, and if I understood it correctly, it found no co-integration between the original values, so I defaulted to using VAR to run a model with the differences.

I don't expect the forecasting to be accurate due to the inherent volatility of the economy, but I wanted to test myself when it came to forecasting on more stable indices.

Thank you for reading, and I hope you learned something too.
