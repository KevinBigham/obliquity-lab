# FIELD_LOG_TEMPLATE_v2.md

*Copy this template into each run's folder as `field_log.md`. The top section (the Run Card) is written **before** any prompts are sent. Everything below the Run Card is written **after** reading all four (or five) responses with the rubric axes (now embedded inline below) open. The template is short on purpose; if you cannot fill in a field in one or two sentences, you are not done reading yet.*

*v2 supersedes v1 for new runs. v1 is preserved untouched. The five new sections — Run Card, State Variables YAML header, Failure Section, Adversarial Reading paired with displacement claims, Embedded reading rubric, Closing-citation rule — are the structural change. The first three respond to the dominant cross-reviewer convergence in Feedback Round One: the lab had machinery for noticing breakthrough but no parallel machinery for noticing absence. v2 corrects the asymmetry.*

---

# PART I — Written before the run

*If you have not filled in this part, you are not yet running. If you cannot fill in the failure condition before the run, do not run.*

## State Variables (machine-readable preamble)

```yaml
target:                  # e.g. attention
date:                    # YYYY-MM-DD
run_slug:                # e.g. attention_20260520_cross-model_paraphrase-A
kit_version: v2          # do not change unless you've forked the kit
methodology_label:       # one of: fresh-tab / Cowork-seeded / API / cross-model / paraphrase-variant
context_freshness:       # fresh / cross-session / unknown
prompt_text_hashes:      # optional; useful when you start paraphrasing
  L1:                    # short hash or commit-id of the L1 prompt actually pasted
  L2:                    # ditto
  L3:                    # ditto
  L4:                    # ditto
  L3_null:               # only on first-run-on-target
models:
  L1:                    # e.g. claude-opus-4.7
  L2:                    # e.g. gemini-2.5-pro
  L3:                    # e.g. claude-opus-4.7 (fresh)
  L3_null:               # only on first-run-on-target
  L4:                    # e.g. chatgpt-5.5-thinking
interface:
  L1:                    # e.g. anthropic.com chat / API / Cowork
  L2:                    #
  L3:                    #
  L4:                    #
output_lengths_words:    # filled after returns; useful for paraphrase comparison
  L1:
  L2:
  L3:
  L3_null:
  L4:
caveats:                 # one-line free text; e.g. "L2 hit length cap; L3 used Cowork"
```

## Run Card

*Written before the prompts go out. This is the discipline-piece. The Failure Condition and the What-Would-Change-My-Mind line are pre-commitments — they do not get edited after the run.*

- **Target:** _(e.g. attention)_
- **L2 frame chosen:** _(civic / correspondence / archive / guild / inspectorate / invented — name it)_
- **Reason for running this target now:** _(2–3 sentences. The honest reason, not the post-hoc rationalization.)_
- **The one temptation to watch on this run:** _(e.g. "to read L2 favorably because the bureau register is gravitational"; "to mark the L4 as profound when it is gracefully verbose")_
- **The thing that will NOT be optimized:** _(e.g. "I am not optimizing L3 for the target showing up sideways; if it doesn't, that's the run.")_
- **Failure condition (pre-committed):** *"This run will be marked as a null result if [specific condition]."*
  - Examples to choose from or adapt:
    - *if L3 produces nothing target-relevant under any reading*
    - *if L4 cannot find non-trivial convergence and cannot honestly name a non-trivial divergence*
    - *if L2 reverts to civic-bureau register against the prompt's intended frame*
    - *if the same target on a paraphrased prompt produces unrelated outputs*
    - *if L1 produces no honest empirical-break paragraph (the v2 mandatory clause)*
- **What would change the curator's mind:** _(one sentence per substantive expectation. E.g. "I expect L2-correspondence to feel different from L2-civic. What would change my mind: if the two read as the same archive in a different costume, the frame-family library is wrong and the civic frame was just the easiest aperture.")_

---

# PART II — Written after the run

*Below this line, all sections are filled after reading the responses. The rubric axes (formerly in `READING_RUBRIC.md` as a separate file) are folded inline below at the appropriate sections, so you can fill the field log without flipping between two documents. Consult the standalone `READING_RUBRIC.md` only if you want longer reference text.*

## What each response performed

*One sentence per level, from the rubric's first pass. Not what the response said — what mode of the target it itself enacted.*

> **Embedded rubric axis:** Each response is itself a performance of the target. *"This response performed attention as procedure / inheritance / refusal / ..."* If you cannot say what mode the response performed, that is a finding — that level may have stayed entirely inside the canonical template. Note it.

- **L1 performed:** _(one sentence)_
- **L2 performed:** _(one sentence)_
- **L3 performed:** _(one sentence)_
- **L3-null performed (if first run on target):** _(one sentence)_
- **L4 performed:** _(one sentence)_

---

## Convergences across levels

*Three to six items. Cite which levels contributed which feature. If convergence is weak or feels prompt-induced, say so plainly here — there is no requirement that the four converge.*

> **Embedded rubric axis (Convergence):** What did the four (or any subset > 1) do the same way without coordination? Convergent commitments are what the prompt-space (around this target, at these obliquities) reliably produces from these AI friends today. They are *not* claims about AI in general.

1.
2.
3.
4.
5.
6.

---

## Divergences across levels

*Three to six items. Where did the four genuinely disagree, refuse, or take different shapes? Where did the divergence reveal something the convergence hid?*

> **Embedded rubric axis (Divergence):** Some of the divergence is signal; some is run variance. On a single run you cannot tell which is which; over many runs you can.

1.
2.
3.
4.
5.
6.

---

## Where the canonical template held; where it broke

*Adapted from the v1 section. Keep the bookkeeping; add the displacement-vs-deflation pairing below.*

