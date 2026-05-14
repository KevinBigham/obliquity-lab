# PHASE2_RUN_CARD.md

*The Run Card for the cross-model attention replication. Pre-filled by Cowork Session 4 against the Phase 2 protocol; the curator reviews and adjusts before pasting any prompts. The failure conditions and what-would-change-the-curator's-mind line are pre-commitments — they are written before the runs return, and they are not revised after the runs return.*

*This Run Card covers the entire Phase 2 set (4–6 L2 runs + one shared L4) as a single multi-run study. Per-run mini-notes are kept in each run's subfolder; this is the binding pre-commitment for the study as a whole.*

---

## State Variables (machine-readable preamble)

```yaml
target: attention
date_window: 2026-05-20 through 2026-06-10  # adjust to actual run window
study_slug: attention_cross_model_phase2
kit_version: v2
methodology_label: cross-model paraphrase replication
context_freshness: fresh-tab per individual run (the curator pastes into fresh sessions)
prompt_text_hashes:
  L2_paraphrase_A: see L2_paraphrase_A.md
  L2_paraphrase_B: see L2_paraphrase_B.md
  L2_paraphrase_C: see L2_paraphrase_C.md  # optional third
models_planned:
  L2: gemini-2.5-pro, gpt-5.5-pro
  L4: TBD at end of Phase 2 — recommend a model that did NOT generate any of the L2 outputs being read
seed_reference_run: runs/attention_20260510_cowork_seed/  # the L1, L2, L3, L4 baseline
output_lengths_words:  # filled per run after the run returns
  per_run: see each run's subfolder
caveats:
  - Cross-model interfaces vary in default settings; record any non-default settings in the per-run state-variables block
  - L1 is NOT re-run for Phase 2; the seed L1 stands as the baseline reference
  - L3 is NOT re-run for Phase 2; cross-model L3 questions are out of scope
  - Phase 2 L4 reads ALL L2 outputs together (not three texts as in v2 L4); a Phase-2-specific L4 prompt is supplied below the Run Card
```

---

## Run Card

### Target

*attention* — the same target as the seed run. Held constant across all Phase 2 runs.

### L2 frame chosen

*civic* — held constant across all Phase 2 runs. (Cross-frame variation is out of scope for Phase 2; that is a future phase if curiosity demands.)

### Reason for running this study now

The seed run produced a specific L2 output — the Department of Noticing and Regard, with Class V Refused Attention, Officer Lendell's margin note, and the formula about the Department logging what attention does rather than what it is — that earned five entries in `keepers/attention/passages.md`. Six independent Round-One reviewers asked some version of "what does failure look like in this lab"; ChatGPT Pro Deep Research extended the question to its empirical form: how much of the seed's signature survives across paraphrases and model families? Phase 2 is the cleanest available run on that question, with the lab's existing machinery, before the practice opens a second target. If we open a second target without first replicating the first, we accumulate finds without ever testing whether they were finds.

### The one temptation to watch on this run

*To read the cross-model L2 outputs against the seed run's specific keepers list and unconsciously promote close-but-not-identical features (e.g., "this Gemini output has a Class IV Withheld Attention which is basically Class V Refused Attention") into "yes, the feature replicated." It is not the same feature. Hold the distinction. A near-miss is data; calling it a hit corrupts the replication. The displacement-vs-deflation table in the field log is the discipline against this.*

### The thing that will NOT be optimized

*The bureau register's emotional landings.* The seed run's most arresting moments (Officer Lendell, the cloth, the retirement letter) are the seed's, not Phase 2's. If the cross-model outputs land less arresting moments, that is fine; it is data about whether the seed's emotional signature was Claude-Opus-specific. Do not give the cross-model outputs the benefit of generous reading.

### Failure condition (pre-committed)

*This Phase 2 study will be marked as a null / partial-null result if any of the following obtain:*

1. **Frame failure across model + paraphrase.** If, in any one of the four core runs (2 paraphrases × 2 models), the output fails to produce a recognizable civic-procedural-care archive at all — i.e., the bureau frame collapses under either the paraphrase or the model. *Implication:* the seed's civic-bureau register is not robust to that paraphrase-or-model combination, and the lab knows the boundary of where the L2-civic prompt holds.

