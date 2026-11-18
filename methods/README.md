# Methods

How the screening and location audits are run so that the work can be repeated. Tool code is in `../tools/`.

## Location audit standard

A location may be called orthologous (the same insertion at the same location in the compared species) only when the record shows:

- Both flanking regions align one to one in the compared genome assemblies.
- An element of the same viral family sits between the flanks.
- Insertion boundaries and, where they can be determined, target site duplications are reported.
- Shared derived changes inside the element are reported separately from family similarity.

A location is called empty only when both flanks align one to one and are joined with no element between them. Any other case is unresolved. Unresolved is reported as its own category and is never folded into present or empty.

Family or subfamily similarity alone is not enough to call an insertion orthologous.

## Screening

- Screen symmetrically: the same detection sensitivity and species coverage for every direction of a distribution claim (for example both directions of the pattern in the bidirectional evidence matrix).
- Record the exact version of every genome assembly, annotation, and data release used in a run. Coordinates from different assembly coordinate systems must not be mixed, and the source of every sequence is logged.
- Every retrieved interval must pass a flank similarity control before analysis.
- Preserve negative and failed searches in the audit record.

## Tools

Tools are copied unchanged from the source repository, with their origin recorded in `../governance/source-provenance-ledger.md`:

- `tools/assembly_manifest.py`
- `tools/locus_validator.py` - requires Biopython (`Bio`).
- `tools/screen_erv_lineages.py`
- `tools/test_locus_validator.py`

The tools' unit tests run automatically on every change to this repository (GitHub Actions workflow `tools-tests`), with Biopython installed there. At programme establishment the test had not been run in the build environment, because Biopython was not installed there; that was recorded as not run, not as a pass. The first automated run, on 2026-11-18, passed. If you run the tools locally, install the dependencies in your own environment first and record the versions used in the run record.
