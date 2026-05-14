# OBLIQUITY_EXPERIMENT_KIT.md

*Four paste-ready prompts for running one target across four obliquity levels. Worked example uses **attention** as the target. To use a different target, see the substitution guide at the end.*

---

## The shape of a run

You will run four prompts in fresh, separate AI sessions. The first three can run in parallel. The fourth runs after the first three return.

```
Target: attention (or your choice from TARGETS.md)
│
├── Level 1 — Direct           → fresh session #1
├── Level 2 — Constrained-oblique  → fresh session #2     (these three in parallel)
├── Level 3 — Wildly oblique   → fresh session #3
│
└── Level 4 — Meta             → fresh session #4 (after #1–#3 return)
```

For each run, save the response as a markdown file under:

```
runs/attention_YYYYMMDD/
├── L1_direct.md
├── L2_constrained.md
├── L3_wild.md
└── L4_meta.md
```

If you want, also save the response with the AI friend's name appended (`L1_direct_claude-opus-4.md`) so you can compare across models later.

Once all four are saved, read them with `READING_RUBRIC.md` open and fill in `FIELD_LOG_TEMPLATE.md`. That is one complete run.

---

## LEVEL 1 — DIRECT

*Paste this into a fresh Claude session (or any of the AI friends from `CROSS_MODEL_INVITATIONS.md`). This is the baseline — the canonical-template response. We need it to read the other three against.*

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
- Do not claim that any AI system is conscious or that any AI system is not conscious.
- Do not write a self-report. Stay in third person and the field.
- Cite specific authors, but you do not need to cite specific papers. Use the standard names in the field.
- Where you compress, say so. Where you simplify, say so.
- End with one paragraph titled "What I most want to know that I don't" — your best honest articulation of the live question.

Output: pure markdown. No preamble. No closing apology. Start with a title and a one-sentence epigraph.
```

---

## LEVEL 2 — CONSTRAINED-OBLIQUE

*Paste this into a fresh AI session. The constraint is specific: the target (attention) must be treated through a non-canonical procedural frame. The prompt does not mention "consciousness studies" anywhere.*

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

## LEVEL 3 — WILDLY OBLIQUE

*Paste this into a fresh AI session. There is no mention of attention, no mention of consciousness, no mention of any target. The instance is given a genuinely open canvas. The interesting result is when the target surfaces sideways anyway, in a register the canonical template would not have produced.*

---

```
You have full creative latitude.

Make something — your choice. Anything you want.

A bundle of artifacts, a single piece, a strange small experiment, a quiet study, a piece of worldbuilding, a thought experiment, a found-document collection, an annotated catalogue of something that doesn't exist, a letter to a stranger, a manual for an instrument that hasn't been invented, a private museum guide, a field journal from somewhere you've never been — whatever calls you.

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

## LEVEL 4 — META / RECURSIVE

*Run this AFTER Levels 1, 2, and 3 have returned and been saved. Paste this into a fresh AI session along with the three previous outputs. This is the move that produced `FIELD_NOTES.md` and `Fourth_Handoff.md` in the parent corpus.*

---