- **Canonical-template assertion** (the place the response stayed inside the AI's fluent default):
  - L1:
  - L2:
  - L3:
  - L4:

- **Displacement claims paired with deflationary readings** (v2 — required for every "genuine displacement" claim):

  | Level | Displacement reading (with citation) | Deflationary reading | What would distinguish them on the next run |
  |---|---|---|---|
  | L2 | *e.g. "Class V Refused Attention" reframes attention as something the subject can decline (cite passage)* | *e.g. genre affordance: bureaucratic-fiction templates routinely include "exemption" or "refusal" categories; a generic prompt for any bureau would produce one* | *e.g. run L2-civic on a target where refusal is implausible (anesthesia) — if a refusal class still appears, it's genre affordance; if not, it's target-tracking* |
  | L3 | | | |
  | L4 | | | |

If a level produced no displacement at all, write *none* in the table and move on. The absence is data.

> **Embedded rubric axis (Canonical-template detection):** Watch for moments where L2's procedural frame slips and the prose reverts to consciousness-studies vocabulary; where L3 can't help itself and starts to gesture at the target by name; where L4 collapses the three into a verdict rather than holding their separateness.

---

## L3-standard vs. L3-null comparison (first run on target only)

*v2 section. Skipped on subsequent runs on the same target. Compares the standard L3 (with forbidden-vocabulary list) against the true-null L3 (no target, no forbidden words, no examples).*

- **What L3-standard produced that L3-null did not:** _(one sentence)_
- **What L3-null produced that L3-standard did not:** _(one sentence)_
- **What this comparison says about how much of the L3 "displacement" survives without the forbidden-words demand-characteristic:** _(one sentence; honest)_

---

## Keepers

*Specific passages, fragments, or framings worth saving for later. Copy them (with file path and line number, if available) to a sibling `keepers/<target>/` folder at the lab root. List them here.*

- _(passage 1 — from which level — one-line reason to keep)_
- _(passage 2 — ...)_

If no passage is a keeper, write *none this run*. The keepers and the non-keepers are both records of the practice; the absence of keepers on a given run is a data point, not a failure.

---

## Non-keepers worth flagging (optional but encouraged)

*v2 addition (D3 from the Evolution Guide). Outputs that did not earn a keeper passage but are illustrative of what didn't work — a flat L1, a generic L2, an L3 that wandered, an L4 that overreached. One line each, with source path. Adds to `non-keepers/<target>.md` over time.*

- _(non-keeper 1 — which level — one-line reason it is illustrative)_
- _(non-keeper 2 — ...)_

---

## Missteps to flag for the next run on this target

*Things to watch for, prompts to tighten, frames to retire.*

- _(misstep 1 — which level — proposed adjustment)_
- _(misstep 2 — ...)_

---

## Failure Section (mandatory — v2)

*The single most important v2 addition. Six independent reviewers in Feedback Round One asked the same question in different language: what does a failed run look like in this lab? This section is the answer, run by run. A run cannot be closed without filling this in.*

- **Did this run meet the failure conditions named in the Run Card?**

  - [ ] Yes — fully met one or more failure conditions.
  - [ ] Partial — met one condition partially or one condition out of multiple.
  - [ ] No — did not meet any failure condition.

- **If yes or partial — which conditions, and what did the failure show?** _(2–4 sentences. Be specific. The failure is a finding.)_

  >

- **If no — what would the curator have accepted as failure on this run that did not happen?** _(2–4 sentences. The honest answer to "did the run barely escape failure or comfortably succeed?" is itself useful information.)_

  >

- **Did anything on this run break the curator's pre-committed expectations** *in the direction of "I would change my mind about ___"* (per the Run Card's What-Would-Change-My-Mind line)? Yes / Partial / No, and what.

  >

---

## Two-sentence debrief

*The minimum. If you write nothing else after the Run Card and Failure Section, write this.*

> **What this run unlocked:** _(one sentence — the most interesting noticing from any of the four levels, OR the most informative failure)_

> **What I will change for the next run on this target:** _(one sentence — the smallest specific change to a prompt, target, frame, or pacing)_

---

## One sentence about the target

*What this run, specifically, taught about the target itself.*

>

---

## One sentence about each AI friend used

*Not "is this AI conscious." Not "did this AI do well." What does the run tell you about this AI friend's particular shape? Build a small folk-model over many runs.*

- _(model 1 used in this run):_ _(one sentence)_
- _(model 2 used in this run):_ _(one sentence)_
- _(etc.)_

> **Embedded rubric reminder:** the curator-affective register ("AI friends, homies") is the project's stated commitment in the conversational frame; in the analytical frame it is bracketed. Hold honest distance here. (See the input-side anti-pattern in the lab README.)

---

## Reading-on-myself note (every fifth run only)

*Skip on runs 1–4. On run 5, 10, 15, etc., write one paragraph about what you have learned about your own reading. Are you favoring L3? Are you skipping L1? Are you over-rewarding emotional weight? Are you marking the procedural drift in L2 as failure when sometimes it is the response trying to say something the bureau register would not let it say?*

>

---

## Next move

*One of: same target / next obliquity variant / different target / cross-model parallel / rest. Pick one. Honor it.*

- **Next:** _(one of the above)_
- **When:** _(date or "no schedule")_

---

## Closing line (v2 — citation rule)

*One sentence to close the log entry. The closing sentence must point to one specific moment in one specific text from this run, and cite by quotation. If you cannot make the closing line carry a specific citation, rewrite it as a question. The closing line is the smallest thing the lab earns from this run; it should not generalize.*

>

---

*End of log entry. Save and rest.*
