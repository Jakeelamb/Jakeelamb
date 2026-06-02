# bbnorm-rs

**Rust implementation of BBTools BBNorm-style read-depth normalization.**

Links:

- Repo: https://github.com/Jakeelamb/bbnorm-rs
- Crate: https://crates.io/crates/bbnorm-rs

## Problem

BBNorm is useful because it is practical and trusted. Porting that kind of tool is not mainly a syntax exercise. The hard part is preserving behavior where users expect it while exposing enough structure to test, profile, and improve the implementation.

## What I Built

- FASTA/FASTQ input and output, including gzip.
- Single-end, paired two-file, explicit interleaved, and auto-interleaved routing.
- BBTools-style `key=value` CLI parsing and common aliases.
- Exact and bounded count-min k-mer counting.
- Histogram, read-depth histogram, peak output, and side-output paths.
- Java-parity integration tests against a vendored BBTools reference snapshot.
- Benchmark harnesses that record git state, tool versions, input metadata, commands, raw run data, timings, RSS, and histogram drift.

## Technical Decisions

The project keeps correctness claims separated:

- Covered exact modes should match the Java oracle byte-for-byte.
- The high-throughput bounded approximate lane is allowed to trade byte-stable collision order for speed and memory, but it has to report drift instead of pretending to be identical.

That distinction matters. Fake parity is worse than no parity.

## Evidence

Local 500k paired-human lane, three-repeat median, `bits=16`, `threads=8`, null read outputs, `hist` and `rhist` enabled:

| Tool | Wall time | Peak RSS |
| --- | ---: | ---: |
| Java BBNorm | 7.814 s | 3.39 GiB |
| bbnorm-rs fast lane | 6.769 s | 2.79 GiB |

Result: Rust was 13.4% faster and used 17.8% less peak RSS on this lane.

## What This Shows

This is the strongest systems-engineering signal in my public GitHub right now: read the existing tool, preserve the important semantics, measure honestly, and only then claim speed.
