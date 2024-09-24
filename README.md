# qdnaseq_cuh_glh

This repo contains several script to run qDNASeq tool. Each script has it's own purpose which will be described below.

## estimate_copy_number.R

This script is used to estimate the copy number of the target region. It takes as input a bam file and a selected bin size to analyse each loci. The output includes a .png file and .tsv file from both the qDNAseq and ACE algorithms with the copy number profiles for each region. qDNAseq provides estimations of normalised copy number
profiles and ACE uses the normalised copy number profiles to estimate the absolute copy number across each bin size.