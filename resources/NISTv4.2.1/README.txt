This directory contains data from the Genome in a Bottle (GIAB) project. It contains the following resources:

- `high_confidence`: A set of high-confidence BED files for the GIAB samples. They are obtained by taking the GIAB benchmark regions and removing the ground truth germline variants. Since these regions are not expected to contain germline variants, mismatches in these regions would indicate sequencing errors and can be used to evaluate sequencing error rates.
- `truth`: A set of VCF files containing the ground truth germline variants for the GIAB samples. These variants are used to evaluate the accuracy of variant calling pipelines and to train machine learning models for germline variant calling.
- `train`: A set of BED files containing the training regions. These regions contain the benchmark regions on chromosomes 1-3 for the GIAB samples. They are used to train machine learning models for germline variant calling.
- `test`: A set of BED files containing the test regions. These regions contain the benchmark regions on chromosomes 4-22 for the GIAB samples. They are used to evaluate the performance of machine learning models for germline variant calling trained on the training regions.
- `eval`: A set of BED files containing the evaluation regions. These regions are the same as the GIAB benchmark regions for the GIAB samples. They are used to evaluate the performance of pretrained machine learning models for germline variant calling.

The GIAB data is available at: https://ftp-trace.ncbi.nlm.nih.gov/ReferenceSamples/giab/release/
