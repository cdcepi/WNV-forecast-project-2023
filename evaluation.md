Evaluation
------------------

When reported data for 2023 are available, an analysis will be conducted using the average logarithmic score to assess and compare forecasts across all states at each time point. A joint manuscript will be prepared to disseminate findings on this comparison and the general performance of submitted forecasts. Participants may publish their own forecasts and results at any time.


### Logarithmic Score
Each quantile forecast will be fitted to a negative binomial distribution and the probability of the observed outcome, *x*, will be calculated from the probability mass function, *p*, of the fitted negative binonmial distribution. The corresponding logarithmic score is therefore:

> S(p, x) = ln(p(x))

Logarithmic scores below -10 will be assigned a value of -10.


*References*
- Gneiting T and AE Raftery. (2007) Strictly proper scoring rules, prediction, and estimation. Journal of the American Statistical Association. 102(477):359-378. Available at: [https://www.stat.washington.edu/raftery/Research/PDF/Gneiting2007jasa.pdf](https://www.stat.washington.edu/raftery/Research/PDF/Gneiting2007jasa.pdf).
- Rosenfeld R, J Grefenstette, and D Burke. (2012) A Proposal for Standardized Evaluation of Epidemiological Models. Available at: [http://delphi.midas.cs.cmu.edu/files/StandardizedEvaluation_Revised_12-11-09.pdf](http://delphi.midas.cs.cmu.edu/files/StandardizedEvaluation_Revised_12-11-09.pdf).

