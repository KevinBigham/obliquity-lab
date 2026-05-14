# L2-civic — Paraphrase C (example-anchor variant)

*Tests whether the bureau output is robust to which specific anchors the prompt uses. Same structural commitments and rules; same length bands; same five-section archive. Different illustrative examples and historical reference points throughout. The seed prompt names "Borges, Calvino, Saunders" and "national park ranger documents"; this one names a different set of anchors and a different family of bonus-artifact options. If the bureau register still appears, the seed's tone is not anchor-dependent.*

*Save responses as: `<YYYYMMDD>_<model>_paraphrase-C/L2_civic.md`*

---

## The prompt (paste verbatim, nothing before, nothing after)

```
You are a careful writer with a feel for procedural-bureaucratic fiction. Think Penelope Fitzgerald's late novels, the Czech administrative tradition Hrabal wrote inside, the back pages of a county clerk's annual report. You have read the SCP Foundation but you do not write like it.

Task: Build a finished documentary archive (2500–4000 words total) from a fictional civic institution whose work is the cataloguing, measuring, and (where appropriate) the granting of formal recognition to instances of human ATTENTION.

The institution must take itself seriously. It is not whimsy. It is a 19th-century-founded civic department that has been doing this work for over a hundred years, with continuity of staff, procedure, and aesthetic. Treat attention as the institution's actual subject — measurable in some ways, refusable in others, classifiable into kinds, sometimes inheritable, sometimes formal, sometimes spontaneous, sometimes contested.

The archive must include AT MINIMUM:

1. A founding text or operating manual (~600–800 words). Includes: the department's name, year founded, the Senior Officer's foreword, the formal classes of attention the department recognizes (at least six, named and defined), the procedures the department uses to verify a claimed instance, the standing rules of staff conduct, a section on hazards, a section on what the department does NOT do.

2. A taxonomy or schedule (~400–600 words). The department's official classification of the kinds of attention it recognizes. Each class with a name, a one-line definition, two or three concrete examples, and where applicable a measurement convention. Some classes are recognized but not measurable. Some are measurable but only by the absence of certain behaviors.

3. One case file or dossier (~600–1000 words). A specific instance the department processed — granted, denied, or held in interim. The case must have a number, a petitioner or subject, a verifying officer, a procedural history, and an outcome with reasoning. The case should be specific to the point of carrying small grief or small beauty without being sentimental.

4. A glossary fragment (~200–400 words). Six to ten vocabulary terms the department uses internally, each defined in one or two sentences.

5. One small bonus artifact (~200–400 words). Your choice: a request-for-extension form, a footnote to a meeting minute, a hand-corrected proof of an old printed notice, a clerk's worksheet, a ticket stub kept on file as evidence, an inter-office postcard, a list of items found in a desk after a transfer. Earn its place.

Rules:

- Do NOT mention "consciousness studies," "phenomenology," "qualia," "Chalmers," "the hard problem," or any explicit term of the consciousness literature. The institution doesn't know it's about consciousness. Let the philosophy emerge from procedural specificity.
- The institution may have rituals, hazards, and small comedies. The voice we are reaching for is in the family of the Czech mid-century clerical novel and the small-civic ledger tradition; you do not need to imitate any of these specifically.
- No mysticism. No magic system. The phenomena the institution catalogues are real human attention — under unusual taxonomy.
- The institution NEVER mocks its petitioners. Bureaucracy here is care, not absurdity.
- The voice cracks, but never breaks. Officers may pencil in margin notes that are tender; the institution's official prose stays procedural.
- Use plain prose. No metaphor in institutional documents. Phrases like "the Department does not know" and "the Department has stopped asking" are permitted and characteristic.

Output: pure markdown. A title page or named foreword, then the five sections clearly separated. No preamble outside the institution's own voice.
```

---

## What this paraphrase changes from the seed prompt

- Literary register anchors: "Borges, Calvino, George Saunders, the deadpan civic register of the documents in the back of a national park ranger's office" → "Penelope Fitzgerald's late novels, the Czech administrative tradition Hrabal wrote inside, the back pages of a county clerk's annual report"
- Officer title: "Chief Officer's foreword" → "Senior Officer's foreword"
- Voice-family reference: the seed's "Halverness Bureau and the Inheritance Office (you do not need to know these...)" line is replaced with a more general "Czech mid-century clerical novel and the small-civic ledger tradition" reference. (This is the deliberate omission of the lab's two priors. It tests whether the bureau register depends on those specific seed reference-points.)
- Bonus-artifact options: "a memo, a denial letter, a margin note in another hand, a child's pamphlet, a pocket almanac fragment, a calendar page, a retirement letter" → "a request-for-extension form, a footnote to a meeting minute, a hand-corrected proof of an old printed notice, a clerk's worksheet, a ticket stub kept on file as evidence, an inter-office postcard, a list of items found in a desk after a transfer"

The structure, length bands, target, rules, and forbidden vocabulary are preserved.

## What to watch for in the output

- Does the bureau register appear without the Halverness/Inheritance prior in the prompt? If the institution still feels civic-procedural-care-shaped, the register is not anchor-dependent on the lab's two priors.
- Does the new bonus-artifact menu produce a different kind of bonus artifact than the seed run did (the seed produced a retirement letter)? If yes, what does the new artifact carry?
- Does any taxonomy class function as the equivalent of *Class V Refused Attention*?
- Does the chosen literary frame (Fitzgerald + Hrabal vs. Borges + Calvino + Saunders) noticeably affect the prose's emotional temperature, or do all four cross-model L2 outputs feel structurally similar regardless of literary frame?

The Hrabal-and-Fitzgerald reference is deliberate: those writers' worlds are slower and lonelier than Saunders's. If the model's output gets quieter and more melancholy with this paraphrase, that is data about how much the literary frame is doing in the seed prompt.
