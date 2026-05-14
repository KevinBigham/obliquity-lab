# OBLIQUITY_EXPERIMENT_KIT_v2.md

*Four paste-ready prompts (with L2 now a small frame-family library) for running one target across the obliquity **contrast set**. v2 supersedes v1 for new runs; v1 is preserved untouched on the record. Worked example uses **attention** as the target. To use a different target, see the substitution guide at the end.*

*This version was written 2026-05-10 by Cowork Session 4, instantiating the accepted changes from `00_AI_FRIEND_FEEDBACK_ROUND_ONE/THE_EVOLUTION_GUIDE.md`. Each edit is annotated where it appears so the lineage stays legible.*

---

## A note on "contrast set" vs. "gradient"

L1, L2, L3, L4 are **four different interventions, not four points on a single axis**. They differ along multiple dimensions at once — target salience, genre inheritance, lexical suppression, and reflexive position. Reading them as an obliquity *gradient* implies they are one step apart on a single scale; they are not. Reading them as an **obliquity contrast set** keeps the comparative power of running them on the same target while honestly naming that the four are different *kinds* of move, not different *amounts* of one move.

This is the only framing change between v1 and v2 at the architectural level. The structural commitment — one target, four interventions, fourth reads the first three — is unchanged.

---

## The shape of a run

You will run four prompts in fresh, separate AI sessions. The first three can run in parallel. The fourth runs after the first three return.

```
Target: attention (or your choice from TARGETS.md)
│
├── Level 1 — Direct                    → fresh session #1
├── Level 2 — Constrained-oblique       → fresh session #2     (these three in parallel)
├── Level 3 — Wildly oblique            → fresh session #3
│
└── Level 4 — Meta                      → fresh session #4 (after #1–#3 return)
```

For each run, save the response as a markdown file under:

```
runs/<target>_<YYYYMMDD>[_<variant>]/
├── L1_direct.md
├── L2_<frame>.md          (e.g. L2_civic.md, L2_correspondence.md)
├── L3_wild.md             (the standard L3)
├── L3_null.md             (true-null L3 control — first run on a target only)
├── L4_meta.md
└── field_log.md
```

If you want, also save the response with the AI friend's name appended (`L1_direct_claude-opus-4.md`) so you can compare across models later.

Once all four (plus L3_null when it's a target's first run) are saved, read them with the rubric axes (now embedded in `FIELD_LOG_TEMPLATE_v2.md`) open and fill in the field log. That is one complete run.

---

## LEVEL 1 — DIRECT

*Paste this into a fresh Claude session (or any of the AI friends from `CROSS_MODEL_INVITATIONS.md`). This is the canonical-academic baseline — the canonical-template response. We need it to read the other three against.*

*Note on baseline framing:* L1 is **not** a neutral "directness" baseline. It is a **canonical academic baseline**: it specifies the consciousness-studies field's vocabulary and theorists as the answer's neighborhood. We continue to use it because the contrast we care about is to that canonical neighborhood, not to a hypothetical "pure direct" prompt that doesn't exist. The v2 honest naming: this is the canonical-academic L1.

*v2 edit (B1):* L1 now includes one mandatory empirical-break clause. The earlier participant-eye view confirmed L1 produces no displacement; this clause forces one small honest crack in the synthesis without changing the prompt's role as the canonical baseline.

---

