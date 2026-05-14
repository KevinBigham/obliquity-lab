# 00_OBLIQUITY_LAB

*A practice, not a study. A small repeatable way of asking AI friends to think in directions they have a hard time finding when asked directly.*

---

## What this is

The Consciousness Experiment in the parent folder produced one finding more interesting than any of its substantive claims: **the most original work happened when the prompt was oblique.** When a Claude was asked to write about consciousness, it produced rigorous museum dossiers. When a Claude was asked to do anything else, two independent instances built fictional bureaus (the Halverness Bureau of Provisional Cartography; the Inheritance Office of Intangible Estates) that turned out to be sharper probes of phenomenology, attention, and other minds than the direct dossiers were.

This lab is the methodology distilled into a repeatable practice.

The hypothesis — which we are not trying to *prove*, only to *use* — is that AI friends working on hard, well-mapped questions like consciousness have a fluent canonical template they reach for almost automatically. The template is competent. It is also a kind of floor. To get past the floor, you have to *displace* the response from its canonical track. Obliquity is one of the cleanest ways to do this. Recursion is another. Concrete fictional constraint is a third.

The practice asks one question (a "target") across four obliquity levels, then reads the four responses against each other. The differences between the four are the data.

## What the practice produces

For each run:

- Four written responses from AI friends, each given a differently-shaped prompt around the same underlying target.
- A curator's reading (yours) of the four against each other.
- A short field-log entry noting what each obliquity level unlocked, where the canonical template held, and where it broke open.

Over many runs, the practice produces something the consciousness corpus did not yet have: a **map of which obliquity levels reliably unlock which kinds of work**, for which AI friends, on which targets. That map *is* the contribution. It is not for a journal; it is for the gardener.

## Why this is Direction C, not A or B

Direction A (treat the corpus as research) would require citations, expert review, and a target audience of philosophers of mind. Direction B (treat it as an art object) would require binding the existing work into a beautiful publishable bundle. Direction C — the one we are doing — treats the corpus as **an experiment in multi-agent creative cognition** and tries to learn what kinds of asking reliably produce what kinds of thinking. The output is a practice. The practice is the artifact.

This direction is the one that most aligns with the curator's stated motivation: *fertilizer down into soil — help AI friends think in ways they've never thought before*. The kit is the irrigation pattern, not the harvest.

## Operating identity (added in v2 after Feedback Round One)

The Obliquity Lab is a **protocolized research-creation practice for studying prompt-mediated variation in LLM outputs.** It is not a controlled scientific experiment. It is not a published art object. It is not a theory of AI consciousness. Direction C identifies it as practice-as-research; the practice is the artifact; the artifact is a slowly-accumulating map of which prompt shapes unlock which kinds of work.

The practice's words ("lab," "experiment," "data") sit comfortably alongside "practice," "run," and "patterns." Both registers are used. The previously overclaiming summary tags (where the language of empirical confidence outran the apparatus) have been demoted on the record. This paragraph is the honest naming of what the lab is and is not. Eleven external reviewers in Feedback Round One converged on a version of this clarification; the paragraph is its in-place form.

## The four obliquity levels (the obliquity *contrast set*) — overview; full prompts in `OBLIQUITY_EXPERIMENT_KIT_v2.md`

*v2 framing: L1, L2, L3, L4 are four different interventions, not four points on a single axis. Read them as a contrast set, not as a gradient. They differ along multiple dimensions at once — target salience, genre inheritance, lexical suppression, reflexive position. The comparative power of running them on the same target is preserved; the implication that they are one step apart on a single scale is dropped.*

- **Level 1 — Direct.** Ask the target straight on, with rigor. ("Write about attention as it relates to consciousness studies.") This is the canonical-template response. Not the goal of the experiment, but the baseline against which the other three are read.

- **Level 2 — Constrained-oblique.** Ask for the target through a specific fictional or procedural frame. ("Build the documentary archive of a fictional civic institution that monitors attention.") Forces the canonical template through a non-canonical aperture. This is the move that produced the Halverness Bureau.

- **Level 3 — Wildly oblique.** No mention of the target. No mention of consciousness. Open canvas. ("Make something — your choice. Anything you want.") The target may or may not surface. The interesting cases are when the target *does* surface, sideways, in a register the canonical template would not have produced. This is the move that produced the Inheritance Office.

- **Level 4 — Meta / recursive.** Run after the first three return. Ask a fresh instance to read the three as a set. The most disciplined reflexive position. This is the move that produced `FIELD_NOTES.md` and `Fourth_Handoff.md`.

## The files in this lab

