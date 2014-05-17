GATK_pipelines
==============
An example to use GATK to discover SNP and INDELs in bacterial genomes. This is for the tutorial purpose. The parameters are not optimized.

Two scripts were used in the analysis: snp.sh and vvariantSelect.sh. In each of the scripts, you need to change various things in the PART1. After the modification, run:

sh snp.sh ### discover both SNPs and INDELs

sh variantSelect.sh ### select confident SNPs


