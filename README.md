# RNA_seq_WS
Notes regarding ngs workshop
Author : Swsti


# Overview of Next Generation Sequencing (NGS) and Bioinformatics

1. Introduction to the fundamental concepts of Next Generation Sequencing (NGS) and its role in modern biological research.

2. Topics covered included the different sequencing strategies such as whole genome sequencing, exome sequencing, and targeted gene panels, highlighting how each approach is selected based on coverage, cost, and application.

3. Also explained the basic workflow of NGS experiments, starting from sample preparation and sequencing to the generation of raw sequencing data in FASTQ format. The importance of quality control of sequencing reads, along with the role of bioinformatics tools such as FastQC in assessing data quality.

4.An overview of downstream data analysis steps was provided, including read alignment to reference genomes, gene expression analysis in RNA-seq experiments, and interpretation of results. The challenges associated with handling large-scale sequencing data, including data storage, computational infrastructure, and data security, were also addressed.

5. Highlighted the wide range of applications of NGS and bioinformatics in areas such as disease diagnosis, cancer genomics, pharmacogenomics, plant and microbial genomics, and environmental biotechnology.



# finding public biological datasets

1. using NCBI
2. using GEO accession numbers


# workflow used for rna-seq analysis using galaxy

1. download the data
2. open galaxy
3. upload data into galaxy


# Uploaded FASTQ file to Galaxy

1. Ran FastQC for quality control analysis
2. Observed quality metrics such as per-base sequence quality,
  GC content, and adapter content


# Key observations:

1.Quality scores vary across read length
2. GC content distribution reflects sample composition
3. FastQC helps assess whether preprocessing is required
