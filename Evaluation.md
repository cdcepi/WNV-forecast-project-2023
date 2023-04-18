## Evaluation
When reported data for 2023 are available, an analysis will be conducted using proper scores, specifically the weighted interval score and the logarithmic score, to assess and compare forecasts across all states at each time point. A joint manuscript will be prepared to disseminate findings on this comparison and the general performance of submitted forecasts. Participants may publish their own forecasts and results at any time.

### Weighted Interval Score
The weighted interval score is a quantile-based approximation of the continuous ranked probability score, a generalization of absolute error that accounts for probabilistic distribution in addition to the most likely outcome. The weighted interval score can be directly calculated based on the quantiles provided in each forecast and the final reported number of cases.

### Logarithmic Score
The logarithmic score assesses the logarithm of the probability assigned to the eventual outcome. It was used for previous WNV forecasting projects, but cannot be calculated directly from quantiles. Quantile forecasts will be therefore fitted with a parametric negative binomial distribution and logarithmic scores will be calculated from the probability mass function of that distribution. Logarithmic scores below -10 will be assigned a value of -10.


*References*
- Gneiting T and AE Raftery. (2007) Strictly proper scoring rules, prediction, and estimation. Journal of the American Statistical Association. 102(477):359-378. Available at: [https://www.stat.washington.edu/raftery/Research/PDF/Gneiting2007jasa.pdf](https://www.stat.washington.edu/raftery/Research/PDF/Gneiting2007jasa.pdf).
- Bracher J, EL Ray, T Gneiting, and NG Reich. (2021) Evaluating epidemic forecasts in an interval format. PLOC Computational Biology. Available at: [https://doi.org/10.1371/journal.pcbi.1008618](https://doi.org/10.1371/journal.pcbi.1008618)
- Rosenfeld R, J Grefenstette, and D Burke. (2012) A Proposal for Standardized Evaluation of Epidemiological Models. Available at: [http://delphi.midas.cs.cmu.edu/files/StandardizedEvaluation_Revised_12-11-09.pdf](http://delphi.midas.cs.cmu.edu/files/StandardizedEvaluation_Revised_12-11-09.pdf).
