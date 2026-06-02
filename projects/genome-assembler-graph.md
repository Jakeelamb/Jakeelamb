# Genome Assembler Graph

**Browser-native knowledge graph of genome assembly workflows.**

Links:

- Live site: https://jakeelamb.github.io/genome-assembler-graph/
- Repo: https://github.com/Jakeelamb/genome-assembler-graph

## Problem

Genome assembly workflow knowledge is scattered across papers, tutorials, benchmark tables, and tool READMEs. A notes document does not show dependencies: which read types support which tools, which algorithmic modules solve which assembly problems, and where metrics enter the pipeline.

## What I Built

- Static web app for exploring genome assembly workflows.
- Curated JSON graph dataset with typed nodes and source-linked relationships.
- Node classes for assembly goals, genome properties, reads, support data, algorithms, modules, tools, stages, outputs, and metrics.
- Deep links for selected nodes and multi-node views.
- JSON schema validation and graph export paths for later database ingestion.
- Vendored graph runtime so the live site is not dependent on a third-party CDN.

## Technical Decisions

The graph stays intentionally small and typed. The point is not to dump every fact into a hairball. The useful version is one where recursive prerequisite and dependent traversal runs on a clean dependency DAG and every highlighted path tells a coherent workflow story.

## Evidence

The current dataset includes curated paths for tools including hifiasm, Verkko, Flye, LJA, HiCanu, Shasta, and long-read support data paths. The repo includes screenshots, schema validation, publishing instructions, and graph export tooling.

## What This Shows

This project is the interface layer: turning scientific domain complexity into structured data and a browser experience someone else can inspect, share, and extend.
