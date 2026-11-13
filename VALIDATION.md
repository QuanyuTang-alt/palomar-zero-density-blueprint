# Validation record

## Deliverable identity

- Entry: PALOMAR-2026-10-11-000010, version 1.
- Source commit: `ee2a8a32be49a4f73c7386e9dffdea24d7e3d8c0`.
- Editable English blueprint: `zeta-density-blueprint.tex`.
- Compiled reading copy: `zeta-density-blueprint.pdf`, 54 pages.
- The TeX line/token counts in `validation.json` refer to the latest revision; 43 proof environments and 99 source-correspondence paragraphs are retained. These counts are descriptive, not a measure or certificate of mathematical completeness.

## Checks performed

1. The upstream clone is at the exact registered revision, with a clean working tree.
2. Registered `Challenge.lean` SHA-256 matches `b0feb005a241a3d2da02def8c8ae83cb9db2e743b6c5679245a5c22775e7675a`.
3. Registered `Solution.lean` SHA-256 matches `8b3e9e2dea3baa6c9db288f6d6bc64662b8fd1f14525599e99abb7fd9bc9f7cb`.
4. All 899 entries in the upstream `SHA256SUMS` were verified without mismatches. The Git archive retains 900 tracked files, including that checksum file.
5. The local module import closure of `Solution.lean` contains 824 modules. This is not the minimal declaration/proof-term dependency closure. The inventory is preserved in `local-module-closure.json`.
6. All explicit LaTeX internal references resolve to unique labels. No unexpected control characters remain. Environments are balanced.
7. Source-correspondence names were checked against source declarations/modules; `source-map.json` retains the matching locations, including ambiguous leaf-name matches where applicable.
8. The full TeX was compiled with portable Tectonic, without shell-escape. Exit code: 0. Required reruns completed.
9. Final compile log: no overfull boxes, undefined references, multiply-defined labels, missing-character warnings, or LaTeX errors. Three minor underfull-box notices and the harmless `inputenc`-ignored-by-XeTeX notice remain. The build log is retained as `latex-build.log`.
10. All PDF pages were checked for extractable text and words outside page boundaries. No blank pages or out-of-page words were found. Representative pages were rendered and visually inspected for equation legibility, page structure, and source references. This is not a claim that every page received independent visual or mathematical peer review.
11. Exact rational endpoint values were checked: `f(1/2)=1`, `f(9/13)=12/17`, `f(5/7)=9/14`, `f(3/4)=9/16`, and `f(1)=0`.
12. Source-level mathematical checks retained real source lengths, natural floors, positive- and negative-ordinate count conventions, actual analytic multiplicity, the cutoff length `5T`, the `1/25` weak mollifier moment loss, strict `sigma>3/4`, and the distinct global-uniform proof route.

## An ambiguity resolved during audit

The literal source expression `min eta 1/20` in the native fourth-moment producer is parsed by Lean as `(min eta 1)/20`, not as `min eta (1/20)`. Thus the actual selected parameter is at most `eta/20` and the required `7q <= eta` holds. The human-readable text uses explicit parentheses. Application precedence was checked with the installed Lean executable on a small arithmetic parsing probe. This probe was not a replay of the registered Lean version and does not claim to recheck the whole theorem. No upstream source change was made.

## Mathematical coverage and limits

The four registered endpoint consumers are reconstructed in English mathematical order. The text supplies their definitions, exact statements, intermediate scale and exponent lemmas, detailed consumer proofs, detector-family construction, zero-multiplicity restoration, and uniform-constant arguments. It also expands finite affine/cubic budget assembly, amplifier range construction, ratio sampling, peak/packet aggregation and the native fourth-to-twelfth moment assembly.

Imported analytic results are explicitly labeled and precisely stated at the interface being used. They are proved dependencies in the source, not added endpoint assumptions. The document does **not** expand every auxiliary proof in the complete local module closure: foundational measure theory, Gamma-ratio and contour estimates, the native stationary Atkinson producer, and the full native classical medium-reflection machinery retain explicitly delimited imported status. The complete fixed source archive preserves those proofs for further expansion.

No fresh complete Lean build or independent kernel replay was run for this informal reconstruction. The registry's verification metadata and upstream `VERIFICATION.json` are preserved separately and are not described as checks performed in this task. No human peer review, author approval, or novelty certification is claimed.

## Corrected Type-II scalar identity

A transcription error in the short-window Type-II exponent comparison was corrected against `WeakShortDensity.weak_short_typeII_exponent_le`. The scaled difference is exactly

`25(7σ+3)[18(1−σ)/(7σ+3) − (2−2σ+1/25)] = 350σ²−657σ+297`.

The source's nonpositive-factor witness is retained through the exact decomposition

`350σ²−657σ+297 = (25/14)(7σ−5)(28σ−33) + (11/2)σ + 33/14`.

On the short interval the product is nonnegative and the remaining terms are positive. At `σ=5/7` the scaled difference equals `44/7`. Exact rational arithmetic also rechecked the adjacent mean-value and closed-upper-window difference identities. The erroneous `(7σ−5)(50σ−69)` expression is absent from the corrected TeX. The PDF, source-map line locations, checksums, ZIP and private remote repository are refreshed together.

## Archive safeguards

The archival repository includes only this task's final materials, the correct immutable registry record, and the exact registered upstream source tree. No credentials, session traces, alternate-entry working files, or unrelated project materials are included. GitHub visibility and pushed contents are checked separately at upload completion.
