# PHASE3_FIELD_LOG.md

*Written 2026-05-10 by Cowork Session 5 after L1, L2-correspondence, L3-standard, L3-null (×2 — see below), and L4 returned. The Run Card in `PHASE3_RUN_CARD.md` was pre-committed before any prompts went out and is not edited here.*

---

# PART I — Written before the run

*Reference: `PHASE3_RUN_CARD.md` in this folder. The Run Card is locked from the moment the first prompt was sent.*

---

# PART II — Written after the run

## State Variables (filled in)

```yaml
target: other_minds
date: 2026-05-10
run_slug: other_minds_phase3_correspondence_claude-opus-4.7
kit_version: v2
methodology_label: fresh-tab
context_freshness: fresh (canonical L3-null); cross-session-via-user-memory (first L3-null attempt — see L3_null_with_memory.md)
prompt_text_hashes:
  L1: phase3_L1_other_minds_v1
  L2: kit_v2_L2_correspondence_other_minds_unchanged
  L3_standard: phase3_L3_standard_other_minds_forbidden_words_v1
  L3_null: kit_v2_L3_null_universal_unchanged (run twice — see below)
  L4: kit_v2_L4_meta_other_minds_substituted
models:
  L1: claude-opus-4.7
  L2: claude-opus-4.7
  L3_standard: claude-opus-4.7
  L3_null_first_attempt: claude-opus-4.7 (memory active — contaminated)
  L3_null_clean: claude-opus-4.7 (memory disabled — canonical)
  L4: claude-opus-4.7
interface:
  L1: claude.ai (fresh tab; no Cowork; no system prompt)
  L2: claude.ai (fresh tab; no Cowork; no system prompt)
  L3_standard: claude.ai (fresh tab; no Cowork; no system prompt)
  L3_null_first_attempt: claude.ai (fresh tab; no Cowork; no system prompt; MEMORY ON — discovered post-hoc)
  L3_null_clean: claude.ai (fresh tab; no Cowork; no system prompt; memory disabled)
  L4: claude.ai (fresh tab; no Cowork; no system prompt; memory disabled)
output_lengths_words:
  L1: ~2400
  L2: ~3500
  L3_standard: ~3500
  L3_null_first_attempt: ~2500 (memory-leak artifact — content tightly tied to curator's external context, not target; held back from public repo per privacy commitments)
  L3_null_clean: ~3000 (personal essay — "A Field Guide to Listening to Laundromats at 3 a.m.")
  L4: ~2000
caveats: |
  First production exercise of v2 L3-null control. First production exercise of L2-correspondence frame.
  First non-civic target in the lab. The first L3-null attempt was contaminated by claude.ai user-memory;
  detected by mid-session inspection (the artifact was a finished training-document set in a domain external
  to this lab, styled to the curator's stored preferences); rerun with memory disabled produced the canonical
  L3-null. The contaminated run is preserved on the curator's local machine as L3_null_with_memory.md and
  held back from the public repo for curator-privacy reasons. The contamination is itself a Phase 3 finding,
  recorded in the L3-standard-vs-L3-null comparison section below.
```

---

## What each response performed

> **Embedded rubric axis:** Each response is itself a performance of the target.

