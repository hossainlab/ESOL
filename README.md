# ESOL: Estimating Aqueous Solubility Directly from Molecular Structure
This paper describes a simple method for estimating the aqueous solubility (ESOL − Estimated SOLubility) of a compound directly from its structure. The model was derived from a set of 2874 measured solubilities using **linear regression** against nine molecular properties. The most significant parameter was calculated $logP_octanol$, followed by molecular weight, proportion of heavy atoms in aromatic systems, and number of rotatable bonds. The model performed consistently well across three validation sets, predicting solubilities within a factor of 5−8 of their measured values, and was competitive with the well-established “General Solubility Equation” for medicinal/agrochemical sized molecules.

## Goal
- Reproduce the Delaney's paper using Python
- To learn more about Computational Drug Discovery

## References
<a id="1">[1]</a>
Delaney, John S. (2004).
ESOL: estimating aqueous solubility directly from molecular structure.
Journal of chemical information and computer sciences.

<a id="1">[2]</a>
Chanin Nantasenamat.
How to Use Machine Learning for Drug Discovery.
https://towardsdatascience.com/how-to-use-machine-learning-for-drug-discovery-1ccb5fdf81ad

<a id="1">[3]</a>
Deep Learning for the Life Sciences: Applying Deep Learning to Genomics, Microscopy, Drug Discovery, and More 1st Edition.

<a id="1">[4]</a>
Pat Walters.
Predicting Aqueous Solubility - It's Harder Than It Looks.
http://practicalcheminformatics.blogspot.com/2018/09/predicting-aqueous-solubility-its.html



## Citation
If you want to do same kind of projects, please cite **Delaney's** paper.
```latex
@article{delaney2004esol,
  title={ESOL: estimating aqueous solubility directly from molecular structure},
  author={Delaney, John S},
  journal={Journal of chemical information and computer sciences},
  volume={44},
  number={3},
  pages={1000--1005},
  year={2004},
  publisher={ACS Publications}
}
```
