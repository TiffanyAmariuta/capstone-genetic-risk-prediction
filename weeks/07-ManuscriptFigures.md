---
layout: week
title: Week 07
permalink: /weeks/07-ManuscriptFigures/
doodle: /PRS_capstone.jpg
---

## Topics

In our discussion section this week, we talked about several different figures you could consider when preparing your quarter 1 project. The task this week is to experiment with making these figures so you feel prepared when writing the paper. Seeing the resulting figure will also help you shape the narrative you will tell in the paper. For example, if you find something very compelling or distinct about a result in a figure, you can choose to focus the paper on it. 

## Reading

There are no manuscript reading assignments this week. As far as plotting, I'd like to get familiar with different types of plots and plotting functions based on the scripting language you prefer. For example, I use R a lot and therefore I use base R and ggplot() for all of my figures. The types of plots you should be familiar with are the following...

* box and whisker plots (e.g. to show an example of a significant cis-eQTL: plot gene expression on y-axis and genotypes (0,1,2 or AA/AT/TT or relevant alleles) on x-axis. 
* barplot (e.g. to show the total number of cis-eQTLs you find in each super population: plot number of cis-eQTLs on y-axis and super population on x-axis)
* stacked barplot (e.g. to show how many genes have how many cis-eQTLs per super populations: plot number of eQTL genes on y-axis, plot discrete numbers 0, 1, 2, 3, 4, etc on x-axis indicating the number of SNPs the gene is an eQTL with, and stack information for each population. 
* LocusZoom plot (using locusZoom software to show your favorite gene locus: this can be the locus with the most significant cis-eQTLs, or the locus with the lowest P value, e.g. most significant cis-eQTL of your whole dataset, etc)
* simple x-y plot (e.g. to show the slopes (or linear regression coefficients) for different significant eqtls across two populations where the x-axis represents one population and the y-axis represents the other. You could demonstrate that the direction of effect (e.g. positive or negative coefficient values) are largely the same for both populations. 
* barplot with standard error (you could show that the eQTL effect size for one SNP-gene pair is significantly different between two or more populations, in this case you could plot the coefficient from the linear model and the 95% confidence interval using its standard error to demonstrate that the effects are indeed different between groups). 

## Tasks

Please use your analysis of chromosome 22 to make one plot for each of the six types listed above and upload them to Gradescope. 


