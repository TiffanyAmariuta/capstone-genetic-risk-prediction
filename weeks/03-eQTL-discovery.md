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

## Tasks

* [Download gene expression data using in Lappalainen 2013 Nature to your remote server using wget](https://www.ebi.ac.uk/arrayexpress/experiments/E-GEUV-3/files/analysis_results/)
Select GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.gz
* Using the 1000Genomes genotype data and this gene expression data, match the sample IDs of the individuals between the two datasets. 
* Run an eQTL analysis for a single SNP-gene pair of your chosing. Using R, python, or something similar perform a linear regression of gene expression on genotype across individuals. Note, R has convenient functions to read plink genotype files. 

## Weekly Questions

Answer the following questions on Gradescope:

* What is an example of pleiotropy?
* Do eQTL tend to be shared across cell types? 
* What is the average heritability of gene expression? 



