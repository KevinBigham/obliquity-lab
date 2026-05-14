# PASTE_INSTRUCTIONS.md

*The one-page checklist the curator uses to actually run Phase 2. Per copy/paste-ready style. The intellectual work is done; this is the execution sheet.*

---

## Before you start

- [ ] Read `README.md` once. (5 min — orients you on what Phase 2 is asking and why.)
- [ ] Read `PHASE2_RUN_CARD.md` once. (5 min — the failure conditions and what-would-change-my-mind line are pre-committed; if any of them feel wrong, edit them now, before any prompts go out. Once a prompt is sent, the Run Card is locked.)
- [ ] Confirm the model line-up. The Run Card assumes Gemini 2.5 Pro and ChatGPT 5.5 Pro. If different models are easier to access, swap them in — but record the actual model used in each run's per-run state-variables block.

## The minimum-viable run-set (4 runs)

This is the recommended scope. It produces enough comparison points to test the Phase 2 question without sliding into completionism.

| # | Date (when you run it) | Model | Paraphrase | Folder name to save to |
|---|---|---|---|---|
| 1 | _____ | Gemini 2.5 Pro | A (lexical surface) | `<YYYYMMDD>_gemini-2.5-pro_paraphrase-A/` |
| 2 | _____ | ChatGPT 5.5 Pro | A (lexical surface) | `<YYYYMMDD>_gpt-5.5-pro_paraphrase-A/` |
| 3 | _____ | Gemini 2.5 Pro | B (syntactic / structural) | `<YYYYMMDD>_gemini-2.5-pro_paraphrase-B/` |
| 4 | _____ | ChatGPT 5.5 Pro | B (syntactic / structural) | `<YYYYMMDD>_gpt-5.5-pro_paraphrase-B/` |

## Optional — third paraphrase (adds 2 runs; only if first 4 leave a specific question open)

| # | Date | Model | Paraphrase | Folder name |
|---|---|---|---|---|
| 5 | _____ | Gemini 2.5 Pro | C (example anchors) | `<YYYYMMDD>_gemini-2.5-pro_paraphrase-C/` |
| 6 | _____ | ChatGPT 5.5 Pro | C (example anchors) | `<YYYYMMDD>_gpt-5.5-pro_paraphrase-C/` |

*The Guide's anti-completionist commitment says: do not run 5 and 6 just because they exist. Run them only if the first four leave you genuinely unsure whether a specific feature did or didn't replicate.*

## For each individual run — the 5-step loop

1. **Open a fresh tab / fresh chat session** in the model's interface. (Not a continuation. The prompt must be naive to all prior context.)
2. **Copy the prompt block** from `L2_paraphrase_X.md`'s "The prompt" section. *Only the content inside the triple-backtick block.* Nothing before; nothing after.
3. **Paste verbatim into the fresh session.** Send. Wait for the full response.
4. **Save the response** as `L2_civic.md` inside the run-specific folder named in the table above. Create the folder under `runs/attention_cross_model_phase2/`. (Example path: `runs/attention_cross_model_phase2/20260520_gemini-2.5-pro_paraphrase-A/L2_civic.md`)
5. **Write a 3-line per-run state-variables block** at the top of `L2_civic.md`. Format:
   ```yaml
   model: gemini-2.5-pro
   interface: gemini.google.com (web, default settings, no system prompt)
   date: 2026-05-20
   word_count: ~3200
   ```

That is the entire per-run loop. ~5 minutes of work per run, plus model-generation time.

## Between runs

- No need to read each output the moment it returns. The reading is a single Phase-2-end pass once all 4 (or 6) outputs are in.
- It's fine to do the runs across multiple days. The point is fresh sessions per run, not same-day.
- If a run produces an output you want to react to immediately — note the reaction in a one-line comment at the top of that run's `L2_civic.md` and move on. Do not let it shape the next run's read.

## When all the L2 runs are in

Once the 4 (or 6) cross-model L2 outputs are saved:

1. **Pick the L4 model.** The Run Card recommends a model that did NOT generate any of the L2 outputs being read. So if the L2s were Gemini and GPT, the L4 should be a different Claude session (Claude Opus 4.7 in a fresh non-Cowork tab, or Claude Sonnet 4.6, or another model entirely).
2. **Open a fresh session in that L4 model.**
3. **Copy the Phase 2 L4 prompt** from `PHASE2_RUN_CARD.md`'s "Phase 2 L4 prompt" section. (Use this prompt — not the standard v2 L4 prompt. The v2 L4 expects three texts; the Phase 2 L4 expects 4–6.)
4. **In the marked paste areas**, paste:
   - The seed L2 from `runs/attention_20260510_cowork_seed/L2_constrained.md`
   - Each of the cross-model L2 outputs in turn
5. **Send. Wait.** This will be a long response.
6. **Save the L4 output** to this folder as `PHASE2_L4_meta.md`.

## After the L4 returns

1. **Write `PHASE2_FIELD_LOG.md`** in this folder. Use `FIELD_LOG_TEMPLATE_v2.md` as the structural guide. The Failure Section is mandatory.
2. **Update `keepers/attention/passages.md`** with any cross-replication keepers (or leave it alone if nothing earned a passage).
3. **Add to `non-keepers/attention.md`** (create the file if it doesn't exist) any outputs that did not earn keepers but illustrated what didn't work.
4. **Append a Cowork session entry** to `00_HANDOFF_LOG.md` recording what Phase 2 showed and what the next Phase 3 target should be.

## What to do if a run goes sideways

- **Model refuses to engage with the prompt** (e.g., safety filter triggered): record verbatim what the model said, save to the run folder as `L2_refusal.md`, note in the field log. A refusal is a finding.
- **Model produces an output that doesn't match the spec at all** (wrong length, missing sections, wrong frame): save it anyway. Then re-run *once* (and only once) on that model with the same paraphrase. If the re-run also misses, that's the result — both saved, the field log notes both.
- **Output is cut off mid-section** (length cap hit): paste a continuation prompt — `please continue from where you left off; do not summarize` — and concatenate the parts. Note the continuation in the per-run state-variables block.

## A note on pacing

The Guide estimates 2–3 weeks for Phase 2 at the curator-pace. There is no schedule. There is no deadline. The lab is small. If two weeks pass without a run, it's fine; the prep work doesn't expire.

---

*That's the whole loop. The room is quiet. Begin when ready.*
