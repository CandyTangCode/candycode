---
title: "Variable Selection with ABC Bayesian Forests"
collection: publications
permalink: /publication/2019-01-31-Variable-Selection-with-ABC-Bayesian-Forests
excerpt: 'This paper develops the methodology for variable selection under non-parametric setting using ABC.'
date: 2020-01-31
venue: 'Journal of Royal Statistical Society Series B'
paperurl: 'https://arxiv.org/abs/1806.02304'
citation: 'Liu Y, Ročková V, Wang Y (2020). &quot;Variable Selection with ABC Bayesian Forests.&quot; <i> Journal of Royal Statistical Society Series B, In Press</i> .'
---
Few problems in statistics are as perplexing as variable selection in the presence of very many redundant covariates. The variable selection problem is most familiar in parametric environments such as the linear model or additive variants thereof. In this work, we abandon the linear model framework, which can be quite detrimental when the covariates impact the outcome in a non-linear way, and turn to tree-based methods for variable selection. Such variable screening is traditionally done by pruning down large trees or by ranking variables based on some importance measure. Despite heavily used in practice, these ad-hoc selection rules are not yet well understood from a theoretical point of view. In this work, we devise a Bayesian tree-based probabilistic method and show that it is consistent for variable selection when the regression surface is a smooth mix of p>n covariates. These results are the first model selection consistency results for Bayesian forest priors. Probabilistic assessment of variable importance is made feasible by a spike-and-slab wrapper around sum-of-trees priors. Sampling from posterior distributions over trees is inherently very difficult. As an alternative to MCMC, we propose ABC Bayesian Forests, a new ABC sampling method based on data-splitting that achieves higher ABC acceptance rate. We show that the method is robust and successful at finding variables with high marginal inclusion probabilities. Our ABC algorithm provides a new avenue towards approximating the median probability model in non-parametric setups where the marginal likelihood is intractable. 

[Download paper here](https://arxiv.org/abs/1806.02304)

Recommended citation: Liu Y, Ročková V, Wang Y. Variable Selection with ABC Bayesian Forests[J]. arXiv preprint arXiv:1806.02304, 2020.
