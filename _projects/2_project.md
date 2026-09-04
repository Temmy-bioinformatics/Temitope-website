---
layout: page
title: Population genomics across ~700 Eurasian minnow genomes
description: Variant discovery, population structure, and introgression analysis in Phoxinus
img: assets/img/popgen_cover.jpg
importance: 2
category: work
giscus_comments: true
---

Beyond a single reference genome, understanding a species means understanding its populations. This project applied population-scale whole-genome sequencing to nearly **700 Eurasian minnow (*Phoxinus*) genomes**, sampled across multiple river drainages, to investigate genetic structure, historical introductions, and species boundaries within a taxonomically complex, cryptic species group.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sampling_map.jpg" title="Sampling sites across river basins" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/variant_calling_pipeline.jpg" title="Variant calling workflow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/population_structure.jpg" title="Population structure plot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From left to right: sampling sites across German river basins, the variant calling pipeline, and inferred population structure across sampled Phoxinus populations.
</div>

### From reads to insights

Working from raw sequencing reads to biological conclusions involved a full population genomics pipeline: quality control, alignment, joint variant calling, and filtering across hundreds of individuals, followed by downstream population genetic analyses including:

- **Population structure** — clustering individuals by genetic ancestry to reveal distinct lineages and admixture
- **Introgression analysis** — detecting historical gene flow between genetically distinct clades, some of it linked to human-mediated stocking of fish for angling
- **K-mer-based analysis** — reference-free approaches to complement alignment-based methods, especially useful where taxonomic boundaries are still debated

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/haplotype_network.jpg" title="Haplotype network" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A haplotype network illustrating shared genetic ancestry across river basins — a key tool for tracing the origin of introduced populations.
</div>

### Untangling nature from human impact

One of the more striking findings from this body of work was how much apparent population structure actually reflects **anthropogenic influence** rather than natural biogeography. Stocking practices, historical introductions, and cryptic species boundaries all leave detectable genomic signatures, and disentangling them required combining genomic evidence with historical and stakeholder-reported context {% cite sternberg2025minnows %}.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/introgression_signal.jpg" title="Introgression signal across drainages" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/clade_distribution.jpg" title="Clade distribution" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Introgression signal detected between river drainages (left), alongside the distribution of distinct genetic clades across the sampled basins (right).
</div>

### Reproducible infrastructure

As with the genome assembly work, all population genomics analyses were implemented as **Snakemake pipelines**, run on SLURM/SGE-based HPC infrastructure, ensuring that variant calling and downstream analyses could scale to the full sample set and be rerun as new samples were added.

Related publication: **Sternberg, N., Bodenheim, A., Oriowo, T. O., Podsiadlowski, L., & Stange, M. (2025). Human impacts on the distribution and genetic diversity of Eurasian minnows (Phoxinus: Leuciscidae) in the Rhenish Massif. *Knowledge & Management of Aquatic Ecosystems*, 426, 20.** {% cite sternberg2025minnows %}
