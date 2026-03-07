- The comparative genomic analysis revealed several nucleotide substitutions across the analyzed SARS-CoV-2 genomes.
- The isolate from the United States showed the highest number of mutations relative to the Wuhan reference genome, whereas the Argentina isolate displayed fewer mutations, indicating a closer similarity to the reference sequence.
### Pairwise Genetic Distances
-    Pairwise genetic distances were computed using the p-distance model in MEGA.
     - Wuhan vs United States → 0.005
     - Wuhan vs Argentina → 0.001
     - Wuhan vs Nigeria → 0.000
   -The p-distance represents the proportion of nucleotide sites that differ between two sequences.
- A 0.5% difference between the United States isolate and the Wuhan reference corresponds to approximately 150 nucleotide differences in a genome of ~29,900 nucleotides.
- A 0.1% difference between the Argentina isolate and the Wuhan reference corresponds to approximately 30 nucleotide differences.
- No nucleotide differences were detected in the Nigeria sequence relative to the reference genome.

### Substitution Patterns
   - Transition mutations were more frequent than transversions, consistent with previously reported SARS-CoV-2 mutation patterns.
   - The global substitution matrix revealed a strong bias toward C→T substitutions, with a rate of 30.19, which is substantially higher than other substitution types.
   - This pattern is consistent with the well-known mutational bias of SARS-CoV-2, often associated with host-mediated RNA editing processes.
   - The Maximum Likelihood Estimate of the transition/transversion bias (R) was 2.17, indicating a clear predominance of transition mutations over transversions.
[Substitution matrix](results/Substitution_matrix.txt)

### Gene-Level Mutation Analysis
   - Mutations were mapped to genomic regions and normalized by gene length in order to compare mutation rates across genes.
   - For the United States genome, the 5' UTR showed the highest mutation rate after normalization by sequence length. The Spike (S) gene displayed a similar normalized mutation rate.
   - Although ORF1ab contained the largest absolute number of mutations (46 substitutions), it is also the longest genomic region (21,290 nucleotides), which results in a lower normalized mutation rate compared with other genes.
   - In the Argentina genome, the 5' UTR also showed the highest mutation rate when normalized by gene length. Similar to the United States genome, ORF1ab contained the largest number of mutations but exhibited a relatively low mutation rate due to its large genomic size.
[summary Table](results/summary_table.csv)

[Mutation Rates Plot](results/Rplot.png)
