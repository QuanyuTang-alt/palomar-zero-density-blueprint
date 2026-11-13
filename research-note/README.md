# Research-style study note

This folder is the revised, human-readable exposition of **Mark Lewko's registered argument**, not an original research submission or an author-approved manuscript. It is separate from the earlier source-faithful blueprint in the repository root.

## Files to read

- **`zero-density-note.pdf`** — compiled English reading copy.
- **`zero-density-note.tex`** — complete single-file English LaTeX source, including its TikZ dependency diagram and bibliography. No abstract, MSC classification or keywords.
- **`修改说明与逐项审查.md`** — Chinese explanation of the changes, with a separate assessment and disposition for all **64 numbered mathematical items** in the original blueprint.
- `proposition-audit.json` — machine-readable version of the same 64-item review.
- `citation-audit.json` — all 12 bibliography entries, authoritative metadata evidence, live citation contexts and scope of support.
- `source-ledger.json` — the original blueprint's 99 source-correspondence paragraphs and their original locations.
- `validation.json` — compilation, cross-reference, equation/citation coverage and PDF checks, with their limitations.
- `literature/crossref-records.json` — preserved authoritative DOI metadata used in checking the bibliography. One examined but unused candidate is kept in this research record; it is not an extra bibliography item.
- `SHA256SUMS` — checksums for this version's retained files.

## What changed mathematically

The revised exposition retains the exact four endpoint statements, the bounded coefficient hypothesis, real polynomial lengths, closed height cutoffs, analytic multiplicities, actual time-support length `5T`, deletion rather than clipping, and the strict rightmost boundary `sigma > 3/4`.

The main proofs have been expanded at several points: smoothing normalization without dividing by mask mass; the finite spectral witness's weighted Hölder inequality and trace-class compression limit; primitive-ratio Fourier sampling; Gamma-tail and local fourth-moment detection; fixed coefficient families; and the weighted long-count reduction to a physical twelfth moment.

The ordinary fourth moment, the twelfth moment, the discrete high-value theorem and the Ingham branch now use precisely identified classical results. Their relevant normalization and constant-selection details remain explained. The global coefficient is obtained more economically by dominating the already-established full curve and applying the same finite-grid argument. This is an explicitly documented reorganization, not a claim to follow the original global Lean proof step by step.

The earlier Type-II polynomial identity and negative-scale telescoping corrections remain in force. A further explanation was corrected: at the interior split `n = 2^j`, the smooth dyadic weight need not vanish. Two half-open dyadic intervals split the sum exactly, with that endpoint counted once. The four Fourier-mask integrals are also distinguished from the disjoint partition before cyclic reindexing.

## Honest proof boundary

This note is a full paper-style exposition, **not a foundational reproof of every lemma in the entire registered source tree**. The unequal/mixed affine recurrence, retained-cubic Poisson and radial estimates, reflection row estimate, separate integer high-threshold large-values theorem, smooth single-zero Mellin cover and some coarse explicit zeta-growth bounds remain attributed analytic results from the registered development. Their interfaces and uses are described, and the audit identifies these cases rather than calling them independently reproved.

No new full Lean kernel replay, author endorsement, independent human peer review or exhaustive novelty certificate is claimed. Classical results already cover portions of the displayed density curve; in particular, Kerr's Theorem 6 covers the rightmost expression for `sigma >= 23/29`. Comparison of global coefficients is not a statement of pointwise optimality.

## Build

With Tectonic:

```sh
tectonic --untrusted --keep-logs zero-density-note.tex
```

Or run `pdflatex -interaction=nonstopmode -halt-on-error zero-density-note.tex` twice with the packages in the preamble installed. No shell escape, external figure or separate bibliography file is required.

## Provenance

The source is Palomar entry **PALOMAR-2026-10-11-000010, version 1**, at registered revision `ee2a8a32be49a4f73c7386e9dffdea24d7e3d8c0`:

https://palomar-registry.org/entry?id=PALOMAR-2026-10-11-000010&version=1

The complete pinned upstream source, its original licenses and third-party notices remain in `../pinned-source/`. No upstream source files were patched. Mathematical results are attributed to their original authors.