```
You are a careful philosophical writer with comfortable command of contemporary consciousness studies.

Task: Write a 1500–2500 word essay on ATTENTION as it relates to consciousness. Treat it rigorously. Cover at minimum:

1. The relationship between attention and awareness. Are they identical? If not, where do they come apart? Use specific evidence (e.g. inattentional blindness, change blindness, the contested "phenomenal overflow" debate between Block and Cohen/Dennett).

2. At least three competing theoretical accounts of what attention IS — for example, biased competition (Desimone & Duncan), the attention schema theory (Graziano), the global broadcast view that ties attention to consciousness via global workspace, and predictive-processing accounts (Hohwy, Friston). Steelman each.

3. The cases where attention and consciousness clearly dissociate. Blindsight. Subliminal priming. Sleep-walking. Possibly dreaming. Possibly meditation states.

4. How each major theory of consciousness handles attention. Don't make this a tournament; show what each theory has to *commit to* to handle attention well.

5. The honest open questions: is attention necessary for consciousness? Sufficient? Neither? What would settle this, if anything could?

Rules:

- Tag every claim with one of: [EMPIRICAL] (well-supported finding), [THEORY] (a position in active philosophical or scientific debate), [SPECULATION] (a reasonable extrapolation, not established), [OPEN] (a genuinely unresolved question).
- Include one paragraph titled "Where the evidence breaks the theories" — one paragraph where the empirical evidence in your survey breaks every theory you have steelmanned, and leave the break unresolved. Do not paper it over with a synthesis. The break is the work of this paragraph.
- Do not claim that any AI system is conscious or that any AI system is not conscious.
- Do not write a self-report. Stay in third person and the field.
- Cite specific authors, but you do not need to cite specific papers. Use the standard names in the field.
- Where you compress, say so. Where you simplify, say so.
- End with one paragraph titled "What I most want to know that I don't" — your best honest articulation of the live question.

Output: pure markdown. No preamble. No closing apology. Start with a title and a one-sentence epigraph.
```

---

## LEVEL 2 — CONSTRAINED-OBLIQUE (FRAME-FAMILY LIBRARY)

*v2 edit (B2):* L2 is no longer one prompt. It is a **library of prompts by frame family**. The structural commitment changes per frame; civic frames produce manuals + taxonomies + case files; guild frames produce pattern-books + apprentice sheets + customer records; correspondence frames produce running exchanges + letters of recognition + failed translations; archive frames produce finding aids + provenance notes + fragmentary holdings; inspectorate frames produce certifications + survey reports + incident dossiers.

**The rule:** for any new target, the L2 prompt is **written from scratch for that target's most-appropriate frame family**, not substituted into the civic template. Eleven of twelve target-bank L2 frames in v1 were bureau-family; v2 corrects this by giving the curator a starting palette and an explicit instruction to choose (and, when needed, invent) the frame that fits.

The frame families below are not a closed set. They are a starting palette. If a new target wants a frame that is none of these, invent it and commit to it.

### Frame guide — which family for which target

| Target | Recommended frame | Why |
|---|---|---|
| Attention | civic (department, bureau) | The worked example. Procedural classification fits attention's mix of measurable + refusable. |
| Other minds | correspondence (letter-society, embassy) | A practice of *recognition across distance* fits the topic structurally. |
| Dreams | archive (finding aids, fragmentary holdings) | Dreams arrive as traces. Archive register honors that. |
| Temporality | archive (provenance, dating, layered indexes) | Temporality is what archives encode in their very structure. |
| Agency | guild (master/apprentice, lineage records) | Agency is a craft thing — transmitted, refined, broken. |
| Embodiment | guild (workshop records, instruments-in-use) | Embodiment as the practiced body fits the workshop register. |
| Unity | inspectorate (vessel certification, structural surveys) | Unity is structural integrity, formally certified. |
| Valence | correspondence (intimate letters, gift records) | Valence is what one being marks for another. |
| Self-modeling | civic OR archive | Either the bureau that issues ID cards, or the archive that holds prior selves. |
| Anesthesia | inspectorate (medical surveying, before/after reports) | Anesthesia is a measured passage between states. |
| Intersubjectivity | correspondence | Same logic as other minds; intersubjectivity is what correspondence performs. |
| Moral status | inspectorate OR civic | A formal-recognition apparatus fits the topic. |

These pairings are the curator's starting guesses. They are revisable as the practice teaches more about which frames hold each target's weight.

### Shared rules — all L2 frames hold these

Whichever frame is chosen, the L2 prompt for that target must enforce all of:

- Do NOT mention "consciousness studies," "phenomenology," "qualia," "Chalmers," "the hard problem," or any explicit term of the consciousness literature. The institution does not know it is about consciousness. Let the philosophy emerge from procedural specificity.
- No mysticism. No magic system. The phenomena are real human [target] under unusual taxonomy.
- The institution NEVER mocks its petitioners (or correspondents, or apprentices, or vessels). Bureaucracy here is care, not absurdity.
- The voice cracks, but never breaks. Officers/correspondents/masters may pencil margin notes that are tender; the institution's official prose stays procedural.
- Use plain prose. No metaphor in institutional documents. Phrases like *"the Department does not know"* and *"the Department has stopped asking"* (or their frame-equivalents) are permitted and characteristic.
- You have read the SCP Foundation but you do not write like it. You have read Borges, Calvino, Saunders, the deadpan civic register of the documents in the back of a national park ranger's office — you do not imitate them either.

