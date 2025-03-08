---
layout: page
title: Research
subtitle: 
---
<style>body {text-align: justify}</style>
---

> I can predict the movement of heavenly bodies, but not the madness of crowds.
>
> <p style='text-align: right;'> -- <cite>Isaac Newton</cite> </p>

# <b>Working Papers</b> 

[<ins>**"Measuring Dynamic Transmission using Pass-Through Impulse Response Functions"**</ins>](https://gionikola.github.io/cv/ptirfs_nikolaishvili.pdf) 

<b>Abstract:</b>
I propose the pass-through impulse response function (PT-IRF) as a novel reduced-form empirical approach to measuring transmission channel dynamics.
In essence, a PT-IRF quantifies the propagation of a shock through the Granger causality of a specified set of endogenous variables within a dynamical system.
This approach has fewer informational requirements than alternative methods, such as structural parameter and empirical policy counterfactual exercises.
A PT-IRF only requires the specification of a reduced-form VAR and identification of a shock of interest, bypassing the need to either build a structural model or identify multiple shocks.
I demonstrate the flexibility of PT-IRFs by empirically analyzing the indirect dynamic transmission of oil price shocks to inflation and output via interest rates, as well as the indirect dynamic effect of monetary policy shocks on output via changes in credit supply.

[<ins>**"Monetary Transmission Through Community and Noncommunity Bank Lending"**</ins>](https://gionikola.github.io/cv/jmp_nikolaishvili.pdf) [Kleinsorge Research Award (University of Oregon)]

<b>Abstract:</b>
This paper examines the dynamic macroeconomic effects of monetary transmission through community and noncommunity bank lending in the United States. 
I find that while both types of banks amplify the impact of monetary policy shocks on output, community banks exhibit a more delayed and persistent amplificatory influence than their noncommunity counterparts. 
These results suggest that continued decline in community banks' market share may dampen the efficacy of monetary policy over longer horizons. 
Moreover, the adverse real effects of monetary tightening are likely to be longer-lasting for small business borrowers who depend on community banks for funding.

[<ins>**"Computing Temporary Equilibria using Exact Aggregation"**</ins>](https://gionikola.github.io/cv/evans&nikolaishvili_2025.pdf) (with [David Evans](http://econevans.com/))

<b>Abstract:</b>
Simulations of heterogeneous agents models with boundedly rational agents and multiple markets in the style of Krusell and Smith (1997, 1998) require solving for market-clearing conditions at each period to determine temporary equilibria.
Existing solution procedures can be computationally intensive, especially in settings with a high-dimensional state space and a large number of agents.
We suggest a new method for approximating temporary equilibria in heterogeneous agents models that offers a speedup of multiple orders of magnitude compared to a conventional benchmark.
We demonstrate the effectiveness of our procedure by applying it to a model with heterogeneous boundedly rational agents featuring a large idiosyncratic state space.

[<ins>**"The Evolution of Community Bank Interconnectedness"**</ins>](https://gionikola.github.io/cv/wp_cbinterconnectedness_nikolaishvili.pdf) [Best Field Paper / PhD Research Paper (University of Oregon)]

<b>Abstract:</b>
I find that the community banking sector in the United States has become more interconnected since the global financial crisis, which implies greater exposure to systemic risk and increased vulnerability in future financial crises.
I estimate a hierarchical dynamic factor model using a Bayesian approach to extract posterior distributions of national, regional, and state-level latent drivers of quarterly fluctuations in state-average community bank return-on-equity for all 50 US states.
The resulting estimates show evidence of both considerable national comovement and state-specific idiosyncrasy with no signs of significant regional comovement. 
Furthermore, the results show a decrease in the intensity of idiosyncratic dynamics of state-level community bank profitability since the crisis, along with an increase in national comovement across most states.

---
# <b>Publications</b>

[1] [<ins>**"Measuring economic activity in the presence of superstar MNEs"**</ins>](https://doi.org/10.1016/j.econlet.2023.111077) (with [Philip Economides](https://philip-economides.com/)) **Economics Letters (2023)**

---
# <b>Works in Progress</b>

**"Estimating Large Bayesian Hierarchical Dynamic Factor Models"**

**"Inference on PT-IRFs: VARs and Local Projections"**

**“Monetary Transmission via Expectations in DSGEs with Bounded Rationality”** (with [Edder Martínez Lazo](https://cas.uoregon.edu/directory/social-sciences/all/edderfer)) 

---
# <b>Other Works & Publications </b>

[4] [<ins>**"A Replication of 'The Macroeconomic Impact of Europe's Carbon Taxes' by Metcalf and Stock (2023)"**</ins>](https://ideas.repec.org/p/zbw/i4rdps/167.html) (with [Thomas Ash](https://sites.google.com/view/thomasash)) **I4R Discussion Paper Series (2024)**

[3] [<ins>**"Mass Reproducibility and Replicability: A New Hope"**</ins>](https://econpapers.repec.org/paper/zbwi4rdps/107.htm) (with [Abel Brodeur](https://sites.google.com/site/abelbrodeur/), [Derek Mikola](https://sites.google.com/view/derekmikola/), [Nikolai Cook](https://sites.google.com/site/nikolaimcook/home), and many others) **IZA Discussion Paper (2024)**

[2] [<ins>**"News Shocks under Financial Frictions: A Comment on Görtz et al. (2022)"**</ins>](https://econpapers.repec.org/paper/zbwi4rdps/51.htm) (with [Thomas Ash](https://sites.google.com/view/thomasash) and [Ethan Struby](https://sites.google.com/site/strubyecon/)) **I4R Discussion Paper Series (2023)**

[1] [<ins>**"Using deep learning to examine the correlation between transportation planning and perceived safety of the built environment"**</ins>](https://journals.sagepub.com/doi/abs/10.1177/2399808320959079) (with Justin Hollander, Alphonsus Adu-Bredu, Minyu Situ, and Shabnam Bista) **Environment and Planning B: Urban Analytics and City Science (2021)**

---
# <b>Software</b>

### <b>[DynamicFactorModeling.jl](https://github.com/gionikola/DynamicFactorModeling.jl)</b>

Julia package for simulating and estimating multi-level/hierarchical dynamic factor models (HDFMs).
