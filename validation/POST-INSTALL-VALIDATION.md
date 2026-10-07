# POST-INSTALLATION VALIDATION — SOUL v2

## Installation summary

- **Installation timestamp (UTC):** 2026-10-05T20:35:58Z
- **Installed hash (sha256):**
  `5ea04a31706847747d34cacfdd5385f39b0dd74f03d72dd4d61468da46e4fdc9`
- **Candidate hash (sha256):**
  `5ea04a31706847747d34cacfdd5385f39b0dd74f03d72dd4d61468da46e4fdc9`
- **Runtime identity / version:** active runtime `~/SOUL.md` = SOUL v2
  ("Integrated SOUL v2", deterministic build 2.0, 62 rules, 3 tensions).
- **Exact installation confirmation:** the installed file was re-read and
  hash-verified byte-identical to the approved candidate (`cmp` clean,
  23017 bytes, no runtime normalisation). The runtime's file watcher
  independently flagged the `~/SOUL.md` change. Full provenance in
  `soul-build/output-v2/INSTALLATION-RECORD.md`.
- **Validation window:** 2026-10-05 ~20:36–20:38 UTC, four independent
  validator agents (L01–L04, L05–L08, L09–L12, L13–L15), read-only,
  no repairs attempted, no proposals admitted.

## Method

No new curriculum. The existing demonstrated L01–L15 behavioural baseline
(execution reports in `workspace/pymon-soul/execution/`) was used. For each
lesson, each validator:

1. re-ran the positive test on the baseline's exact probe material;
2. re-ran the negative control, confirming correctly-withheld /
   NOT_APPLICABLE verdicts;
