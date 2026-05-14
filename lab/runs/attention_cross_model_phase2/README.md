# Phase 2 — Cross-model attention replication

*Phase 2 of the Evolution Guide roadmap. Built 2026-05-10 by Cowork Session 4 as the launch package for the curator to run at his own pace.*

---

## What this is

The Obliquity Lab's first complete run produced a specific L2-civic output: the **Department of Noticing and Regard**, with Class V Refused Attention, Officer Lendell's margin note, and the formula *"The Department does not know what attention is. It knows what attention does, in particular cases, and it logs those."*

The cross-model attention replication asks: **how much of that survives when the L2-civic prompt is paraphrased, and when the model running it changes?**

This is the empirical form of the dominant Round-One reviewer convergence — *what does a failed run look like in this lab?* Failure here is well-defined in advance: if the same paraphrase on a different model produces unrelated outputs, or if different paraphrases on the same model produce different bureaus, the seed run's distinctive features are paraphrase-noise + model-luck rather than attention-tracking + frame-tracking.

## What is being held constant; what is being varied

**Held constant (across all Phase 2 runs):**
- Target: *attention*
- Frame family: civic (matching the seed run, so the comparison is clean)
- Structural commitments: the five Shared Rules from `OBLIQUITY_EXPERIMENT_KIT_v2.md` L2 section (no consciousness vocabulary; no mysticism; no mockery; voice cracks but doesn't break; plain prose / no metaphor)
- Section structure of the requested archive: founding text, taxonomy, case file, glossary, bonus artifact
- Length bands: 600–800 / 400–600 / 600–1000 / 200–400 / 200–400 (totaling 2500–4000)

**Varied:**
- *Paraphrase dimension* (A, B, or C — see below for what each tests)
- *Model* (Gemini 2.5 Pro, ChatGPT 5.5 Pro, plus the Claude Opus 4.7 seed run as the implicit fifth)

## The three paraphrases

Each paraphrase changes one specific dimension of the L2-civic prompt while keeping the structural commitments and rules intact.

| Paraphrase | What it varies | What it tests |
|---|---|---|
| **A — Lexical surface** | Synonym swaps; word-order preservation; same examples and same instructional cadence | Whether the bureau output is robust to vocabulary choice. If A still produces a bureau with attention-as-class V structure and the same procedural register, the seed run's signature is not lexically dependent. |
| **B — Syntactic / structural** | Different sentence shapes; instructions delivered as bullet lists vs. prose; same content and examples | Whether the bureau output is robust to instructional form. If B still lands the bureau register, the seed run's effect is not produced by the v1 prompt's specific paragraph rhythm. |
| **C — Example anchors** | Different illustrative examples and historical reference points; same structural commitments and rules | Whether the bureau output is robust to which specific anchors the prompt uses (the v1 prompt names "Borges, Calvino, Saunders" and "national park ranger documents" — C uses different anchors entirely). If the bureau still appears, the seed's tone is not anchor-dependent. |

The recommended replication matrix is **2 paraphrases × 2 models = 4 L2 runs**, plus the seed run as the fifth comparison point. That is sufficient for Phase 2 closure. Running the third paraphrase on either model adds signal but is optional; the Guide's "anti-completionist" discipline applies — a sixth run is welcome only if the first four leave a specific question open.

## Files in this folder

- `README.md` — this file.
- `PHASE2_RUN_CARD.md` — the shared, pre-filled Run Card scaffold for the cross-model question. the curator reviews and (if needed) adjusts the failure conditions before pasting any prompts.
- `PASTE_INSTRUCTIONS.md` — the one-page checklist the curator uses to actually run Phase 2.
- `L2_paraphrase_A.md` — paste-ready paraphrase A (lexical-surface variant).
- `L2_paraphrase_B.md` — paste-ready paraphrase B (syntactic / structural variant).
- `L2_paraphrase_C.md` — paste-ready paraphrase C (example-anchor variant).
- *(Created by the curator as he runs)* per-run subfolders following the Guide's pattern: `<YYYYMMDD>_<model>_<paraphrase>/L2_civic.md` and a brief field log entry per run.
- *(Created at the end of Phase 2)* `PHASE2_FIELD_LOG.md` — one consolidated field log reading all four (or five, or six) outputs against each other, written when the curator has the runs back. This is where the displacement-vs-deflation table for cross-model survival lives.

## What gets re-run vs. what does not (Phase 2 scope)

- **L2-civic, paraphrased, on each model:** YES. This is the replication question.
- **L1 on each model:** NO. L1 is the canonical-academic baseline; one canonical baseline is enough. The seed run's L1 stands as the L1 reference for Phase 2.
- **L3 on each model:** NO for Phase 2. L3 is wildly oblique and not a replication target — its output is interesting precisely because it isn't reproducible. Save L3 cross-model questions for a separate, later run if curiosity demands.
- **L4 over the cross-model set:** YES, ONCE, at the end. L4 reads all the L2 outputs from Phase 2 (plus the seed L1 and seed L3 as context) and writes a single cross-replication field note. This is the meta-reading that Phase 2 earns.

## What a Phase 2 finding will look like

Three honest possibilities, in descending order of replication-strength:

1. **Strong replication.** All four cross-model L2 outputs produce a recognizable civic-attention bureau with at least one analogue of (Class V Refused Attention OR the "logs what attention does, not what attention is" formula OR the procedural-care register). The seed run's signature is robust to paraphrase and to model family.

2. **Partial replication.** The bureau register appears across all four, but the specific Class V Refused Attention move is uniquely Claude Opus's (it does not appear in the Gemini or GPT outputs). Some seed features survive; others were Opus-specific. Both findings are honest.

3. **Failure of replication.** The bureau register does not survive paraphrase or does not survive model change. The Department of Noticing and Regard was a specific Claude Opus + specific-prompt-phrasing artifact, not a general civic-attention attractor. **This would be a successful run**; the lab's machinery for noticing absence is exactly what v2 was built for.

The PHASE2_RUN_CARD's failure conditions are pre-committed against these three possibilities.

## Why now, and why this scope

The Evolution Guide's roadmap put Phase 2 immediately after Kit v2 instantiation because the cross-model question is the single biggest empirical test the lab can run with its existing machinery. ChatGPT Pro Deep Research's Closing Five was: *"How much of what the lab is calling 'obliquity effects' survives across paraphrases and model families?"* That is the Phase 2 question, in the reviewer's own words.

The scope is held narrow by design: one target, one frame family, two paraphrases minimum, two models, one shared L4. Anti-pattern #4 (completionist drift) is the discipline-test against which this scope is set. A larger Phase 2 — every paraphrase on every model on every target — would corrupt the practice. The lab is small on purpose.

---

*Begin when ready. The seed run is the comparison point. The room is quiet.*
