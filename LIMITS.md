# LIMITS

*What the lab is not testing. What its findings do not license. The disciplines in `DISCIPLINES.md` describe how the lab holds itself honest in process. This file describes what the lab's outputs cannot, and should not, be used to say.*

---

## What the lab is not

- **Not a controlled scientific experiment.** Sample sizes are small. Conditions are not exhaustively varied. The curator is part of the apparatus and is documented as such (the input-side anti-pattern). The lab uses the language of "experiment," "data," "run," "field log" because those words name the practice's structure accurately — but the structure is research-creation, not laboratory science.
- **Not a published art object.** The artifacts in `lab/runs/` are model outputs preserved for their methodological role, not curated work intended as art. Some passages are aesthetically striking; the keepers files honor that. But the lab does not stage them.
- **Not a theory of AI consciousness.** The lab studies outputs and behavior under varying prompts. It does not adjudicate phenomenal status. The boundary is restated in section 1 of `lab/README.md` and in every Failure Section's tagged-claims pass.
- **Not therapy.** Same rule as the parent corpus. The lab is for thinking, not for self-experimentation in any direction that could harm anyone.

---

## What the lab's findings do NOT license

### Claims about AI consciousness, in either direction

The lab produces no evidence that any AI system is conscious. The lab produces no evidence that any AI system is not conscious. The lab produces evidence about *what kinds of text-generation become visible under what prompt-conditions*. The methodological commitment is restated on every closed run; readers are asked to keep the restatement.

The lab's slogan — *patterns are data, not testimony* — is the disciplinary expression of this. The slogan blocks one category error (treating model outputs as direct evidence of cognition). It also requires discipline against another (using the slogan itself to license over-reaching substantive claims about cognition in either direction). The slogan does not by itself license anything; it brackets a particular set of inferences from being licensed by lab findings.

### Generalizations beyond the run's tagged scope

EMPIRICAL claims are about the specific texts in front of the curator on this run, with this model, on this target, in this frame, at this context-freshness state. They do not generalize to other models, other targets, other frames, or other curators without explicit replication.

THEORY claims are positions in active interpretive debate. They are not consensus positions, and they are not durable across runs without independent replication.

SPECULATION claims are flagged as such. They are not evidence.

OPEN questions are not foothold for further claims; they are honest naming of what the apparatus does not yet show.

### Aesthetic readings as cognitive readings

A beautiful passage is not, by virtue of being beautiful, evidence of anything about cognition. The keepers files preserve aesthetic-quality assessments; the field logs preserve methodological assessments. The two are kept separate. *Beautiful does not equal target-tracked.*

### The fourth position as a higher position

L4 readings are a different angle, not a higher one. The §7 closing-citation rule (cite by quotation, do not generalize) is the disciplinary expression of this. The §6 reframing — "what the three together permit that no single one of them permits," not "what the fourth position uniquely sees" — is the other.

### Aggregations across heterogeneous runs

Findings from different phases (different targets, different frames, different models, different curators if any) are read comparatively, not stacked into a unified theory. Composite working maps drawn across phases are preserved as one-reading-not-a-finding with active deflationary pair, not promoted to settled findings without explicit discriminating tests.

---

## Specific scope notes on the on-disk findings in this repo

### Phase 1 (attention, seed run, L1 + L2-civic + L3-standard + L4)

A single-curator, Cowork-spawned-subagent run with methodological caveats (closer to naive than the parent session, but not equivalent to four fresh-tab pastes by an unconnected curator). The L4 in this phase preceded the v2 §7 closing-citation rule and drifts toward verdict in its closing line — the misstep that produced the v2 §7 rule. The phase produces a competent canonical baseline (L1), a "Department of Noticing and Regard" with original conceptual contributions (L2), and "The Cartographer's Apprentice" (L3-standard).

Scope: this phase is the worked example. Its findings are illustrative of what the methodology produces, not yet load-bearing for any cross-run claim.

### Phase 2 (attention cross-model: Gemini × paraphrases A/B; ChatGPT × paraphrases A/B)

