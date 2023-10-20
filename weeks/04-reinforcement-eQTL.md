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
* Separately, let's start to analyze 23andme data using this tutorial (https://samtools.github.io/bcftools/howtos/convert.html). The conversion pipeline will be 23andme text file -> VCF file -> plink file. You will then be able to estimate my predicted gene expression using my genotype data. 

## Quarter 1 Project Paper Outline 

* Part 1: Identify ciseQTLs in 1000 Genomes LCLs, where cis is defined by +/- 500 Mb of the gene body.
    * a. across all genes genome-wide (n = 20K protein coding genes) Note: might need to subset gene expression data. If so, use gene_annot.txt.gz to figure out which genes are protein coding.
* Part 2: Predict genetic risk for different diseases in 1000 Genomes individuals. Using Tiffany's 23andme data, where does she fall on the distribution? 

## Weekly Questions

The purpose of this week's questions are to prepare you for the checkpoint. Please answer the following questions on Gradescope:

* What is the biological purpose of wanting to understand how genetic variation impacts gene expression?
* What would be a good title for a paper about the analysis we are trying to do in this capstone?
* What will you include in the introduction to this paper? (think about defining what an eQTL is, what a genetic risk score is, and what a genome-wide association study is, and what we stand to learn about disease biology from these)
* What was the distribution of correlation of true gene expression and predicted gene expression across genes in 1000 Genomes? 
* Plot the distribution of predicted gene expression for one gene across 1000 Genomes individuals, and indicate where Tiffany's predicted expression lies.


