# Code accompanying The Evolutionary history of 2,658 cancers

This repository contains software and analysis code used for the publication The Evolutionary history of 2,658 cancers, bioRxiv.

The repository is organised into multiple git submodules pointing to individual repositories and the version of code used for the analysis.
It is recommended to check out the most recent version of each software tool for future analyses.

## Contents
At current the repository contains the following modules.

* `MutationTimeR`
An R package to time copy number gains and point mutations.

* `EBI`
An archive of Rmarkdown analysis workflows. This archive also contains an html report
with the code to generate Figures 1b,e-h, 2, 4, 5 & Extended Data Figures 34, 37, 39 and 40. Also contains code related to Extended Data Figure 33. 

* `PhylogicNDT`
A Python package to, among others, perform evolutionary league model analysis related to Figure 3 & Extended Data Figure 33 and 35.

* `Crick` 
A collection of R scripts for timing and signature analysis, related to Figure 1c,d, 4c,d & Extended Data Figure 33 and 38.

## Dependencies
Please refer to the original repositories (links provided above) for the exact requirements and run times.

## Loading this repository
Please check out this repository using
```
git clone --recurse-submodules https://github.com/PCAWG-11/Evolution.git
```
which automatically retrieves all submodules.

