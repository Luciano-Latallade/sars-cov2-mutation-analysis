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
   - Pairwise genetic distance calculation (p-distance model)

5. Statistical analysis in R
   - Import aligned sequences
   - Transition/transversion rate calculation (%Ts & %Tv)
   - Mutation count per genome
   - Assignment of mutations to genomic regions based on Wuhan-Hu-1 gene coordinates

6. Data visualization
   - Graphical representation using ggplot2

## Tools

- NCBI Virus
- Clustal Omega
- MEGA 12
- R
- ggplot2

## Results

- A comparative genomic analysis identified several nucleotide substitutions
across the analyzed SARS-CoV-2 genomes.
- The United States isolate showed the highest number of mutations relative
to the Wuhan reference genome.

Detailed results are available in the [Results report](RESULTS.md).


## Data/        -> raw genomes and alignment files
### Original genome references in FASTA format 

- [USA genome](data/raw/USA.txt)
- [Wuhan reference genome](data/raw/Wuhan.txt)
- [Nigeria genome](data/raw/Nigeria.txt)
- [Argentina genome](data/raw/Buenos_Aires.txt)

### Multiple sequence alignment generated with clustal omega 

- [Alignment file](data/alignment/alignment.aln-fasta)
## Scripts/     -> R scripts for analysis
All R scripts used for the analysis are available in [Scripts Directory](/Scripts)