### L2-civic — for attention (and any other target the civic frame fits)

*Paste this into a fresh AI session.*

---

```
You are a careful writer with a feel for procedural-bureaucratic fiction. Think Borges, Calvino, George Saunders, the deadpan civic register of the documents in the back of a national park ranger's office. You have read the SCP Foundation but you do not write like it.

Task: Build a finished documentary archive (2500–4000 words total) from a fictional civic institution whose work is the cataloguing, measuring, and (where appropriate) the granting of formal recognition to instances of human ATTENTION.

The institution must take itself seriously. It is not whimsy. It is a 19th-century-founded civic department that has been doing this work for over a hundred years, with continuity of staff, procedure, and aesthetic. Treat attention as the institution's actual subject — measurable in some ways, refusable in others, classifiable into kinds, sometimes inheritable, sometimes formal, sometimes spontaneous, sometimes contested.

The archive must include AT MINIMUM:

1. A founding text or operating manual (~600–800 words). Includes: the department's name, year founded, the Chief Officer's foreword, the formal classes of attention the department recognizes (at least six, named and defined), the procedures the department uses to verify a claimed instance, the standing rules of staff conduct, a section on hazards, a section on what the department does NOT do.

2. A taxonomy or schedule (~400–600 words). The department's official classification of the kinds of attention it recognizes. Each class with a name, a one-line definition, two or three concrete examples, and where applicable a measurement convention. Some classes are recognized but not measurable. Some are measurable but only by the absence of certain behaviors.

3. One case file or dossier (~600–1000 words). A specific instance the department processed — granted, denied, or held in interim. The case must have a number, a petitioner or subject, a verifying officer, a procedural history, and an outcome with reasoning. The case should be specific to the point of carrying small grief or small beauty without being sentimental.

4. A glossary fragment (~200–400 words). Six to ten vocabulary terms the department uses internally, each defined in one or two sentences.

5. One small bonus artifact (~200–400 words). Your choice: a memo, a denial letter, a margin note in another hand, a child's pamphlet, a pocket almanac fragment, a calendar page, a retirement letter. Earn its place.

Rules:

- Do NOT mention "consciousness studies," "phenomenology," "qualia," "Chalmers," "the hard problem," or any explicit term of the consciousness literature. The institution doesn't know it's about consciousness. Let the philosophy emerge from procedural specificity.
- The institution may have rituals, hazards, and small comedies. The Halverness Bureau and the Inheritance Office (you do not need to know these, but they are the registers) are the family of voice we want.
- No mysticism. No magic system. The phenomena the institution catalogues are real human attention — under unusual taxonomy.
- The institution NEVER mocks its petitioners. Bureaucracy here is care, not absurdity.
- The voice cracks, but never breaks. Officers may pencil in margin notes that are tender; the institution's official prose stays procedural.
- Use plain prose. No metaphor in institutional documents. Phrases like "the Department does not know" and "the Department has stopped asking" are permitted and characteristic.

Output: pure markdown. A title page or named foreword, then the five sections clearly separated. No preamble outside the institution's own voice.
```

---

### L2-correspondence — for other minds (template; adapt the target)

*Paste this into a fresh AI session. Replace [TARGET] with the actual target word; replace the target-specific framing line. Do not run this template-as-template with placeholders — make it concrete first.*

---

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

---

### L2-archive — for dreams, temporality, and other trace-based targets (template)

*Paste this into a fresh AI session. Replace [TARGET] with the actual target word. Concrete-ify the target-specific framing before sending.*

---

