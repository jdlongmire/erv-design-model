# Methods

Reproducible screening and assembly aware locus audit method, at programme level. Tool code is in `../tools/`.

## Locus audit standard

A locus may be called orthologous only when the record shows:

- Both flanking regions align one to one in the compared assemblies.
- An element of the same family sits between the flanks.
- Insertion boundaries and, where callable, target site duplications are reported.
- Shared derived changes inside the element are reported separately from family similarity.

A locus is called empty only when both flanks align one to one and are contiguous with no element between them. Any other case is unresolved. Unresolved is reported as its own column and is never folded into present or empty.

Family or subfamily similarity alone is not an orthologous insertion call.

## Screening

- Screen symmetrically: the same detection sensitivity and species coverage for every direction of a distribution claim (for example both A and B patterns in the bidirectional matrix).
- Pin every assembly, annotation, and data release version in the run record. Coordinates from different assembly coordinate systems must not be mixed; provenance per sequence is logged.
- Every retrieved interval must pass a flank homology control before analysis.
- Preserve negative and failed searches in the audit record.

## Tools

Tools are copied unchanged from the source repository, with provenance in `../governance/source-provenance-ledger.md`:

- `tools/assembly_manifest.py`
- `tools/locus_validator.py` - requires Biopython (`Bio`). At programme establishment the module compiles under Python 3, but its unit test was not run in the build environment because Biopython and pytest were not installed there. That is recorded as not run, not as a pass.
- `tools/screen_erv_lineages.py`
- `tools/test_locus_validator.py`

Install dependencies in your own environment before running the test, and record the versions used in the run record.
