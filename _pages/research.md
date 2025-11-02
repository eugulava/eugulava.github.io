---
permalink: /research/
title: "Research"
---

## Job Market Paper (Working Paper)
[**Horizon-Targeted Estimation of Volatility Models: Application to a Misspecification Testing and Forecasting (2025)**](../files/Ekaterina_Ugulava_JMP.pdf)

<details>
<summary>Abstract</summary>

Multi-period volatility forecasting is crucial for financial decision-making. We consider a scenario where the decision-maker specifies an ex-ante loss function, such as the QLIKE, to assess the accuracy of multi-period volatility forecasts from a candidate volatility model. To reduce the impact of model misspecification on forecast accuracy, we introduce an estimator that is `matched' to the specification of the forecast evaluation loss function. We examine the estimator's performance under a bias-variance trade-off, highlighting conditions where it is likely to offer improvements over standard estimation methods. We also propose a model misspecification test based on the Hausman principle, which exploits the fact that our estimator and the standard estimator are consistent for the true parameter under the null of correct specification but converge to different pseudo-true values under the alternative. In a Monte Carlo study, we examine the misspecification with respect to long-memory dynamics. Our results show that the misspecification test is reasonably sized and has power that increases with the degree of long-memory misspecification. Additionally, we recover multi-period volatility forecasts and find that under correct specification, both estimators perform equivalently; however, under misspecification, our estimator provides superior forecast accuracy. Finally, an out-of-sample analysis across ten return and realised measure series from 2001 to 2010 suggests three key findings: first, it is optimal for our estimator to match the estimation loss function to a shorter horizon than the forecasting horizon; second, our estimator provides greater accuracy gains for GARCH-type volatility models applied to realised measures of volatility compared to those applied to returns; and third, our estimator leads to greater accuracy gains for underparameterised models (which are more likely to be misspecified), highlighting the bias-variance trade-off.

</details>

## Other Working Papers
**Long Memory Realised GAS Model** (2022, draft available soon)

<details>
<summary>Summary</summary>
We introduce a univariate score-driven model that explicitly incorporates long-memory dynamics in the conditional variance of daily returns. We model the conditional variance both as a fractionally integrated process and as a heterogeneous autoregressive model. The new model accommodates heavy-tailed densities for both daily returns and realized measures. This choice of observational densities ensures automatic correction for influential observations through the score function. Our out-of-sample analysis identifies that accounting for long memory is particularly useful for volatility level evaluation and return risk assessment during non-crisis periods.
</details>

<br>
## Work in Progress
**Constructing Multi-Period Quantile Forecasts from the Dynamic Quantile Regression Model** (2025) 

<details>
<summary>Summary</summary>
We propose a method for constructing multi-period quantile forecasts for variables of interest (e.g., GDP
growth over a yearly horizon) based on a finite set of one-step-ahead conditional quantiles estimated from the
dynamic multiple quantile model of Catania and Luati (2023). We show that the resulting multi-period
quantile forecast is optimal in the sense that it minimises the expected quantile tick-loss function. This
property is confirmed through simulations. We apply our methodology to forecast GDP growth over a yearly
horizon, as motivated by Adrian et al. (2019). Our approach directly produces quantiles at any desired level
(e.g., 1%, 5%), and also provides the predictive density of GDP growth and the macroeconomic Expected
Shortfall, which is the expected GDP growth conditional on falling below a given quantile.
</details>