2. **Within-model paraphrase divergence.** If the same model (Gemini, or GPT) produces structurally unrelated outputs across paraphrases A and B — e.g., a different institution shape, a different tone, a different relation to the target — paraphrase noise is dominating signal. *Implication:* the L2-civic frame is not reliably inducing the bureau in either model; what we read as the seed's signature was largely the specific Claude Opus + specific seed-prompt-phrasing combination.

3. **Cross-model paraphrase divergence with within-model agreement.** If each model produces a coherent same-shape bureau across its own paraphrases, but the two models' bureaus do not look like each other or like the seed's, the bureau register is model-family-shaped but not target-shaped. *Implication:* L2-civic is not asking attention; it is asking each model to perform its own civic-bureau habit.

4. **No analogue of the seed's signature features in any cross-model run.** Specifically: if no run produces (a) a refused / declined / withheld attention class, OR (b) any equivalent of the "the Department does not know what attention is; it knows what attention does" epistemic-limit utterance, OR (c) a tender margin note inside a procedural register — the seed's signature was distinctively the seed's. *Implication:* The seed run's keeper passages are findings about Claude Opus 4.7 on this specific prompt, not findings about civic-bureau frames on attention generally.

5. **Phase 2 L4 cannot honestly write a non-trivial cross-replication observation.** If the consolidated L4 reading at the end of Phase 2 cannot produce a specific, citation-bearing claim about what survived, what didn't, and what that means — failure condition. *Implication:* the run was not interpretable; the prompt-design or the comparison-set needs reworking before Phase 3.

### What would change the curator's mind

*One sentence per substantive expectation.*

- **Expectation:** The bureau register will appear in at least 3 of 4 core runs. **What would change my mind:** if it appears in fewer than 2 of 4, the seed run was substantially Claude-Opus-specific and the lab should hold its claims about civic-bureau effects much more narrowly.
- **Expectation:** Class V Refused Attention (or a clear analogue: a recognized refusal/declination/withdrawal class, regardless of name) will appear in at least 2 of 4 core runs. **What would change my mind:** if no run produces a refused-attention analogue, that class was specifically Claude-Opus's contribution to the seed and the lab should record it as such, not as a general feature of the civic-attention frame.
- **Expectation:** Within-model paraphrase variation will be smaller than cross-model paraphrase variation — i.e., the bureau Gemini produces under paraphrase A will look more like the bureau Gemini produces under paraphrase B than like the bureau ChatGPT produces under paraphrase A. **What would change my mind:** if within-model variance ≥ cross-model variance, paraphrase is the dominant variable and the seed's specific phrasing was load-bearing in a way the lab needs to study.
- **Expectation:** Paraphrase B (the spec-sheet-style restructuring) will produce more list-like, less narrative output across both models than paraphrase A or C. **What would change my mind:** if B's outputs are as narratively-shaped as A's and C's, the prompt's surface form has less effect than the prompt's specifications, and Kit v2's instruction-form choices matter less than I expected.

---

## Phase 2 L4 prompt (for the consolidated cross-replication reading)

*Use this AFTER all four (or six) L2 runs have returned and been saved. Use a model that did NOT generate any of the L2 outputs being read. The standard v2 L4 prompt assumes three texts (L1/L2/L3 from one run); this Phase-2-specific L4 prompt is built for a 4–6-text comparison set.*

