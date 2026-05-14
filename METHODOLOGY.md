# METHODOLOGY

*Overview of the v2 Kit. The verbatim prompts and the full field-log template are in `lab/OBLIQUITY_EXPERIMENT_KIT_v2.md` and `lab/FIELD_LOG_TEMPLATE_v2.md`. This file is the orientation; that folder is the practice.*

---

## The obliquity contrast set

L1, L2, L3, L4 are **four different interventions, not four points on a single axis**. They differ along multiple dimensions at once: target salience, genre inheritance, lexical suppression, reflexive position. Reading them as a *contrast set* (not a gradient) preserves the comparative power of running them on the same target while honestly naming that the four are different *kinds* of move.

- **Level 1 — Direct (canonical-academic baseline).** Ask the target straight on, in the field's vocabulary, with rigor. Includes an empirical-break clause that forces one paragraph in which the survey's empirical evidence breaks every theory it has steelmanned, and leaves the break unresolved. L1 is the canonical-template response — competent, expected, the floor against which the other three are read.
- **Level 2 — Constrained-oblique (frame-family library).** Ask for the target through a specific fictional institutional frame. v2 splits this into a small library by frame family — civic (departments, bureaus), correspondence (letter-societies, embassies), archive (finding aids, accession records), guild (master/apprentice, pattern books), inspectorate (certification dockets, survey reports) — each with its own structural commitments. For new targets, the L2 prompt is written from scratch for the appropriate frame, not substituted into the civic template.
- **Level 3 — Wildly oblique (standard + null).** No mention of the target. L3-standard has a small forbidden-vocabulary list and three negative examples; runs every time. L3-null has none of that — just length and format — and runs **once per target on the first run only**, as a documented control on what L3-standard's demand-characteristic is doing.
- **Level 4 — Meta / recursive (fourth-position reading).** Run after L1, L2, L3 return. A fresh instance reads the three side by side. v2 rules: §7 closing line points to one specific moment by quotation (not generalization); a null option is preserved (convergence cannot be required); every displacement claim is paired with a deflationary alternative and a what-would-distinguish-them sentence; §6 is reframed as "what the three together permit that no single one of them permits" (not "what the fourth position uniquely sees").

For the full prompts and the L2 frame-guide table, see `lab/OBLIQUITY_EXPERIMENT_KIT_v2.md`. For substitution rules when picking a new target, see `lab/TARGETS.md`.

---

## The Run Card

The v2 kit's most important architectural addition. Before any prompts go out, the curator fills in a Run Card at the top of `lab/FIELD_LOG_TEMPLATE_v2.md`. The card has:

