# MAS_NaiveVsMarkowitzStrategySharpeRatio
Based on  DeMiguel, Lorenzo and Raman (2009), in their Review of Financial Studies paper "Optimal Versus Naive Diversification: How Inefficient is the 1/N Portfolio Strategy?


DeMiguel, Lorenzo and Raman (2009), in their Review of Financial Studies paper "Optimal Versus Naive Diversification: How Inefficient is the 1/N Portfolio Strategy?" demonstrated that various asset allocation strategies (including mean-variance analysis) do no better than a naive strategy that assigns equal weights to all assets. Sharpe ratio is used to evaluate performance of strategy. Ackermann, Pohl, and Schmedders  (2016) in their Management Science paper "Optimal and Naive Diversification in Currency Markets" demonstrated that in the case of currency markets,  a mean-variance portfolio constructed using interest rates (rather than using exchange rates) significantly outperforms a naive strategy.

We aim to build on the Ackermann, Pohl, and Schmedders  (2016) paper to propose and evaluate a multi-agent currency trading system as follows:

Instead of limiting ourselves to mean-variance analysis as Ackerman et al have done, we can have multiple agents using alternate strategies (see models 1-11 in Table 2 of the DeMiguel et al paper) to come up with alternate currency portfolio selection strategies;  portfolio weights are based on interest rates rather than currency rates. Agents then cooperate to evolve optimal combinations of strategies a-la strategies 12, 13, and 14 in Table 2.

This work ties in well with the DeMiguel study and the Ackermann paper. As a first step, we should replicate the results in these papers. This should be relatively easy to do. 

A notebook uses the same data as DeMiguel paper (from Ken French's site) and replicates the results for the Naive vs mean-variance strategies. 