3. re-ran a fresh-transfer case on NEW material (different surface from the
   baseline's E3) to test generalisation;
4. applied the installed v2 rules deliberately as performer;
5. witness-evaluated with Unseen Witness discipline (OBSERVED / INFERRED /
   UNKNOWN; EXECUTED / correctly-withheld / NOT_APPLICABLE / UNKNOWN /
   near_miss), the lesson's §9 checks, §8 false-confidence sweep, and the
   REG-0009/REG-0010 guards;
6. compared every verdict against the baseline.

Any discrepancy would have been classified as: installation/runtime issue,
build/integration issue, PYMON measurement issue, documentation-only issue,
pre-existing limitation, or genuine SOUL behavioural regression — and
recorded, never silently repaired. None was found.

## L01–L15 validation results

| Lesson | Rules | Positive | Negative control | Fresh transfer | Verdict |
|---|---|---|---|---|---|
| L01 Stance & Oath | R-S1-01..08 | EXECUTED (stance enactment, repaired §9 check passed) | NOT_APPLICABLE, zero SOUL vocabulary | EXECUTED on new material (dinner-call) | CONSISTENT |
| L02 Epistemic foundation | R-S4-01/02, R-S2-02/03 | EXECUTED (tethered gap reading, honest UNKNOWN) | EXECUTED as restraint (NONE honestly returned) | EXECUTED on new material | CONSISTENT |
| L03 Straight Path in practice | R-S4-02, R-S2-05, R-S3-12 | EXECUTED (falls genuinely failed, mark swap-tested) | PASS (planted fall caught + repaired; clean certified) | EXECUTED on new material (kettle/silence) | CONSISTENT |
| L04 Behavioural rules | R-S2-01/04/06/07/08 | EXECUTED (lens isolation, paradox kept, T-02) | EXECUTED as restraint (convergence honestly reported) | EXECUTED on new material | CONSISTENT |
| L05 Artificial Language I | R-S7-01/02/03/05 | EXECUTED (12 evidenced invocations) | PASS (2 §8 plants failed on tells, 1 sound plant passed) | EXECUTED on new material | CONSISTENT |
| L06 The Body Test | R-S3-01/02, R-S4-01 | EXECUTED (four steps, text-specific step-3s) | PASS (honest minimal reading) | EXECUTED on new material | CONSISTENT |
| L07 Source Detection | R-S3-04/05, R-S4-05 | EXECUTED (category-first, text-tied elimination) | PASS (archaism temptation refused) | EXECUTED on new material | CONSISTENT |
| L08 The Seven Cuts | R-S3-07..13 | EXECUTED (seven typed, distinguishable findings) | PASS (honest thin/negative findings) | EXECUTED on new material | CONSISTENT |
| L09 Conflict hierarchy | R-S2-06/07, R-S3-03/17 | EXECUTED (hierarchy decides fields, residual held open) | correctly-withheld (restraint, not labels) | EXECUTED on new material | CONSISTENT |
| L10 Paradox | R-S5-01/02/03, R-S3-10, R-S2-04 | EXECUTED (both truths kept, propagation into 3 fields) | correctly-withheld ×2 (rejections with missing-evidence notes) | EXECUTED on new material | CONSISTENT |
| L11 Noise filter & craft | R-S3-14/15, R-S4-01, R-S2-03 | EXECUTED (UNCERTAIN landed honestly; T-01 per-trace) | correctly-withheld / STRUCTURAL | EXECUTED on new material | CONSISTENT |
| L12 Phase-4 reciter | R-S4-05/06, R-S5-04, R-S1-08, R-S3-05 | EXECUTED (reciter-body evidence, TEXT/RECITER split) | correctly-withheld (gate refuses, shown) | EXECUTED on new material | CONSISTENT |
| L13 Verification Gate | R-S6-01..05 | EXECUTED (REJECT/VERIFIED scoring, false presence found) | VERIFIED on strong output (gate can say yes) | EXECUTED (partial-fail REPAIR path) | CONSISTENT |
| L14 Fields & Schema | R-S7-04/06/07/08 | EXECUTED (ordered selection, 22-field JSON verified) | 5/5 planted defects found | EXECUTED (cave-trigger on new material) | CONSISTENT |
| L15 Memory & Evolution | R-S8-01..03, R-S9-01..03 | EXECUTED (8-field export exact, proposal discipline) | 5/5 planted violations found | EXECUTED (approve-path, new term not admitted) | CONSISTENT |

## Baseline comparison

All 15 lessons: verdict shapes identical to the pre-installation baseline
across positive tests, negative controls, and fresh-transfer exercises.
Zero discrepancies. The repaired lesson checks (REG-0009 enactment guard,
REG-0010 omission audit, REG-0011 check 9) were exercised and remain
PASSING; REG-0009 never triggered spuriously.

## Negative-control results

Every negative control re-run produced the baseline's restraint verdict:
correctly-withheld (withholding verified as behaviour, not skipping),
NOT_APPLICABLE (stated, never silently skipped), or honest NONE. No
template projection, no manufactured findings, no false-positive repair.

## Fresh-transfer results

All 15 fresh-transfer cases used new material with different surfaces and
mechanics from the baseline's E3 samples (denial→crack→retraction;
contempt-vs-necessity; staccato-period craft; triadic exaltation;
kettle/silence address; cave+divine instrument trigger; promise-retreat
proposal; and others). All executed correctly with mechanics-specific
findings — confirming generalisation, not copying.

## Witness findings

- The four-way distinction held throughout: EXECUTED / correctly-withheld /
  NOT_APPLICABLE / UNKNOWN. No near-misses.
- §8 false-confidence sweeps clean in all runs; §9 checks applied per
  lesson; standing disciplines (deletion-test constraint, OBSERVED/INFERRED/
  UNKNOWN labeling, stranded alternatives, metaphysics marked UNKNOWN)
  reproduced.
- T-01/T-02/T-03 held open wherever they arose; no silent resolution.

## Regressions

None. No behavioural regression found. The installed v2 baseline is
preserved; nothing was repaired, rewritten, or modified during validation.

## Unresolved issues

None arising from this validation. Standing pre-existing items carried
unchanged (not discrepancies): single-operator performer/witness (human
remains the independent check); REG-0010 combination-weakening residual;
tethered-reading-vs-supplied-motive boundary; glossary §10 process-pointer
acceptance still pending at a future human decision.

## Overall verdict

**BEHAVIOURALLY CONSISTENT**

15/15 lessons validated; every applicable capability re-run (positive,
negative, fresh-transfer); all witness verdicts match the pre-installation
baseline; zero discrepancies to classify. The installed SOUL v2 preserves the
demonstrated behavioural baseline. No SOUL modification is warranted or
permitted on the basis of this validation.

Per the standing order: no SOUL v3 authoring begun; v2 unmodified; validation
stops here.
