---
layout: week
title: Week 04
permalink: /weeks/04-reinforcement-eQTL/
doodle: /PRS_capstone.jpg
---

## Topics

This week's assignments will help prepare you for the Quarter 1 Project Checkpoint due Oct 30th. 

## Reading

Feel free to reread the GTEx paper and take a look at the methods section (located in Supplemental Material) if you want to see the math behind the analysis.

## Tasks

* For those of you who had data acquisition issues or software download issues and could not complete last's week task of running a single eQTL analysis of one random gene on chromosome 22 and one random (nearby) variant on chromosome 22, please try to complete this analysis. This is the key component of the quarter 1 project, which will be a scaled up version of this assignment. 
* For those of you who were able to run a linear regression or compute the correlation between gene expression and genotype for a gene and variant on chromosome 22, scale up your analysis to include all genes on chromosome 22. For each gene, test for a cis-eQTL with each variant within 1Mb of the gene body, e.g. +/- 500 kb. 

## Quarter 1 Project Paper Outline 

* Part 1: Identify ciseQTLs in LCLs, where cis is defined by +/- 500 Mb of the gene body.
    * a. across all genes genome-wide (n = 20K protein coding genes) Note: might need to subset gene expression data. If so, use Ensembl to figure out which genes are protein coding. 
    * b. in each of five populations in the 1000 Genomes dataset: the CEPH (CEU), Finns (FIN), British (GBR), Toscani (TSI) and Yoruba (YRI). Note: you will need to subset the individuals in your plink files for this. 
* Part 2: Assess the population-specificity of eQTLs.
    * a. how many eQTL are found in only CEU, only FIN, only GBR, only TSI, only YRI? If you want, you could also note how many eQTLs are found in each possible pair/trio/four of these five populations and how many are found in all five populations. 

*Note, all of these analyses are different flavors of performing a single cis eQTL analysis which hopefully you all will have done by next week. 

## Weekly Questions

The purpose of this week's questions are to prepare you for the checkpoint. Please answer the following questions on Gradescope:

* What is the biological purpose of wanting to understand how genetic variation impacts gene expression?
* What would be a good title for a paper about the analysis we are trying to do in this capstone, e.g. if we are interested in identifying genetic variation that impacts gene expression across many different tissues of the body and across different populations?
* What will you include in the introduction to this paper? (think about defining what an eQTL is, how we can use eQTL to understand human disease, think about why it's cool that we have this functional genomics data across so many different tissue types in the body)
* What was the correlation of genotype and gene expression for the cis-eQTL analysis you ran? 
* What was the p-value of the correlation of genotype and gene expression for the cis-eQTL analysis you ran? 
* If you scaled up your analysis to multiple genes and multiple variants, how many SNP-gene pairs passed the significance threshold of 0.05/(how many SNP-gene pairs you tested)?