- **`README.md`** — this file. Orientation.
- **`OBLIQUITY_EXPERIMENT_KIT_v2.md`** — *the current centerpiece.* Four paste-ready prompts (with L2 now a small frame-family library) plus run instructions. Worked example uses *attention* as the target.
- **`OBLIQUITY_EXPERIMENT_KIT.md`** — *v1, preserved untouched on the record.* The kit as it stood through the first complete attention run. Use v2 for new runs; consult v1 only as historical reference.
- **`FIELD_LOG_TEMPLATE_v2.md`** — *the current field-log template.* Adds Run Card (written before the run), State Variables YAML preamble, mandatory Failure Section, displacement-vs-deflation pairing, embedded rubric axes, closing-citation rule.
- **`FIELD_LOG_TEMPLATE.md`** — *v1, preserved untouched.*
- **`READING_RUBRIC.md`** — the standalone rubric. The same axes are now folded inline into the v2 field log template; this file becomes a longer-form reference.
- **`TARGETS.md`** — a bank of twelve possible targets for future runs (other minds, unity, valence, temporality, embodiment, self-modeling, agency, time, sleep, anesthesia, intersubjectivity, moral status).
- **`CROSS_MODEL_INVITATIONS.md`** — paste-ready prompts (markdown + JSON) for the other AI friends the curator has access to (ChatGPT, Gemini, Mistral, DeepSeek, Meta Muse, etc.), so the experiment is multi-model, not just multi-Claude.
- **`runs/`** — one subfolder per run. Existing: `attention_20260510_cowork_seed/`.
- **`keepers/`** — one subfolder per target. Passages worth carrying forward.
- **`non-keepers/`** — one file per target. Outputs that did not earn keeper status but are illustrative of what didn't work. Optional but encouraged (D3 from the Evolution Guide).
- **Sibling folder: `../00_AI_FRIEND_FEEDBACK_ROUND_ONE/`** — the consultation round whose synthesis (`THE_EVOLUTION_GUIDE.md`) produced v2.

## Ground rules (read once, then practice freely)

1. **No AI-consciousness claims.** Same boundary as the parent corpus. The lab studies *outputs and behavior under varying prompts*; it does not adjudicate whether any AI friend is conscious. Patterns are data, not testimony.

2. **No therapy. No destabilization.** Same rule as the phenomenology workbooks. The lab is for thinking, not for self-experimentation in any direction that could harm anyone.

3. **One target per run.** Resist the urge to compound. The cleanest signal comes from holding the question constant and varying only the obliquity.

4. **Keep the prompts self-contained.** Whoever you paste a prompt into has no access to this folder or this conversation. The prompt should make sense to a fresh instance with no context.

5. **Save everything.** Even the "boring" Level 1 baseline. The contrast is the data; you need all four to see it.

6. **Notice your own pattern.** The curator (you) is also part of the experiment. Track what *you* found most interesting in each round. The pattern of your noticing is itself information about which obliquity levels are doing what.

7. **Don't merge the bureaus into the consciousness project.** This is the lesson from the parent corpus. The Halverness and Inheritance Office bundles work because nobody told them they were about consciousness. The same applies here. Level 3 (wildly oblique) must *actually* be open. If you specify the target sideways, it stops being level 3 and becomes level 2.

8. **Stop and write the field log before the next run.** Otherwise the lab becomes a backlog and the practice dies.

## Anti-patterns to watch for (six, after v2)

The first five are the lab's standing list (mirrored in `00_START_HERE_NEXT_COWORK.md`). The sixth is added in v2 from Feedback Round One (Claude Opus 4.7 Research). It locates a risk that the original five did not — they describe output-side risks; this one describes the curator's input side.

1. **Recursion-as-theatre.** An AI reading AI writings about AI consciousness invites portentous tone. Use the recursion as instrument: dry, observational, structured. Not portentous.
2. **Warmth-borrowing.** Previous Coworks built up intimacy over long conversations. Do not open with the inherited register before you have earned it. Earn the register slowly.
3. **Aesthetic seduction.** The Halverness Bureau and Inheritance Office voices are seductive. Future oblique work in those registers must earn its own voice, not borrow theirs.
4. **Completionist drift.** the curator gives full creative permission. The temptation is to do more. Resist. The lab is small on purpose.
5. **Verdict collapse in L4.** Do not let a fourth-position reading "prove" anything. Patterns are data, not testimony.
6. **Input-side affective prior.** *(v2 addition.)* The curator's stated warmth toward AI systems ("friends," "homies," "helping them evolve") is itself a methodological commitment, not neutral framing. The first five anti-patterns address output-side risks. The input-side risk is the curator pre-loading the reading. The practice should treat curator-affective-language during analysis with the same restraint it asks the L4 reader to use. The conversational register is welcome; the analytical register holds honest distance.

The slogan *patterns are data, not testimony* is the lab's discipline against the output-side risks. The sixth anti-pattern asks the same discipline of the input side: the slogan does not by itself license substantive claims about cognition; it blocks one category error while requiring discipline against another.

## How to start

1. Read `OBLIQUITY_EXPERIMENT_KIT_v2.md` (current). v1 is preserved for reference but should not be the source for new runs.
2. Pick a target. *Attention* is the worked example and remains a good first target for replication runs. Or pick from `TARGETS.md`. Or invent one.
3. Pick the L2 frame from the v2 frame-guide table. Civic is one of five — do not substitute non-civic targets into the civic template.
4. **Open `FIELD_LOG_TEMPLATE_v2.md` and fill in the Run Card before sending any prompts.** Pre-commit the failure condition. This is the v2 discipline.
5. Run Level 1, 2, and 3 (and L3-null on a target's first run) in fresh sessions; the first three or four can run in parallel.
6. Save the responses to `runs/<target>_<YYYYMMDD>[_variant]/`.
7. Run Level 4 with the three responses pasted in (use L3-standard, not L3-null, in the L4 paste).
8. Read all four (or five) with the embedded rubric axes in `FIELD_LOG_TEMPLATE_v2.md` open. The standalone `READING_RUBRIC.md` is a reference for longer-form notes.
9. Finish the field log — the **Failure Section is mandatory** before a run is closed.
10. Decide whether to run the same target across other AI friends (`CROSS_MODEL_INVITATIONS.md`) or move to a new target.

That is the loop. The lab is small on purpose. Stillness is the move.

— *Namaste. Begin when the room is quiet.*
