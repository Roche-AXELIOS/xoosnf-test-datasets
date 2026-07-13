This folder contains the pangenome graph, relevant index files and haplotype information file for the HPRC Pangenome Reference Graph version 1.1 generated with minigraph cactus with GRCh38 as the base.
Known reference errors in GRCh38 have been masked in the graph. Additionally, reference tags have been removed, with paths names having the form `chr1` rather than `GRCh39#0#chr1`. Singleton sequences have been removed from the graph, with each path having occurred in at least 2 of the 90 haplotypes used to generate the pangenome.

All the index files and haplotype information file have been generated using vg v1.70. These index files are compatible for use with vg v1.70

The files are organized as follows:
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.dist - distance index file for the graph
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.fa - FASTA file containing the sequences of the graph
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.hapl - haplotype information file for the graph, required for genome personalization
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.xg - xg index file for the graph
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.gbz - Graph in GBZ format, which is a compressed format for storing pangenome graphs
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.min - minimizer index file for the graph, used for efficient mapping of reads to the graph
hprc-v1.1-mc-grch38.masked.remove_prefix_vg-1.70_indexed.zipcodes - zipcodes index file for the graph, used for efficient mapping of reads to the graph

