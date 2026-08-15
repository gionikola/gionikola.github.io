---
layout: page
title: Research
subtitle: 
---
<style>body {text-align: justify}</style>
---

# <b>Working Papers</b> 

[<ins>**"Doubly Robust Nonparametric Local Projections"**</ins>](https://gionikola.github.io/cv/dr-lp_nikolaishvili.pdf) [Under Review]

<b>Abstract:</b>
Nonparametric local projections estimate impulse responses without imposing parametric assumptions on the response function.
Existing plug-in implementations identify the response through a nonparametric regression of future outcomes on the structural shock.
This paper shows that the same response function can also be identified by reweighting outcomes according to how a structural shock shifts the shock density.
Combining the two representations yields a doubly robust estimator: a nonparametric regression estimate augmented with a residual correction based on shock density reweighting.
Consistency requires only that either the outcome regression or the density ratio be consistently estimated, making the method less vulnerable to smoothing, approximation, and specification errors.
The correction also improves the calibration of confidence intervals, both by reducing centering bias and by producing a score whose variation the standard error fully reflects.
In simulations, the residual correction removes persistent regression bias and substantially improves empirical coverage.

[<ins>**"Scanning for Significance: False Discovery Control for Impulse Responses"**</ins>](https://gionikola.github.io/cv/irf-fdr_nikolaishvili-gade.pdf) (with [Noah Gade](https://www.ndgade.com/)) [Under Review]

<b>Abstract:</b>
Applied impulse response analysis often follows a workflow: researchers identify a shock, estimate a large set of responses, select statistically significant estimates, and use their features (e.g. sign, magnitude, and timing) to construct an economic narrative.
Two inferential approaches dominate current practice.
Pointwise inference treats each response in isolation, so false rejections accumulate among many pointwise intervals.
Simultaneous inference bounds the probability of even one false rejection, so its bands widen as the response family expands.
Researchers therefore face a stark tradeoff between reliability and power.
We propose false discovery rate (FDR) and false coverage rate (FCR) control as an alternative approach that balances this tradeoff by matching inference to the selection and interpretation steps of the workflow.
FDR control governs which responses are declared significant, and FCR control ensures the confidence intervals used to interpret them remain valid post-selection.
As a byproduct, calibrating coverage to the selected set can deliver greater power than simultaneous inference.
The procedure integrates into standard vector autoregression and local projection bootstraps.
Applications show the strategy recovers effects lost under simultaneous bands while discarding fragile pointwise findings, at times materially altering the economic narrative.

[<ins>**"Efficient Aggregation in Heterogeneous-Agent Models with Bounded Rationality"**</ins>](https://gionikola.github.io/cv/evans&nikolaishvili_2025.pdf) (with [David Evans](http://econevans.com/)) [Under Review]

<b>Abstract:</b>
A key challenge in heterogeneous-agent models with bounded rationality is the intensive computational burden of repeatedly aggregating policy functions when solving for temporary equilibrium within a given period. 
This cost scales with belief heterogeneity, creating a severe bottleneck. We propose a fast aggregation method that replaces
repeated summations with a compact representation of aggregate demand as a function of prices, delivering speedups of several orders of magnitude over conventional approaches while preserving accuracy. 
Demonstrated in a model with multiple dimensions of belief heterogeneity, our method directly overcomes a central obstacle to simulating boundedly rational heterogeneous-agent economies and extends the scope of feasible applications.

[<ins>**"Monetary Transmission Through Community and Noncommunity Bank Lending"**</ins>](https://gionikola.github.io/cv/jmp_nikolaishvili.pdf) [**R&R @ Journal of Empirical Finance**]

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

---
# <b>Publications</b>

[3] [<ins>**"Reproducibility and robustness of economics and political science research"**</ins>](https://www.nature.com/articles/s41586-026-10251-x) (with [Abel Brodeur](https://sites.google.com/site/abelbrodeur/), [Derek Mikola](https://sites.google.com/view/derekmikola/), [Nikolai Cook](https://sites.google.com/site/nikolaimcook/home), and many others) **Nature (2026)**

[2] [<ins>**"Measuring economic activity in the presence of superstar MNEs"**</ins>](https://doi.org/10.1016/j.econlet.2023.111077) (with [Philip Economides](https://philip-economides.com/)) **Economics Letters (2023)**

[1] [<ins>**"Using deep learning to examine the correlation between transportation planning and perceived safety of the built environment"**</ins>](https://journals.sagepub.com/doi/abs/10.1177/2399808320959079) (with Justin Hollander, Alphonsus Adu-Bredu, Minyu Situ, and Shabnam Bista) **Environment and Planning B: Urban Analytics and City Science (2021)** [Predoctoral work]

---
# <b>Works in Progress</b>

**"Impulse Response Inference Under a Stochastic Null"** (with [Noah Gade](https://www.ndgade.com/))

**"Regime-Knockout Impulse Responses: Decomposing State-Dependent Propagation"** (with [Kenneth Rich](https://www.kennethmrich.com/) and [Noah Gade](https://www.ndgade.com/))

**"Distributional Nonparametric Local Projections”**

**"The Effects of Monetary Policy on Regional Inequality"** (with [Aeimit Lakdawala](https://aeimit.weebly.com/) and [Mike Owyang](https://www.stlouisfed.org/research/economists/owyang))

**“Uncertainty and the Price Puzzle”** (with [Sebastian Laumer](https://sites.google.com/view/sebastianlaumer))

---
# <b>Other Works & Publications </b>

[2] [<ins>**"A Replication of 'The Macroeconomic Impact of Europe's Carbon Taxes' by Metcalf and Stock (2023)"**</ins>](https://ideas.repec.org/p/zbw/i4rdps/167.html) (with [Thomas Ash](https://sites.google.com/view/thomasash)) **I4R Discussion Paper Series (2024)**

[1] [<ins>**"News Shocks under Financial Frictions: A Comment on Görtz et al. (2022)"**</ins>](https://econpapers.repec.org/paper/zbwi4rdps/51.htm) (with [Thomas Ash](https://sites.google.com/view/thomasash) and [Ethan Struby](https://sites.google.com/site/strubyecon/)) **I4R Discussion Paper Series (2023)**

---
# <b>Software</b>

### <b>[DynamicFactorModeling.jl](https://github.com/gionikola/DynamicFactorModeling.jl)</b>

Julia package for simulating and estimating multi-level/hierarchical dynamic factor models (HDFMs).
