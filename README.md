Hello!

On this GitHub account, you will find the work I do during several contracts focused on Bioinformatics (either directly on this profile or on the [AuReMe repository](https://github.com/AuReMe), owned by the Dyliss of Inria).

I try to answer the issues but my available time for this is variable and I can be slow to answer.

## Modelling metabolism

I participate in the development of several methods and tools to reconstruct and study metabolic networks:

- [mpwt](https://github.com/AuReMe/mpwt): a little multiprocessing wrapper for Pathway Tools to help reconstructing draft metabolic networks at a large-scale.
- [emapper2gbk](https://github.com/AuReMe/emapper2gbk): a conversion tool to create GenBank file from eggnog-mapper results. 
- [metage2metabo](https://github.com/AuReMe/metage2metabo): a pipeline to estimate the producible metabolites by a microbial community and to estimate the synthetic minimal communitiesable to produce specific metabolites. It relies on [menetools](https://github.com/cfrioux/MeneTools), [miscoto](https://github.com/cfrioux/miscoto), mpwt and [padmet](https://github.com/AuReMe/padmet).
- [esmecata](https://github.com/AuReMe/esmecata): a pipeline to estimate functions of taxonomic affiliations using comparative genomics (with MMseq2), UniProt database and eggnog-mapper.
- [kegg2bipartitegraph](https://github.com/ArnaudBelcour/kegg2bipartitegraph): a little package to create metabolic bipartite graphs from different inputs using KEGG database.

## Singularity recipes

I like Singularity and use it often. I try each time I create a Singularity recipe to make it available:

- [singularity recipe for mpwt with Pathway Tools](https://github.com/AuReMe/mpwt-singularity): you need a Pathway Tools installer to use this recipe.
- [CarveMe recipe](https://github.com/ArnaudBelcour/carveme_singularity): this is a fork of [cfrioux/carveme_singularity](https://github.com/cfrioux/carveme_singularity), that I update when I need it. This recipe requires a cplex installer from IBM.
- [UBCG recipe](https://github.com/ArnaudBelcour/singularity_ubcg): a recipe to use UBCG (Up-to-date Bacterial Core Genes), it requires the files found in the UBCG folder (UBCG.jar, programPath, UBCG.hmm).
- [Circos singularity](https://github.com/ArnaudBelcour/circos-singularity).
