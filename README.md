# Personal Nextflow pipelines

## FSHD
The FSHD pipeline is for quickly determining the repeat number of DUX4 of an FSHD patient and its methylation level.
Dependencies:
  - Samtools
  - makeblastdb
  - blastn
  - modkit
  - Python
  - pandas (Python)
  - plotnine (Python)

## fq2bam
The fq2bam pipeline is used to create a sorted and indexed BAM file from paired FASTQ sequence files, following GATK best practices. The reference genome needs to be indexed using bwa.
