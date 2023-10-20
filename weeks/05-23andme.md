---
layout: week
title: Week 05
permalink: /weeks/05-23andme/
doodle: /PRS_capstone.jpg
---

## Topics

This week's assignments will guide you through the following topic:

* Integrating 23andme data with PRS analysis and 1000 Genomes predictions

## Reading

Please read the following:
* No new reading for this week, but if you want more references on PRS models, you can refer to Amariuta 2020 Nature Genetics, Martin 2019 Nature Genetics, and Khera 2018 Nature Genetics. 

## Tasks

* Convert Tiffany's 23andme data to VCF and plink files using this tutorial: https://samtools.github.io/bcftools/howtos/convert.html
* Download genome-wide summary statistics for a trait of your choosing (height is a great option) from my Github page (https://github.com/TiffanyAmariuta/TCSC/tree/main/sumstats), perform pruning and thresholding using a fixed threshold (p = 10 x 10^-4) because we cannot optimize this without the individual level data like we did for 1000 Genomes data.
* Generate a PRS for each 1000 Genome individual and using Tiffany's genetic data (could merge Tiffany's plink file with 1KG plink files so you only need to run a single script to generate the PRS).
* Plot the distribution of predicted phenotype (PRS) for the 1KG individuals and report what Tiffany's relative risk for the trait/disease is. 


## Weekly Questions

Answer the following questions on Gradescope:

* Given that Tiffany is 5 foot 6 inches tall, is her height PRS sensible with respect to the population?
* Upload an image of the bell curve of the 1000 Genomes height PRS with a line indicating Tiffany's height PRS. 
