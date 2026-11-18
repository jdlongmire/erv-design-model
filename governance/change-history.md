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

## 2026-11-18 - GitOps closeout

At JD's direction, all work tied to this programme's establishment was landed and every related branch resolved:

- `jdlongmire/designed-functional-maturity` PR #53 (WP-038) was merged to master (squash commit 029148ea) after the missing work-packages index row for WP-038 was added (commit 7eebd36d) and repo-checks passed on that exact head; all four CI jobs passed on the merge commit. The branch `research/wp-038-erv-model` was deleted. WP-038's gates are unchanged by the merge: parity gate HOLD, scoring gate unresolved, parity not established.
- `jdlongmire/christian-designism`: branches `erv-avenues-log` and `p006-foamy-fail`, both verified fully merged into main (zero ahead), were archived to tags `archive/erv-avenues-log` and `archive/p006-foamy-fail` at their tips and deleted.
- `jdlongmire/ztype-erv-explanatory-model`: branches `probe/a`, `probe/b`, `probe/c`, and `research/biid-erv-origin` were archived to tags under `archive/` at their verified tips and deleted. The BIID research files on that branch were never merged to main (its PR #2 was closed unmerged) and are preserved by the archive tag as source record; they are not part of this programme.
- This repository was added to the owner's GitHub triage watchlist on publication.

## 2026-11-18 - Plain-language pass and repository hygiene

At JD's direction, following recommendations filed by thinx-claude through ai-bridge (plain language) and the establishment build report (repository hygiene):

- Plain-language pass on the public files: README and Programme Charter rewritten to lead with the research question, a plain status line, the failure condition, and the distinction between what the programme assumes and what it tests. The Lakatosian parts are renamed in plain words (core commitments, working models, research plan, rules against special pleading, gaining or losing ground), with the technical terms kept once in brackets. A GLOSSARY.md was added. The research, predictions, and methods section guides were lightly revised to match. The curated source files (whitepapers, causal model, comparative evaluation, audits) are unchanged, byte for byte.
- Continuous integration: a GitHub Actions workflow (tools-tests) now compiles the four tools and runs the locus validator unit tests with Biopython installed, on every push and pull request to main. First run passed (commit 21287c5d). The methods guide records this; the establishment note that the test was not run in the build environment stands as the historical record for that date.
- Branch protection on main: pull request required, the Tools tests check required and branch must be up to date, rules enforced for administrators, no force pushes, no branch deletion.
- Not done in this pass, by the owner's reservation: no LICENSE or CITATION.cff (licensing decision still the owner's), no preregistrations yet, and the publisher-level bibliography revalidation flagged in the whitepapers remains queued programme work.

## 2026-11-18 - Programme stance adopted

JD set the programme's approach: design-forward, and skeptical of the consensus model. The programme begins with the explanatory plausibility of design; consensus explanations are critically interrogated on causal sufficiency and historical assumptions; and competing accounts are evaluated on demonstrated explanatory reach, predictive performance, and independently justified assumptions. The stance is stated in the charter (section 1, Programme stance) and summarized in the README. Recorded findings are unchanged by the stance: a result favouring a competing account on specified evidence remains an accounting result on that evidence, not a default.

## 2026-11-18 - Licensing ruled

JD ruled licensing on the recommendation recorded at establishment: the repository is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0), the same pattern as christian-designism. LICENSE (the full Creative Commons text) and CITATION.cff (version 0.1.0, released 2026-11-18) were added, and the README licensing section now states the terms and the citation. The earlier reservation of licensing pending the owner's decision is closed by this entry.

## 2026-11-18 - Cross-linked to the Designed Functional Maturity programme

At JD's direction, this programme and the Designed Functional Maturity (DFM) programme are now cross-linked in both directions. The charter names and links the framework repository, and the README carries a short Wider framework section. The DFM repository links back: an ERV row in its research tracks, a repository map entry, and a Relationship to the ERV Design Model programme section in its README.
