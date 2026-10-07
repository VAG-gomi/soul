# MIGRATION.md — Repo 3 (SOUL repository, working name `soul`)

**Version:** SOUL 2.0 (version tracks the normative artifact, not repo birth).
**Sources:** secondary sources only — R3's bytes exist nowhere in the
primary v1.0.2 source.
**Gates:** GATE-4 (extraction + verification). No transformations were
performed on any normative bytes.

## Per-item provenance

| Target | Source | Source hash | Action | Result hash | Notes |
|---|---|---|---|---|---|
| SOUL.md | ~/SOUL.md | 5ea04a3170684774…4d6146 | COPY-IDENTICAL | 5ea04a3170684774…4d6146 | Byte-exact; 23,017 bytes; `cmp` clean. Pre-extraction reverification passed. |
| history/SOUL.historical.DRAFT.frozen.md | ~/workspace/pymon-soul/archive/SOUL.historical.DRAFT.frozen.md | 679c1cd9a1f40981…01ed1c | COPY-IDENTICAL | 679c1cd9a1f40981…01ed1c | 24,905 bytes; pre-install runtime SOUL, archived 2026-10-05. |
| validation/POST-INSTALL-VALIDATION.md | ~/workspace/pymon-soul/soul-build/output-v2/POST-INSTALL-VALIDATION.md | b1b01ec58c885278… | COPY-IDENTICAL | b1b01ec58c885278… | The SOUL-specific validation record from output-v2/. Contains no SOUL rule texts (verified: 0 `> **R-S` lines). Other output-v2/ records (installation, incident) are *referenced* via PROVENANCE.md, not bulk-copied, per the plan. |
| fingerprints/SOUL-v2.0.sha256 | (generated from R3/SOUL.md) | — | NEW (generated) | — | `sha256sum` output; verified equal to `5ea04a31…4d6146`. |
| PROVENANCE.md | (new) | — | NEW | — | From the SOUL preamble + build/installation records. All 13 build-input hashes machine-verified against the preamble. Facts only; no normative restatement. |
| VERSION | (new) | — | NEW | — | Content `2.0`. |
| CHANGELOG.md | (new) | — | NEW | — | SOUL-only history (2.0 build/install/incident; 1.0 baseline lineage). |
| MANIFEST.txt | (generated) | — | NEW | — | Deterministic: sorted paths + sha256, same format as v1.0.2/R1. |

## What was NOT put in R3

- No PYMON skill, procedures, modes, or helpers (R1's domain).
- No curriculum, lessons, regression corpus, or evaluation records (R2's domain).
- No compatibility claims (R2's `COMPATIBILITY.md`, GATE-6).
- No SOUL build machinery (authoring tree, build scripts) — referenced
  by provenance, not vendored.
- No invented content: every byte is either copied-verified or
  generated-from-recorded-facts.

## Invariants held

- `sha256(R3/SOUL.md)` == `sha256(~/SOUL.md)` == `5ea04a31…4d6146`
  (binding byte-integrity rule; any deviation would have been ABORT).
- A/B/C distinction: (A) normative implementation here; (B) structural
  contract in R1; (C) compatibility evidence in R2. No duplication, no
  cross-dependency.
- Protected artefacts untouched: staged v1.0.2, v1.0.0, v1.0.1, R1 build
  tree, R2 build dir, frozen stress-test work, frozen logical-correctness
  design, `~/SOUL.md` itself.