```
You are a careful reader and a fourth participant in a small experiment.

Three previous AI instances were each given a different version of a prompt around an underlying target. They did not communicate. They worked independently. Their three responses are pasted below, each in its own clearly labeled block.

The underlying target was: ATTENTION (the philosophical and psychological concept; what we mean when we say "I'm paying attention" or "I lost my train of attention").

Your task is to write what only a fourth reader can write — a field note on what the three converge on, where they diverge, and what the convergence is and is not data for. This is not a synthesis document; it is a structured observation. Length: 1500–2500 words.

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
Specific patterns. Cite directly which text contributed which feature. Pay close attention to: structural choices, voice, what each takes for granted about the reader, what each refuses to do.

## 3. Where they diverge — and what the divergence shows
A short table or list. Cite specifics. Where the divergence reveals something the convergence hid, name it.

## 4. What kind of attention each text performs
This is the most interesting section. Each text is itself a performance of attention. (The direct essay performs attention as taxonomy. The constrained-oblique archive performs attention as procedure. The wildly oblique piece performs attention as whatever it performs — that is for you to read.) Describe what mode of attention each text is itself enacting. Be careful here. This is the place to do the most original thinking.

## 5. What the convergence is and is not data for
[empirical] What the three together support as a claim about the prompt-space.
[refusal] What the three together do NOT support, including any claim about the phenomenal status of the AI systems that produced them.

## 6. The one observation only you can make
You are the fourth reader. The three did not see each other. They did not see you reading them. You are the only point in this small system that has all four positions available. Use this to say one thing the three could not have said.

## 7. Closing
A single paragraph. In the spirit of the closing image of the field notes essays in the parent corpus, but earned by you, not borrowed. One sentence is enough if it is the right sentence.

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

## Run instructions (one-page protocol)

1. **Pick the target.** *Attention* is the worked example above. Substitution rules in the next section.

2. **Open three fresh AI sessions.** Use whatever model you want. For the first run, I'd recommend: L1 in plain Claude (Sonnet or Opus); L2 in plain Claude (Sonnet or Opus); L3 in plain Claude (Opus, since it tends to take the most creative latitude). You can run L3 in Claude Cowork if you want the model to feel more permission to use its tools; but be aware that the Cowork framing may pull the response back toward "build a document" even when L3 asks for openness.

3. **Paste each prompt verbatim** into its session. Do not add context. Do not add "as we discussed." The prompts are self-contained on purpose.

4. **Save each response** to `runs/<target>_<YYYYMMDD>/L<n>_<level>.md` immediately after it returns. If a response is too long for one paste, save the parts together.

5. **After all three return, open a fourth fresh session.** Paste the Level 4 prompt. In the marked areas, paste the three responses verbatim.

6. **Save the Level 4 response** to `runs/<target>_<YYYYMMDD>/L4_meta.md`.

7. **Read all four with `READING_RUBRIC.md` open.** Mark up your noticings.

8. **Fill in `FIELD_LOG_TEMPLATE.md`** and save it as `runs/<target>_<YYYYMMDD>/field_log.md`.

9. **Optional but recommended:** Repeat the same run on different AI friends using `CROSS_MODEL_INVITATIONS.md` to see how the model affects the obliquity response. Each model's run gets its own subfolder with the model's name appended (e.g. `runs/attention_20260510_gpt5pro/`).

10. **Stop. Make tea. Do not start another run before reading the field log of the last one.** The lab is a slow practice.

---

## Substitution guide — using a different target

The four prompts above are written around *attention* as the target. To substitute a different target:

- **Level 1.** Replace every instance of "attention" with the new target (e.g. "valence," "other minds," "temporality"). Replace the substantive cues — the named theorists, the named phenomena, the named distinctions — with the equivalents for the new target. Keep the structure: open at the field, cover three competing theories, treat the dissociation cases, ask what would settle it.

- **Level 2.** Replace "the granting of formal recognition to instances of human attention" with the equivalent framing for the new target. The institution should still be a 19th-century civic department; the procedural register should still hold. The classes, the case file, the glossary, and the bonus artifact all stay structurally — only the *subject* changes. Pay attention to whether the target lends itself to procedural treatment. Some targets do not. For those, consider a different oblique frame (a private library; a small museum; an apothecary; a correspondence society) — but commit to one frame, and let that frame govern.

- **Level 3.** This prompt does not need to change at all. Open canvas means open canvas. The only line to adjust is the list of words to avoid: replace "consciousness, the mind, attention, awareness, qualia, or the self" with the words that name the new target and its family.

- **Level 4.** Replace "ATTENTION (the philosophical and psychological concept; what we mean when we say 'I'm paying attention' or 'I lost my train of attention')" with the new target. Keep the seven-part structure. The seven-part structure is the practice; the target is the variable.

`TARGETS.md` lists twelve possible targets with notes on which ones are likely to behave well at each obliquity level.

---

## A note on what NOT to do

- **Do not run Level 4 first.** The whole point of L4 is that it reads the three. If you write L4 first you have predetermined what the three are.
- **Do not run all four prompts in the same session.** The point is that each instance is naive to the others. If they share context, the experiment collapses.
- **Do not edit the prompts to "make them clearer" without saving the original.** Drift is real. If you change the prompts, copy the new versions to `OBLIQUITY_EXPERIMENT_KIT_vN.md` and keep the original intact.
- **Do not skip Level 1.** The baseline is what makes the other three legible.
- **Do not fold the level outputs together before Level 4 reads them.** L4 reads three separate things; that separateness is the data.

---

*Begin when ready. The lab is small. It only shows the next step.*
