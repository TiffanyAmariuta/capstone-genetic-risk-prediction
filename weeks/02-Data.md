---
layout: week
title: Week 02
permalink: /weeks/02-Data/
doodle: /PRS_capstone.jpg
---

# Methods and analysis of genotyping + introduction to population genetics

## Topics

This week's assignments will guide you through the following topics:
* Why genotyping data is heavily protected due to reidentification issues. 
* How next gen sequencing is used to genotype samples for genetic analysis. 
* Implications of rare (< 1 percent), low frequency (1 - 5 percent), and common alleles (> 5 percent) on disease. 

## Reading

Please read the following:
* [Review paper on next generation sequencing to call genotypes](https://www.nature.com/articles/nrg2986)
  (Read the introduction, section on Alignment and Assembly, Genotype and SNP Calling, Probabilistic Methods, Incorporating LD information)
* [Review paper on privacy concerns and ethics surrounding genomics data](https://www.nature.com/articles/s41576-022-00455-y)
  (Read all main text)
* [Review paper on population genetics and allele frequency spectrum](https://www.sciencedirect.com/science/article/pii/S0092867411010695?via%3Dihub)
  (Read all main text)

## Tasks
TO DO: Download plink from [HERE](https://www.cog-genomics.org/plink/2.0/)
Choose the correct Development (5 Oct) version of plink for your machine. You will need to unzip the downloaded file for the plink2 executable to be usable.
You can test it by running ./plink2 in the directory where you downloaded it. 

Using the 1000 Genomes genotype data downloaded from the LDREF [link](https://data.broadinstitute.org/alkesgroup/FUSION/LDREF.tar.bz2):
* How many alleles are common (MAF > 5%); how many alleles are of low frequency (1% < MAF < 5%) or rare (MAF < 1%)? Note, you could either use plink2 to compute allele frequencies using bed/bim/fam files. Or you could check out the .frq (frequency) files.
* How many people in the plink genotype files have gene expression measured in the expression dataset? 

## Weekly Questions

Answer the following questions on Gradescope:

* What is the tradeoff between rare and common alleles in studying the genetics of human disease?
* What are the risks associated with the distribution of personally identifiable genetic data?

