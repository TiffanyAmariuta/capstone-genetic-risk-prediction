---
layout: week
title: Week 06
permalink: /weeks/06-Visualization/
doodle: /PRS_capstone.jpg
---

## Topics

This week's assignments will guide you through the following topics:
* Querying linkage disequilibrium between variants. 
* Plotting cis-eQTL associations per gene locus using LocusZoom, a very popular software that researchers use when making manuscript figures. 
* If you finish this week's assignment too quickly, feel free to read up on fine-mapping of cis-eQTL association data, using CAVIAR (http://genetics.cs.ucla.edu/caviar/). For example, feed in your cis-eQTL association data and the 1000Genomes genotype files to figure out which associated variants are likely to be causal in a gene locus.
* In the following weeks, we will discuss fine-mapping cis eQTLs and colocalization with GWAS summary statistics. 

## Reading

Please read about the following software package:
* [LocusZoom: plotting cis-eQTL associations in a gene locus](http://locuszoom.org/)
  (Navigate to either Interactive LocusZoom.js or Original LocusZoom on the right-hand column of the webpage. Download the necessary software.)

## Tasks

* Follow the tutorial for LocusZoom. 
* Use LocusZoom to plot cis-eQTL associations from your dataset. On the y-axis, we want the -log10 P of the cis-eQTL. On the x-axis, we want the genomic position of the variants. And the color of the variants will correspond to the linkage disequilibrium (r2 of genotypes) between the lead variant (variant with largest -log10P) and each other variant in turn. 
* Note: I think you will need plink and the 1000Genomes bed/bim/fam files for LocusZoom to figure out the pairwise LD between variants. 
* Note: I think you will also need as input to LocusZoom, a table of summary statistics for your cis-eQTLs, meaning a table where one column is the SNPs (rsIDs) and one column is the -log10P of the SNP-gene pair. 
* Note: You will need a different summary statistics file for each gene locus, since you should plot one gene locus at a time. 

## Weekly Questions

Answer the following questions on Gradescope:
* How many significant cis-eQTLs did you find on chr 22? (e.g. p-value < 0.05/number of SNP-gene pairs you tested)
* For any one gene locus, how many cis-eQTLs have LD r2 > 0.8 with the lead variant? 
* For any one gene locus, how many cis-eQTLs have LD r2 > 0.5 with the lead variant? 
* For any one gene locus, how many cis-eQTLs have LD r2 > 0.1 with the lead variant? 
* Please include a LocusZoom plot for your favorite gene locus. 



