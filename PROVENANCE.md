# PROVENANCE.md — SOUL v2

Provenance for the normative SOUL artifact in this repository. Facts only;
no normative content is restated here — the artifact is `SOUL.md` itself.

## Artifact identity

- **Version:** 2.0
- **File:** `SOUL.md`
- **sha256:** `5ea04a31706847747d34cacfdd5385f39b0dd74f03d72dd4d61468da46e4fdc9`
- **Size:** 23,017 bytes
- **Composition:** 62 anchored rules, 3 preserved tensions (counts only;
  texts live in `SOUL.md`)

## Build

- **Pipeline:** soul-v2 deterministic build 2.0 (multi-file authoring tree)
- **Build timestamp (UTC):** 2026-10-05T21:30:00Z
- **Authoring baseline:** v1 normative representation
  (`soul-build/output-v1/SOUL.integrated.v1.md`)
- **Proposals:** excluded from this artifact (quarantined separately;
  none admitted)
- **Build input hashes** (authoring tree files, as recorded in the
  artifact's own preamble):

| File | sha256 |
|---|---|
| 10-identity-stance/identity-stance.md | eae2e0531981c2dfd6898424e8cd5240a125a7d38a9297b8118c55af653f13e6 |
| 20-behavioural-rules/behavioural-rules.md | b9297dd2a45d3def04229f10e04cddca08702e0716248514bd29d54b3160117d |
| 30-reasoning/reasoning.md | a2213d27848484578dbdc203756a5f3ea0a0a36ad56700f8120710fc83e10908 |
| 40-epistemology/epistemology.md | c42736b12a59f471d87a94bd45c7bf1c838d7b77d6b3a9204b3ba77863774655 |
| 50-contradiction-handling/contradiction-handling.md | e5f496e71f43f30c0c4495f7a86b84d9898348584bc90081e9ccee59a82621d1 |
| 60-verification/verification.md | 1a1628bbd78cb18ee9df3e9686bb0d505ada87a6912addd7e5d0849c3df2f48f |
| 70-communication/artificial-language.md | b7c1f845a368247d0014b64b3be0aa87027435f50fa6ade9ec819ad32054c7d7 |
| 70-communication/output-contract.md | 544c71567705b7cc8873fcfe72eb414584644c6f428a0faee85359d798d5856e |
| 80-memory/memory-behaviour.md | fb7a130b662722f6d56beff692e08f66ea2391450b77f36d82530c3998576f9e |
| 90-evolution/evolution.md | 2bb5dbcd3e6a4cf651c0b1c7716d582bbeb9662dd72f6d0035adae2f49ab5849 |
| glossary/glossary.md | 81fd45a1f7de5dc0e4f35f794dd3832369ce5cff45dd35a05aa11e64d2ca6801 |
| schema/field-schema.md | e8e5927d2cae0e503a51d3944d2c30335806acbf4c315b20dbdcb08283108051 |
| tensions/tensions.md | 31d723fc3f25c09c66342f192f71c739b4e9c21515d37dfc67651548ba0d4488 |

## Installation (runtime)

- **Installed:** 2026-10-05T20:35:58Z, by byte-exact file replacement of
  the active runtime `~/SOUL.md` with the approved candidate; hashes
  matched (`cmp` clean; no runtime normalisation observed).
- **Previous artifact:** historical DRAFT ("USC Witness Configuration"),
  sha256 `679c1cd9a1f40981175d92daccbc28977d602d73234b8b6d70758e1fd701ed1c`,
  archived to `history/SOUL.historical.DRAFT.frozen.md` before replacement.

## Runtime incident (2026-10-05)

- **Observed:** 2026-10-05T20:58:30Z — the runtime `~/SOUL.md` observed
  in a truncated (0-byte) state. Cause UNKNOWN.
- **Response:** empty-file state preserved as evidence; restored
  byte-exact from the approved candidate — restored file byte-identical
  (`5ea04a31…4d6146`, 23,017 bytes, `cmp` clean).
- The artifact itself was unmodified; no new validation was required.

## What this artifact is not

- Not a PYMON skill, procedure, or evaluation record.
- Not a curriculum, regression corpus, or compatibility claim.
- Contains no π/TGF material and no experimental evidence.
- Tensions T-01/T-02/T-03 are preserved unresolved, as built.
- No proposals admitted.

## Three-repository distinction

This repository holds **(A) the normative SOUL implementation**. The
generic structural contract for *inputs* to evaluation tooling lives in
the `pymon-witness` repository **(B)**. Compatibility evidence for
specific (skill × SOUL) pairs lives in the integration repository
**(C)**. Nothing here duplicates or depends on either.
