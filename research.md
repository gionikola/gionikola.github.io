---
layout: page
title: Research
subtitle: 
---
<style>body {text-align: justify}</style>
---

# <b>Working Papers</b> 

[<ins>**"Doubly Robust Nonparametric Local Projections"**</ins>](https://gionikola.github.io/cv/dr-lp_nikolaishvili.pdf) 

<b>Abstract:</b>
Nonparametric local projections estimate impulse responses without functional form restrictions, but their consistency hinges on the accuracy of the conditional mean regression. 
I propose an estimator that supplements this regression with a bias correction derived from the marginal density of the shock. 
This estimator is doubly robust: it remains consistent when either the conditional mean or the density ratio is misspecified, and attains the semiparametric efficiency bound when the product of their errors vanishes faster than the parametric rate. 
This bound decomposes into the regression-only variance plus an explicit cost-of-robustness term. 
Monte Carlo simulations confirm the double robustness property and suggest that the efficiency cost of robustness is modest --- a small premium for insurance against misspecification of the conditional mean, which in nonparametric settings cannot be ruled out.

[<ins>**"Scanning for Significance: False Discovery Control for Impulse Responses"**</ins>](https://gionikola.github.io/cv/irf-fdr_nikolaishvili-gade.pdf) (with [Noah Gade](https://scholar.google.com/citations?user=8QfEoKIAAAAJ&hl=en)) [Under Review]

<b>Abstract:</b>
Impulse response analysis builds economic narratives by scanning a large set of coefficients for significant effects. 
Pointwise inference ignores this multiplicity, so the false rejection rate grows unbounded with the response family. 
Simultaneous inference bounds the probability of even a single false rejection, which yields increasingly uninformative results as the family expands. 
Researchers are left to choose between overstating their evidence and understating it. 
We propose false discovery and false coverage control as a more appropriate target: 
bounding the expected share of false rejections among responses declared significant, with calibrated post-selection confidence intervals. 
Neither guarantee deteriorates as the response family grows, so researchers are not penalized for investigating thoroughly. 
The procedure integrates into standard VAR and local projection bootstrap workflows. 
Applications show that this inference strategy recovers effects lost under simultaneous bands while discarding fragile pointwise findings, in some cases materially altering the economic narrative.

[<ins>**"Efficient Aggregation in Heterogeneous-Agent Models with Bounded Rationality"**</ins>](https://gionikola.github.io/cv/evans&nikolaishvili_2025.pdf) (with [David Evans](http://econevans.com/)) [Under Review]

<b>Abstract:</b>
A key challenge in heterogeneous-agent models with bounded rationality is the intensive computational burden of repeatedly aggregating policy functions when solving for temporary equilibrium within a given period. 
This cost scales with belief heterogeneity, creating a severe bottleneck. We propose a fast aggregation method that replaces
repeated summations with a compact representation of aggregate demand as a function of prices, delivering speedups of several orders of magnitude over conventional approaches while preserving accuracy. 
Demonstrated in a model with multiple dimensions of belief heterogeneity, our method directly overcomes a central obstacle to simulating boundedly rational heterogeneous-agent economies and extends the scope of feasible applications.

[<ins>**"Monetary Transmission Through Community and Noncommunity Bank Lending"**</ins>](https://gionikola.github.io/cv/jmp_nikolaishvili.pdf) [Under Review]

<b>Abstract:</b>
This paper develops a horizon-by-horizon decomposition of impulse responses to quantify how monetary policy shocks transmit to U.S. real activity through community and noncommunity bank lending. 
Endogenous responses in lending by both bank types are shown to amplify the output effects of monetary policy, but with distinct timing: noncommunity bank lending contributes more at short horizons, whereas community bank lending contributes with greater delay and persistence.
The evidence suggests that this bank-type heterogeneity reflects differences in the responsiveness of output to lending, rather than differences in how strongly lending responds to monetary policy shocks.

<ins>**"The Complexity and Source of Small Bank Systemic Risk"**</ins> (with Jimmy Ren) [Available Upon Request] 

<b>Abstract:</b>
The large segment of U.S. commercial banks with under $1 billion in assets is often regarded as a collection of institutions whose performance varies idiosyncratically, posing limited macroeconomic risk.
In contrast to this view, I document substantial comovement in the profitability of small banks. 
More strikingly, I find that this comovement cannot be explained by shared exposure to macroeconomic shocks, suggesting that its origins lie within the financial system itself.
These findings uncover an overlooked channel of systemic risk in the commercial banking sector and highlight that such risk need not originate solely from large institutions.

<ins>**"Measuring Dynamic Transmission using Pass-Through Impulse Response Functions"**</ins> [Available Upon Request]

<b>Abstract:</b>
I propose the pass-through impulse response function (PT-IRF) as a novel reduced-form empirical approach to measuring transmission channel dynamics.
In essence, a PT-IRF quantifies the propagation of a shock through the Granger causality of a specified set of endogenous variables within a dynamical system.
This approach has fewer informational requirements than alternative methods, such as structural parameter and empirical policy counterfactual exercises.
A PT-IRF only requires the specification of a reduced-form VAR and identification of a shock of interest, bypassing the need to either build a structural model or identify multiple shocks.
I demonstrate the flexibility of PT-IRFs by empirically analyzing the indirect dynamic transmission of oil price shocks to inflation and output via interest rates, as well as the indirect dynamic effect of monetary policy shocks on output via changes in credit supply.

<ins>**"The Evolution of Community Bank Interconnectedness"**</ins> [Available Upon Request]

<b>Abstract:</b>
I find that the community banking sector in the United States has become more interconnected since the global financial crisis, which implies greater exposure to systemic risk and increased vulnerability in future financial crises.
I estimate a hierarchical dynamic factor model using a Bayesian approach to extract posterior distributions of national, regional, and state-level latent drivers of quarterly fluctuations in state-average community bank return-on-equity for all 50 US states.
The resulting estimates show evidence of both considerable national comovement and state-specific idiosyncrasy with no signs of significant regional comovement. 
Furthermore, the results show a decrease in the intensity of idiosyncratic dynamics of state-level community bank profitability since the crisis, along with an increase in national comovement across most states.

---
# <b>Publications</b>

[3] [<ins>**"Reproducibility and robustness of economics and political science research"**</ins>](https://www.nature.com/articles/s41586-026-10251-x) (with [Abel Brodeur](https://sites.google.com/site/abelbrodeur/), [Derek Mikola](https://sites.google.com/view/derekmikola/), [Nikolai Cook](https://sites.google.com/site/nikolaimcook/home), and many others) **Nature (2026)**

[2] [<ins>**"Measuring economic activity in the presence of superstar MNEs"**</ins>](https://doi.org/10.1016/j.econlet.2023.111077) (with [Philip Economides](https://philip-economides.com/)) **Economics Letters (2023)**

[1] [<ins>**"Using deep learning to examine the correlation between transportation planning and perceived safety of the built environment"**</ins>](https://journals.sagepub.com/doi/abs/10.1177/2399808320959079) (with Justin Hollander, Alphonsus Adu-Bredu, Minyu Situ, and Shabnam Bista) **Environment and Planning B: Urban Analytics and City Science (2021)** [Predoctoral work]

---
# <b>Works in Progress</b>

**“Impulse Response Inference Under a Stochastic Null”** (with [Noah Gade](https://sites.google.com/view/noahdgade/home))

**"Augmented Impulse Response Matching"**

**"International Evidence on Monetary Policy Transmission: High-Frequency Analysis of Central Bank Communications"** (with [Aeimit Lakdawala](https://aeimit.weebly.com/) and [Saroj Bhattarai](https://sites.google.com/site/bhattaraisaroj/))

**“Uncertainty and the Price Puzzle”** (with [Sebastian Laumer](https://sites.google.com/view/sebastianlaumer))

---
# <b>Other Works & Publications </b>

[2] [<ins>**"A Replication of 'The Macroeconomic Impact of Europe's Carbon Taxes' by Metcalf and Stock (2023)"**</ins>](https://ideas.repec.org/p/zbw/i4rdps/167.html) (with [Thomas Ash](https://sites.google.com/view/thomasash)) **I4R Discussion Paper Series (2024)**

[1] [<ins>**"News Shocks under Financial Frictions: A Comment on Görtz et al. (2022)"**</ins>](https://econpapers.repec.org/paper/zbwi4rdps/51.htm) (with [Thomas Ash](https://sites.google.com/view/thomasash) and [Ethan Struby](https://sites.google.com/site/strubyecon/)) **I4R Discussion Paper Series (2023)**

---
# <b>Software</b>

### <b>[DynamicFactorModeling.jl](https://github.com/gionikola/DynamicFactorModeling.jl)</b>

Julia package for simulating and estimating multi-level/hierarchical dynamic factor models (HDFMs).
