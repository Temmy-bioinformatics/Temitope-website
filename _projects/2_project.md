---
layout: page
title: Population Genomics Across ~700 Eurasian Minnow Genomes
description: Population structure, genetic diversity, and introgression across European Phoxinus populations
img: assets/img/popgen_cover.png
importance: 2
category: work
giscus_comments: true
related_publications: true
---

Understanding genomic diversity requires analysing populations across geographic and evolutionary scales. In this project, I analysed nearly **700 whole genomes of Eurasian minnows (*Phoxinus*)** sampled across multiple European river drainages to investigate population structure, genetic diversity, admixture, introgression, and the evolutionary history of a taxonomically complex species group.

### What I worked on

I developed and applied a population-scale genomic workflow spanning variant discovery, quality control, population genetic analyses, and phylogenomic inference. Key components included:

- **Whole-genome variant discovery** across hundreds of individuals
- **Variant filtering and quality control** to generate high-confidence SNP datasets for downstream analyses
- **Population structure analysis** to identify genetically distinct lineages and patterns of admixture
- **Genetic diversity and population differentiation** across European river drainages
- **Introgression and gene-flow analysis** to investigate genetic exchange between divergent lineages
- **Phylogenomic analysis** to characterise relationships among closely related taxa
- **K-mer-based analysis** to identify genomic patterns using a reference-free approach
- Integration of genomic results with **geographic, ecological, and historical information** to distinguish natural population structure from patterns associated with human-mediated introductions

The analyses involved large genomic datasets and were implemented using reproducible workflows designed for execution on **high-performance computing systems**.

### Key outcome

The genomic data revealed substantial geographic structure across *Phoxinus*and showed that **anthropogenic introductions and stocking**can strongly influence observed distributions and patterns of genetic diversity. Combining population genomic evidence with historical context helped distinguish naturally structured populations from genetic patterns shaped by human activity {% cite sternberg2025minnows %}.

The dataset also provided a genomic framework for investigating **cryptic diversity and species boundaries** within *Phoxinus*, demonstrating how genome-wide data can resolve evolutionary relationships that are difficult to distinguish using morphology or traditional genetic markers alone.

### Computational toolkit

**Variant discovery:** Whole-genome sequencing · read alignment · joint variant calling · SNP filtering  
**Population genomics:** Population structure · genetic diversity · population differentiation · admixture  
**Gene flow & phylogenomics:** Introgression · gene flow · phylogenomic analysis · demographic inference  
**Reference-free genomics:** K-mer analysis  
**Programming & workflow:** R · Python · Bash · Snakemake  
**HPC:** Linux · SLURM · SGE

### Publication

Sternberg, N., Bodenheim, A., Oriowo, T. O., Podsiadlowski, L., & Stange, M. (2025). *Human impacts on the distribution and genetic diversity of Eurasian minnows (Phoxinus: Leuciscidae) in the Rhenish Massif.* **Knowledge & Management of Aquatic Ecosystems**, 426, 20.
