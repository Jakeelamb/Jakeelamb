# Desmognathus TE Analysis

**Comparative transposable-element evolution analysis across 34 salamander species.**

Link: https://github.com/Jakeelamb/Desmognathus_TE_analysis

## Problem

Comparative repeat analysis is easy to turn into a folder of fragile scripts. The real problem is keeping species IDs, repeat classifications, phylogenies, derived tables, statistics, and figures aligned across many analysis stages.

## What I Built

- Processing scripts for dnaPipeTE, RepeatMasker, ectopic recombination analysis, divergence, diversity metrics, LTR insertion age estimation, and tree cleaning.
- R analysis scripts for PCA, phylogenetic PCA, phylogenetic signal, trait evolution, PGLS, and PERMANOVA.
- Central path configuration for inputs, interim outputs, canonical tables, and figures.
- Visualization scripts and derived tables for class, order, and superfamily-level summaries.

## Technical Decisions

The project uses staged scripts rather than a single opaque monolith. That keeps each biological question inspectable: expected inputs, expected outputs, and the transformation between them.

## Evidence

The public README documents a 12-stage workflow, environment setup, required input data, processing commands, and generated output locations. Scale: 34 species and roughly 100 Gb of salamander genome data.

## What This Shows

This is the unglamorous middle of computational biology: keeping messy biological data, statistical models, and provenance coherent long enough to produce interpretable science.
