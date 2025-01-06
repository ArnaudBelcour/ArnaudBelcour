Hello!

I am a post-doc in the [MICROCOSME](https://team.inria.fr/microcosme/) team of Inria Grenoble.

## Research interests

My work focuses on modelling the metabolism at different levels (specific metabolic pathways, single organism or environmental communities). My reseach combines knowledge representation and reasoning, DNA sequence analyses and systems biology. The methods I have particiapted in can be found in this GitHub account or in the [AuReMe repository](https://github.com/AuReMe) (owned by the Dyliss team of Inria).

## Modelling metabolism

I participate in the development of several methods and tools to reconstruct and study metabolic networks:

- [mpwt](https://github.com/AuReMe/mpwt): a little multiprocessing wrapper for Pathway Tools to help reconstructing draft metabolic networks at a large-scale.
- [metage2metabo](https://github.com/AuReMe/metage2metabo): a method to compute the producible metabolites by a microbial community and predict the synthetic minimal communities able to produce these metabolites. It relies on [menetools](https://github.com/cfrioux/MeneTools), [miscoto](https://github.com/cfrioux/miscoto), [mpwt](https://github.com/AuReMe/mpwt) and [padmet](https://github.com/AuReMe/padmet).
- [esmecata](https://github.com/AuReMe/esmecata): a method to estimate functions of taxonomic affiliations using comparative genomics of proteomes from UniProt database.
- [pathmodel](https://github.com/pathmodel/pathmodel): a prototype implementing the Metabolic Pathway Drift to predict alternative metabolic pathways.
- [aucome](https://github.com/AuReMe/aucome): a method to homogenise the reconstruction of metabolic networks from genomes of public databases.

## Conversion of file format

- [emapper2gbk](https://github.com/AuReMe/emapper2gbk): a conversion tool to create GenBank file from eggnog-mapper results.

## Singularity recipes

Singularity recipe for: [mpwt with Pathway Tools](https://github.com/AuReMe/mpwt-singularity), [CarveMe recipe](https://github.com/ArnaudBelcour/carveme_singularity) (fork of [cfrioux/carveme_singularity](https://github.com/cfrioux/carveme_singularity)), [UBCG recipe](https://github.com/ArnaudBelcour/singularity_ubcg) and [Circos singularity](https://github.com/ArnaudBelcour/circos-singularity).

I try to answer the issues but my time available for this varies and I can be slow to answer.

