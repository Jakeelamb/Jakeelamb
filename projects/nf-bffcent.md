# nf_BFFcent

**Variant discovery and population-genomics workflow for black-footed ferret samples.**

Link: https://github.com/Jakeelamb/nf_BFFcent

## Problem

Variant discovery pipelines become fragile when read groups, reference indexes, interval-level GVCFs, sample maps, and joint genotyping outputs are handled manually. The failure mode is silent metadata drift.

## What I Built

- Reference index checks.
- FASTQ metadata and read-group extraction.
- Quality control and trimming with FASTP.
- Alignment with BWA-MEM2.
- SAM/BAM processing with Samtools.
- Per-sample, per-interval GATK HaplotypeCaller GVCFs.
- GVCF concatenation with bcftools.
- Sample-map generation for joint genotyping.
- Population-genomics outputs with PLINK2 PCA.

## Technical Decisions

The workflow extracts read-group information from FASTQ headers and carries it into alignment. Sample identity is not bookkeeping. It is the difference between a trustworthy variant callset and an expensive mistake.

## Evidence

The public README documents the pipeline stages, requirements, sample file format, reference genome handling, SLURM execution, process-specific resource parameters, and output directory contract.

## What This Shows

This is biological data infrastructure at the variant-discovery layer: preserve sample identity, reference context, intermediate outputs, and final statistics across many compute-heavy steps.
