# sars-cov2-mutation-analysis
Comparative genomic analysis of SARS-CoV-2 complete genomes from different countries. This project includes multiple sequence alignment, mutation detection, transition/transversion analysis, and gene-length normalized mutation rates using R.

## Objectives

- Identify genomic mutations across SARS-CoV-2 isolates from 4 different geographic regions
- Multiple sequencing alignment
- Calculate mutation frequencies
- Estimate transition/transversion ratios
- Compute gene-level normalized mutation rates
- Visualize results using ggplot2

## Workflow

1. Genome download from NCBI Virus (complete SARS-CoV-2 genomes)

2. Multiple Sequence Alignment (MSA)
   - Alignment performed using Clustal Omega
   - Reference genome included for mutation comparison

3. Manual mutation inspection
   - Visual comparison of aligned sequences against the reference genome
   - Identification of nucleotide substitutions (A→G, C→T), insertions and deletions
   - Recording of mutation positions and affected genomic regions

4. Mutation validation and analysis in MEGA
   - Confirmation of mutation sites
   - Evaluation of substitution patterns
   - Estimation of transition/transversion patterns
   - Compute of pairwise distances

5. Statistical analysis in R
   - Transition/transversion rate calculation (%Ts & %Tv)
   - Mutation count per genome
   - Gene-level mutation rate normalized by gene length

6. Data visualization
   - Graphical representation using ggplot2

## Tools

- NCBI Virus
- Clustal Omega
- MEGA 12
- R
- ggplot2
