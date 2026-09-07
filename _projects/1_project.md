---
layout: page
title: Haplotype-resolved genome assembly
description: Chromosome-level reference genome for Phoxinus phoxinus using PacBio HiFi, Hi-C, and RNA-Seq
img: assets/img/minnow_genome_cover.jpg
importance: 1
category: work
related_publications: true
---

<<<<<<< HEAD
The Eurasian minnow (*Phoxinus phoxinus*) is a widespread freshwater fish that, until recently, lacked a high-quality genomic reference. I developed a reproducible workflow to generate a **chromosome-level, haplotype-resolved genome assembly** from a diploid individual, integrating PacBio HiFi long reads, Hi-C chromatin conformation data, and RNA-Seq evidence.
=======
---

The Eurasian minnow (_Phoxinus phoxinus_) is a small freshwater fish widely distributed across European river systems, but until recently it lacked a high-quality genomic reference. This project produced a **chromosome-level, haplotype-resolved genome assembly** for the species, combining PacBio HiFi long reads, Hi-C chromatin conformation data, and RNA-Seq transcriptomic evidence to assemble and annotate both haplotypes of a diploid individual.
>>>>>>> deb3d9e (update projects)

### What I worked on

The workflow covered the complete genome assembly and annotation process, from raw sequencing data through chromosome-level scaffolding and quality assessment. Key components included:

- **PacBio HiFi** long-read genome assembly
- **Haplotype phasing and separation** to retain both homologous chromosomes
- **Hi-C scaffolding** to achieve chromosome-level contiguity
- **RNA-Seq-supported structural and functional annotation**
- **Assembly quality assessment**, including BUSCO completeness and contiguity metrics
- Reproducible workflow development using **Snakemake**

The workflow was designed to be scalable and reproducible across high-performance computing environments, providing a framework that can be adapted for additional *Phoxinus* samples.

<<<<<<< HEAD
### Biological impact
=======
- Long-read assembly from PacBio HiFi data
- Hi-C-based scaffolding to chromosome-level contiguity
- Haplotype phasing and separation
- Structural annotation supported by RNA-Seq evidence
- Quality assessment (BUSCO completeness, assembly contiguity metrics)
>>>>>>> deb3d9e (update projects)

Maintaining the two haplotypes separately allowed us to quantify genomic variation within a single individual and demonstrated substantial **haplotype diversity** that would be obscured by a conventional collapsed reference assembly {% cite oriowo2025minnow %}.

<<<<<<< HEAD
The resulting reference genome has since provided the foundation for downstream population-scale genomic analyses of approximately **700 *Phoxinus* whole genomes**, including variant discovery, population structure, and introgression analyses. It has also been used as a reference in subsequent work investigating **sex chromosome evolution** in the genus.

### Computational toolkit

**Genome assembly:** PacBio HiFi · Hi-C · haplotype phasing  
**Annotation:** RNA-Seq · structural annotation · functional annotation  
**Workflow:** Snakemake · Bash · HPC  
**Quality control:** BUSCO · assembly contiguity metrics

### Publication

Oriowo, T. O. *et al.* (2025). *A chromosome-level, haplotype-resolved genome assembly and annotation for the Eurasian minnow (Leuciscidae: Phoxinus phoxinus) provide evidence of haplotype diversity.* **GigaScience**, 14, giae116. {% cite oriowo2025minnow %}
=======
This reference genome now underpins downstream population-scale work on ~700 _Phoxinus_ whole genomes, including variant calling, population structure, and introgression analyses, and has already been used as the mapping reference in follow-up studies on sex chromosome evolution in the genus.

Read the full paper: **Oriowo, T. O. _et al._ (2025). A chromosome-level, haplotype-resolved genome assembly and annotation for the Eurasian minnow (Leuciscidae: _Phoxinus phoxinus_) provide evidence of haplotype diversity. _GigaScience_, 14, giae116.** {% cite oriowo2025minnow %}
>>>>>>> deb3d9e (update projects)
