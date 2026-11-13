# Zero-density Lean-to-LaTeX study archive

This is a public study archive of an English, source-faithful mathematical blueprint for Palomar entry **PALOMAR-2026-10-11-000010, version 1**, *Zero-density estimates from an improved large-values bound*. It was initially created privately and made public at the user's request.

A separately revised, research-style English study note is in **[`research-note/`](research-note/README.md)**, with its complete TeX, PDF, 64-item mathematical audit and citation checks. The original blueprint and registered source snapshot remain unchanged.

## Start here

- `zeta-density-blueprint.tex`: the primary editable deliverable. The mathematics is prose and equations, not executable proof code.
- `zeta-density-blueprint.pdf`: compiled reading copy of the same source.
- `VALIDATION.md`: verification performed for this reconstruction, with its limits stated explicitly.
- `source-map.json`: every LaTeX source-correspondence paragraph with declaration/file locations in the pinned tree.
- `local-module-closure.json`: the local import closure of `Solution.lean`, not a minimal proof-term dependency closure.
- `registry-v1.json`: preserved immutable registration record.
- `pinned-source/`: complete upstream tracked source snapshot with its original licenses, notices, manifests and verification receipt.
- `registered-source.tar.gz`: Git archive of the same immutable source revision.
- `SHA256SUMS`: checksums for the kept reconstruction and source materials.

## Exact source identity

Requested entry:
https://palomar-registry.org/entry?id=PALOMAR-2026-10-11-000010&version=1

Immutable record actually used:
https://data.palomar-registry.org/entries/PALOMAR-2026-10-11-000010-v1.json

Upstream repository: https://github.com/mrklwk/zeta-density-39-over-17-lean

Registered revision: `ee2a8a32be49a4f73c7386e9dffdea24d7e3d8c0`.

Mathlib revision: `065356127b1dc0016f66b7283ce0ce2c4055aa55`.

The blueprint follows all four registered endpoint statements: `full_curve`, `global_uniform`, `uniform_away_boundary`, and `middle_large_values` in namespace `GuthMaynardStatement`.

## Reading order

1. Genuine finite zero sets, analytic multiplicity, polynomial and separation conventions, exact quantifier order.
2. Height-aware Fourier-affine input, smoothing and masks.
3. Literal centered cubic, nuclear/finite spectral comparison, amplifier and source correction.
4. Primitive-ratio sampling, exceptional Fourier mass, literal truncation, optimized fourth moment and absorption.
5. Good/bad occupied cells and all-threshold separated large values.
6. Actual short contour detector, fixed Taylor family, convolution powers and normalization.
7. Variable short window and closed upper window, unconditional weak Type-II fourth moment.
8. Jensen multiplicity restoration and dyadic height accumulation.
9. Native Ingham branch, actual fourth/twelfth moment machinery, finite peak/packet aggregation, strictly upper density branch.
10. Endpoint assembly, actual global proof route, finite-grid uniform constants and the discontinuous boundary audit.

## Coverage boundary

The document gives detailed complete consumer proofs relative to precisely identified, previously established analytic inputs. Those inputs are proved dependencies in the pinned Lean development, not additional assumptions of the registered endpoints. The source's finite peak aggregation, fourth-moment assembly, scale algebra, masks, operators, detector families and uniformization are expanded in mathematical prose. Foundational measure theory, Gamma-ratio contour bounds, native stationary/Atkinson source estimates, and the full classical Ingham medium-reflection producer are explicitly delimited imported machinery; this file does not claim to translate every auxiliary lemma in all 824 locally imported modules.

In particular:

- Both signs of ordinates, inclusive height cutoffs, analytic multiplicities and natural-floor source endpoints are retained.
- The strictly upper curve starts only at `sigma > 3/4`; its value is not substituted at `sigma = 3/4`.
- The actual weak mollified fourth-moment loss `1/25` is retained. `ShortMobiusFourthMoment` is not assumed.
- The truncated density discards values above the threshold; it is not clipping.
- The time cutoff's true support length `5T` is charged in cubic/spectral scales.
- A source-level ambiguity in `min eta 1/20` is resolved as `(min eta 1)/20`, matching Lean application precedence. No upstream source patch was made.

This reconstruction is not an author-approved paper, a human peer review, a novelty certificate, or a new complete kernel replay. The registry verification record and upstream `VERIFICATION.json` are preserved as source evidence and are not reported as computations performed here.

## Compile the TeX

From this directory, with a current TeX distribution:

```sh
pdflatex -interaction=nonstopmode -halt-on-error zeta-density-blueprint.tex
pdflatex -interaction=nonstopmode -halt-on-error zeta-density-blueprint.tex
```

Alternatively, Tectonic can resolve packages and perform the necessary reruns:

```sh
tectonic --untrusted --keep-logs zeta-density-blueprint.tex
```

Required packages are listed in the TeX preamble. No shell-escape is required. This task used a session-local portable Tectonic compiler; it did not change the user's global Lean or TeX configuration.

## Lean reproducibility

Use the registered toolchain in `pinned-source/lean/lean-toolchain` and the exact `lake-manifest.json` pins. The upstream source contains its own verification documentation and probes. A full Lean rebuild was not performed for this informalisation; source-hash validation, source correspondence, exact arithmetic checks and LaTeX compilation are separate checks.

## Attribution and licenses

Mathematics and the upstream formalisation are attributed to Mark Lewko and the adapted developments documented in the source's notices. New upstream material is AGPL-3.0-only. Adapted MIT, MIT-0 and Apache-2.0 material retains its respective license and notices. The complete upstream source is preserved without alteration. This generated study reconstruction does not imply approval or endorsement by any upstream author. No blanket relicensing of adapted sources is asserted.

## Archive scope and privacy

Only this task's deliverables and its registered public source materials are included. Unrelated project files, alternate-source working folders, credentials, editor state and session traces are excluded. The repository was initially created privately; it is now public at the user's explicit request, with its current visibility verified using GitHub's repository API.
