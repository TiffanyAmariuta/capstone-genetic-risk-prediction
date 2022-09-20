---
layout: page
title: "Genetic risk prediction of gene expression, complex traits, and polygenic disease"
doodle: "/doodle.png"
permalink: /
---

Data science capstone domain of inquiry (DSC 180AB A17 2022-2023)

Developed by Tiffany Amariuta.

---
* TOC
{:toc}

---

# Introduction

A genetic risk score (GRS) or polygenic risk score (PRS) is a weighted sum of an individual's risk alleles across one's genome for a particular phenotype, i.e. disease or other measurement. The weights are typically the effect sizes of the risk allele, estimated by a genome-wide association study (in the case of complex traits / polygenic diseases) or an eQTL study (in the case of gene expression). PRS have great potential to revolutionize preventive care. In theory, an individual may arrive at the clinic not knowing their genetic susceptibility to a disease, have their DNA sequenced, and learn what is their lifetime risk for the disease. There is a theoretical liability threshold of PRS at which individuals who have a PRS value lower than the threshold will not develop the disease and those with a value higher than the threshold will develop disease. For diseases with a monogenic basis, it has been shown that the same degree of disease risk can be conferred by polygenic risk alone (Khera 2018 Nature Genetics). PRS are generally useful for understanding how predictive genetics is of disease and how disperse the genetic contributions are. PRS is especially useful in understanding genetic liability when individual effects are too small to be easily detected by genome-wide association studies (Purcell 2009 Nature). 

In this capstone, students will use population genetics and genomics data to assess individual risk for disease outcomes and transcriptomic measurements. Students will learn to work with genotype data from 1000Genomes and genetic association data from genome-wide association studies (GWAS) and transcriptome-wide association studies (TWAS).

In this capstone, we will be trying to answer the following questions:
* What proportion of disease-associated genetic variation is propagated through gene expression? 
* How does genetic liability (high PRS) for gene expression correlate with genetic liability for polygenic disease?
* What explains the missing phenotypic variance of gene expression and polygenic disease?

To answer these questions, we will be working toward performing the following types of analysis:
* Detection of genetic effects on gene expression (eQTL analysis)
* Identification of disease-associated genes: colocalization analysis of eQTL and GWAS data
* From association to causation: fine-mapping analysis of detected eQTLs

This domain centers around understanding computer code as *data*. You
will spend a significant amount of work writing parsing logic for this
code that measures the behaviors of interest (i.e. data processing).

## Result replication (introduction to topic)

The bulk of the first half of the project will focus the task of
"computer code understanding" on the specific problem of detection
whether given source code is Malware or a benign application. The bulk
of the result replication will focus on static code analysis using
machine learning on graphs, as developed in the following papers:
* [Hindroid](https://www.cse.ust.hk/~yqsong/papers/2017-KDD-HINDROID.pdf)
* [MaMaDroid](https://arxiv.org/pdf/1612.04433.pdf)

The latter-half of Quarter 1 will introduce you to further topics,
like graph embedding techniques and adversarial ML, to inform possible
avenues for further research.

## An initial note on ethics

The ability to identify and combat Malware requires understanding how
Malware works. Such knowledge is divorced from how it gets used by the
practitioner; you, as the practitioner must be aware of ethical
concerns with the usage of this knowledge and behave accordingly. In
particular, while working with the material in this course, you must
never engage in illegal activity related to your coursework and you
must adhere to the code of academic integrity, as laid out in th
syllabus.

The topic of ethics will be regularly approached in this domain. For
more reading on the ethics of teaching Malware, see this opinion
pience [On the Growing Harm of Not Teaching
Malware](http://www.csl.sri.com/users/neumann/cacm223.pdf) and a
related study on [the ethics of teaching
malware](https://www.ieee-security.org/TC/SPW2014/papers/5103a001.PDF).

---

# Section Participation

Participation in the weekly discussion section is *mandatory*. Each
week, you are responsible for doing the reading/task assigned in the
[schedule](#schedule). Come to section prepared to ask questions about
and discuss the results of these tasks.

Each week, turn in answers to the weekly questions to Canvas. These
questions are meant to focus your work for the week and help prepare
you for discussion. If you have questions about your work, please ask
them in section or office hours (I will rarely comment on your
submission).

You are responsible for the entire weekly reading/task, even if
portions are not covered in the weekly questions. The weekly tasks are
the building blocks for the project proposals/assignments due at the
end of the quarter.

---

# Schedule

|Week|Topic|
|--|--|
|1|[Introduction to Code-Understanding and Malware]({{ "weeks/01-Introduction" | absolute_url }})|
|2|[Data: Code Parsing, Malware]({{ "/weeks/02-Data" | absolute_url }})|
|3|[Creating Graphs from Code; What is Malware?]({{ "/weeks/03-Android-Graphs" | absolute_url }})|
|4|[Graph Invariants as Measurements]({{ "/weeks/04-Graph-Features" | absolute_url }})|
|5|[Building a Baseline Model]({{ "/weeks/05-Baseline-Model" | absolute_url }})|
|6|[Evalulating the HinDroid Result]({{ "/weeks/06-Hindroid" | absolute_url }})|
|7|[Graph Embedding I: node2vec]({{ "/weeks/07-Graph-Embeddings-I" | absolute_url }})|
|8|[Graph Embedding II: metapath2vec]({{ "/weeks/08-Graph-Embeddings-II" | absolute_url }})|
|9|[Production and Adversarial ML]({{ "/weeks/09-Adversarial-ML" | absolute_url }})|
|10|Present Proposals|

---

# Office Hours

Fridays 9-11AM



