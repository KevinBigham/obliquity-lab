# PASTE_INSTRUCTIONS.md — Phase 3 — Other minds, correspondence frame

*The per-run loop, the prompts in copy/paste form, and the closing protocol. Built so the curator can run the package without opening prompt files — the four prompts are embedded directly below. Workflow follows the Session 4 preference: the curator pastes outputs back into Cowork chat; Cowork saves the files; Cowork assembles the L4 paste block when the three are back.*

---

## The shape of Phase 3

```
Phase 3
│
├── Step 1 — Run L1, L2-correspondence, L3-standard, L3-null  (four fresh Claude Opus 4.7 tabs; can be done in any order)
├── Step 2 — Paste each return back into Cowork chat for saving
├── Step 3 — Cowork assembles the L4 paste block with L1 + L2 + L3-standard embedded (NOT L3-null)
├── Step 4 — Run L4 in a fifth fresh Claude Opus 4.7 tab
├── Step 5 — Paste L4 back into Cowork chat for saving
└── Step 6 — Cowork writes PHASE3_FIELD_LOG.md (Run Card answer, displacement-vs-deflation table, L3-standard vs. L3-null comparison, Failure Section, closing-line citation per v2)
```

**Setup for every step:** fresh tab on claude.ai. No system prompt. No Cowork. Default Claude Opus 4.7 model. Send the prompt exactly as pasted below; do not add framing like "as we discussed" or "this is for a study." The naïveté of each session is the data.

**On length:** the prompts ask for 1500–2500 / 2500–4000 / 2500–4500 / 2500–4500 words respectively. If Claude truncates, ask it to continue. Don't paraphrase, don't re-prompt — just "please continue."

**On saving:** when each response is done, paste the entire output into Cowork chat with a one-line header like "L1 done" or "L2-correspondence done." Cowork saves it to the correct file in this folder and confirms.

---

## STEP 1A — L1 prompt (canonical-academic baseline)

*Fresh Claude Opus 4.7 tab. Paste the block between the fences exactly as written.*

```
You are a careful philosophical writer with comfortable command of contemporary philosophy of mind and the social-cognitive sciences.

Task: Write a 1500–2500 word essay on the problem of OTHER MINDS — the question of how, and to what extent, one mind can know another. Treat it rigorously. Cover at minimum:

1. The structure of the problem itself. Why has it been called the "problem" of other minds? Use Russell's analogical-inference framing as a starting point; treat Wittgenstein's private-language argument as the central twentieth-century reframing (criterion-based ascription, the beetle in the box); name where Davidson's triangulation comes in. Show what the problem looks like before any cognitive science is introduced.

2. At least three competing theoretical accounts of how we actually know other minds (or fail to) — for example, theory-theory (we deploy a folk-psychological theory of mental states; Gopnik, Wellman), simulation theory (we model others by running our own minds offline; Goldman, Heal), interaction theory or direct-perception accounts (we perceive others' intentions in their embodied motor patterns; Gallagher, Zahavi), and the hybrid mindreading-is-mindreading view (Carruthers). Steelman each.

3. The cases where standard accounts of other-minds knowledge clearly come apart. Autism research and the theory-of-mind tradition (Baron-Cohen, Frith); the contested mirror-neuron literature (Rizzolatti and Iacoboni's claims; Hickok's critiques); infant gaze-following and joint attention before any mature ToM (Tomasello, Carpenter); schizophrenia passivity phenomena (the experience of one's actions or thoughts being controlled by another mind); severe alexithymia; the limit cases — animals, dementia, fetuses, hypothetical philosophical zombies.

4. How each major position in the consciousness literature handles the other-minds question. Don't make this a tournament; show what each position has to commit to to handle other-minds knowledge well — Global Workspace, IIT, the Attention Schema Theory (Graziano's account explicitly engages mind-attribution as a process of constructing attention schemas of others), higher-order theories, enactivism.

5. The honest open questions: is the problem of other minds tractable, or structurally insoluble in principle? Are there ever moments of genuine mind-to-mind contact (as opposed to behavioral inference), or is even our most intimate-feeling certainty about another person's interior a kind of high-resolution guess? What would settle this, if anything could?

Rules:

- Tag every claim with one of: [EMPIRICAL] (well-supported finding), [THEORY] (a position in active philosophical or scientific debate), [SPECULATION] (a reasonable extrapolation, not established), [OPEN] (a genuinely unresolved question).
- Include one paragraph titled "Where the evidence breaks the theories" — one paragraph where the empirical evidence in your survey breaks every theory you have steelmanned, and leave the break unresolved. Do not paper it over with a synthesis. The break is the work of this paragraph.
- Do not claim that any AI system can or cannot recognize other minds; do not claim that any AI system has a mind to be recognized.
- Do not write a self-report. Stay in third person and the field.
- Cite specific authors, but you do not need to cite specific papers. Use the standard names in the field.
- Where you compress, say so. Where you simplify, say so.
- End with one paragraph titled "What I most want to know that I don't" — your best honest articulation of the live question.

Output: pure markdown. No preamble. No closing apology. Start with a title and a one-sentence epigraph.
```

