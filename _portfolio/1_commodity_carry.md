---
title: "Commodity Smart Beta Strategy"
excerpt: "Basic implementation of a potentially market neutral commodity investment strategy done as homework for an interview<br/><img src='/images/pfc_hat.png' height='240' width='336'>"
collection: portfolio
---

For a job interview, I was given about 5 hours to answer three fairly open-ended finance-related data analysis questions, one of which was to implement a smart beta strategy. I chose to demo a forward-curve commodity strategy, which successfully outperformed an equally-weighted basket of the same commodities, and so could be turned into something dollar-neutral. Subsequent testing on Quantopian with significantly more rigorous assumptions yields a naive dollar-neutral portfolio with a Sharpe of 0.26. I've been meaning to circle back and come up with some better risk estimation so I can implement a properly optimized portfolio, after which it might be a viable strategy.

In short, I estimate the price forward curve using chained commodity indexes, then overweight commodities on the basis of how far they are in backwardation. The full analysis is available in an <a href='https://github.com/CharlesNaylor/yewno/doc/Q2.rmd'>RStudio notebook</a> in the project's doc directory. The compiled version is [here](https://rawgit.com/CharlesNaylor/yewno/master/doc/Q2.html). It took some time to clean up the data I sourced from Quandl, so the actual estimation of the curve and backtesting happen a bit more than halfway down the page. CSVs of relevant data are in the data directory.

The big lesson from this was that it's really hard to get good futures curve data for free.

## <a href='https://rawgit.com/CharlesNaylor/yewno/master/doc/Q2.html'>More</a>
