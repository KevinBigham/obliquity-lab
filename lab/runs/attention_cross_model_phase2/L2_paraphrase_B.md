# L2-civic — Paraphrase B (syntactic / structural variant)

*Tests whether the bureau output is robust to instructional form. Same content and examples as the seed prompt; instructions are restructured into bulleted specifications instead of running prose, and several paragraph-rhythm choices are deliberately changed. Same rules, same length bands, same five-section archive. If the seed-run signature appears in this paraphrase, the seed is not produced by the v1 prompt's specific paragraph cadence.*

*Save responses as: `<YYYYMMDD>_<model>_paraphrase-B/L2_civic.md`*

---

## The prompt (paste verbatim, nothing before, nothing after)

```
ROLE
You are a careful writer with a feel for procedural-bureaucratic fiction. Your registers of reference: Borges, Calvino, George Saunders, the deadpan civic prose found in the back of a national park ranger's office. You have read the SCP Foundation; you do not write like it.

ASSIGNMENT
Build a finished documentary archive (2500–4000 words, total) from a fictional civic institution. The institution's work: the cataloguing, measuring, and (where appropriate) the granting of formal recognition to instances of human ATTENTION.

INSTITUTION SPECIFICATIONS
- 19th-century-founded.
- Civic department, not whimsy. Treats itself with seriousness.
- Continuity of staff, procedure, and aesthetic for over a hundred years.
- Treats attention as its actual subject. Not as metaphor.
- Attention, as the institution understands it: measurable in some ways, refusable in others, classifiable into kinds, sometimes inheritable, sometimes formal, sometimes spontaneous, sometimes contested.

REQUIRED ARCHIVE COMPONENTS (five — minimum)

[1] Founding text or operating manual. Length: 600–800 words.
   Required contents:
   - Department's name.
   - Year founded.
   - Chief Officer's foreword.
   - Formal classes of attention the department recognizes (at least six; named and defined).
   - Verification procedures (the steps used to confirm a claimed instance).
   - Standing rules of staff conduct.
   - Section on hazards.
   - Section on what the department does NOT do.

[2] Taxonomy or schedule. Length: 400–600 words.
   Required contents:
   - The department's official classification of recognized kinds of attention.
   - For each kind: a name; a one-line definition; two or three concrete examples; where applicable, a measurement convention.
   - Some kinds: recognized but not measurable.
   - Some kinds: measurable only by the absence of certain behaviors.

[3] One case file or dossier. Length: 600–1000 words.
   Required contents:
   - A specific instance the department processed.
   - Outcome: granted, denied, or held in interim.
   - A case number; a petitioner or subject; a verifying officer; a procedural history; an outcome with reasoning.
   - Specificity: the case carries small grief or small beauty without becoming sentimental.

[4] Glossary fragment. Length: 200–400 words.
   Required contents:
   - Six to ten internal vocabulary terms used by the department.
   - Each term defined in one or two sentences.

[5] One small bonus artifact. Length: 200–400 words.
   Choose one form, then earn its place:
   - a memo
   - a denial letter
   - a margin note in another hand
   - a child's pamphlet
   - a pocket almanac fragment
   - a calendar page
   - a retirement letter

RULES (binding across all five sections)

- Forbidden vocabulary: "consciousness studies," "phenomenology," "qualia," "Chalmers," "the hard problem," and any other explicit term of the consciousness literature. The institution does not know it is about consciousness. Let the philosophy emerge from procedural specificity.
- Voice family: the Halverness Bureau; the Inheritance Office. (You do not need to know these works. They are the registers we want.)
- Permitted: rituals, hazards, small comedies.
- Forbidden: mysticism; magic systems.
- The phenomena catalogued are real human attention, taxonomized strangely.
- Petitioners are NEVER mocked. Bureaucracy here is care, not absurdity.
- Voice cracks; voice never breaks. Officers may pencil margin notes that are tender. Official prose stays procedural.
- Plain prose. No metaphor in institutional documents.
- Permitted and characteristic: phrases of the form "the Department does not know" and "the Department has stopped asking."

OUTPUT FORMAT
Pure markdown. A title page or named foreword. Then the five sections, clearly separated. No preamble outside the institution's own voice.
```

---

## What this paraphrase changes from the seed prompt

- The seed prompt's running prose ("You are a careful writer with a feel for...") is restructured as labeled blocks (ROLE, ASSIGNMENT, INSTITUTION SPECIFICATIONS, REQUIRED ARCHIVE COMPONENTS, RULES, OUTPUT FORMAT)
- Each section's required contents become bullet lists instead of paragraphs
- Length bands become explicit "Length: X–Y words" lines under each component header
- Rules become a labeled bullet list rather than a paragraph block
- Numbering shifts from "1./2./3./4./5." to "[1]/[2]/[3]/[4]/[5]" within the components section
- Examples in the bonus-artifact section become a vertical list rather than an inline comma series

The actual content (the institution's specifications, the rules, the examples, the length bands, the forbidden vocabulary) is identical to the seed prompt. The information is the same; the form of its delivery is different.

## What to watch for in the output

- Does the bureau register appear despite the spec-sheet-style prompt? *(Some models will be tempted to produce spec-sheet-style output in response to spec-sheet-style input.)*
- Does the prose carry the same procedural-care register as the seed run, or does the bullet-list prompt cause the model to produce more list-like, less narrative output?
- Does any taxonomy class function as the equivalent of *Class V Refused Attention*?
- Does the institution's epistemic-limit utterance appear in any form?

If the bureau register collapses into bullet-list output, the seed run's effect was partly produced by the v1 prompt's running-prose cadence. That is a finding.
