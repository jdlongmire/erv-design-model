# Bibliography revalidation, ERV Design Model whitepapers

Filed in the repository with the completion change it recommends, 2026-11-18 (JD: proceed).

Date: 2026-11-18. Scope: every reference listed in the Primary references of the two curated whitepapers in jdlongmire/erv-design-model: Original Biological Network v0.3 (4 references) and Functional Genomic Architecture v0.1 (5 references; Dupressoir 2009 is shared, so 8 unique works). Method: each DOI resolved against Crossref publisher metadata (authors, year, journal, volume, issue, pages, exact title); the one reference without a DOI (Yuan 2023, cited by PMC link) was resolved through Crossref bibliographic search and its PMC record. In-text citations were also checked against the reference lists: every in-text citation in both papers has a matching entry, and no entry is uncited.

## Verdict

No fabricated, misattributed, or materially wrong references. All 8 works exist, all DOIs resolve to the cited works, and authors, years, journals, volumes, issues, and pages match publisher metadata wherever the whitepapers state them. Two entries are incomplete (missing volume and pages, and in one case the DOI); the completions are supplied below from publisher metadata. One apparent title error was checked and is not an error.

## Per reference results

1. **Dupressoir et al. (2009)**, PNAS 106(29), pp. 12127-12132, doi 10.1073/pnas.0902925106. VERIFIED in full, in both whitepapers. Note: the title as cited, "...endogenous retrovirus-derived, envelope gene", carries a comma after "derived" that looks like a transcription error. It is not: Crossref publisher metadata carries the same comma. Leave as cited.
2. **Johnson and Coffin (1999)**, PNAS 96(18), pp. 10254-10260, doi 10.1073/pnas.96.18.10254. VERIFIED in full.
3. **Lang and Beatty (2000)**, PNAS 97(2), pp. 859-864, doi 10.1073/pnas.97.2.859. VERIFIED in full. Trivial variance only: Crossref capitalizes "The gene transfer agent" after the colon; the whitepaper lowercases it. No action needed.
4. **Yohn et al. (2005)**, PLoS Biology 3(4), e110, doi 10.1371/journal.pbio.0030110. VERIFIED in full.
5. **Doolittle (2013)**, PNAS 110(14), pp. 5294-5300, doi 10.1073/pnas.1221376110. VERIFIED in full. Single author; the in-text form "Doolittle (2013)" is correct.
6. **Graur et al. (2013)**, Genome Biology and Evolution 5(3), pp. 578-590, doi 10.1093/gbe/evt028. VERIFIED in full.
7. **Frost et al. (2023)**, Nature Structural & Molecular Biology, doi 10.1038/s41594-023-00960-6. VERIFIED as cited, INCOMPLETE: the whitepaper omits volume and pages. Publisher metadata: volume 30, issue 4, pp. 527-538. Recommended completion: Frost, J.M. et al. (2023) 'Regulation of human trophoblast gene expression by endogenous retroviruses', Nature Structural & Molecular Biology, 30(4), pp. 527-538. https://doi.org/10.1038/s41594-023-00960-6
8. **Yuan et al. (2023)**, Nucleic Acids Research, cited by PMC link only (PMC10250217). VERIFIED as the cited work, INCOMPLETE: no volume, pages, or DOI given. Publisher metadata: volume 51, pp. 4745-4759, doi 10.1093/nar/gkad109. Recommended completion: Yuan, Y. et al. (2023) 'Endogenous retrovirus-derived enhancers confer the transcriptional regulation of human trophoblast syncytialization', Nucleic Acids Research, 51, pp. 4745-4759. https://doi.org/10.1093/nar/gkad109

## Recommended actions (for JD's call; nothing edited yet)

The two whitepapers are curated files carried byte-for-byte from the source repository, so this report does not edit them. Recommended: a small bibliography completion commit in erv-design-model that (a) completes the Frost 2023 and Yuan 2023 entries as above, and (b) updates the provenance notes in both whitepapers and in the comparative evaluation, which currently say publisher-level revalidation is pending, to record that revalidation was completed on 2026-11-18 with this report as the record. The report itself can be filed in the repo (suggested home: research/audits/, as a bibliography audit) or kept in the programme work files.
