# nf_denovo_transcriptome

**Nextflow pipeline for de novo eukaryotic transcriptome assembly.**

Link: https://github.com/Jakeelamb/nf_denovo_transcriptome

## Problem

Transcriptome assembly work becomes fragile when sample handling, read trimming, pair validation, normalization, assembly, and completeness checks live as disconnected commands. You may get an assembly, but you cannot easily trust or reproduce it.

## What I Built

- Sample-sheet-driven Nextflow workflow for paired-end RNA-seq.
- Trimming with `fastp`.
- Read-pair and quality checks with `seqkit`.
- Multi-sample read merging.
- Digital normalization with BBNorm.
- Assembly with either rnaSPAdes or Trinity.
- Completeness assessment with BUSCO.
- SLURM-ready profile for larger runs.

## Technical Decisions

Normalization and assembly are explicit pipeline stages rather than hand-run commands. That gives every run a reviewable shape: what went in, what was filtered, what was normalized, what assembled, and how completeness was checked.

## Evidence

Used in the context of a mosquito RNA-seq resource with 100+ individuals and more than 2 TB of raw reads.

## What This Shows

This is sample-to-output workflow engineering. It is directly relevant to teams building reusable biological data infrastructure because the point is not a single assembly; the point is a repeatable path.