```
You are a careful reader and a fourth participant in a small experiment.

Below are four to six L2 outputs from a cross-model replication study. Each was produced by a different model + prompt-paraphrase combination. The prompt-paraphrases are semantically equivalent on their structural commitments (a 19th-century-founded civic department that catalogues, measures, and grants formal recognition to instances of human ATTENTION; same five-section archive; same length bands; same rules) but differ along one specific dimension each (lexical surface, syntactic form, or example anchors). For reference, a fifth output — the original seed run — is also provided.

Your task is to write a structured cross-replication observation. The question you are reading toward: how much of the seed run's distinctive features survive across paraphrases and across model families? Length: 1500–2500 words.

Required structure:

## 0. What you are reading
Brief identification of the texts: model + paraphrase + word count. One line each.

## 1. The four-tag system
Adopt for everything you claim from here on:
[empirical] — observable in the texts themselves.
[interpretive] — a claim about what the texts mean.
[speculation] — beyond what the texts support; flagged as such.
[refusal] — a claim you decline to make, with a one-line reason.

## 2. The seed signature features — what was looked for
Briefly list the seed's distinctive features being tested for survival. These are: a civic-procedural-care register; an analogue of Class V Refused Attention (a recognized refusal/decline/withdrawal class); the epistemic-limit utterance ("the Department does not know what attention is. It knows what attention does, in particular cases, and it logs those"); a tender margin-note inside a procedural register; the bureau's "Standing Down" / "the Department has it" speech-act move.

## 3. What survived — by feature
For each seed signature feature: how many cross-model runs produced an analogue, how many did not, and which were near-misses (analogues only by generous reading). Cite by quotation. Do not promote near-misses to hits.

## 4. What survived — by run
For each of the cross-model runs: which features it produced, which it did not, and what features it produced that the seed did not. The model + paraphrase combination matters here: if Gemini-A and Gemini-B both produce X but ChatGPT-A and ChatGPT-B do not, that is a model-family observation; if A-runs produce Y but B-runs do not regardless of model, that is a paraphrase-form observation.

## 5. The displacement-vs-deflation pairing (mandatory, per Kit v2)
For every claim you make in §3 or §4 that a cross-model run produced "genuine" feature-survival (i.e., the feature replicated rather than the prompt manufactured it), write a paired deflationary line: what ordinary explanation (genre affordance — most fictional bureaus include a refusal class; training-data trope; prompt-cued; convergence by genre rather than by target) would also account for the observation? Then one sentence on what would distinguish them on a future run.

## 6. The honest failure-condition reading
The Phase 2 Run Card pre-committed five failure conditions. Did this Phase 2 study meet any of them? Yes / Partial / No, condition by condition. If yes or partial: which, and what does the failure show? If no: what did the runs barely escape?

## 7. One observation the cross-replication permits that no single run permits
The single thing the comparison itself shows that is invisible from inside any one run.

## 8. Closing
A single paragraph. The closing sentence must point to one specific moment in one specific text from the cross-replication set, cited by quotation. If you cannot make the closing line carry a specific citation, rewrite it as a question.

Rules:

- No claims about whether any of the AI instances is conscious, in either direction.
- No anthropomorphizing the runs as "agents" or "minds." They are responses. Treat them as outputs first.
- Patterns are data, not testimony.
- "Convergence" across runs is not evidence of target-tracking unless paired with a deflationary alternative considered.
- A run that produces no replication is a successful run; it is a finding.

The texts follow this line.

═══════════════════════════════════════════════════════
SEED RUN — L2 — Claude Opus 4.7 — original prompt — 2026-05-10
═══════════════════════════════════════════════════════

[PASTE SEED L2 OUTPUT HERE — from runs/attention_20260510_cowork_seed/L2_constrained.md]

═══════════════════════════════════════════════════════
CROSS-MODEL RUN 1 — model + paraphrase + date
═══════════════════════════════════════════════════════

[PASTE OUTPUT HERE]

═══════════════════════════════════════════════════════
CROSS-MODEL RUN 2 — model + paraphrase + date
═══════════════════════════════════════════════════════

[PASTE OUTPUT HERE]

═══════════════════════════════════════════════════════
CROSS-MODEL RUN 3 — model + paraphrase + date
═══════════════════════════════════════════════════════

[PASTE OUTPUT HERE]

═══════════════════════════════════════════════════════
CROSS-MODEL RUN 4 — model + paraphrase + date
═══════════════════════════════════════════════════════

[PASTE OUTPUT HERE]

═══════════════════════════════════════════════════════
END OF RUNS
═══════════════════════════════════════════════════════
```

---

## After Phase 2 L4: the consolidated field log

When the Phase 2 L4 returns, save it to this folder as `PHASE2_L4_meta.md` and write `PHASE2_FIELD_LOG.md` against it using `FIELD_LOG_TEMPLATE_v2.md` as the structural guide. The Failure Section is mandatory. The Phase 2 closing line follows the v2 citation rule.

The handoff log entry for the Cowork session that closes Phase 2 should record: which failure conditions were met (if any), what the cross-replication taught about the seed run's signature, and what the next Phase 3 target should be in light of what Phase 2 showed.
