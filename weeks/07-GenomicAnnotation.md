---
layout: week
title: Week 07
permalink: /weeks/07-GenomicAnnotation/
doodle: /PRS_capstone.jpg
---

## Topics
Genomic annotation using high throughput experimental approaches to understand the cellular and biological context of cis-eQTLs.

## Reading

Please read the following:
* [Landmark paper for Roadmap Epigenomics consortium](https://pubmed.ncbi.nlm.nih.gov/25693563/)
  (Read the Abstract; Intoduction; Subsection 1. Reference epigenome mapping ... up to and including the paragraph starting with "We jointly processed..."; the first paragraph of Subsection 6. Epigenome dynamics reveal ...; the first two paragraphs of Subsection 8. Complex trait variants are enriched...)
* [ENCODE consortium resource paper](https://www.nature.com/articles/s41586-020-2493-4)
  (Read the Abstract; Intoduction up to but not including Expanding human and mouse ENCODE, the following subsections are each about different experimental techniques - feel free to skim this, just to get a sense of the many different ways we can measure biological function in genomes.)

* [Download the following ATAC-seq dataset for B cells from the ENCODE website (should be 6-column bed file format)](https://www.encodeproject.org/experiments/ENCSR603LVR/) Click on the file details tab, download ENCFF421XIL (bed narrowPeak file).

## Tasks
* Intersect the genomic positions of this functional annotation with the variants and genes you have been looking at in your cis-eQTL models. Is there any overlap? For example, take a gene's chromosome and genomic start and end positions (base pairs) and see if there are any open chromatin peaks in this area based on the chromosome and genomic start and end positions of the ATAC-seq peaks in the file above. 

## Weekly Questions
* What are two names of experimental assays to measure open chromatin (in other words, DNA accessibility)? Hint: One of them is a column of Figure 2 from the Roadmap Epigenomics paper. The other strategy is mentioned in the section titled "Transposase accessible regions" of the ENCODE paper linked above. 
* What is the importance of measuring open chromatin (in other words, DNA accessibility)? What does it mean about the functional potential of the DNA? (Hint: in the introduction to the Roadmap paper, the authors discuss how DNA sequence only gives us a limited perspective on biology and the "epigenome" is very informative for learning the ways in which the DNA is regulated.)
* What are some examples of histone modifications that enhance gene expression and what are some examples of histone modifications that suppress gene expression? (Hint: In Figure 2 from the Roadmap Epigenomics paper, there are 7 histone modification assays listed in the columns, 2 of them are markers of repressed gene expression, while 5 of them are markers of enhanced gene expression. Which are which? The functional implications of each are discussed in the subsection "1. Reference epigenome mapping across tissues and cell types".)
 