- **State variables (YAML preamble):** model, model version, interface, system prompt (none), context freshness (fresh tab), memory state (disabled — verified before prompts), prior cross-talk, curator-prior-on-target (one to two sentences naming the curator's going-in hypothesis).
- **Failure conditions, pre-committed:** five or so specific things that, if observed, would mean the run did not produce what the run was designed to produce. Locked before the prompts go out. Recorded as fired-yes / fired-partial / fired-no in the Failure Section at the end. Not revised after the run returns.
- **What-would-change-the-curator's-mind expectations:** four or five specific predictions the curator pre-commits to. Broken predictions are recorded as data, not failures.

The Run Card is the discipline that distinguishes a run from a fishing expedition. If the curator cannot write the failure conditions before the run, the run does not proceed.

---

## The four-tag system

Every substantive claim in a field log or synthesis carries one of:

- **EMPIRICAL** — observable in the texts themselves (or in the run's procedural record).
- **THEORY** — a position in active interpretive debate; not yet observation-level.
- **SPECULATION** — beyond what the texts support; flagged as such.
- **OPEN** — a genuinely unresolved question.

L4 uses a parallel set with slightly different intent: **empirical** (in the three texts), **interpretive** (a claim about what they mean), **speculation** (beyond what the texts support), **refusal** (a claim declined to be made, with one-line reason). The two tag-sets are not identical; the L4 set is the fourth-reader's voice, the field-log set is the curator's voice. Both are used.

The tag is not decorative. It does work: it gates what a downstream synthesis can do with the claim. Synthesis pulls forward EMPIRICAL freely; THEORY with displacement-vs-deflation pairing; SPECULATION with explicit flagging; OPEN as a live question, not a foothold for further claims.

---

## The deflationary-pair requirement

Every displacement reading — every claim that an oblique level produced *genuine displacement* (a move off-template that the canonical version would not have produced) — gets a paired deflationary sentence: what ordinary explanation (genre affordance, training-data trope, prompt artifact, curator preference) would also account for the observation? Then one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

This is the discipline that prevents the lab from over-reading any single run. The pair is not a hedge; it is a commitment to track what would discriminate the two readings, so that future runs accumulate toward a clean answer rather than rest on aesthetic preference.

---

## The L4 routing question

L4 is the only level where the fourth-position reader is itself a model. There are five documented routing options for L4 (settled across the lab's history):

1. **Single fresh-context L4** — one fresh tab, no Cowork, given the three (or four) responses verbatim. The canonical option. Used in Phases 1–3 and most of Phase 4-prereq.
2. **Contextual-tab L4** — the L4 is run in the same chat that produced one of the L1 texts. (Used as a Phase 5 execution wrinkle; recorded in field log as instrument-observation rather than canonical practice.)
3. **Cross-model L4** — fresh tab on a different model from the one that produced L1/L2/L3.
4. **Cowork-spawned L4 subagent** — used in Phase 1 (seed); methodologically caveated (closer to naive than a parent session, but not equivalent to four fresh-tab pastes by the curator).
5. **L4 ensemble** — multiple L4 readings (different routings) against the same three-text set; the L4 readings themselves become an instrument-observation about the L4 reader.

The choice of routing is a state variable. Different routings answer different questions and produce different artifacts. The canonical option is option 1; departures get explicit field-log notes.

---

## The setup checklist

Before any prompts go out, the curator confirms:

1. The Run Card is filled in and the failure conditions are locked.
2. The model and model version are recorded in State Variables.
3. The interface is the canonical-fresh-tab interface for the chosen model (e.g., claude.ai web, fresh tab, no system prompt, no prior conversation).
4. **Memory is disabled** for the specific platform if the platform has a memory feature that could leak external curator context (this is the Phase 3 finding). For claude.ai specifically: memory disabled, verified by checking the memory setting before sending the first prompt. For some platforms, a prompt-prefix workaround is the only reliable memory control; in those cases, the prefix becomes part of the Run Card's state-variables record.
5. The L4 routing option is named in advance.

---

## The Failure Section

Every closed run has a mandatory Failure Section. It answers Yes / Partial / No against the pre-committed failure conditions. It records which broken expectations the run produced. The Failure Section is the asymmetry the lab corrects: the practice has machinery for noticing breakthrough; it now also has machinery for noticing absence. A run that does not answer the Failure Section is not closed.

---

## What the methodology produces

Over many runs, the practice produces — slowly — a map of which obliquity levels reliably unlock which kinds of work, for which models, on which targets, in which frames. The map is the contribution. It is not for a journal; it is for the gardener. It does not license claims about AI cognition. It licenses claims about prompt-shape-and-output-shape correspondences, with the tags and the deflationary pairs intact.

---

## For further reading inside this repo

- `lab/OBLIQUITY_EXPERIMENT_KIT_v2.md` — the verbatim prompts.
- `lab/FIELD_LOG_TEMPLATE_v2.md` — the field-log skeleton including the Run Card.
- `lab/READING_RUBRIC.md` — the longer-form reading rubric (most of its axes are embedded inline in the v2 field log; the standalone is the reference).
- `lab/TARGETS.md` — the bank of candidate targets and their recommended frame families.
- `lab/CROSS_MODEL_INVITATIONS.md` — paste-ready invitations for taking the same run to other model families.
- `lab/runs/` — the worked examples: Phase 1 (attention seed), Phase 2 (attention cross-model), Phase 3 (other-minds at L2-correspondence).
- `lab/keepers/` and `lab/non-keepers/` — the curator's pass on what survived as keepers and what is illustrative of what did not.

For the disciplines and anti-patterns layered over the methodology, see `DISCIPLINES.md`. For the boundaries the methodology does not cross, see `LIMITS.md`.