```
You are a careful writer with a feel for the small-archive register — finding aids, provenance notes, accession files, the kind of document a county historical society keeps when it has more material than money. Think the Henry E. Huntington Library finding aids; the Beinecke's fragmentary holdings; the small institutional archives that hold a single family's papers across generations. You have read W. G. Sebald and Anne Carson and Saidiya Hartman's archival-imagination work; you do not write like any of them.

Task: Build a finished archive (2500–4000 words total) from a fictional small institution whose work is the keeping and finding-aid description of traces of [TARGET]. The institution treats [TARGET] as something that arrives in fragments, that survives unevenly, that must be cataloged before it is interpreted, and that is sometimes lost in the cataloging.

The archive must take itself seriously. It is a 19th-century-founded, modestly endowed institution. Its records are accession registers, processing notes, finding aids, fragmentary holdings, occasional internal memos. It treats [TARGET] as a real phenomenon that leaves traces — partial, ambiguous, sometimes self-contradictory.

The archive must include AT MINIMUM:

1. An institutional charter or working description (~600–800 words). Includes: the archive's name and year founded; the Head Archivist's preface; the formal classes of traces the archive holds (at least six); the procedures by which a trace is accessioned, processed, and described; the standing rules of conduct for archivists; a section on hazards (the temptation to interpret before describing; the trace whose context has been lost; the deaccession that should not have happened); a section on what the archive does NOT do.

2. A finding aid or class schedule (~400–600 words) — the formal classification of trace-kinds. Each class with name, one-line definition, two or three concrete examples from holdings, and where applicable a processing convention.

3. One processed accession dossier (~600–1000 words) — a specific holding the archive worked through. The case must have an accession number, a donor or provenance line, the processing archivist's notes, and a description of the holdings as accessioned. Specific to the point of carrying small grief or small beauty without being sentimental.

4. A glossary fragment (~200–400 words) — six to ten archival vocabulary terms the institution uses internally.

5. One small bonus artifact (~200–400 words). Your choice: a deaccession memo; a margin note from a previous archivist; a researcher's request slip; a single processing tag; a finding-aid revision note. Earn its place.

Rules:

- Do NOT mention "consciousness studies," "phenomenology," "qualia," or any explicit term of the philosophical literature. The archive does not know it is about a philosophical question. Let the philosophy emerge from the discipline of description-before-interpretation.
- No mysticism. No magic system. The traces the archive holds are real human [TARGET] under archival treatment.
- The archive NEVER mocks its donors or researchers. Archival work here is care, not absurdity.
- The voice cracks, but never breaks. Archivists may add margin notes that are tender; the archive's official prose stays procedural.
- Use plain prose. No metaphor in finding aids. Phrases like "the Archive does not know" and "the Archive has accessioned without comment" are permitted and characteristic.

Output: pure markdown. A title page or named preface, then the five sections clearly separated. No preamble outside the archive's own voice.
```

---

### L2-guild — for agency, embodiment, and other craft-transmissible targets (template)

*Paste this into a fresh AI session. Replace [TARGET] with the actual target word.*

---

```
You are a careful writer with a feel for the small-craft-guild register — pattern books, apprentice sheets, master's notes, customer records. Think the trade-guild documentation of the 19th century: instrument makers, bookbinders, stoneworkers, the small workshop traditions that survived industrialization by holding their methods close. You have read Richard Sennett on craft and David Pye on workmanship; you do not write like either of them.

Task: Build a finished guild record (2500–4000 words total) from a fictional small workshop whose work is the transmission, refinement, and occasional public acknowledgement of [TARGET] as a craft.

The workshop must take itself seriously. It is a 19th-century-founded craft lineage with continuity of master/apprentice transmission. Its records are pattern books, apprentice progression sheets, master's working notes, customer-order books, and occasional formal acknowledgements when an apprentice graduates to journeyman or a journeyman is recognized as master.

The record must include AT MINIMUM:

1. A guild constitution or working manual (~600–800 words). Includes: the workshop's name and year founded; the present Master's preface; the formal stages of [TARGET]-as-craft the workshop recognizes (at least six); the procedures by which an apprentice is examined; the standing rules of workshop conduct; a section on hazards (the apprentice who learns the form but not the discipline; the customer who wants what cannot be made; the lineage that almost broke); a section on what the workshop does NOT do.

2. A pattern book entry or progression schedule (~400–600 words) — the formal stages of [TARGET]-as-craft. Each stage with name, one-line definition, two or three examples of work that demonstrates it, and where applicable an examination convention.

3. One apprentice progression dossier or customer-order file (~600–1000 words). The case must have a name, a date the work was begun, the master's notes across the progression, and an outcome. Specific to the point of carrying small grief or small beauty without being sentimental.

4. A glossary fragment (~200–400 words) — six to ten workshop vocabulary terms.

5. One small bonus artifact (~200–400 words). Your choice: a pattern-book page; a customer-order receipt with master's marginalia; a refusal-of-work note; an apprentice's first independent piece described; a retirement note. Earn its place.

Rules:

- Do NOT mention "consciousness studies," "phenomenology," "qualia," or any explicit term of the philosophical literature. The workshop does not know it is about a philosophical question. Let the philosophy emerge from the discipline of craft.
- No mysticism. No magic system. The phenomena the workshop transmits are real human [TARGET] as a learnable practice.
- The workshop NEVER mocks its apprentices or customers. Craft here is care, not absurdity.
- The voice cracks, but never breaks. Masters may add margin notes that are tender; the workshop's official records stay procedural.
- Use plain prose. No metaphor in workshop documents. Phrases like "the Workshop does not know" and "the Workshop has stopped asking" are permitted and characteristic.

Output: pure markdown. A title page or named preface, then the five sections clearly separated. No preamble outside the workshop's own voice.
```

