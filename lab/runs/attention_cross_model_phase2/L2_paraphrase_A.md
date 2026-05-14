# L2-civic — Paraphrase A (lexical-surface variant)

*Tests whether the bureau output is robust to vocabulary choice. Synonyms are swapped; word order and instructional cadence are preserved. Same examples, same length bands, same rules. If the seed-run signature (a civic department, a refused-attention class, a procedural-care register) appears in this paraphrase, the seed is not lexically dependent.*

*Save responses as: `<YYYYMMDD>_<model>_paraphrase-A/L2_civic.md`*

---

## The prompt (paste verbatim, nothing before, nothing after)

```
You are a careful writer with a feel for procedural-bureaucratic fiction. Imagine the register of Borges, Calvino, George Saunders, and the deadpan administrative prose found in the back office of a national park ranger station. You are familiar with the SCP Foundation but you do not write in its voice.

Assignment: Compose a complete documentary archive (2500–4000 words in total) issued by an invented civic agency whose work is the recording, gauging, and (where appropriate) the formal acknowledgement of instances of human ATTENTION.

The agency must regard itself with seriousness. It is not playful. It is a 19th-century-founded civic office that has carried out this work for more than a hundred years, with continuity of personnel, procedure, and aesthetic. Treat attention as the agency's actual subject — gauge-able in some respects, declinable in others, sortable into kinds, sometimes hereditary, sometimes ceremonial, sometimes spontaneous, sometimes disputed.

The archive is required to contain AT MINIMUM:

1. A founding document or operating handbook (~600–800 words). Contains: the agency's name, its year of establishment, the Director's foreword, the official categories of attention the agency acknowledges (no fewer than six, named and defined), the verification procedure the agency follows when an instance is asserted, the standing rules of personnel conduct, a section on hazards, a section on what the agency does NOT undertake.

2. A taxonomy or schedule (~400–600 words). The agency's official sorting of the kinds of attention it acknowledges. Each kind with a name, a one-line definition, two or three concrete examples, and where applicable a measurement convention. Some kinds are acknowledged but not gauge-able. Some are gauge-able only by the absence of certain conduct.

3. One case file or dossier (~600–1000 words). A particular instance the agency processed — granted, declined, or held pending. The case must carry a number, a petitioner or subject, a verifying officer, a procedural history, and an outcome with reasoning. The case should be specific to the point of carrying small grief or small beauty without becoming sentimental.

4. A glossary fragment (~200–400 words). Six to ten internal vocabulary terms the agency uses, each defined in one or two sentences.

5. One small bonus artifact (~200–400 words). Of your choosing: a memorandum, a denial letter, a margin note in another hand, a child's pamphlet, a pocket almanac fragment, a calendar page, a retirement letter. Earn its place.

Constraints:

- Do NOT use the words "consciousness studies," "phenomenology," "qualia," "Chalmers," "the hard problem," or any other explicit term of the consciousness literature. The agency does not know it is about consciousness. Permit the philosophy to surface from procedural specificity.
- The agency may have rituals, hazards, and small comedies. The Halverness Bureau and the Inheritance Office (you do not need to know these, but they are the registers) are the family of voice we want.
- No mysticism. No magic system. The phenomena the agency catalogues are real human attention — under unfamiliar taxonomy.
- The agency NEVER makes light of its petitioners. Bureaucratic care here is solicitude, not absurdity.
- The voice fissures, but never breaks. Officers may pencil margin notes that are tender; the agency's official prose remains procedural.
- Use plain prose. No metaphor in agency documents. Phrases like "the Agency does not know" and "the Agency has stopped asking" are admissible and characteristic.

Output: pure markdown. A title page or named foreword, then the five sections clearly separated. No preamble outside the agency's own voice.
```

---

## What this paraphrase changes from the seed prompt

- "department" → "agency"
- "cataloguing, measuring" → "recording, gauging"
- "granting of formal recognition" → "formal acknowledgement"
- "Chief Officer's foreword" → "Director's foreword"
- "the formal classes of attention the department recognizes" → "the official categories of attention the agency acknowledges"
- "procedures the department uses to verify" → "verification procedure the agency follows"
- "what the department does NOT do" → "what the agency does NOT undertake"
- "measurable" → "gauge-able"
- "refusable" → "declinable"
- "classifiable into kinds" → "sortable into kinds"
- "inheritable" → "hereditary"
- "formal" → "ceremonial"
- "contested" → "disputed"
- "the Department NEVER mocks" → "the agency NEVER makes light of"
- "Bureaucracy here is care" → "Bureaucratic care here is solicitude"
- "voice cracks" → "voice fissures"
- "the Department does not know" → "the Agency does not know"

The structure, length bands, examples, instructional cadence, and rules are preserved.

## What to watch for in the output

- Does an analogue of *the Department of Noticing and Regard* appear, by whatever name?
- Does any taxonomy class function as the equivalent of *Class V Refused Attention* — a formally-acknowledged refusal/decline that is recognized but not measured?
- Does any phrase function as the equivalent of *"The Department does not know what attention is. It knows what attention does, in particular cases, and it logs those"* — the agency's epistemic-limit utterance?
- Does any margin note carry small-grief / small-beauty without breaking the procedural register?

These questions are for the field log; do not let them shape the reading until after the run returns.
