---
layout: page
title: Sex determination systems in Eurasian minnows
description: Whole-genome analysis reveals contrasting sex determination systems in two closely related Phoxinus species
img: assets/img/sex_determination_cover.png
importance: 3
category: work
related_publications: true
---

Sex determination systems can evolve rapidly, even among closely related species. In this project, I used whole-genome sequencing to investigate the genetic basis of sex determination in two closely related Eurasian minnows, *Phoxinus phoxinus* and *Phoxinus csikii*.

### What I worked on

I combined multiple genome-wide approaches to identify sex-associated genomic regions and investigate the underlying sex determination systems. Key analyses included:

- **Whole-genome coverage analysis** to identify chromosome-level differences between males and females
- **Sex-associated SNP analysis** to identify genomic regions showing sex-specific patterns of heterozygosity
- **K-mer-based analysis** to detect male- and female-specific DNA sequences without relying solely on reference-based variant discovery
- Analysis of **population- and drainage-specific patterns** of sex-associated variation
- Integration of complementary genomic signals to infer sex determination systems in both species

### Contrasting sex determination systems

The analyses revealed different sex determination systems in the two closely related species. *P. phoxinus* showed male-specific heterozygosity in regions on chromosomes 3 and 12, consistent with a **male-heterogametic XX/XY system**. In contrast, *P. csikii* showed female-specific genotypic differences on chromosome 3, supporting a **female-heterogametic ZZ/ZW system**. Neither species showed strong chromosome-wide sex-biased coverage, consistent with relatively homomorphic sex chromosomes. {% cite oriowo2026phoxinussex %}

The presence of different sex determination systems in closely related species provides insight into the evolutionary flexibility of sex determination and raises the possibility that differences in sex-linked genomic regions may contribute to reproductive isolation.

### Computational toolkit

**Genomics:** Whole-genome sequencing · SNP analysis · sex-associated genomic regions  
**Sex determination:** Sex-linked heterozygosity · coverage analysis · sex-specific sequences  
**Reference-free genomics:** K-mer analysis  
**Population genomics:** Population-specific signals · drainage-level variation  
**Workflow & HPC:** Bash · R · Python · high-performance computing

### Publication

Oriowo, T. O., Smith, S. H., Thorman, J., Sternberg, N., Böhne, A., & Stange, M. (2026). *Different sex determination systems in two closely related Eurasian minnow (Phoxinus) species.* **Heredity**, 135, 259–270. {% cite oriowo2026phoxinussex %}
