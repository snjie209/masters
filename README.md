# Neural Differential Equations for Circadian Rhythm Gene Regulatory Networks
Samba Njie JHU ACM Masters Thesis 2024-2025 NCDE in Gene Regulatory Networks

## Information

**Author:** Samba Reyes Njie (snjie1@jhu.edu)
**Thesis Period:** Fall 2024 - Spring 2025 Semesters
**Thesis Advisor:** Thomas Woolf, Ph.D.

This research project is for the [Johns Hopkins Applied and Computational Mathematics Master's program](https://ep.jhu.edu/programs/applied-and-computational-mathematics/) as a final research project exemplifying learnings from the program. 

## Problem Statement
Ordinary differential equations have existed for centuries as a mathematical field describing the dynamics of physical systems. There have been many years of theory to solve it analytically and numerically (such as Runge-Kutta methods). Neural ODEs are another class of numerical analysis methods that leverage the universal approximation power of neural networks to estimate highly complex systems, which can be used to estimate very complex differential equations, even ordinary and controlled differential equations, which are the focus of this thesis.

In this research project, we hope to apply neural differential equations in the field of bioinformatics. Specifically, we want to study the dynamics of gene regulatory networks and external factors that influence circadian rhythms (such as temperature, entrainment cycles, etc.). The coupling of such factors influencing circadian rhythms can probably be described as a complex ordinary (or partial) differential euquations, but here we attempt to solve them using neural networks in the neural controlled differential equations (NCDE) framework.

## Navigating the repo
The repo is currently in its nascent stages (as of `2024-10-19`) but is organized as follows:

1. The `proposal/` subdirectory has the proposal submitted on August 2024 which summarizes the research problem, potential methods, and a brief review of the literature. Would encourage readers to start there to gain some context.
2. Then, explore the `notebooks/` main subdirectory. This has all the code used to explore the gene regulatory networks data and experiment various model configurations. At the time of this writing (`2024-10-19`), `KaiC_Diffrax.ipynb` uses the `diffrax` package to implement the NCDE framework. A prior library, namely `torchcde`, was also tried in the notebook `KaiC_torchcde.ipynb` but the package is no longer actively maintained, hence moving to the more recent `diffrax` package and newer notebook.
3. The `data/` main subdirectory has data that is used by the `notebooks/` subdirectory. Only go here if you'd like to explore the data a bit further.
4. 

