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

* Perform a cis-eQTL analysis for all genes on a chromosome of your choosing using 1000 Genome data. This is simply a scaled up version of your analysis from last week. 
* Follow the tutorial for building a polygenic risk score (PRS) for a single gene from your eQTL analysis above via the most widely used pruning and thresholding [approach](https://choishingwan.github.io/PRS-Tutorial/plink/) P+T which conveniently uses plink commands. Here, Height.QC.gz is analogous to your week 3 eQTL analysis results and the scaled up analysis you just did. Please consider the following things: we will pretend that we don't have any covariates (EUR.cov) to simplify the analysis. You will perform "Clumping" using different p-value thresholds described below. You will then "Generate PRS". Please stop when you get to the section on Population Stratification. 
*  When we build a PRS, we have to make sure our model is not overfit. This requires cross-validation analysis. Please build this pipeline for one gene. Step 1. Randomly sample 80% of individuals and perform the cis-eQTL analysis for one gene (you can use the --keep flag for plink to select certain sample IDs). Step 2. Randomly sample half of the remaining 20% of individuals. With these people, run the PRS pipeline with several p-value thresholds: 1, 0.05, 0.01, 0.001, and 0.00001. Correlate the predicted value of gene expression with the true value. Pick the p-value threshold that maximizes the prediction R2. Step 3: Assess the PRS accuracy in the remaining individuals (none of these people have been used in the model fitting part). What is the final R2? 

## Quarter 1 Project Paper Outline 

* Part 1: Identify ciseQTLs in 1000 Genomes LCLs, where cis is defined by +/- 500 Kb of the gene body.
    * a. across all genes genome-wide (n = 20K protein coding genes) Note: might need to subset gene expression data. If so, use gene_annot.txt.gz to figure out which genes are protein coding.
* Part 2: Predict genetic risk for different diseases in 1000 Genomes individuals. Using Tiffany's 23andme data, where does she fall on the distribution? Are the results reasonable? 

## Weekly Questions

The purpose of this week's questions are to prepare you for the checkpoint. Please answer the following questions on Gradescope:

* What is the biological purpose of wanting to understand how genetic variation impacts gene expression?
* What would be a good title for a paper about the analysis we are trying to do in this capstone?
* What will you include in the introduction to this paper? (think about defining what an eQTL is, what a genetic risk score is, and what a genome-wide association study is, and what we stand to learn about disease biology from these)
* What was the distribution of correlation of true gene expression and predicted gene expression across genes in 1000 Genomes? 


