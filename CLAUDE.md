# Crucible Examples

## Purpose

Example configurations for running benchmarks with crucible. This repo is a reference for users learning how to construct run files and explore results.

## Structure

| Directory | Purpose |
|-----------|---------|
| `runfile/` | Modern runfile-based examples (the current approach) |
| `legacy/` | Older-style examples using separate parameter files (preserved for reference) |
| `doc/` | Documentation on querying results and re-indexing |
| `utils/` | Helper scripts (e.g., dynamic runfile generation) |

## Conventions

- New examples should use the runfile format in `runfile/`
- Each benchmark subdirectory should include a README explaining usage
- Run files are JSON and follow the rickshaw run schema
- Primary branch is `main`
