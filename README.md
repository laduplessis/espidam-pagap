# Espidam - Pathogen Evolution Genomic Epidemiology and Phylodynamics

This repository contains the datasets and tutorials for the Espidam 2026 course on Pathogen Evolution and Genomic Epidemiology and Phylodynamics, focussed on phylogenetic and phylodynamic analyses in BEAST2. 

The datasets are stored in [datasets](datasets/). 

## Tutorials

- [Introduction to phylogenetics in R](phylogenetics/): Simple R-tutorial for building different types of trees in R and plotting them. Uses a dataset from a criminal cases about HIV-1 transmission.
- [Introduction to substitution and molecular clock models](clockdating/): This is an introductory BEAST2 tutorial that shows how to set up a basic analysis on a small Ebola virus dataset, and analyse the output files. The focus is on using different types of substitution and clock models. 
- [Introduction to phylodynamic models](phylodynamics/): This is a BEAST2 tutorial that shows how to use the coalescent and birth-death skyline models on a SARS-CoV-2 dataset. 

## Additional tutorials
These are a few [Taming the BEAST](https://taming-the-beast.org) tutorials that can be useful to do. 

- [Troubleshooting initialisation](https://taming-the-beast.org/tutorials/Troubleshooting-initialization-issues/): Steps through common mistakes that can keep your analysis from starting.
- [MASCOT tutorail](https://taming-the-beast.org/tutorials/Mascot-Tutorial/): Basic tutorial for setting up an analysis in MASCOT.
- [BDMM Prime tutorial](https://taming-the-beast.org/tutorials/Structured-birth-death-BDMM-Prime/): Basic tutorial for setting up a multitype birth-death model using the BDMM prime package. 
- [Visualizing BEAST2 results in R](https://taming-the-beast.org/tutorials/Visualizing-BEAST2-results/): How to import BEAST2 output files and produce pretty figures in R.
- [Skyline Plots](https://taming-the-beast.org/tutorials/Skyline-plots/): Very similar to the phylodynamics tutorial above, but using the Hepatitus C dataset from the course, which is not heterochronous. This tutorial still uses the BDSKY package for the birth-death skyline instead of BDMM Prime. 
- [Molecular clock dating and modelling rate variation](https://taming-the-beast.org/tutorials/Molecular-clock-dating-and-modelling-rate-variation/): This tutorial is about birds, not viruses, but shows how to model different types of rate variation in BEAST2.

If you're interested in BEASTX, there are many tutorials on [beast.community](beast.community)