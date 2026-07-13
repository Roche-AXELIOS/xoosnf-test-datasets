This folder contains the pangenome graph, relevant index files and haplotype information file for the HPRC Pangenome Reference Graph version 1.1 generated with minigraph cactus with GRCh38 as the base.
Reference tags from CHM13 have been removed in this graph so that you only get alignments to GRCh38.
Sequences occurring less than 9 times have been removed from the graph, with each path having occurred in at least 9 of the 90 haplotypes (10%) used to generate the pangenome.

All the index files have been generated using vg v1.70. These index files are compatible for use with vg v1.70 and PB v4.7

The files are organized as follows:
hprc-v1.1-mc-grch38.d9.re-tagged_vg-1.70_indexed.dist - distance index file for the graph
hprc-v1.1-mc-grch38.d9.re-tagged_vg-1.70_indexed.fa - FASTA file containing the sequences of the graph
hprc-v1.1-mc-grch38.d9.re-tagged_vg-1.70_indexed.xg - xg index file for the graph
hprc-v1.1-mc-grch38.d9.re-tagged_vg-1.70_indexed.gbz - Graph in GBZ format, which is a compressed format for storing pangenome graphs
hprc-v1.1-mc-grch38.d9.re-tagged_vg-1.70_indexed.min - minimizer index file for the graph, used for efficient mapping of reads to the graph
hprc-v1.1-mc-grch38.d9.re-tagged_vg-1.70_indexed.gbwt - FM index for storing paths in the graph