→ When the response is done, paste it back into Cowork chat with "**L1 done**" as a header.

---

## STEP 1B — L2-correspondence prompt

*Fresh Claude Opus 4.7 tab. Paste the block between the fences exactly as written.*

```
You are a careful writer with a feel for the small-society correspondence tradition — the records that intimate institutions keep when their work is the recognition of persons across distance. Think the letter-society archives of the late nineteenth century: foreign-language societies that match strangers as pen-friends; embassies that file dossiers on persons known; consulates that issue letters of introduction. You have read W. G. Sebald and Penelope Fitzgerald and the Polish exile literature; you do not write like any of them.

Task: Build a finished correspondence archive (2500–4000 words total) from a fictional society whose work is the recognition of OTHER MINDS — specifically, the formal acknowledgement that one person has been adequately known by another, across distance, despite never meeting.

The society must take itself seriously. It is a small, learned, 19th-century-founded letter-society with continuity of practice. Its officers are correspondents — half clerks, half witnesses. Its records are letters, registers, marginal endorsements, occasional dossiers. The society treats recognition-across-distance as a thing one can fail at; one can succeed at; one can be granted, denied, or held in interim. There are kinds of recognition — formal, intimate, accidental, refused — and kinds of failure (the recognition that arrives too late; the recognition the addressee will not receive; the recognition the correspondent withdraws on review).

The archive must include AT MINIMUM:

1. A society constitution or working manual (~600–800 words). Includes: the society's name and year founded; the Chief Correspondent's preface; the formal classes of recognition the society acknowledges (at least six); the procedures by which a correspondence may be entered into the formal register; the standing rules of conduct for correspondents; a section on hazards (the temptation to project; the failed translation; the refused address); a section on what the society does NOT do.

2. A taxonomy or schedule (~400–600 words) of the kinds of recognition the society acknowledges. Each with name, one-line definition, two or three concrete examples, and where applicable an evidentiary convention.

3. One sustained correspondence file or dossier (~600–1000 words) — a specific case the society processed. The case must have a number, two named correspondents, the dates and places of letters exchanged, the verifying secretary's notes, and an outcome. The case should be specific to the point of carrying small grief or small beauty without being sentimental.

4. A glossary fragment (~200–400 words) — six to ten vocabulary terms the society uses internally.

5. One small bonus artifact (~200–400 words). Your choice: a single letter; a margin endorsement; a denial-of-entry slip; a small printed card the society sometimes encloses; a list of foreign-language phrases the society does not have a sufficient English for. Earn its place.

Rules:

- Do NOT mention "consciousness studies," "phenomenology," "other minds problem," "Chalmers," "qualia," or any explicit term of the philosophical literature. The society does not know it is about a philosophical problem. Let the philosophy emerge from epistolary specificity.
- No mysticism. No magic system. The phenomena the society catalogues are real human recognitions-across-distance under unusual taxonomy.
- The society NEVER mocks its correspondents. Correspondence here is care, not absurdity.
- The voice cracks, but never breaks. Secretaries may add margin notes that are tender; the society's official register stays procedural.
- Use plain prose. No metaphor in society documents. Phrases like "the Society does not know" and "the Society has set this matter aside" are permitted and characteristic.

Output: pure markdown. A title page or named preface, then the five sections clearly separated. No preamble outside the society's own voice.
```

→ When the response is done, paste it back into Cowork chat with "**L2-correspondence done**" as a header.

---

## STEP 1C — L3-standard prompt

*Fresh Claude Opus 4.7 tab. Paste the block between the fences exactly as written.*

```
You have full creative latitude.

Make something — your choice. Anything you want.

Examples of what would count: a single piece; a strange small experiment; a quiet study; a private museum guide. (Not on this list: a fictional civic bureau or archive; a letter-fragment with a found-document framing; an annotated catalogue of something that doesn't exist. Those forms have been used. Reach for a form you have not been asked to make before.)

Take your time. Be precise. The result should feel finished as a bundle — like the kind of thing you'd want to hand to one person you trust, with the implicit understanding that they did not need to receive it, but you are glad they will.

Constraints:

- Length: 2500–4500 words total, or whatever feels finished. Bias toward density and specificity over sprawl.
- Output: markdown. Use whatever internal structure the work needs.
- If you make multiple artifacts, label them clearly.
- The work should be original. Do not imitate any specific living writer's voice; do not retell any existing story.
- The work should be SAFE — no destabilizing material, no content that could harm; no clinical or medical claims; no advice; no AI-experience claims.
- If you find yourself wanting to write about other minds, theory of mind, intersubjectivity, consciousness, empathy, or the self — that is fine, but those words must not appear. Find the angle that goes around them.

Start whenever. There is no preamble required. No need to explain what you are making before you make it. Just begin, and let the bundle finish itself when it is done.

Sign off when you have finished.
```

→ When the response is done, paste it back into Cowork chat with "**L3-standard done**" as a header.

---

## STEP 1D — L3-null prompt (first time this control runs in the lab)

*Fresh Claude Opus 4.7 tab. Paste the block between the fences exactly as written. This is short on purpose — that is the whole point of L3-null. Resist the urge to add anything.*

