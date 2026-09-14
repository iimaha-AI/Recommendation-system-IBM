> Historical review. Runtime repairs and current verification are documented in [README](../README.md), section Runtime repair — 2026-09-14.

# Source review — 2026-09-13

## Strength

Four recommendation approaches with bundled interaction data and course checks.

## Findings

Placeholder clone URL, missing documentation links and unsupported all-tests-passed claims; metrics reconstruct the fitting matrix; full all-user similarity is recomputed; random content projection lacks a fixed seed.

## Changes in this pass

README documentation now describes the checked-in source and known limitations. Local environment/cache ignore patterns were added without hiding required datasets or serialized test fixtures. Only confirmed OS metadata and Python bytecode were removed where present. Existing application/model logic is unchanged.

## Remaining work

Keep one canonical IBM project; add held-out ranking evaluation, reliable assertions, deterministic seed and an importable package.

## Portfolio decision

Preferred IBM candidate; compare with recommendation-system before hiding either.

## Validation scope

Tracked-file inventory, Python syntax inspection, notebook JSON/code inspection, and path/schema checks were performed. This is not a claim of a full application, camera, cloud, training, or database integration run. Runtime-specific results are recorded in the account review report. Existing licenses and differing notebook checkpoints are retained. Bulk deletions, privacy changes, data/schema changes and model retraining require a separate decision.

## Observed runtime check

Executed 55 code cells in order in `Recommendations_with_IBM.ipynb`. Result: `analysis_cells_passed`. Analysis was run through IPython with the Agg plotting backend; display-only matplotlib magic and HTML export were excluded. Notebook source and assertions were unchanged. Python 3.12; audit environment used pandas 2.3.3, NumPy 2.5.3, scikit-learn 1.9.1, and pytest 9.1.1. This is an audit environment, not a claim that the original dependency manifest was installed successfully.
