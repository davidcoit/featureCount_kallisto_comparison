# featureCount_kallisto_comparison
This repository contains an R markdown file created to analyze the differences between tophat-featureCounts and kalliso based RNA-Seq analysis.

RNA analysis based on pseudoalignment to a transcriptome with tools such as kallisto can be completed much faster than alignment to genomes with tools such as tophat. This notebook takes the outputs from a kallisto-based pseudoalignment and a combined tophat alignment and featureCounts analysis (both performed on NYULH's Big Purple HPC facility) and investigates the correlation between them. 
