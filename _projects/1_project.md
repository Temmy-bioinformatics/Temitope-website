---
layout: page
title: Haplotype-Resolved Genome Assembly
description: Chromosome-level reference genome for Phoxinus phoxinus using PacBio HiFi, Hi-C, and RNA-Seq
img: assets/img/minnow_genome_cover.jpg
importance: 1
category: Work
related_publications: true
---

The Eurasian minnow (*Phoxinus phoxinus*) lacked a high-quality genomic reference suitable for population-scale genomic research. I developed a **reproducible, chromosome-level, haplotype-resolved genome assembly workflow** from a diploid individual, integrating PacBio HiFi long reads, Hi-C chromatin conformation data, and RNA-Seq evidence.

### What I worked on

I developed and implemented the computational workflow from raw sequencing data through chromosome-level assembly, annotation, and quality assessment. Key components included:

- **PacBio HiFi genome assembly** for high-contiguity long-read reconstruction
- **Haplotype phasing and separation** to retain both homologous chromosomes
- **Hi-C scaffolding** to produce chromosome-level assemblies
- **RNA-Seq-supported structural and functional annotation**
- **Assembly quality assessment**, including BUSCO completeness and contiguity metrics
- **Reproducible workflow development** using Snakemake
- Execution and scaling of computational analyses on **HPC systems**

The workflow was designed to be reproducible and scalable, providing a framework that can be adapted for additional *Phoxinus* genomes and downstream comparative genomic analyses.

### Key outcome

Maintaining the two haplotypes separately allowed genomic variation within a single individual to be characterised directly, revealing substantial **haplotype diversity that would be obscured by a conventional collapsed reference assembly**.

The resulting chromosome-level reference genome provided the foundation for subsequent population-scale analyses of approximately **700 *Phoxinus* whole genomes**, supporting variant discovery, population structure, admixture, and introgression analyses.

The assembly has also been used as a genomic reference for subsequent work investigating **sex chromosome evolution** in *Phoxinus*.

### Computational toolkit

**Genome assembly:** PacBio HiFi · Hi-C · haplotype phasing  
**Annotation:** RNA-Seq · structural annotation · functional annotation  
**Workflow & HPC:** Snakemake · Bash · Linux · HPC  
**Quality assessment:** BUSCO · assembly contiguity metrics

### Publication

Oriowo, T. O. *et al.* (2025). *A chromosome-level, haplotype-resolved genome assembly and annotation for the Eurasian minnow (Leuciscidae: Phoxinus phoxinus) provide evidence of haplotype diversity.* **GigaScience**, 14, giae116.
