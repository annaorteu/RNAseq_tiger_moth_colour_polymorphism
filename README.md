# RNAseq analyses of pupal wing disks of wood tiger moths

This repository contains the RNAseq analyses of pupal wing disks of wood tiger moths (*Arctia plantaginis*) with the aim of pinpointing candidate genes involved with colouration. This is part of a pre-print that can be found here: 

Colour polymorphism associated with a gene duplication in male wood tiger moths
Melanie N. Brien*, Anna Orteu*, Eugenie C. Yen, Juan A. Galarza, Jimi Kirvesoja, Hannu Pakkanen, Kazumasa Wakamatsu, Chris D. Jiggins, Johanna Mappes
bioRxiv 2022.04.29.490025; doi: https://doi.org/10.1101/2022.04.29.490025


File description: 
1. [tmoth_RNAseq_mapped2WW.R](tmoth_RNAseq_mapped2WW.R): differential expression (DE) analysis using the [limma package](http://bioconductor.org/packages/release/bioc/html/limma.html). 
2. [seq_samples_RNAseq.csv](seq_samples_RNAseq.csv): file containing information on the samples used for the study. 
3. [featureCounts_mapped2WW](featureCounts_mapped2WW): Read counts output from featureCounts and used as input for the DE analysis.
4. [mapww_significant_genes_allStages_001.csv](mapww_significant_genes_allStages_001.csv): DE genes between colour morphs with p-value < 0.01
5. [mapww_significant_genes_allStages_005.csv](mapww_significant_genes_allStages_005.csv):DE genes between colour morphs with p-value < 0.05 