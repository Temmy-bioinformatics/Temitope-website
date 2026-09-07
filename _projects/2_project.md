---
layout: page
title: Population genomics across ~700 Eurasian minnow genomes
description: Population structure, genetic diversity, and introgression across European Phoxinus populations
img: assets/img/popgen_cover.png
importance: 2
category: work
<<<<<<< HEAD
related_publications: true
---

Understanding genomic diversity requires looking beyond a single reference genome to populations across the landscape. In this project, I analysed nearly **700 whole genomes of Eurasian minnows (*Phoxinus*)** sampled across multiple European river drainages to investigate population structure, genetic diversity, introgression, and the evolutionary history of a taxonomically complex species group.
=======
giscus_comments: true
---

---

Beyond a single reference genome, understanding a species means understanding its populations. This project applied population-scale whole-genome sequencing to nearly **700 Eurasian minnow (_Phoxinus_) genomes**, sampled across multiple river drainages, to investigate genetic structure, historical introductions, and species boundaries within a taxonomically complex, cryptic species group.
>>>>>>> deb3d9e (update projects)

### What I worked on

I developed and applied a population-scale genomic workflow spanning variant discovery through to population genetic and phylogenomic analyses. Key components included:

<<<<<<< HEAD
- **Whole-genome variant discovery** across hundreds of individuals
- **Population structure analysis** to identify genetically distinct lineages and patterns of admixture
- **Genetic diversity and population differentiation** across river drainages
- **Introgression and gene-flow analysis** to investigate historical exchange between divergent lineages
- **K-mer-based analysis** to complement reference-based approaches and identify genomic patterns without relying entirely on a reference genome
- Integration of genomic results with **geographic, ecological, and historical information** to distinguish natural population structure from patterns associated with human-mediated fish introductions
=======
- **Population structure** — clustering individuals by genetic ancestry to reveal distinct lineages and admixture
- **Introgression analysis** — detecting historical gene flow between genetically distinct clades, some of it linked to human-mediated stocking of fish for angling
- **K-mer-based analysis** — reference-free approaches to complement alignment-based methods, especially useful where taxonomic boundaries are still debated
>>>>>>> deb3d9e (update projects)

### Biological impact

The genomic data revealed substantial geographic structure across *Phoxinus*, while also showing that some observed distributions and patterns of genetic diversity are strongly influenced by **anthropogenic introductions and stocking**. Combining population genomic evidence with historical context helped distinguish naturally structured populations from genetic patterns shaped by human activity {% cite sternberg2025minnows %}.

The analyses also provided a genomic framework for investigating **cryptic diversity and species boundaries** within *Phoxinus*, highlighting how genome-wide data can reveal evolutionary relationships that are difficult to resolve using morphology or traditional genetic markers alone.

### Computational toolkit

<<<<<<< HEAD
**Variant discovery:** Whole-genome sequencing · alignment · joint variant calling · SNP filtering  
**Population genomics:** Population structure · genetic diversity · differentiation · admixture  
**Gene flow:** Introgression · phylogenomic analysis · demographic inference  
**Reference-free genomics:** K-mer analysis  
**Workflow & HPC:** Snakemake · Bash · R · Python · SLURM · SGE

### Publication

Sternberg, N., Bodenheim, A., Oriowo, T. O., Podsiadlowski, L., & Stange, M. (2025). *Human impacts on the distribution and genetic diversity of Eurasian minnows (Phoxinus: Leuciscidae) in the Rhenish Massif.* **Knowledge & Management of Aquatic Ecosystems**, 426, 20. {% cite sternberg2025minnows %}
=======
Related publication: **Sternberg, N., Bodenheim, A., Oriowo, T. O., Podsiadlowski, L., & Stange, M. (2025). Human impacts on the distribution and genetic diversity of Eurasian minnows (Phoxinus: Leuciscidae) in the Rhenish Massif. _Knowledge & Management of Aquatic Ecosystems_, 426, 20.** {% cite sternberg2025minnows %}
>>>>>>> deb3d9e (update projects)