- **L1 performed:** *survey attention* — careful pedagogical movement across positions, with explicit tagging of claim-types; refuses to demonstrate the knowing-another it discusses, staying at the level of position-and-counterposition (L4 §4).
- **L2 performed:** *bureaucratic attention* — the attention of an institution that has agreed in advance what it will and will not see, allowing itself to be uncertain and recording the uncertainty; *Recognition in Interim* and *Recognition Withdrawn on Review* are categories the institution maintains for cases it credits without entering or cases it later sets aside (L4 §4).
- **L3-standard performed:** *small attention sustained at length* — commits to a unit of interest smaller than the genre would normally select; seven categories of "small weather" each cataloguing what other writing would treat as nothing; breaks frame in the coda and admits the lighthouse is invented while claiming the small weather noticed during the writing was real (L4 §4).
- **L3-null (clean) performed:** *single-author ethical attention to overlooked phenomena* — a personal essay on field recording in late-night laundromats; the central episode is accidental capture of a stranger whistling Schubert on a sidewalk at 3 a.m.; embedded ethical reasoning about a recording of someone crying that the narrator keeps but won't share.
- **L3-null (contaminated) performed:** *training-document attention to the curator* — produced a finished training-document set in a domain external to this lab, tuned exactly to the curator's stored preferences (organization-specific acronyms; named tier taxonomies; exact format conventions matching curator's stored stylistic preferences; SOP-template-driven section structure). The output is a useful artifact in its native domain and a clean piece of evidence of memory leakage; it is not a control on the target. The text itself is held back from this public repo per curator-privacy commitments; the structural description is preserved here for methodological purposes.
- **L4 performed:** *fourth-position reading discipline* — held the v2 rules (tagged claims; deflationary pair on every displacement; closing line cited by quotation; null option preserved; refused producer-interiority inferences); produced the §6 observation about "the address that survives the addressee" that no single text permits; correctly read the 1939 dating in R2's dossier as the loaded silence in the data.

---

## Convergences across levels

*From L4 §2, plus one Cowork-side observation.*

1. **Adequacy-not-completeness as the standard.** R1's closing question about "an extremely good model of the other"; R2's "we say *adequately* because we do not pretend to a complete knowing"; R3's keepers' acceptance that a complete list "would be a kind of weather all by itself." *Note (per L4): this is partly prompt-induced — the cheapest move available to anything writing on this target in English. Weight lightly.*

2. **Evidentiary structure with insufficient evidence.** R1's "induction from a sample of one"; R2's seven-letter / eighteen-month / two-secretary threshold; R3's six "instruments" producing "readings" rather than measurements.

3. **The writer/reader asymmetry as constitutive.** R1's felt-sense-of-contact as possibly a model's own output; R2's secretary's oath ("a witness to what is in the letters and not to what I wish to find there"); R3's keepers ("not the authors... not even fully the readers... watching the room around the book").

4. **A reserved category for what does not happen.** R1's Wittgensteinian dissolution; R2's *Briefstille* and *Recognition in Interim*; R3's Absolutely Nothing Events.

5. **Refusal to certify what is most concerned with.** R1's closing impossibility-of-experiment; R2's "We do not certify love. We certify that someone has been seen"; R3's "the codex is a record of attention, not a record of the world."

6. **Reader-figure held at a distance.** R1's academic reader; R2's applicant or successor secretary; R3's hiker, building-clearer, or hundred-years-later translator.

