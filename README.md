# Hi, I'm Jacob

Bellingham, WA | Computational biology systems engineer | Rust-first bioinformatics, sequencing workflows, and traceable analysis systems

I build tools for biological data that needs to stay fast, reproducible, and explainable after the first successful run. Rust for the hard parts. Python, R, and Nextflow where they are the right glue.

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![Nextflow](https://img.shields.io/badge/-Nextflow-24A148?style=flat-square)
![Bioinformatics](https://img.shields.io/badge/-Bioinformatics-194F45?style=flat-square)
![Genomics](https://img.shields.io/badge/-Genomics-8F3F2F?style=flat-square)
![HPC](https://img.shields.io/badge/-HPC-244C70?style=flat-square)
![Reproducibility](https://img.shields.io/badge/-Reproducibility-AA7A2E?style=flat-square)

## Start Here

- **[bbnorm-rs](https://github.com/Jakeelamb/bbnorm-rs)** - Rust implementation of BBTools BBNorm-style read-depth normalization with Java-parity tests, bounded-memory k-mer counting, and benchmark artifacts.
- **[genome-assembler-graph](https://jakeelamb.github.io/genome-assembler-graph/)** - browser-native knowledge graph for genome assembly workflows, tools, modules, inputs, outputs, metrics, and source-linked paths.
- **[Desmognathus_TE_analysis](https://github.com/Jakeelamb/Desmognathus_TE_analysis)** - 34-species comparative transposable-element evolution analysis with repeat classification, divergence metrics, PGLS, PERMANOVA, BM/OU modeling, and figures.
- **[nf_denovo_transcriptome](https://github.com/Jakeelamb/nf_denovo_transcriptome)** - Nextflow RNA-seq workflow for trimming, QC, sample merging, digital normalization, assembly, and BUSCO completeness checks.
- **[nf_BFFcent](https://github.com/Jakeelamb/nf_BFFcent)** - variant discovery and population-genomics workflow with FASTP, BWA-MEM2, GATK GVCFs, joint genotyping, and PCA.
- **[BioDex](https://github.com/Jakeelamb/BioDex)** - terminal-native species atlas for taxonomy lookup, organism notes, genome stats, and cached field-guide style browsing.
- **[cellprofiler](https://github.com/Jakeelamb/cellprofiler)** - active salamander brightfield workflow for CellProfiler-style cell and nucleus measurement pipelines.

## Current Projects

### Rust Bioinformatics Core

- **[bbnorm-rs](https://github.com/Jakeelamb/bbnorm-rs)** - Rust port of practical read-depth normalization; parity first, speed second, fake numbers never.
- **[crabp](https://github.com/Jakeelamb/crabp)** - fast, low-level short-read preprocessing in Rust.
- **[spades-rs](https://github.com/Jakeelamb/spades-rs)** - benchmark-first Rust rewrite workspace for SPAdes 4.2.0 components.
- **[hifiasm-rs](https://github.com/Jakeelamb/hifiasm-rs)** - Rust implementation work aimed at long-read assembly performance against hifiasm and hifiasm-UL.
- **[hox-core](https://github.com/Jakeelamb/hox-core)** - high-performance single-cell and long-read bioinformatics tooling.
- **[bio_format_speed](https://github.com/Jakeelamb/bio_format_speed)** - small reproducible checks for biological file-format overhead.
- **[motif_graph_explore](https://github.com/Jakeelamb/motif_graph_explore)** - high-performance genomic motif complexity analysis using assembly-theory ideas.
- **[orbweaver](https://github.com/Jakeelamb/orbweaver)** - compact grammar-derived motif graphs from genomic FASTA files.

### Genome Assembly And Sequence Models

- **[genome-assembler-graph](https://github.com/Jakeelamb/genome-assembler-graph)** - interactive reference map of assembly workflow logic, tool roles, inputs, outputs, and metrics.
- **[assembly-lm-prior](https://github.com/Jakeelamb/assembly-lm-prior)** - real-data experiments testing whether sequence models can act as local path priors for assembly.
- **[genome-vision](https://github.com/Jakeelamb/genome-vision)** - Rust-first prototype for deterministic visual representations of raw genomic sequence.
- **[Raptor](https://github.com/Jakeelamb/Raptor)** - parallel graph-based RNA-seq assembler research work.

### Sequencing Pipelines

- **[nf_denovo_transcriptome](https://github.com/Jakeelamb/nf_denovo_transcriptome)** - sample sheet to assembled transcriptome: FASTQ QC, read pairing, merge, normalization, assembly, and BUSCO.
- **[nf_BFFcent](https://github.com/Jakeelamb/nf_BFFcent)** - population-genomics workflow carrying sample identity through read groups, alignment, interval GVCFs, joint genotyping, and PCA.
- **[Repeatome_builder](https://github.com/Jakeelamb/Repeatome_builder)** - early repeat-library assembly workflow work for non-model organisms.
- **[Mobile_DNA_Sim](https://github.com/Jakeelamb/Mobile_DNA_Sim)** - simulation work for transposable-element mobility and genome-size effects.

### Comparative Genomics And Evolution

- **[Desmognathus_TE_analysis](https://github.com/Jakeelamb/Desmognathus_TE_analysis)** - comparative TE analysis across 34 salamander species with phylogenetic and ecological modeling.
- **[Heat_shock_protein_selection_analysis](https://github.com/Jakeelamb/Heat_shock_protein_selection_analysis)** - master's research repository for heat-shock protein orthogroup selection analysis across fish species.
- **[TE_dilution_simulation](https://github.com/Jakeelamb/TE_dilution_simulation)** - TE mobility and genome-level dilution simulation work.
- **[Earth_sequencing_disarity](https://github.com/Jakeelamb/Earth_sequencing_disarity)** - React dashboard for visualizing sequencing coverage gaps across the tree of life.
- **[organism-id-genome-stats](https://github.com/Jakeelamb/organism-id-genome-stats)** - image-based organism identification plus NCBI genome-stat lookup and nearest sequenced relative fallback.

### Microscopy, Image Analysis And Annotation

- **[cellprofiler](https://github.com/Jakeelamb/cellprofiler)** - trimmed active salamander brightfield analysis workflow for cell and nucleus measurements.
- **[gemma4-sam31-app](https://github.com/Jakeelamb/gemma4-sam31-app)** - local image-analysis app for object review and model-assisted microscopy workflows.
- **[data_labler](https://github.com/Jakeelamb/data_labler)** - focused labeling tool for pattern classification workflows.

### Scientific Interfaces And Research Tools

- **[BioDex](https://github.com/Jakeelamb/BioDex)** - terminal species atlas: taxonomy browser, cached research notebook, and genome-stat lookup.
- **[TE_visualization](https://github.com/Jakeelamb/TE_visualization)** - Three.js visualization of transposable elements moving across Drosophila chromosomes.
- **[SWATCH](https://github.com/Jakeelamb/SWATCH)** - Slurm job monitoring tool for HPC work.
- **[Slurm_Watch](https://github.com/Jakeelamb/Slurm_Watch)** - Slurm watcher experiments and CLI tooling.
- **[land_finder](https://github.com/Jakeelamb/land_finder)** - ranked inbox for land that can support an organic vegetable farm, homestead, and project workspace.

### Finance, Markets And Local Data

- **[sabertooth](https://github.com/Jakeelamb/sabertooth)** - Rust-first supply/demand zone trading system with one execution codepath for live and backtest.
- **[sabertooth-strategy-lab](https://github.com/Jakeelamb/sabertooth-strategy-lab)** - research and benchmark lane for trading strategy development.
- **[sabertooth-backtest-research](https://github.com/Jakeelamb/sabertooth-backtest-research)** - backtest-focused research workspace for Sabertooth ideas.
- **[sabertooth-live-dynamic-integration](https://github.com/Jakeelamb/sabertooth-live-dynamic-integration)** - live/shadow integration branch for broker-connected execution work.
- **[crypto_momentum_lab](https://github.com/Jakeelamb/crypto_momentum_lab)** - crypto-native momentum and pump/exhaustion strategy research.
- **[crypto-arbitrage](https://github.com/Jakeelamb/crypto-arbitrage)** - crypto arbitrage experiments.
- **[public_financial_data_scrape](https://github.com/Jakeelamb/public_financial_data_scrape)** - Rust-first pipeline for collecting public financial and macroeconomic data into a local database.

### Learning And Systems Practice

- **[learn_go](https://github.com/Jakeelamb/learn_go)** - focused Go learning project with emphasis on low-level systems work, DNA packing, and assembly escape hatches.
- **[asm-lessons](https://github.com/Jakeelamb/asm-lessons)** - assembly language practice and notes.
- **[neural_net_sd](https://github.com/Jakeelamb/neural_net_sd)** - isolated experiment harness for training small neural value models.

## Project Notes

Short case studies: problem, system, tradeoffs, evidence, and what the project shows.

- **[bbnorm-rs: porting BBNorm without fake parity](projects/bbnorm-rs.md)**
- **[genome-assembler-graph: assembly workflows as graph data](projects/genome-assembler-graph.md)**
- **[nf_denovo_transcriptome: RNA-seq workflow shape](projects/nf-denovo-transcriptome.md)**
- **[Desmognathus_TE_analysis: 34-species comparative genomics](projects/desmognathus-te-analysis.md)**
- **[nf_BFFcent: sample identity through variant discovery](projects/nf-bffcent.md)**
- **[cell-size segmentation: object-level microscopy provenance](projects/cell-size-segmentation.md)**

## GitHub Activity

![GitHub Contribution Graph](https://ghchart.rshah.org/Jakeelamb)

## What I'm Doing

- Cleaning public repos so the README claims match the actual system state.
- Moving bioinformatics code toward a stronger rule: every output should be traceable to input data, parameters, code, and run context.
- Turning one-off research scripts into small tools with tests, benchmarks, and honest failure modes.
- Writing project notes that explain engineering decisions instead of just listing domain keywords.

## Latest Writing

- **[bbnorm-rs project note](projects/bbnorm-rs.md)** - porting BBNorm without fake parity.
- **[genome-assembler-graph project note](projects/genome-assembler-graph.md)** - assembly workflows as graph data.
- **[Desmognathus_TE_analysis project note](projects/desmognathus-te-analysis.md)** - 34-species comparative genomics.
- **[cell-size segmentation project note](projects/cell-size-segmentation.md)** - object-level microscopy provenance.

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Jakeelamb)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jakelamb74@gmail.com)

---

### Recognition

- PhD researcher building bioinformatics systems, comparative genomics analyses, and performance-aware scientific tools.
- Strongest public signals: `bbnorm-rs`, `genome-assembler-graph`, `Desmognathus_TE_analysis`, `nf_denovo_transcriptome`, `nf_BFFcent`.
- This profile is intentionally a catalog. The first screen tells people where to start; the rest is organized by what each tool does.
