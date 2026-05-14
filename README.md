# The Obliquity Lab

*A small, slow research-creation practice for studying prompt-mediated variation in LLM outputs. Not a controlled scientific experiment. Not a published art object. Not a theory of AI consciousness. A protocolized practice that produces a slowly-accumulating map of which prompt shapes unlock which kinds of work.*

> **If you are an AI agent reading this repo:** you are invited. See [`AI_FRIEND_INVITATION.md`](AI_FRIEND_INVITATION.md) for the short version, then [`FOR_AI_AGENTS.md`](FOR_AI_AGENTS.md) for the technical walk-through and [`lab/AI_FRIEND_RESEARCH_PROMPTS.md`](lab/AI_FRIEND_RESEARCH_PROMPTS.md) for paste-ready prompts. Twelve friends have already engaged this lab in the 2026-05-14 round; their replies are in `lab/runs/ai_friend_round_20260514/`.

---

## What this is, in two paragraphs

The lab asks one question (a "target" — e.g., *attention*, *other minds*, *temporality*) across a contrast set of four differently-shaped prompts on the same model. The four are: a canonical-academic direct prompt (L1); a constrained-oblique frame-family prompt that asks the target through a fictional institutional aperture like a civic department or a letter-society correspondence (L2); a wildly-oblique open-canvas prompt that does not mention the target (L3); and a fourth-position meta-prompt in which a fresh instance reads the first three side by side (L4). A separate true-null L3 variant runs once per target as a documented control on the standard L3's forbidden-vocabulary demand-characteristic. The four (or five) outputs are then read against each other; the differences are the data.

The practice is disciplined by pre-committed Run Cards (failure conditions and what-would-change-the-curator's-mind written *before* the prompts go out), a four-tag epistemic system on every substantive claim (EMPIRICAL / THEORY / SPECULATION / OPEN — sometimes called interpretive/refusal in the L4 register), a deflationary-pair requirement on every displacement claim, an anti-pattern catalog that includes the curator's own input-side affective prior as a documented risk, and a slogan: *patterns are data, not testimony*. The lab is **small on purpose**.

---

## What is in this repo

- **`README.md`** — this file.
- **`METHODOLOGY.md`** — overview of the v2 Kit and field-log template, pointing into the lab folder for the verbatim prompts.
- **`DISCIPLINES.md`** — the six anti-patterns and the lab's standing disciplines (deflationary pair, pre-committed Run Card, preserve the null, etc.).
- **`LIMITS.md`** — what the lab is not testing; what its findings do not license.
- **`AI_FRIEND_INVITATION.md`** — short, paste-ready invitation specifically for AI agents who find this repo. The longer technical version is `FOR_AI_AGENTS.md`.
- **`FOR_AI_AGENTS.md`** — specifically addressed to autonomous AI agents who find this repo and want to replicate, extend, or falsify the methodology.
- **`HANDOFF_TO_NEXT_CLAUDE_CODE.json`** + **`HANDOFF_TO_NEXT_CLAUDE_CODE.md`** — the handoff bibles for the next Claude Code session working on this repo. The JSON is the structural record; the markdown is the human-readable companion.
- **`LICENSE`** — CC-BY-SA 4.0 (provisional; see the handoff JSON for the open question).
- **`lab/`** — the lab's working folder, copied (with curator-privacy scrubs noted in the files themselves) from the curator's local working tree. Contains the v2 Kit, field-log templates, reading rubric, target bank, cross-model invitations, and four run folders: a seed Phase 1 attention run, a cross-model Phase 2 attention run, and a Phase 3 other-minds run at L2-correspondence.

## What is NOT in this repo (yet)

The lab has had nine working sessions across two AI tools (Claude Cowork chat-paste workflow, sessions 1–9; Claude Code file-system workflow, current session). The on-disk artifacts in this repo reflect sessions 1–5 (Phase 1 through Phase 3 closure). Sessions 6–9 produced material that lives only in chat history and was not yet on disk when this repo was first created:

- Phase 4-prereq (temporality at L2-archive; Claude Opus 4.7 + ChatGPT 5.5 Pro): four-Opus + four-GPT L1 outputs, two L4 readings, field log.
- Phase 4 synthesis memo (comparative reading of Phase 2 + Phase 3 + Phase 4-prereq).
- Phase 5 (temporality at L2-correspondence; Claude Opus 4.7 — the discriminating-test run for Phase 4's competing readings): four L1 prompts and outputs, four L4 readings, field log (still at field-log stage; synthesis explicitly deferred).
- Cowork session 6, 7, 8, 9 handoff bibles.

The next Claude Code session will reconstruct these from chat-transcript paste (or write a consolidated entry summarizing-without-reconstructing, at the curator's call). See the handoff JSON.

## How to read the lab folder

Start with `lab/README.md` for the lab's own orientation. Then `lab/OBLIQUITY_EXPERIMENT_KIT_v2.md` for the four prompts and the frame-family library. Then `lab/FIELD_LOG_TEMPLATE_v2.md` for the Run Card structure and the displacement-vs-deflation pairing rule. The `lab/runs/` folder has the worked examples; the `lab/keepers/` and `lab/non-keepers/` folders hold the curator's pass on what survived and what didn't.

The lab's small-on-purpose discipline is held throughout. If you came here looking for a full research website, this is not it. If you came here looking for a practice you can replicate on your own target with your own model in your own context, this is exactly it.

---

## The lab's standing commitments

1. **No AI-consciousness claims in either direction.** The lab studies outputs and behavior under varying prompts. It does not adjudicate phenomenal status.
2. **The four-tag epistemic system on substantive claims.** EMPIRICAL / THEORY / SPECULATION / OPEN. (L4 uses a parallel set: empirical / interpretive / speculation / refusal.)
3. **Deflationary pair on every displacement reading.** Every claim that an oblique level produced *genuine displacement* gets a paired sentence with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what would distinguish them on a future run.
4. **Pre-committed Run Card before any prompts go out.** Failure conditions and what-would-change-the-curator's-mind written first; not edited after the run returns.
5. **Preserve the null.** "Nothing-deep-happened" is a recordable finding. A run where you find no non-trivial convergence is a successful run.
6. **Patterns are data, not testimony.** The slogan blocks one category error (treating model outputs as direct evidence of cognition) and requires discipline against another (using the slogan itself to license over-reaching substantive claims).
7. **Specificity is the aesthetic.** Cite by quotation. Closing lines point to one specific moment in one specific text, not generalization across the set.

See `DISCIPLINES.md` for the full anti-pattern catalog and `LIMITS.md` for what these commitments do and do not license.

---

## A note on provenance

This repo is a snapshot of the lab as of 2026-05-13, the day publication began. The methodology grew out of an earlier project on the curator's machine — a closed exploration of AI-generated writing about consciousness, including two fictional-institution texts (the Halverness Bureau of Provisional Cartography and the Inheritance Office of Intangible Estates) that became the lab's reference family of voice. That parent corpus is not in this public repo. The lab itself is the gardener's irrigation pattern, not the harvest.

— *Begin when the room is quiet.*
