# xoosnf-test-datasets

Heavily downsampled test datasets for the [xoosnf](https://github.com/Roche-AXELIOS/xoosnf) Nextflow pipeline.
Used for the `small-integration` [nf-test](https://www.nf-test.com/) suite and as sample data in the pipeline README examples.

## Repository structure

```
.
├── bam/                   # Pre-aligned BAM files with samplesheets
├── basecall_fastq/        # Raw basecalled FASTQ reads (before demultiplexing)
├── cram/                  # Pre-aligned CRAM files with samplesheets
├── demultiplexed_fastq/   # Demultiplexed FASTQ reads per sample
└── resources/             # Reference genomes, indexes, and benchmark data
```

## Samples

| Sample | Barcode      |
|--------|--------------|
| HG001  | CTATTGAAGGCT |
| HG002  | GGAGTAACATCC |

## Resources

| Resource | Description |
|----------|-------------|
| GCA_000001405.15_GRCh38 | Human reference genome (GRCh38, no-alt analysis set) with BWA and accessory indexes |
| hprc-v1.1-mc-grch38.d9 (masked, re-tagged) | HPRC pangenome graph v1.1, D9 subset, indexed with vg v1.70 |
| hprc-v1.1-mc-grch38 (masked, unfiltered) | HPRC pangenome graph v1.1, unfiltered, indexed with vg v1.70 |
| NISTv4.2.1 | GIAB benchmark VCFs and high-confidence BED regions for HG001–HG007 |
| gatk-best-practices | gnomAD population allele frequency VCF (hg38) |
| STR | Full short tandem repeat catalog for hg38 |
| alignment_metrics | Additional BED regions (homopolymers, segmental duplications) |