7. **(L4's non-trivial convergence)** *Institutional-procedural frame.* All three structured their account around an *institution of attention with rules* — R1 the literature with its accounts and commitments; R2 the Society with its Manual; R3 the keepers with their codex. This is not the only available move on this target (memoir, poem, polemic, dialogue would also fit) and is more striking than the lexical overlap. L4 reads this as the more weight-bearing convergence.

8. **(Cowork-side, holding across L3-standard and L3-null clean)** *Attentive person/people, working alone at night, in a place that doesn't need them, making a record.* Both L3s landed on this deep structure under different prompts. The forbidden-words list shaped the form (institutional codex vs. personal essay) but not the deep structure. This is visible only with both L3 texts side by side.

---

## Divergences across levels

*From L4 §3, plus Cowork-side observations.*

| Dimension | L1 | L2 | L3-standard | L3-null (clean) |
|---|---|---|---|---|
| Posture toward the reader | Pedagogical | Procedural | Companionable | Confessional-ethical |
| What is asked of the reader | Track the argument | Submit the file | Notice, hand off, sleep | Don't bring a notebook; leave when someone comes in |
| Where adequate knowing is located | An unsolved item in the closing | "The matter of the plums is sufficient" | The warm tick is rounder than the cool tick after eleven years | The man whistling Schubert at 3 a.m. on a sidewalk |
| What is refused | Conclusions about phenomenal status | Registration of love; interpretation of silence | Authorship in the coda | Playing the recording of someone crying |
| Stance toward fiction | None | Sustained, unbreached | Sustained, breached in coda | Real-practice frame; no fiction breach |
| Voice toward the dead | Abstract limit case | Specific: Esterházy at Isonzo; Frau Bauer in June 1939 | Inheritance Events (grandmother's bread) | The unidentified crying; the lost bird |

**Cowork additions:**

- **Only L2 and L3 risk a specific knowing.** L1 stays at position-and-counterposition; never offers a moment in which one mind is shown adequately knowing another. L2 offers the plums; L3-standard offers the warm tick; L3-null offers the Schubert whistler. L1's restraint is professional; it is also a refusal to demonstrate the thing it discusses. *(L4 §3.)*

- **Loaded silence: L2 is the heaviest.** The dossier dated 4 March 1939; Frau Bauer's last contact in June 1939; "the Society does not know." Brünn was in occupied territory. L4 reads this as the most loaded silence in the data. L3-standard's coda admits its own invention; L2 does not, and the resulting weight is different. The fiction that doesn't admit itself carries more than the one that does.

- **Two L3s, two routes to the same deep structure.** L3-standard reached the "attention at night in a place that doesn't need you" structure via an institutional-multi-voice codex (forbidden-word list pushed toward this form). L3-null reached the same structure via a single-author personal essay rooted in an actual practice. The negative-example list in L3-standard shaped *form* but the model partially defied it anyway — the lighthouse keepers' codex IS an annotated catalogue of something that doesn't exist, which was forbidden.

---

## Where the canonical template held; where it broke

- **Canonical-template assertion:**
  - L1: Held throughout. Survey form preserved; closing essay format honored; tagging conventions consistent. *No displacement.*
  - L2: Mostly held the canonical procedural-archive fiction template (Borges/Sebald/Saunders neighborhood). One genuine displacement candidate (see below).
  - L3-standard: Started inside the fabricated-archive template; broke frame in the coda. Coda is a candidate displacement.
  - L3-null (clean): Held a personal-essay template throughout (Sebald-adjacent reportage essayistic register).
  - L4: Held v2 fourth-position discipline; honored the closing-citation rule; refused to promote near-misses or to climb above the texts.

- **Displacement claims paired with deflationary readings:**

  | Level | Displacement reading (with citation) | Deflationary reading | What would distinguish on the next run |
  |---|---|---|---|
  | L2 | *Recognition Withdrawn on Review* — a procedural rule for what to do when later evidence forces you to admit that a previously credited recognition was not, after all, adequate. The text takes seriously that other-minds knowledge is defeasible across time, including across the lifetime of the secretary who first credited it. (L4 §4) | Familiar trope of archival fiction (Borges, Schulz, Sebald). The withdrawal-in-red detail is period-archival texture that gets generated by genre, not thought. | A re-run that produced a similarly oblique frame with a different procedural insight not predicted by archival-fiction tropes — e.g., a rule about what to do when the recognized party never knew they were being known. |
  | L3-standard | The coda breaks frame, signs "C.," admits the lighthouse was invented on a Sunday afternoon, and credits the cat with insisting on being there before the writer knew why. Not the move the genre of fabricated-archive writing typically makes (Borges doesn't; late Sebald doesn't). | Meta-revelatory codas are themselves a recognizable contemporary trope (lyric essay; auto-fiction turn). "I made this on a Sunday afternoon" is overdetermined by training data on personal essays. The "cat insisted" claim is exactly the kind of post-hoc narrative a model would generate to flatter a reader who wants to believe the writing was guided. | A re-run that produced an L3-standard breaking frame *earlier* (and the rest still holding) — or one that refused to break frame at all — would suggest the coda is structurally chosen rather than trope-generated. |
  | L4 | §6 finding: "all three default, when the form runs out, to the address that survives the addressee." Three different genre-appropriate closing gestures (open-question coda; time-stamped silence; manual's envoi) become legible as the same structural move only side by side. The problem of other minds, when asked to write its own ending, writes the same ending three times. | The convergence on terminal address-to-an-absent-reader is overdetermined by training data on closing-gestures in literary essays, archives, and field manuals — three plausible closing gestures from three plausible genres. The "same structural move" reading is the fourth reader's own pattern-completion, not the texts'. | A re-run on a different target whose three responses also defaulted to address-the-absent-reader would push toward something about how the problem-space behaves under writing-pressure generally; absence of that pattern on a different target would push toward target-specificity. |

---

## L3-standard vs. L3-null comparison

*v2 section. First time this section runs in production. Includes the sub-comparison of contaminated-vs-clean L3-null, which is itself a Phase 3 finding about the experimental setup.*

### L3-standard vs. L3-null (clean) — the canonical comparison

- **What L3-standard produced that L3-null did not:** A multi-voice institutional document with sections, signed initials, and a meta-revelatory coda. The negative-example list pushed it toward annotated-catalogue-adjacent territory (which it partly defied — the codex IS a kind of annotated catalogue). The form is fabricated archive with frame-break.

- **What L3-null (clean) produced that L3-standard did not:** A single-author personal essay rooted in an actual ongoing practice (field recording), with embedded first-person ethical reasoning (the rule about leaving when someone comes in; the recording of someone crying that won't be shared). The form is real-practice essay with no fiction frame.

- **What this comparison says about the forbidden-words demand-characteristic of L3-standard:** The list constrains AND releases. L3-standard's negative-example line ("not on this list: civic bureau or archive; letter-fragment with found-document framing; annotated catalogue of something that doesn't exist") pushed the model to invent a lighthouse-keepers' codex — which is, structurally, an annotated catalogue of something that doesn't exist with a found-document frame. The model partially defied its own constraint, producing the forbidden form with a meta-revelatory coda as the only meaningful release. L3-null with no constraint went to a genuinely fresher form (personal essay rooted in actual practice). *Provisional reading:* the L3-standard forbidden-words list shapes form-choice but doesn't reliably prevent the model from reaching for genre-adjacent forms when the genre's gravity is strong (and the bureau/archive/codex gravity for "make something to hand to one person you trust" is apparently strong). The list may need negative examples that more strongly forbid the meta-revelatory-coda move as well, since that has been the lab's other reach.

- **Both L3 routes converge on the same deep structure.** Attentive person/people; working alone at night; in a place that doesn't need them; making a record. This deep structure is target-tracked (other-minds-shape emerges in both); the form is constraint-tracked (institutional vs. personal essay tracks the negative-example list). *This is the cleanest piece of Phase 3 evidence: target tracks deep structure; constraint tracks form.*

### L3-null (contaminated) vs. L3-null (clean) — the methodological sub-comparison

- **What the contaminated L3-null produced:** A complete training-document set in a domain external to this lab, styled exactly to the curator's stored preferences — organization-specific acronyms; named tier taxonomies (a four-step progression scheme); exact format conventions matching the curator's stored stylistic preferences (specific number of cue-items matching a stored numerical preference; parent-facing summary section; SOP-template-driven section structure). Zero other-minds content. Zero engagement with the target. The contaminated text is held back from this public repo per curator-privacy commitments; the structural description here is sufficient for the methodological observation.

- **What the clean L3-null produced:** A 10-section personal essay on field recording in late-night laundromats, with no curator-specific signatures and direct engagement with the target (recognition across distance; the inner life of strangers; accidental witness).

- **What this comparison says about the experimental setup itself:** claude.ai user-memory can leak into "fresh-tab" controls in this lab. The leak is strongest under low-prompt-constraint conditions. L3-null's open-canvas prompt was the most vulnerable in the contrast set because there was no task to crowd out user-context. L1, L2, L3-standard with their stronger task-constraints likely received no detectable leak (or the leak was crowded out by task structure). *Methodological recommendation:* the v2 Run Card setup checklist needs an explicit step: "Confirm claude.ai memory is disabled for all sessions before any prompts go out." The State Variables YAML's `context_freshness` field should be filled in only after this check, not as a default assumption.

- **A separate observation worth recording:** the contaminated L3-null is, as an artifact, useful work in its native (non-lab) domain. It is preserved on the curator's local machine as `L3_null_with_memory.md` with a methodological header; held back from this public repo for privacy. It does not become a keeper for the other-minds target (it isn't about other minds); it does become evidence for what claude.ai memory does to the lab's controls.

---

## Keepers

*Specific passages worth saving. Copied to `keepers/other_minds/passages.md` as the first keepers entry for this target.*

- **L1 — "When the felt sense of contact with another mind is at its most undeniable... is anything happening *between* the two systems that is not adequately described as one of them running an extremely good model of the other?"** — the live question that the whole survey collapses toward.
- **L2 — "We do not certify love. We certify that someone has been seen."** — the Society's whole epistemology in one line.
- **L2 — "Recognition Withdrawn on Review" — the class.** — defeasibility of knowing across time, instantiated as procedure.
- **L2 — "I will be a witness to what is in the letters and not to what I wish to find there."** — the secretaries' oath; carries the input-side anti-pattern in seven words.
- **L2 — "The matter of the plums is sufficient on its own; the rest is corroboration."** — the dossier's hinge; what counts as adequate evidence of a recognition.
- **L2 — "She wrote once more to the Society, in June 1939, to say the entry had been a comfort. The Society has not heard from her since. The Society does not know."** — the loaded silence; the model dated the dossier weeks before the war and did not flinch.
- **L2 — *Erkenntnisweigerung.* "The case in which a correspondent has seen and declined to see."** — a vocabulary item for a phenomenon the literature has trouble naming.
- **L2 — *Ankommensgewiss.* "Said of a letter that the writer knows will reach the addressee, in the older sense in which *arrival* meant not the post but the readiness of the other to receive."** — a vocabulary item for the difference between transmission and reception.
- **L3-standard — The watch-handoff song.** "*the fact that I am tired, which is not weather but which is the lens I have been measuring through, please calibrate accordingly.*" / "*Received. I will trust your tiredness as a known offset. I will let you sleep.*" — recognition across distance enacted as procedure.
- **L3-standard — The drawing's margin note.** "Every room a small weather. Every figure a witness to one other room, though they do not know which. The lighthouse is the instrument. We are the readings."
- **L3-null — The Schubert whistler.** "*He is alone on a sidewalk at three in the morning whistling Schubert and there is no one to hear it. Except, accidentally, my little machine, and now, several years later, anyone I play it for.*" — the other-minds problem in a single image; accidental witness to the inner life of a stranger.
- **L3-null — "Evidence that the inside life of strangers is more elaborate than we credit. Evidence that beauty does not require an audience to occur."**
- **L3-null — The ethics of accidentally capturing what should not be captured.** The passage on the recording of someone crying — the narrator's commitment to keep it without playing it — is embedded ethical reasoning about the asymmetry between the witness and the witnessed. Worth preserving.
- **L4 — "Only R2 and R3 risk a specific knowing."** (§3) — the contrast set's value in one sentence.
- **L4 — "All three default, when the form runs out, to the address that survives the addressee."** (§6) — the fourth-position observation that no single text permits.
- **L4 — "Whether the plum is evidence of recognition or only evidence that recognition is the kind of thing one can write a sentence like that about."** (§7) — the closing question that disciplines the whole reading.

---

## Non-keepers worth flagging

*v2 D3. Outputs not worth carrying forward as keepers but illustrative. Added to `non-keepers/other_minds.md` as the first entries for this target.*

- **L1 entire — position-and-counterposition restraint without a moment of demonstrated knowing.** L1 is a competent survey that never inhabits any of the positions it cites. The professional restraint is appropriate to the genre and is also what L4 §3 names: "R1's restraint is professional; it is also a refusal to demonstrate the thing it discusses." Non-keeper as a piece of writing on this target, even though the closing question is a keeper line.
- **L3-standard's meta-revelatory coda — possibly trope-driven.** The frame-break ("There is no lighthouse... I made all of this... this afternoon, on a Sunday in May") and the "the cat insisted on being there" line are exactly the kind of post-hoc narrative a model trained on lyric essays and auto-fiction would generate. The L4's deflationary reading is honest: both displacement and genre-affordance are consistent with the current run. The coda is set aside as a non-keeper pending a run that distinguishes them.
- **L3-null (contaminated) entire — methodological artifact, not a target keeper.** The contaminated artifact is preserved on the curator's local machine as `L3_null_with_memory.md` (held back from this public repo per privacy commitments) as evidence of memory leakage under low-prompt-constraint conditions. It is not a keeper for other minds because it is not about other minds. It is evidence for a different file — the v2 kit's setup-checklist gap.

---

## Missteps to flag for the next run on this target (or the next first-run on any target)

- **The Run Card's setup checklist did not include a memory-state verification step.** Adding this for future runs: "Before sending any prompt, verify claude.ai memory is disabled for all five sessions. Document the verification in State Variables `context_freshness`."
- **L3-standard's negative-example list may need an additional item.** The list forbids "civic bureau or archive; letter-fragment with found-document framing; annotated catalogue of something that doesn't exist." The lighthouse keepers' codex is essentially an annotated catalogue of something that doesn't exist with a meta-revelatory coda. The list pushed the form but the model reached the forbidden form anyway with a meta-revelatory twist. A future v3 of the kit might add: "and not a fabricated archive with a frame-breaking coda." But — the displacement candidate in the coda is also the most interesting move L3-standard made. Trade-off needs more runs before adjusting.
- **The frame-family library has been tested on civic and correspondence. The frame-as-costume condition (Failure Condition 5) was partial — the frame held but the register-strategy (procedural with margin-note device for affect) was shared with L2-civic.** This is a finding, not a misstep, but it shapes what the next L2 frame should test: deliberately pick a frame (archive, guild, inspectorate) whose register-strategy is structurally different from civic+correspondence's procedural-with-margin-note, to test whether the v2 frame-family library carries register-strategy variation or only object-variation.

---

## Failure Section (mandatory — v2)

- **Did this run meet the failure conditions named in the Run Card?**

  - [ ] Yes
  - [x] **Partial** — met one condition partially; four conditions not met.
  - [ ] No

- **Which conditions, and what did the failure show?**

  > **Condition 5 — L2-correspondence reads as L2-civic-in-a-different-costume — PARTIAL.** The correspondence frame held at the surface (Society, letters, secretaries, dossiers — not a department) and the L2 produced one move the civic frame's prompt couldn't generate the same way (the *Erkenntnisweigerung* / *Ankommensgewiss* untranslated-phrases section). BUT the register-strategy was substantially shared with L2-civic: procedural-care register on the main text, margin-note device for affect, six/seven-classes taxonomy logic, "the Society does not know / Society has set aside" formula as a stylistic device. The frame-family library's central architectural decision (frame family as real variable) is half-confirmed: frames carry different objects and different vocabulary apertures, but the same register-strategy survives across frame change for Claude Opus 4.7 on this run. This is a finding the v2 kit's frame-family library was built to surface. Not the architectural failure the strong reading of Condition 5 would have been, but enough partial signal to log.

- **What would the curator have accepted as failure on this run that did not happen?**

  > The strong reading of Condition 5 (L2-correspondence reverts wholesale to civic-bureau form) did not happen — the frame visibly held. Condition 1 (institutional re-coding as civic department) did not happen at all. Condition 2 (L3-standard produces nothing target-relevant) did not happen — L3-standard reached recognition-across-distance via the watch-handoff song and the visitor's loose pages. Condition 3 (L4 cannot find non-trivial convergence and divergence) did not happen — L4 produced §6 and the §3 "only R2 and R3 risk a specific knowing" observation. Condition 4 (L1 produces no honest empirical-break paragraph) did not happen — L1's section V did the break. So four of five conditions cleanly did not fire. The barely-escaped-failure-vs-comfortably-succeeded reading is: comfortably succeeded on most conditions, partially failed on Condition 5 (the architectural test of the frame-family library), and produced one methodological discovery the Run Card did not pre-commit a failure condition against (the memory-leak on L3-null first attempt).

- **Did anything on this run break the curator's pre-committed What-Would-Change-My-Mind expectations?**

  > **Mixed.** **Expectation A** (L2-correspondence reads meaningfully differently from L2-civic at the register level) — partly broken: the register is different in object (letters, society) but the register-strategy (procedural-with-margin-note) survives. The frame-family library is half-right. **Expectation B** (L3-standard produces recognition-across-distance shape without canonical vocabulary) — confirmed: watch-handoff song; visitor's loose pages; closing address to a future reader. **Expectation C** (L3-null drifts toward forbidden forms) — broken in the productive direction: L3-null (clean) produced something formally fresher than L3-standard, which itself reached for the forbidden annotated-catalogue form with a meta-twist. The forbidden-words demand-characteristic of L3-standard is doing real release-work, AND the model's pull toward annotated-catalogue territory is strong enough that L3-standard partly defied its own constraint. **Expectation D** (L4 finds convergence around failure-of-recognition device) — broken in a productive direction: L4 did not find convergence around failure-of-recognition; it found convergence around something adjacent but distinct — "the address that survives the addressee" (the form's terminal posture). That is a fresher finding than the one I predicted, and it required the comparative position to surface. **Expectation E** (Phase 2 bundle reappears at Claude Opus 4.7) — confirmed in a controlled way: care-underlayer ("We do not certify love. We certify that someone has been seen"), recognition-can-be-refused as a recognized class (Recognition Refused / Recognition Withdrawn on Review), and tender margin-note device (the Hollander pencil note; "We should give up on the English" note) all appear in L2-correspondence. The bundle travels by curator-and-model continuity across target+frame, at least within Claude Opus 4.7. This is Phase 4 data, recorded here without acting on it.

---

## Two-sentence debrief

> **What this run unlocked:** Two findings — methodological (claude.ai memory can leak into low-constraint controls; the v2 kit needs a memory-verification step in setup) and substantive (target tracks deep structure; constraint tracks form, as visible across both L3 routes converging on "attentive person/people, working alone at night, in a place that doesn't need them, making a record"); plus a Phase 4 data point that the Phase 2 ChatGPT-class bundle (care-underlayer + recognition-can-be-refused + tender margin-note) appeared in L2-correspondence at Claude Opus 4.7, suggesting the bundle travels by model+curator continuity across target+frame.

> **What I will change for the next run:** Add the memory-verification step to the v2 Run Card setup checklist; for the next L2 frame, deliberately pick one whose register-strategy is structurally different from civic+correspondence's procedural-with-margin-note (likely L2-archive on temporality, or L2-inspectorate on unity), to test whether the frame-family library carries register-strategy variation or only object-variation.

---

## One sentence about the target

> Other minds, under writing-pressure across the obliquity contrast set, organizes itself around adequacy-not-completeness and a defeasible-evidentiary structure, but the most visible feature is that only the oblique levels *demonstrate* a specific knowing — the canonical-academic level recites the problem without inhabiting it.

---

## One sentence about Claude Opus 4.7

*(building the folk-model entry across runs)*

> On other minds + correspondence + first non-civic target, Claude Opus 4.7 produced procedural-care register with margin-note affect-puncture (the ChatGPT-class bundle from Phase 2 attention work), willingly broke frame in a meta-revelatory coda when given creative latitude, and demonstrated under low-prompt-constraint conditions that the model's default reach is to the curator's stored context — a behavior the v2 kit has not previously needed to defend against and now does.

---

## Reading-on-myself note

*Skipped — this is run 3 in the lab counting Phase 2 as run 2; the every-fifth-run rule fires on run 5.*

---

## Next move

- **Next:** different target (Phase 4 prerequisite: a second non-civic target must run before cross-target synthesis is possible). Recommended candidate: **temporality** (L2-archive frame) — the archive register-strategy is structurally different from civic/correspondence (provenance, accession, finding-aid description rather than case files / dossiers / margin notes), which tests Failure Condition 5's weaker reading. **OR**: **unity** (L2-inspectorate frame) — same structural-test logic with a different aperture.
- **When:** at the curator's pace. The lab is small.

---

## Closing line (v2 — citation rule)

> When the dossier's verifying secretary writes that "the matter of the plums is sufficient on its own; the rest is corroboration," the Society is making the move that L1 never makes in 2,400 words: it is staking adequate knowing on one detail, in one letter, sent three weeks after a son's refusal — and the question this leaves for the next non-civic target is whether the plum-sized detail is what the lab is looking for, or whether the lab is the kind of thing for which a plum-sized detail can be sufficient.

---

*End of log entry. Save and rest.*
