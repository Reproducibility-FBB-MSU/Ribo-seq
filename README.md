# Ribo-seq
Reproducibility of some plots from "Clarifying the Translational Pausing Landscape in Bacteria by Ribosome Profiling" paper (Mohammad et al., 2016 Cell Reports) for the purpose of learning Python for computational biology.

Initial files (genome sequence, Genebank file, affinity table and coverage files for both chains of three stains) are in the Data folder. 
Primarty script for getting CDS coordinates based on Genebank file using Biopython functions are in the root folder as these data are futher used in both parts of investigation.
There are two main parts of the work, two folders stands for each of them. Firstly, we checked correlation of the affinity of hexamer sequense to Shaino-Dalgarno sequense and coverage of the hexamer by ribosome. So, two scripts have been used: getting the coverage of each hexamer in gene; vizualization of correlation. Secondly, we found out crosscorelation between affinity and coverage of hexomers in genes. Three scripts have been used: getting files with values of affinity for every hexamer in third position and files of coverage values for every hexamer in third position too; crosscorelation script; vizualization script.