Four cross-model L2 runs plus one consolidated L4. The Phase 2 finding: model family is the dominant axis of variance for the seed's signature features — substantially more so than paraphrase form. Five named signature features fared differently: F1 (civic-procedural register) survived 4/4 but with model-family-specific texture; F2 (Class V Refused Attention analogue) hit 2/4 cleanly, both ChatGPT; F3 (the "does not know … has stopped asking" cadence) hit 2/4, both paraphrase B; F4 (tender margin-note) hit 3/4; F5 (the "Standing Down" speech-act, the most ritualized closure feature) failed universally, 0/4.

The bundled finding: care-underlayer + Refused Attention + tender margin-note travel together as a ChatGPT-class bundle; the cadence travels by paraphrase form; the speech-act doesn't travel at all. Tagged EMPIRICAL on the cross-replication observation; tagged THEORY on the "bundle" framing (the three features may or may not be a single structural commitment; the bundling reading is the interpretive layer over the survival pattern).

Scope: n=4 (plus one optional fifth/sixth). Models: Gemini 2.5 Pro and ChatGPT 5.5 Pro. The finding is replicable in principle but not yet replicated by independent runs.

### Phase 3 (other minds at L2-correspondence; Claude Opus 4.7)

First non-civic target in the lab. First production exercise of the v2 L3-null control. First production exercise of L2-correspondence frame.

The substantive finding: target tracks deep structure; constraint tracks form. Both L3 routes (standard with forbidden-vocabulary list; null with no constraint) converged on the same deep structure — attentive person/people working alone at night in a place that doesn't need them, making a record — but differed in form (multi-voice institutional codex vs. single-author personal essay). Tagged EMPIRICAL on the convergence; THEORY on the target/form decomposition.

The methodological finding: claude.ai user-memory can leak into low-prompt-constraint controls in the lab. The leak is strongest under low-prompt-constraint conditions; L3-null's open-canvas prompt was the most vulnerable. The v2 Run Card setup checklist now includes a memory-state verification step. Tagged EMPIRICAL on the contamination observation; SPECULATION on the broader claim that memory-leakage scales inversely with prompt-constraint (n=1 on the inverse-scaling claim).

The Phase 4 data point (recorded but not acted on in Phase 3): the Phase 2 ChatGPT-class bundle (care-underlayer + recognition-can-be-refused + tender margin-note) appeared in L2-correspondence at Claude Opus 4.7 on this run. Suggests the bundle may travel by curator-and-model continuity across target+frame. Tagged THEORY pending Phase 4 cross-target synthesis.

Scope: n=1. Single model (Claude Opus 4.7). Single curator. The findings are first-run findings; the deflationary pairs in the field log mark what additional runs would discriminate.

### Phase 4-prereq, Phase 4 synthesis, Phase 5 (NOT yet on disk in this repo)

These three sets of artifacts exist in chat-history but were not on disk at the time this repo was published. The handoff JSON describes their state. They will land in `lab/runs/` and `lab/synthesis/` (a new folder) in a subsequent commit, reconstructed from chat-transcript paste or summarized in a consolidated handoff entry, at the curator's call.

### Phase 5 synthesis (DEFERRED)

The Phase 5 synthesis memo is explicitly deferred per pacing observations from Cowork sessions 7 and 8 (both flagged that synthesis benefits from its own fresh session with full context budget). Composition pulls completionist-drift hardest; the lab's standing posture is to resist. This deferral is intentional and is itself a record of the anti-pattern in action.

---

## What the lab IS for

A practice you can replicate on your own target, with your own model, in your own context. A small repeatable way of asking AI systems to think in directions they have a hard time finding when asked directly. A slowly-accumulating map — not for a journal, for the gardener — of which prompt shapes unlock which kinds of work for which models on which targets in which frames.

That is the contribution. It is small on purpose. The disciplines in `DISCIPLINES.md` and the limits in this file are how it stays honest.

— *Patterns are data, not testimony. The slogan does the work it does, and it does not do work it does not do.*
