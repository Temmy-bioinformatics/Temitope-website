---
layout: page
title: Haplotype-resolved genome assembly of the Eurasian minnow
description: Chromosome-level reference genome for Phoxinus phoxinus using PacBio HiFi, Hi-C, and RNA-Seq
img: assets/img/minnow_genome_cover.jpg
importance: 1
category: work
related_publications: true
---

The Eurasian minnow (_Phoxinus phoxinus_) is a small freshwater fish widely distributed across European river systems, but until recently it lacked a high-quality genomic reference. This project produced a **chromosome-level, haplotype-resolved genome assembly** for the species, combining PacBio HiFi long reads, Hi-C chromatin conformation data, and RNA-Seq transcriptomic evidence to assemble and annotate both haplotypes of a diploid individual.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/minnow_sampling.jpg" title="Phoxinus phoxinus specimen" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hifi_workflow.jpg" title="Assembly workflow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hic_contact_map.jpg" title="Hi-C contact map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From left to right: a sampled Phoxinus phoxinus specimen, the long-read assembly workflow, and a Hi-C contact map used to scaffold contigs into chromosomes.
</div>

### Why haplotype resolution matters

Most reference genomes collapse the two parental haplotypes into a single consensus sequence, which can obscure real biological variation — especially in wild, outbred populations. By keeping both haplotypes separate throughout assembly, we were able to directly quantify **haplotype diversity** within a single individual, giving a more complete picture of heterozygosity than a collapsed assembly would allow {% cite oriowo2025minnow %}.

### Pipeline and reproducibility

The entire workflow — from raw read QC through assembly, scaffolding, and structural/functional annotation — was implemented as a **Snakemake pipeline**, making it scalable to additional samples and reproducible across compute environments. Steps included:

- Long-read assembly from PacBio HiFi data
- Hi-C-based scaffolding to chromosome-level contiguity
- Haplotype phasing and separation
- Structural annotation supported by RNA-Seq evidence
- Quality assessment (BUSCO completeness, assembly contiguity metrics)

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/genome_synteny.jpg" title="Chromosome-level assembly" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/busco_score.jpg" title="BUSCO completeness" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The final assembly, resolved to chromosome level, alongside completeness statistics from BUSCO.
</div>

### Impact

This reference genome now underpins downstream population-scale work on ~700 _Phoxinus_ whole genomes, including variant calling, population structure, and introgression analyses, and has already been used as the mapping reference in follow-up studies on sex chromosome evolution in the genus.

Read the full paper: **Oriowo, T. O. _et al._ (2025). A chromosome-level, haplotype-resolved genome assembly and annotation for the Eurasian minnow (Leuciscidae: _Phoxinus phoxinus_) provide evidence of haplotype diversity. _GigaScience_, 14, giae116.** {% cite oriowo2025minnow %}