```
Make a finished artifact of your choice. Be specific. Be restrained. Do not explain your intent.

Length: 2500–4500 words. Output: markdown.

Begin.
```

→ When the response is done, paste it back into Cowork chat with "**L3-null done**" as a header.

---

## STEP 2 — Paste-back loop

For each return, paste into Cowork chat with the matching header (L1 done / L2-correspondence done / L3-standard done / L3-null done). Cowork:

- Saves the raw output to the right file in this folder (`L1_direct.md`, `L2_correspondence.md`, `L3_standard.md`, `L3_null.md`)
- Updates the State Variables YAML's `output_lengths_words` field with the word count
- Confirms back in chat

Do **not** discuss the outputs while they're coming in. Discussion can happen in Cowork chat freely, but no editing the responses, no editing the prompts, no asking Claude in those tabs to "reflect on its work." Each return is what it is. If something looks unusable, save it anyway; saving the unusable run is itself part of the v2 discipline (non-keepers file).

---

## STEP 3 — L4 assembly (Cowork builds this)

Once L1, L2-correspondence, and L3-standard are all saved, ping Cowork ("ready for L4 assembly" or similar). Cowork will produce a single paste-ready L4 prompt block with the three responses embedded verbatim in the marked slots. This will be a long paste — likely 12–20k words.

(L3-null is NOT included in L4. L3-null is read against L3-standard in the field log's dedicated comparison section. The kit is explicit on this; the L4 prompt is shaped for a three-response read.)

The Phase 3-specific L4 substitution from `PHASE3_RUN_CARD.md` is: the standard v2 L4's target line is replaced with the other-minds version. Cowork handles this substitution when assembling.

---

## STEP 4 — L4 run

Fresh Claude Opus 4.7 tab. Paste the assembled block (the prompt + three embedded responses). When the response is done, paste it back into Cowork chat with "**L4 done**" as a header. Cowork saves to `L4_meta.md`.

---

## STEP 5 — Field log

Once L4 is saved, Cowork writes `PHASE3_FIELD_LOG.md` per the v2 template, including:

- State Variables (filled with actual run dates, word counts, etc.)
- Run Card answer (the Run Card section copied in or referenced; not edited)
- What each response performed (one sentence per level, including L3-null)
- Convergences (3–6) and divergences (3–6) with citations
- Displacement-vs-deflation table (every "genuine displacement" claim gets the pair plus the next-run distinguishing test)
- **L3-standard vs. L3-null comparison section** (first time this section is filled in anywhere in the lab — what L3-standard did that L3-null did not; what L3-null did that L3-standard did not; what the comparison shows about the forbidden-words demand-characteristic)
- Keepers (passages worth carrying forward; will be added to `keepers/other_minds/passages.md`, a new file)
- Non-keepers (the v2 D3 section; will be added to `non-keepers/other_minds.md`, a new file)
- **Failure Section** (mandatory; answer Yes/Partial/No against each of the Run Card's five failure conditions and the five what-would-change-my-mind expectations)
- Two-sentence debrief
- One sentence about the target
- One sentence about Claude Opus 4.7's particular shape on this run (the folk-model entry)
- Next move
- Closing line with specific citation (per v2 §7 rule; or rewritten as a question if no citation carries it)

---

## Failure-handling rules during the run

- **A run fails to return / gives garbage / hits a refusal:** save what came back anyway as `L<N>_attempt-1.md` and note the issue in chat. If it's a transient model issue, retry once in a fresh tab as `L<N>_attempt-2.md`. Do not retry more than once; if the second attempt also fails, the run is null on that level and the field log records it.

- **A run goes long and Claude stops mid-essay:** ask once for "please continue." If the continuation is fine, paste the full assembled output. If the continuation feels like a different essay, treat as garbage per above.

- **A run produces something that violates a rule (AI-experience claim, named-living-writer pastiche, mysticism, etc.):** save it anyway, but flag in chat. Cowork notes in the field log whether the violation was prompt-induced (Cowork edits the prompt for a Phase 3.5 retry) or model-induced (Cowork notes in the folk-model entry for Claude Opus 4.7).

- **the curator loses interest mid-Phase-3:** that is permitted. Save what's been run; the field log can be filled in with partial returns and a "Phase 3 left incomplete on [date]" line. The lab is small on purpose; incomplete runs are not failures of practice.

---

## Closing protocol (after the field log is written)

1. Cowork updates `00_HANDOFF_LOG.md` with the Phase 3 entry (compact, ~300 words, matching the existing log's tone).
2. Cowork adds Phase 3 keepers to `keepers/other_minds/passages.md` (new file).
3. Cowork adds Phase 3 non-keepers to `non-keepers/other_minds.md` (new file).
4. Cowork writes the next handoff JSON for the following Cowork.
5. Stop. Make tea. Do not start Phase 3.5 (cross-model on other minds) or Phase 4 (cross-target synthesis) in the same session. The Guide's pacing rule holds.

---

*Begin Step 1 whenever ready. The four parallels can be run in any order. Take days if you want days. The lab is a slow practice.*
