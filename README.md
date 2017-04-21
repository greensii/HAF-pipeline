# HAF-pipeline
a bash- and R-based pipeline to calculate haplotype-inferred allele frequencies from pool-seq data and founder SNP profiles

INPUT FILES:
-one or more fastq files, each containing reads from one sample
-founder SNP table in .csv form for each chromosome
----rows are SNPs, columns are founders, entries are alleles [A/C/G/T/N]
----file must have one header row
----the first column is position/coordinate, second column is reference allele

PARAMETERS:
inference window size
inference window shift