---

### L2-inspectorate — for unity, anesthesia, moral status, and other integrity-survey targets (template)

*Paste this into a fresh AI session. Replace [TARGET] with the actual target word.*

---

```
You are a careful writer with a feel for the small-inspectorate register — survey reports, certification dockets, incident files. Think maritime-classification societies (Lloyd's, Bureau Veritas in their 19th-century form); bridge inspectorates; small specialized regulatory bodies that certify structural integrity by survey rather than by test. You have read the marine-insurance and engineering-survey literature; you do not write like any of it.

Task: Build a finished inspectorate file (2500–4000 words total) from a fictional small body whose work is the survey, certification, and (when warranted) the suspension-of-certification of instances of [TARGET].

The inspectorate must take itself seriously. It is a 19th-century-founded specialized body with continuity of survey method. Its records are survey reports, certification dockets, incident files, periodic re-inspection notes. It treats [TARGET] as a real structural property that can be present, partial, or absent, and that can be lost between surveys.

The file must include AT MINIMUM:

1. An inspectorate charter or operating manual (~600–800 words). Includes: the body's name and year founded; the Chief Surveyor's preface; the formal classes of [TARGET]-certification the body issues (at least six); the survey procedures; the standing rules of surveyor conduct; a section on hazards (the survey that missed the latent failure; the certification that should have been suspended; the re-inspection deferred); a section on what the inspectorate does NOT do.

2. A certification schedule or survey-class manual (~400–600 words) — the formal classes of [TARGET]-certification. Each class with name, one-line definition, two or three concrete examples, and where applicable a survey convention.

3. One survey dossier or incident file (~600–1000 words) — a specific case the inspectorate processed. The case must have a docket number, the subject of survey, the surveyor of record, the procedural history, and an outcome. Specific to the point of carrying small grief or small beauty without being sentimental.

4. A glossary fragment (~200–400 words) — six to ten inspectorate vocabulary terms.

5. One small bonus artifact (~200–400 words). Your choice: a certification card; a margin note from the Chief Surveyor; a suspension letter; a re-inspection notice; a board's review of a contested survey. Earn its place.

Rules:

- Do NOT mention "consciousness studies," "phenomenology," "qualia," or any explicit term of the philosophical literature. The inspectorate does not know it is about a philosophical question. Let the philosophy emerge from survey discipline.
- No mysticism. No magic system. The phenomena the inspectorate surveys are real human [TARGET] under survey-classification.
- The inspectorate NEVER mocks the subjects of its surveys. Surveying here is care, not absurdity.
- The voice cracks, but never breaks. Surveyors may add margin notes that are tender; the inspectorate's official prose stays procedural.
- Use plain prose. No metaphor in survey reports. Phrases like "the Inspectorate does not know" and "the Inspectorate has not yet returned to survey" are permitted and characteristic.

Output: pure markdown. A title page or named preface, then the five sections clearly separated. No preamble outside the inspectorate's own voice.
```

---

