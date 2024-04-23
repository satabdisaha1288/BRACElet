# BRACElet
Bayesian Regression with Agglomerated Compositional Effects using a dirichLET process

Ongoing advances in microbiome profiling have allowed unprecedented insights into the molecular activities of microbial communities. This has fueled a strong scientific interest in understanding the critical role the microbiome plays in governing human health, by identifying microbial features associated to clinical outcomes of interest. Several aspects of microbiome data limit the applicability of existing variable selection approaches. In particular, microbiome data are high-dimensional, extremely sparse, and compositional. Importantly, many of the observed features, although categorized as different taxa, may be playing related functional roles. To address these challenges, we propose a novel approach, Bayesian Regression with Agglomerated Compositional Effects using a dirichLET process (BRACElet), to identify groups of features with common effects on an outcome. By clustering the coefficients in the model, we achieve dimension reduction and identify sets of taxa that may be functionally related. We demonstrate that our proposed method outperforms existing approaches for microbiome variable selection through simulation studies and an application elucidating the impact of oral microbiome composition on insulin resistance.

# Required Functions
This directory has all the functions required for running scripts Simulation.R and RunBRACElet.R

# Other files
Simulation.R simulates data for an example case study.
RunBRACElet.R runs BRACElet for the simulated data example with compositional predictors and a continuous response.
ProcessOutputs.R processes the outputs returned by RunBRACElet.R and calculates the performance metrics.


