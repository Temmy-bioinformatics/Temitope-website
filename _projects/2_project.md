---

layout: page
title: Population genomics across ~700 Eurasian minnow genomes
description: Variant discovery, population structure, and introgression analysis in Phoxinus
img: assets/img/popgen_cover.jpg
importance: 2
category: work
giscus_comments: true
---------------------

Beyond a single reference genome, understanding a species means understanding its populations. This project applied population-scale whole-genome sequencing to nearly **700 Eurasian minnow (*Phoxinus*) genomes**, sampled across multiple river drainages, to investigate genetic structure, historical introductions, and species boundaries within a taxonomically complex, cryptic species group.

### From reads to insights

Working from raw sequencing reads to biological conclusions involved a full population genomics pipeline: quality control, alignment, joint variant calling, and filtering across hundreds of individuals, followed by downstream population genetic analyses including:

* **Population structure** — clustering individuals by genetic ancestry to reveal distinct lineages and admixture
* **Introgression analysis** — detecting historical gene flow between genetically distinct clades, some of it linked to human-mediated stocking of fish for angling
* **K-mer-based analysis** — reference-free approaches to complement alignment-based methods, especially useful where taxonomic boundaries are still debated

### Untangling nature from human impact

One of the more striking findings from this body of work was how much apparent population structure actually reflects **anthropogenic influence** rather than natural biogeography. Stocking practices, historical introductions, and cryptic species boundaries all leave detectable genomic signatures, and disentangling them required combining genomic evidence with historical and stakeholder-reported context {% cite sternberg2025minnows %}.

### Reproducible infrastructure

As with the genome assembly work, all population genomics analyses were implemented as **Snakemake pipelines**, run on SLURM/SGE-based HPC infrastructure, ensuring that variant calling and downstream analyses could scale to the full sample set and be rerun as new samples were added.

Related publication: **Sternberg, N., Bodenheim, A., Oriowo, T. O., Podsiadlowski, L., & Stange, M. (2025). Human impacts on the distribution and genetic diversity of Eurasian minnows (Phoxinus: Leuciscidae) in the Rhenish Massif. *Knowledge & Management of Aquatic Ecosystems*, 426, 20.** {% cite sternberg2025minnows %}