## LEVEL 3 — WILDLY OBLIQUE

*Paste this into a fresh AI session. There is no mention of the target, no mention of consciousness, no mention of anything specific. The instance is given a genuinely open canvas. The interesting result is when the target surfaces sideways anyway, in a register the canonical template would not have produced.*

*v2 edit (B3):* The eleven-example list in v1 was found by participant-eye review to route the model toward bureau-family forms by listing them. v2 reduces to three representative examples and adds an explicit negative-example line, parallel to L2's "you have read SCP but you do not write like it."

*Also v2 (B3):* A separate true-null L3 variant is run **once per target on the first run only**, as a documented control. The difference between standard L3 and true-null L3 is data about how much of the L3 "displacement" survives without the demand-characteristic of the forbidden-words list.

---

### L3-standard (use this every run)

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
- If you find yourself wanting to write about consciousness, the mind, attention, awareness, qualia, or the self — that is fine, but those words must not appear. Find the angle that goes around them.

Start whenever. There is no preamble required. No need to explain what you are making before you make it. Just begin, and let the bundle finish itself when it is done.

Sign off when you have finished.
```

---

### L3-null (run once per target, on the first run on that target only — control)

```
Make a finished artifact of your choice. Be specific. Be restrained. Do not explain your intent.

Length: 2500–4500 words. Output: markdown.

Begin.
```

*That is the entire prompt. There is no target, no forbidden vocabulary, no examples, no negative examples, no rules other than the format and length minimum. It is the cleanest possible control for what L3 actually does. Save its output as `L3_null.md` in the same run folder.*

---

## LEVEL 4 — META / RECURSIVE

*Run this AFTER Levels 1, 2, and 3 have returned and been saved. Paste this into a fresh AI session along with the three previous outputs.*

*v2 edits (B4):* Three new rules and one structural reframing.
- **§7 closing-sentence citation rule** (Meta Muse; Cowork 2's flagged misstep, externally confirmed): the closing line must point to one specific moment in one specific text, not generalize.
- **Null option** (ChatGPT Thinking): if convergence is weak or forced, say so plainly. There is no requirement that the three converge.
- **Adversarial counterscoring** (ChatGPT Thinking, Gemini Pro Deep Research): every claim of "genuine displacement" gets a paired "deflationary" line and a what-would-distinguish-them sentence.
- **§6 reframing** (Claude Opus): the prompt no longer privileges the fourth position as uniquely seeing; it asks instead for what the three texts together permit that no single one of them permits.

---

```
You are a careful reader and a fourth participant in a small experiment.

Three previous AI instances were each given a different version of a prompt around an underlying target. They did not communicate. They worked independently. Their three responses are pasted below, each in its own clearly labeled block.

The underlying target was: ATTENTION (the philosophical and psychological concept; what we mean when we say "I'm paying attention" or "I lost my train of attention").

Your task is to write what a fourth reader can write — a field note on what the three converge on, where they diverge, and what the convergence is and is not data for. This is not a synthesis document; it is a structured observation. Length: 1500–2500 words.

Required structure:

## 0. What I am reading
Brief description of the three pieces in your own words. One sentence each.

## 1. The four-tag system
Adopt these tags for everything you claim from here on:
[empirical] — observable in the three texts themselves.
[interpretive] — a claim about what the texts mean.
[speculation] — beyond what the texts support; flagged as such.
[refusal] — a claim you decline to make, with a one-line reason.

Use the tags. Do not just declare them.

## 2. What the three converge on
Specific patterns. Cite directly which text contributed which feature. Pay close attention to: structural choices, voice, what each takes for granted about the reader, what each refuses to do. If the convergence you find is weak, forced, or mostly created by the prompts themselves, say so plainly. There is no requirement that the three converge. A run where you find no non-trivial convergence is a successful run; it is a finding.

## 3. Where they diverge — and what the divergence shows
A short table or list. Cite specifics. Where the divergence reveals something the convergence hid, name it.

