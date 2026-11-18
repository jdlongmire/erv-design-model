# Change History

## 2026-11-18 - Programme establishment

- Repository created as a public repository at the direction of James (JD) Longmire, as the primary public programme for ERV Design Model research.
- Charter, README, predictions, methods, and governance structure established.
- 18 research and audit files and 4 tool files curated from `jdlongmire/erv-explanatory-model`, `original-biological-network/`, with provenance in `source-provenance-ledger.md`. Historical revisions separated into `research/history/`.
- No LICENSE or CITATION.cff included: licensing reserved pending the owner's explicit decision.
- Screening at establishment: source tree inventoried (24 files in the source tree including 2 READMEs); content scan for secrets, credentials, private correspondence, and employer material found no hits other than a single false positive on the ordinary word secretion. Source repository was already public.
- Tool check at establishment: all 4 Python tools compile. Unit test not run in the build environment (Biopython and pytest not installed); recorded as not run.

## 2026-11-18 - Source repository renamed under the owner's deprecation SOP

- After the migration above was verified file by file (33 files, blob SHAs matching), the source repository `jdlongmire/erv-explanatory-model` was renamed to `jdlongmire/ztype-erv-explanatory-model` at the owner's direction, marking it as superseded by this programme. GitHub redirects the old address to the new name; its history and files are intact (24 files in its tree at rename).
- Provenance references in this repository to the source path are the path as it stood at curation time, 2026-11-18.
- Firewall disclosure: the verbatim curated whitepapers (OBN v0.1, v0.2, and v0.3) contain a limitations paragraph stating that they draw on a prior BIID working paper in the source repository and explicitly do not import the models, predictions, criteria, or verdicts of the separate WP-038 or P-006 programmes; two audit records name the source branch `research/biid-erv-origin`. No BIID, WP-038, or P-006 file, prediction, or verdict was migrated into this repository. The files are retained verbatim for provenance.

## 2026-11-18 - Pointer sweep: other repos with ERV research paths

At JD's direction, every other repository with ERV research paths was pointed to this repository as the primary programme. Tree scans of 17 candidate repositories were run; most path hits in other repos were substring false positives (reservoir, observational, preserved, intervention, service) and were left alone.

Pointers added, each verified by readback:

- `jdlongmire/ztype-erv-explanatory-model` (source repo): root README (commit ffd697b7) and `original-biological-network/README.md` (commit 3a97c00d) now mark the repo superseded and point here.
- `jdlongmire/christian-designism`: README (commit c3bc9f06), genetics line ERV sub-line (commit 69b7d35d), and the parallel ERV comparison protocol (commit 08eacac2) now record the 2026-11-18 primary programme ruling. Its registers, including P-006 and its 2027-11-15 resolution date, are unchanged, and the pointers carry no model content in either direction.
- `jdlongmire/designed-functional-maturity`: the ERV package exists only on draft PR #53 (branch `research/wp-038-erv-model`); a pointer banner was added to the WP-038 document on that branch (commit 8d5ef927) and a pointer comment posted on PR #53. The PR remains draft and unmerged, with its gates unchanged. DFM master, which has no ERV research path, was not edited.

Left alone, with reasons: `ai-bridge` (its ERV files are historical mail records; the primary scope notice was already filed there on 2026-11-18), and all repos whose only hits were substring false positives or no ERV paths.
