---
layout: page
title: Research
subtitle: 
---

---
# <b>Working Papers</b> 

**"Commercial Bank Heterogeneity and the Transmission of Monetary Policy".**

<div style="text-align: right">
<b>Abstract:</b>
The literature on the aggregate bank lending channel (BLC) shows evidence of the transmission of monetary policy into the real economy through changes in the supply of bank loans.
However, insights on the distributional properties of the BLC are scarce and inconclusive. 
I study how different dimensions of bank heterogeneity influence their individual roles in the BLC, with a special focus on the distinction between community and non-community banks in the United States.
I find that the bank-level responses of lending growth to monetary policy shocks are quite diffuse across both community and non-community banks, but also that the spread of community bank responses to monetary policy shocks is greater than that of non-community banks. 
My results also suggest that output growth is affected quite differently by shocks to community bank lending than those to non-community bank lending.
Lastly, I find that community banks play a key role in influencing the real output growth of certain sectors of the U.S. economy. 
</div>

**"The Evolution of Community Bank Interconnectedness".**

<b>Abstract:</b>
I estimate national and regional latent drivers of quarterly fluctuations of state-average community bank return-on-equity (ROE) for all 50 US states. 
I do so by modeling a dataset of state-average community bank ROE series as a multi-level / hierarchical dynamic factor model (HDFM), which I then estimate using Bayesian methods to extract posterior distributions of country- and region-level dynamic factors. 
I find a decrease in the intensity of idiosyncratic dynamics of state-level community bank profitability since the global financial crisis, along with an increase in national comovement across most states. 
I conclude that the US community banking sector has become more interconnected since the crisis, which implies greater exposure to systemic risk and increased vulnerability during future financial crises.

**"Measuring Economic Activity in the Presence of Superstar MNEs"** with Philip Economides.

<b>Abstract:</b> 
In 2015, changes to Irish tax legislation, known as the "2015 Finance Act", coincided with a 25 percent annual increase in real gross domestic product. 
We provide evidence confirming the convictions of existing literature that the presence of large multinational enterprises (MNEs) is likely to have "distorted" Irish GDP, a measure previously considered to be a reliable proxy of domestic economic activity. 
Furthermore, we provide an alternative method of statistically isolating the variation in GDP growth attributable solely to domestic activity growth to infer the prevailing state of the Irish economy.
Our findings imply a 21% lower level of GDP relative to the official measure recorded for 2020. 
We suggest that our methodology may be applied by policymakers in small open economies to improve the accuracy of growth and business cycle monitoring.


---
# <b>Works in Progress</b>

**"Pass-Through Impulse Response Function (PT-IRF)".**

<b>Abstract:</b>
The impulse response function (IRF) of a vector autoregression (VAR) represents the partial effect of a shock on a given endogenous variable over time. 
However, what if we are interested in the dynamic effect of a shock on a given variable *through another* endogenous variable in the system? 
For example, suppose we are interested in estimating the effect of monetary policy on output growth *through* bank lending in a simple VAR.
Determining such a partial effect would require decomposing an IRF according to contributions attributable to all given endogenous variables in the system, and then isolating the contributions of the variable of interest.
Currently, there exists no methodology that allows for such a decomposition.
I construct an object called a pass-through IRF (PT-IRF), which decomposes IRFs with the aim of identifying the passage of structural shocks through specific media in the system.
I demonstrate the applicability of the PT-IRF by estimating and performing inference on the effect of a monetary policy shock on output growth through bank lending in a VAR, effectively estimating and testing the existence of the credit channel of monetary transmission.

**"Efficiently Estimating Many-Level High-Dimensional Hierarchical Dynamic Factor Models".**

<b>Abstract:</b>
As the availability of high-dimensional panel data improves, it is crucial for the computational usability of Bayesian dimension-reduction methods to keep up in order to allow researchers to take full advantage of growing resources.
I combine existing Bayesian multi-level/hierarchical dynamic factor model (HDFM) estimators into a single procedure with the purpose of estimating HDFMs with rich hierarchical structures in a computationally and econometrically optimal manner.
HDFMs allow for flexible modeling of both cross-sectional and dynamic dependence in large panel datasets, and Bayesian estimators offer particularly useful means of inference on the underlying latent factors.

**"Arms Races and International Business Cycles".**

<b>Abstract:</b>
Arms races are characterized by international co-movements in military resource accumulation, which may be linked with economic growth.
I measure and study the relationship between international military resource accumulation and business cycles.
I present a novel method of analyzing trends and cycles in military arms races, as well as a flexible framework for identifying the relationship between arms races and international business cycles.

**“Model Uncertainty and Agent Survival”** with David Evans.

---
# <b>Publications</b>

["Using deep learning to examine the correlation between transportation planning and perceived safety of the built environment"](https://journals.sagepub.com/doi/abs/10.1177/2399808320959079) with Justin Hollander, Alphonsus Adu-Bredu, Minyu Situ, and Shabnam Bista, Environment and Planning B: Urban Analytics and City Science, 2020.

---
# <b>Software</b>

### <b>DynamicFactorModeling.jl</b>

[DynamicFactorModeling.jl](https://github.com/gionikola/DynamicFactorModeling.jl) is a Julia package I'm currently creating that allows users to simulate, estimate, and forecast using multi-level dynamic factor models.
My focus at the moment is on Bayesian estimators, as they allow for inference on the latent factors, although I plan on including classical estimators in the future.

---
# <b>Other</b>

### <b>Library of Statistical Techniques (LOST)</b>

[LOST](https://lost-stats.github.io/) is an open source website with the goal of making it easy to execute statistical techniques in statistical software.
I am an author of multiple pages, and have written the Julia sections of others across time series methods. 