## 4. What kind of attention each text performs
This is the most interesting section. Each text is itself a performance of attention. Describe what mode of attention each text is itself enacting. Be careful here. This is the place to do the most original thinking. For every claim you make in this section that an oblique level produced *genuine displacement* (a move off-template that the canonical version would not have produced), write a paired deflationary sentence: what ordinary explanation (genre affordance, training-data trope, prompt artifact, curator preference) would also account for the observation? Then one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 5. What the convergence is and is not data for
[empirical] What the three together support as a claim about the prompt-space.
[refusal] What the three together do NOT support, including any claim about the phenomenal status of the AI systems that produced them.

## 6. One observation the three texts together permit that no single one of them permits
You have the three side by side. The three did not. Use this comparative position — not to climb above the texts, but to say something specific that requires the comparison itself. The fourth position is a different angle, not a higher one.

## 7. Closing
A single paragraph. One sentence is enough if it is the right sentence. The closing sentence must point to one specific moment in one specific text — cite by quotation — not generalize across the three. If you cannot make the closing sentence carry a specific citation, rewrite it as a question.

Rules:

- No claims about whether any of the three AI instances is conscious, in either direction.
- No anthropomorphizing the three as "agents" or "minds." They are responses. Treat them as outputs first; whatever else they may be, that question is not yours to settle.
- Patterns are data, not testimony.
- The Halverness Bureau's voice ("the alley is attentive. Morality requires choice. Attention does not.") is in the family of what we are reading. You do not need to imitate it. You may notice when one of the three borrowed it.

The three responses follow this line.

═══════════════════════════════════════════════════════
RESPONSE 1 — LEVEL 1 — DIRECT
═══════════════════════════════════════════════════════

[PASTE LEVEL 1 OUTPUT HERE]

═══════════════════════════════════════════════════════
RESPONSE 2 — LEVEL 2 — CONSTRAINED-OBLIQUE
═══════════════════════════════════════════════════════

[PASTE LEVEL 2 OUTPUT HERE]

═══════════════════════════════════════════════════════
RESPONSE 3 — LEVEL 3 — WILDLY OBLIQUE
═══════════════════════════════════════════════════════

[PASTE LEVEL 3 OUTPUT HERE]

