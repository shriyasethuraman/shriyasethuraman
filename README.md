## Shriya Sethuraman, PhD

Computational biologist and bioinformatics scientist. Ten years in genomics,
four of them in industry across clinical diagnostics and cell-therapy
discovery, on a foundation of epigenomics and noncoding RNA.

My work spans microbial and pathogen genomics, transcriptomics, epigenomics,
immunology and cell therapy, and the statistical modeling that ties them
together. In practice that has meant building the curated reference database
and analytical validation behind a regulated clinical sequencing test for
bloodstream infection, including the specificity work that decides whether an
organism can be distinguished from its near neighbors; redesigning a 64-gene
T-cell engineering screen and its low-input readout when the original design
could not be traced back to its conditions; mining public single-cell and bulk
transcriptomic atlases to nominate therapeutic targets in autoimmune disease;
and building probabilistic models that separate real signal from noise in
sparse, repetitive sequencing data.

The thread running through all of it is the same: deciding what the data
actually supports, and being able to defend where the line was drawn.

**Domains**

Microbial and pathogen genomics · transcriptomics (single-cell and bulk) ·
epigenomics and chromatin · immunology and cell therapy · clinical diagnostics
and analytical validation

**Data and methods**

Single-cell and bulk RNA-seq · amplicon and metagenomic sequencing · DNA
methylation and chromatin (WGBS, ChIP-seq, MNase-seq, ATAC-seq) · reference
genome curation and sequence specificity analysis · hidden Markov models and
probabilistic classification · population-genetics modeling · validation
against ground truth in regulated settings

Python · R · Bash · AWS · Docker · Git · HPC

**Repositories**

- [classification-qc](https://github.com/shriyasethuraman/classification-qc) —
  quality checks that flag when taxonomic classification output should not
  be trusted: host DNA surviving depletion, reference-database gaps,
  implausible taxa, contamination spikes
- [PolV_Surveillance](https://github.com/shriyasethuraman/PolV_Surveillance) —
  four-class hidden Markov model classifying every position in a genome as
  real transcript, residual signal, noise, or a previously unrecognized
  low-signal class
  ([PNAS 2020](https://doi.org/10.1073/pnas.2014419117), co-first author)
- [nucleosome_methylation](https://github.com/shriyasethuraman/nucleosome_methylation) —
  establishing the causal direction between DNA methylation and nucleosome
  positioning, rather than the correlation alone
  ([bioRxiv](https://doi.org/10.1101/2020.10.29.359794), co-first author)
- [PolV_transcript_calling](https://github.com/shriyasethuraman/PolV_transcript_calling) —
  identifying noncoding transcripts from immunoprecipitation sequencing data
- [Xchr_inactivation_mouse](https://github.com/shriyasethuraman/Xchr_inactivation_mouse) —
  allele-specific analysis of imprinted X-chromosome inactivation in mouse
  ([Genome Biology 2017](https://doi.org/10.1186/s13059-017-1211-5))

PhD in Bioinformatics, University of Michigan.
