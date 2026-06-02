# Cell-size Segmentation

**Traceable microscopy object measurement workflow.**

This work currently lives in local project history rather than a polished public repo. Do not make it the first public link until the cleaned run bundle and README are ready.

## Problem

Segmentation output is not useful if nobody can trace a measurement row back to the image, tile, mask, settings, and quality-control view that produced it. Pretty masks are not enough.

## What I Built

- Manifest-driven wrapper for cell-size segmentation runs.
- Two brightfield backends: rule-based nucleus-first watershed segmentation and a Cellpose model-based path.
- Cell-level and nucleus-level measurement paths with masks, overlays, per-image CSVs, tile manifests, logs, and summary figures.
- Traceability target linking source image, manifest row, measurement CSV, label mask/object map, overlay, and downstream analysis row.

## Technical Decisions

The important direction is a single canonical output contract rather than ad hoc experiment folders. Completed runs should preserve manifests, settings snapshots, per-object measurements, masks, overlays, and logs under a predictable run root.

## Evidence

Scale: 16,500+ specimen images routed through segmentation and measurement work. The current local documentation names the canonical inputs, scripts, output locations, traceability plan, reproducibility rules, and known gaps.

## What This Shows

This is image-derived biological data engineering: object identity, provenance, QC artifacts, and downstream usability.