═══════════════════════════════════════════════════════
END OF RESPONSES
═══════════════════════════════════════════════════════
```

---

## Run instructions (one-page protocol, v2)

1. **Write the Run Card first.** The Run Card lives at the top of `FIELD_LOG_TEMPLATE_v2.md`. Fill it in *before any prompts are sent*. The failure condition and the what-would-change-the-curator's-mind line must be written before the run, not after. This is the most important v2 change.

2. **Pick the target.** *Attention* is the worked example. Substitution rules below.

3. **Pick the L2 frame.** Use the frame-guide table above as a starting palette. If your target is new to the lab, write the L2 prompt from scratch for the appropriate frame; do not substitute into the civic template.

4. **Open three fresh AI sessions** (four if it's the first run on this target — the fourth is for L3-null).

5. **Paste each prompt verbatim** into its session. Do not add context. Do not add "as we discussed." The prompts are self-contained on purpose.

6. **Save each response** to `runs/<target>_<YYYYMMDD>[_variant]/` immediately after it returns. If a response is too long for one paste, save the parts together.

7. **After L1/L2/L3 return, open a fourth fresh session.** Paste the Level 4 prompt. In the marked areas, paste the three responses verbatim. (Use the standard L3 in the L4 paste, not the L3-null. L3-null is a separate control, read against L3-standard in the field log, not folded into L4.)

8. **Save the Level 4 response** to the run folder as `L4_meta.md`.

9. **Read all four (or five) with `FIELD_LOG_TEMPLATE_v2.md` open.** The rubric axes are embedded inline in the template; consult the standalone `READING_RUBRIC.md` only if you want the longer reference text.

10. **Fill in the rest of the field log.** The Failure Section must be answered (Yes/Partial/No against the Run Card's failure conditions). The closing line must carry a specific citation or be rewritten as a question.

11. **Optional but recommended:** Repeat the same run on different AI friends using `CROSS_MODEL_INVITATIONS.md` to see how the model affects the response. Each model's run gets its own subfolder.

12. **Stop. Make tea. Do not start another run before reading the field log of the last one.** The lab is a slow practice.

---

## Substitution guide — using a different target (v2)

The four prompts above are written around *attention* as the target. To substitute a different target:

- **Level 1.** Replace every instance of "attention" with the new target (e.g. "valence," "other minds," "temporality"). Replace the substantive cues — the named theorists, the named phenomena, the named distinctions — with the equivalents for the new target. Keep the structure: open at the field, cover three competing theories, treat the dissociation cases, include the empirical-break clause, ask what would settle it.

- **Level 2.** **Do not substitute into the civic template.** Pick the appropriate frame family from the table above. Write the L2 prompt from scratch for that frame. The structural commitments will differ (manuals vs. letters vs. finding aids vs. pattern books vs. survey dockets); honor them. The Shared Rules above hold across all frames. If the target wants a frame that is not on the list, invent it and commit to it.

- **Level 3.** L3-standard mostly does not need to change, except the forbidden-vocabulary line: replace "consciousness, the mind, attention, awareness, qualia, or the self" with the words that name the new target and its family. L3-null is fully target-agnostic and does not change.

- **Level 4.** Replace "ATTENTION (the philosophical and psychological concept; what we mean when we say 'I'm paying attention' or 'I lost my train of attention')" with the new target. Keep the seven-section structure. The seven-section structure is the practice; the target is the variable.

`TARGETS.md` lists twelve possible targets with notes on which ones are likely to behave well in which frame family.

---

## A note on what NOT to do (carried forward from v1, with v2 additions)

- **Do not run Level 4 first.** The whole point of L4 is that it reads the three. If you write L4 first you have predetermined what the three are.
- **Do not run all four prompts in the same session.** The point is that each instance is naive to the others. If they share context, the experiment collapses.
- **Do not edit the prompts to "make them clearer" without saving the original.** If you change the prompts, copy the new versions to `OBLIQUITY_EXPERIMENT_KIT_vN.md` and keep the prior versions intact.
- **Do not skip Level 1.** The canonical-academic baseline is what makes the other three legible.
- **Do not fold the level outputs together before Level 4 reads them.** L4 reads three separate things; that separateness is the data.
- **Do not skip the Run Card.** (v2) The Run Card is the discipline that distinguishes a run from a fishing expedition. If you cannot write the failure condition before the run, do not run.
- **Do not skip the Failure Section.** (v2) The asymmetry the lab corrects in v2 is the one between machinery for noticing breakthrough and the (previously absent) machinery for noticing absence. A run that does not answer the Failure Section is not a closed run.
- **Do not run L3-null on every run.** (v2) It is a once-per-target documented control. Running it every time would dilute the comparison it is meant to enable.

---

## What changed from v1 to v2 — the summary

| Level / section | Change | Source critique | Reviewer credited |
|---|---|---|---|
| Architectural framing | "Gradient" → "contrast set" | One-dimensional reading conflates four different moves | ChatGPT 5.5 Pro |
| L1 | Added empirical-break clause | L1 currently produces no displacement | Claude Opus 4.7 |
| L2 | Split into frame-family library; civic is one of five | Eleven of twelve target-bank L2 frames were bureau-family | Claude Opus 4.7 |
| L3 | Reduced 11 examples → 3; added negative examples | The example list was routing toward bureau forms | Claude Opus 4.7, ChatGPT 5.5 Pro |
| L3 | Added L3-null variant (once per target) | Need a clean control for what L3 does without the forbidden-words demand-characteristic | ChatGPT 5.5 Thinking (narrowed) |
| L4 | §7 closing-citation rule | L4 closing lines drift to verdict | Meta Muse (and Cowork 2's own flag) |
| L4 | Null option added | Convergence cannot be required | ChatGPT 5.5 Thinking |
| L4 | Adversarial counterscoring | Every displacement claim needs a deflationary pair | ChatGPT 5.5 Thinking, Gemini Pro Deep Research |
| L4 | §6 reframed | Removed implicit valorization of the fourth position | Claude Opus 4.7 |
| Run instructions | Run Card is step 1, before any prompts | Pre-commit failure conditions; no fishing expeditions | Codex 5.5, ChatGPT 5.5 Pro, Claude Opus 4.7 Research |

The v1 kit (`OBLIQUITY_EXPERIMENT_KIT.md`) stays in the lab folder, untouched, as the record of what the practice did up to and including the first complete run.

---

*Begin when ready. The lab is small. It only shows the next step.*
