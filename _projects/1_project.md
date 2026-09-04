---

layout: page
title: Haplotype-resolved genome assembly of the Eurasian minnow
description: Chromosome-level reference genome for Phoxinus phoxinus using PacBio HiFi, Hi-C, and RNA-Seq
img: assets/img/minnow_genome_cover.jpg
importance: 1
category: work
related_publications: true
--------------------------

The Eurasian minnow (*Phoxinus phoxinus*) is a small freshwater fish widely distributed across European river systems, but until recently it lacked a high-quality genomic reference. This project produced a **chromosome-level, haplotype-resolved genome assembly** for the species, combining PacBio HiFi long reads, Hi-C chromatin conformation data, and RNA-Seq transcriptomic evidence to assemble and annotate both haplotypes of a diploid individual.

### Why haplotype resolution matters

Most reference genomes collapse the two parental haplotypes into a single consensus sequence, which can obscure real biological variation — especially in wild, outbred populations. By keeping both haplotypes separate throughout assembly, we were able to directly quantify **haplotype diversity** within a single individual, giving a more complete picture of heterozygosity than a collapsed assembly would allow {% cite oriowo2025minnow %}.

### Pipeline and reproducibility

The entire workflow — from raw read QC through assembly, scaffolding, and structural/functional annotation — was implemented as a **Snakemake pipeline**, making it scalable to additional samples and reproducible across compute environments. Steps included:

* Long-read assembly from PacBio HiFi data
* Hi-C-based scaffolding to chromosome-level contiguity
* Haplotype phasing and separation
* Structural annotation supported by RNA-Seq evidence
* Quality assessment (BUSCO completeness, assembly contiguity metrics)

### Impact

This reference genome now underpins downstream population-scale work on ~700 *Phoxinus* whole genomes, including variant calling, population structure, and introgression analyses, and has already been used as the mapping reference in follow-up studies on sex chromosome evolution in the genus.

Read the full paper: **Oriowo, T. O. *et al.* (2025). A chromosome-level, haplotype-resolved genome assembly and annotation for the Eurasian minnow (Leuciscidae: *Phoxinus phoxinus*) provide evidence of haplotype diversity. *GigaScience*, 14, giae116.** {% cite oriowo2025minnow %}
