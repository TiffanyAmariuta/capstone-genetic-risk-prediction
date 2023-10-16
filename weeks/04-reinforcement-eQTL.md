---
layout: week
title: Week 04
permalink: /weeks/04-reinforcement-eQTL/
doodle: /PRS_capstone.jpg
---

## Topics

This week's assignments will help prepare you for the Quarter 1 Project Checkpoint due on XX. 

## Reading

Feel free to reread the GTEx paper and take a look at the methods section (located in Supplemental Material) if you want to see the math behind the analysis.

## Tasks

* Following the tutorial for building a polygenic risk score (PRS) via the most widely used pruning and thresholding approach (https://choishingwan.github.io/PRS-Tutorial/plink/). Here, Height.QC.gz is analogous to your week 3 eQTL analysis results. You will make one PRS for each gene you analyzed. You will be ultimately predicting gene expression (for the gene or genes in your analysis) in all the individuals in 1000 Genomes. 

## Quarter 1 Project Paper Outline 

* Part 1: Identify ciseQTLs in LCLs, where cis is defined by +/- 500 Mb of the gene body.
    * a. across all genes genome-wide (n = 20K protein coding genes) Note: might need to subset gene expression data. If so, use gene_annot.txt.gz to figure out which genes are protein coding.
* Part 2: Predict genetic risk for different diseases in 1000 Genomes individuals. Using Tiffany's 23andme data, where does she fall on the distribution? 

## Weekly Questions

The purpose of this week's questions are to prepare you for the checkpoint. Please answer the following questions on Gradescope:

* What is the biological purpose of wanting to understand how genetic variation impacts gene expression?
* What would be a good title for a paper about the analysis we are trying to do in this capstone, e.g. if we are interested in identifying genetic variation that impacts gene expression across many different tissues of the body?
* What will you include in the introduction to this paper? (think about defining what an eQTL is, how we can use eQTL to understand human disease, think about why it's cool that we have this functional genomics data across so many different tissue types in the body)
* What was the correlation of genotype and gene expression for the cis-eQTL analysis you ran? 
* What was the p-value of the correlation of genotype and gene expression for the cis-eQTL analysis you ran? 
* If you scaled up your analysis to multiple genes and multiple variants, how many SNP-gene pairs passed the significance threshold of 0.05/(how many SNP-gene pairs you tested)?


