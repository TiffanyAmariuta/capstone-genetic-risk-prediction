---
layout: week
title: Week 03
permalink: /weeks/03-eQTL-discovery/
doodle: /PRS_capstone.jpg
---

## Topics

This week's assignments will guide you through the following topic:
* eQTL (expression quantitative trait loci) mapping to understand genetic regulatory effects on gene expression. 

## Reading

Please read the following:
* [Landmark paper for cis-eQTL mapping across human tissues](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7737656/)
  (Read the whole paper - it is very integral to our replication project)
* [Identification of cis-eQTLs in single cell data (new model considerations)](https://pubmed.ncbi.nlm.nih.gov/35545678/)
  (Just take a look at the methods section and compare to the models used in the GTEx paper)
* [Regarding formatting a scientific paper](https://www.sciencedirect.com/science/article/pii/S0002929720300781)
  (Just take a look at how the paper is structured, e.g. abstract, introduction, methods, results, discussion)

## Tasks

* Using the 1000Genomes genotype data and this gene expression data, match the sample IDs of the individuals between the two datasets. 
* Run an eQTL analysis for a single gene of your chosing. For this gene, select only the SNPs within +/- 500 kb of the gene body (you can use gene_annot.txt.gz as the master list of all genes genome-wide). You can select these SNPs by using plink with the --extract bed1 flag. For example: plink2 --bfile 1000G.EUR.15 --extract bed1 $my_coord --out 1000G.EUR.15.GeneX --make-bed (in this case, $my_coord is a single line 6-column tab delimited text file with the genomic coordinates of the +/- 500 kb window around your gene of interest, for example, chr15 200000 1200000 mygene 0 +
* You can use different software to run an eQTL analysis. For example, fastQTL is a user-friendly software although I haven't used it before. I prefer to use simple linear regression models in R or python and use a for loop or an apply() function. In R, you can use the lm() function as follows: lm(y_gene_expression ~ genotype_snp_j). If you use R, you can use the plink2R library and the read_plink function to read a .bed plink file of genotypes: genos = read_plink("1000G.EUR.15.bed",impute="avg")
* Bonus: to visualize the results of an eQTL analysis, we like to plot the -log10 p-value of the linear regression (y-axis) versus the genomic coordinate of the SNP (x-axis). This is known as a locusZoom plot (http://locuszoom.org/).

## Weekly Questions

Answer the following questions on Gradescope:

* What does pleiotropy mean?
* Do eQTL tend to be shared across cell types?
* How many SNPs tend to be in a 1 Mb window around a gene? 




