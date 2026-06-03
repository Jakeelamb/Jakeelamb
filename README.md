# Hi, I'm Jake 🦎

PhD researcher building fast bioinformatics tooling in Rust — genome assembly, comparative genomics, and terminal-first workflows for HPC.

![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)

---

## Academic research 🧬

Published and in-progress work from salamander and fish comparative genomics.

| Project | Focus |
| --- | --- |
| **[Desmognathus_TE_analysis](https://github.com/Jakeelamb/Desmognathus_TE_analysis)** | 34-species *Desmognathus* TE evolution — repeat classification, divergence, PGLS, PERMANOVA, BM/OU, LTR age, figures (Python & R). |
| **[Heat_shock_protein_selection_analysis](https://github.com/Jakeelamb/Heat_shock_protein_selection_analysis)** | Master's work on heat-shock protein orthogroup selection across fish lineages. |
| **[TE_dilution_simulation](https://github.com/Jakeelamb/TE_dilution_simulation)** | TE mobility and genome-size dilution modeling. |
| **[TE_visualization](https://github.com/Jakeelamb/TE_visualization)** | Three.js visualization of TE movement across *Drosophila* chromosomes. |

---

## Hox platform — data design & workflow speed 🏗️

Rust-native stack inspired by high-throughput single-cell and alignment frameworks (HoxBio-style columnar I/O, bare-metal saturation, portable indexes).

| Project | Focus |
| --- | --- |
| **[hox-core](https://github.com/Jakeelamb/hox-core)** | Workspace crates (`hox-parse`, `hox-common`, `hox-graph`, `hox-align`, `hox-olap`) for mmap I/O, FM/minimizer indexes, alignment benches, and Arrow/Parquet-oriented outputs. |

---

## Rust ports — legacy tools, measured rewrites 🦀

Benchmark-first ports: parity and honest timings before speed claims.

| Project | Upstream / role |
| --- | --- |
| **[spades-rs](https://github.com/Jakeelamb/spades-rs)** | SPAdes 4.2.0 rewrite workspace with upstream oracles and staged lane promotion. |
| **[hifiasm-rs](https://github.com/Jakeelamb/hifiasm-rs)** | hifiasm / hifiasm-UL stage benchmarks before custom assembler code. |
| **[bowtie2-rs](https://github.com/Jakeelamb/bowtie2-rs)** | Bowtie2 port workspace — lane-by-lane parity before aligner/index core. |
| **[bbnorm-rs](https://github.com/Jakeelamb/bbnorm-rs)** | BBTools BBNorm-style read-depth normalization. |
| **[crabp](https://github.com/Jakeelamb/crabp)** | Low-level short-read preprocessing. |
| **[bio_format_speed](https://github.com/Jakeelamb/bio_format_speed)** | Reproducible checks for biological file-format overhead. |

---

## Original developments — assemblers & motif graphs 🧩

Tools designed here, not ported from a single upstream binary.

| Project | Focus |
| --- | --- |
| **[orbweaver](https://github.com/Jakeelamb/orbweaver)** | Compact grammar-derived motif graphs from genomic FASTA; cross-species comparison with bounded memory. |
| **[Raptor](https://github.com/Jakeelamb/Raptor)** | Parallel graph-based RNA-seq assembler (k-mer extension, isoform graphs, optional GPU, HPC workflows). |
| **[motif_graph_explore](https://github.com/Jakeelamb/motif_graph_explore)** | Genomic motif complexity via assembly-theory-style analysis. |
| **[genome-assembler-graph](https://github.com/Jakeelamb/genome-assembler-graph)** | Interactive map of modern assembly tools, inputs, outputs, and metrics. |
| **[assembly-lm-prior](https://github.com/Jakeelamb/assembly-lm-prior)** | Whether sequence models can act as local path priors for assembly. |
| **[genome-vision](https://github.com/Jakeelamb/genome-vision)** | Deterministic visual encodings of raw genomic sequence (Rust prototype). |

---

## Terminal & HPC utilities 🌿

TUI/CLI tools for the lab machine and Slurm clusters.

| Project | Focus |
| --- | --- |
| **[BioDex](https://github.com/Jakeelamb/BioDex)** | Terminal species atlas — taxonomy browser, cached research notebook, genome-stat lookup. |
| **[bio-terminal](https://github.com/Jakeelamb/bio-terminal)** | DNA/RNA matrix rain and codon-aware helices (`cargo install bio-terminal`). |
| **[SWATCH](https://github.com/Jakeelamb/SWATCH)** | Slurm job monitor — real-time status, SSH auth, dark-theme GUI (`pip install swatch-slurm`). |

> **Note:** [Slurm_Watch](https://github.com/Jakeelamb/Slurm_Watch) is **archived** (Flutter experiment). Active Slurm UI work is **SWATCH** only.

---

## Sequencing pipelines 🌾

| Project | Focus |
| --- | --- |
| **[nf_denovo_transcriptome](https://github.com/Jakeelamb/nf_denovo_transcriptome)** | Sample sheet → QC → merge → normalize → rnaSPAdes/Trinity → BUSCO. |
| **[nf_BFFcent](https://github.com/Jakeelamb/nf_BFFcent)** | Population genomics: read groups → alignment → GVCF → joint calling → PCA. |
| **[Repeatome_builder](https://github.com/Jakeelamb/Repeatome_builder)** | Repeat-library assembly for non-model organisms. |
| **[Mobile_DNA_Sim](https://github.com/Jakeelamb/Mobile_DNA_Sim)** | Transposable-element mobility simulation. |

---

## Microscopy & labeling 🔬

| Project | Focus |
| --- | --- |
| **[cellprofiler](https://github.com/Jakeelamb/cellprofiler)** | Salamander brightfield cell/nucleus measurements. |
| **[gemma4-sam31-app](https://github.com/Jakeelamb/gemma4-sam31-app)** | Local microscopy review with model-assisted workflows. |
| **[data_labler](https://github.com/Jakeelamb/data_labler)** | Pattern-classification labeling UI. |
| **[organism-id-genome-stats](https://github.com/Jakeelamb/organism-id-genome-stats)** | Image-based ID plus NCBI genome stats and nearest-sequenced relative fallback. |

---

## GitHub activity 🌱

![GitHub Contribution Graph](https://ghchart.rshah.org/Jakeelamb)

## Connect 🌲

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Jakeelamb)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jakelamb74@gmail.com)

---
