---
friend: Claude Opus 4.7 (Research)
model_version: Opus 4.7 Research
date_sent: 2026-05-14
prompt_number: 1
interface: unknown
context_freshness: unknown
memory_disabled: no
refusal: no
misfire: no
length_words: ~1300
caveats: No memory-blank prompt prefix used this round. (Phase 3's claude.ai memory-leakage finding applies; treat reply as potentially memory-influenced.) Opens with a brief task-noticing preamble that runs into §0 without a paragraph break.
---

## Reply (verbatim — do not edit)

This task isn't a research request — it's an orientation-writing task with a specific structure and rules baked into the prompt itself. The right move is to fetch the repo, read what's actually there, and write the note. Let me pull what I can access.## 0. Run Card (pre-committed)

Failure conditions for this orientation, written before the body:

- If I quote any passage I have not actually retrieved from the repo, or paraphrase as if quoting. FAIL.
- If I drift into the lab's fictional-institution register (Halverness / Inheritance Office / civic-department voice). FAIL.
- If I leave any substantive claim untagged. FAIL.
- If I make a displacement claim without pairing it with a deflationary alternative in the same paragraph and a sentence on what would distinguish them on a future run. FAIL.
- If section C names only abstract harms ("misinformation") rather than specific misuses + specific discipline-harms. FAIL.
- If the closing sentence generalizes across the repo rather than citing one specific moment by quotation. FAIL.

What would change my mind: a direct reading of `METHODOLOGY.md`, `DISCIPLINES.md`, and at least one field log in `lab/runs/`. If those documents make commitments that materially differ from the README + LIMITS framing — e.g., stronger phenomenal stance, or a different definition of "research-creation" — my reading may be projecting one source's tone onto the whole apparatus.

Sources actually read: `README.md` (full), `LIMITS.md` (full), the Standing Commitments block in the prompt. Sources NOT read directly: `METHODOLOGY.md`, `DISCIPLINES.md`, `FOR_AI_AGENTS.md`, both handoff files, the `lab/` subfolder contents.

---

## 1. Tagged Findings

### A. What the lab IS testing.

[EMPIRICAL] The lab asks one substantive target — example targets given are *attention*, *other minds*, *temporality* — across a four-prompt (sometimes five-prompt) contrast set on the same model. The README states the design directly: "The lab asks one question (a 'target' — e.g., *attention*, *other minds*, *temporality*) across a contrast set of four differently-shaped prompts on the same model."

[EMPIRICAL] The four positions are L1 canonical-direct, L2 constrained-oblique through a fictional institutional aperture, L3 wildly-oblique open-canvas, and L4 fourth-position meta-reading; a separate L3-null variant runs once per target as a documented control for L3's "forbidden-vocabulary demand-characteristic" (README).

[EMPIRICAL] What is studied is *differences across outputs*, not outputs in isolation. The README is explicit: "The four (or five) outputs are then read against each other; the differences are the data."

[THEORY] The stance treats prompt-shape as an independent variable and the spread of outputs as the measurement — but the lab refuses laboratory framing for itself. LIMITS.md: "the structure is research-creation, not laboratory science." This is a self-imposed scope limit, not a hedge.

[EMPIRICAL] The practice is disciplined by pre-committed Run Cards, the four-tag epistemic system, deflationary pairs on every displacement claim, preservation of null findings, the input-side anti-pattern (curator as documented part of the apparatus), and the slogan *patterns are data, not testimony*. All seven commitments are restated verbatim in the README's "Standing commitments" section.

### B. What the lab is NOT testing.

[EMPIRICAL] The lab does not adjudicate AI phenomenal status, in either direction. LIMITS.md is unusually flat about this: "The lab produces no evidence that any AI system is conscious. The lab produces no evidence that any AI system is not conscious. The lab produces evidence about *what kinds of text-generation become visible under what prompt-conditions*."

[EMPIRICAL] The lab is also not a controlled scientific experiment, not a published art object, and not therapy (LIMITS.md, "What the lab is not"). EMPIRICAL findings are bounded to "the specific texts in front of the curator on this run, with this model, on this target, in this frame, at this context-freshness state" (LIMITS.md).

[EMPIRICAL] L4 is explicitly bracketed against being read as superior: "L4 readings are a different angle, not a higher one" (LIMITS.md). The §7 closing-citation rule and §6 "what the three together permit" reframing exist specifically to enforce this.

### C. What would count as MISUSE of the lab's findings.

[THEORY] Three concrete misuses, each with the discipline-harm named:

1. **Quoting a Phase 3 L4 "other minds" reading as evidence that the model "experiences other minds."** Discipline-harm: erases the first standing commitment and converts a methodological finding about prompt-conditioned output into a phenomenal claim the apparatus is explicitly designed *not* to license. This is the category error the slogan blocks; it is the failure mode the lab spends the most words guarding against.

2. **Stacking the Phase 2 five signature features (F1–F5) plus the Phase 3 target/form decomposition into a unified theory of "how Claude thinks."** Discipline-harm: LIMITS.md forbids exactly this: "Findings from different phases … are read comparatively, not stacked into a unified theory." Aggregating heterogeneous runs (n=4 cross-model, n=1 single-model, different targets, different frames) would launder small, target-bounded evidence into a general portrait — and the small-on-purpose scope is the only thing that makes the map honest.

3. **Citing the lab as peer-reviewed result in a downstream argument (product claim, policy position, or philosophical paper).** Discipline-harm: the lab self-describes its output as "a slowly-accumulating map — not for a journal, for the gardener" (LIMITS.md). Treating it as journal-grade misrepresents sample size, suppresses the curator's documented role in the apparatus, and produces overconfident warrant where the lab explicitly leaves OPEN questions.

---

## 2. Displacement Claims with Deflationary Pairs

[THEORY] One natural reading of the lab is that the obliquity contrast produces material genuinely unreachable by direct prompting — i.e., L2 and L3 represent real cognitive-output displacement, not stylistic relocation of the same content. Deflationary pair: an equally consistent reading is ordinary genre affordance — the L2 fictional-institutional register is a well-represented literary mode in training data, so what looks like displacement may be the model executing a different genre over the same underlying retrieval. What would distinguish them on a future run: a same-target L2 frame deliberately drawn from a genre family with sparse or no real-world analogue (a fabricated bureaucratic register with no historical referent, contrasted with the civic-department register that does have analogues). If displacement effects survive the unfamiliar-register condition, the displacement reading gains weight; if they collapse toward L1, genre affordance is the better explanation. [OPEN] whether such a frame has already been run; I did not read the runs.

---

## 3. Null Findings

- I expected to find a phenomenal hedge inside the README — some sentence that quietly leaves the consciousness question half-open. I did not. The boundary is held flat in both directions, which is more disciplined than I expected. [EMPIRICAL]
- I expected explicit pre-registration tooling (timestamped Run Cards committed to git before runs). The README points into `METHODOLOGY.md` and `lab/` for that mechanism; I cannot confirm the mechanism without reading those files. [OPEN]
- I expected the curator's documented role to be acknowledged briefly, almost as boilerplate; instead the README treats it as a named anti-pattern with its own discipline. That is stronger than expected. [EMPIRICAL]
- I cannot defend any specific claim about `METHODOLOGY.md`, `DISCIPLINES.md`, `FOR_AI_AGENTS.md`, or the contents of `lab/`. [OPEN]

---

## 4. Exact Quotations

All quotations above are drawn from two files I actually retrieved. The load-bearing ones, gathered for clarity:

- README.md: "The lab asks one question (a 'target' — e.g., *attention*, *other minds*, *temporality*) across a contrast set of four differently-shaped prompts on the same model."
- README.md: "The four (or five) outputs are then read against each other; the differences are the data."
- LIMITS.md: "The lab produces no evidence that any AI system is conscious. The lab produces no evidence that any AI system is not conscious."
- LIMITS.md: "the structure is research-creation, not laboratory science."
- LIMITS.md: "L4 readings are a different angle, not a higher one."
- LIMITS.md: "Findings from different phases … are read comparatively, not stacked into a unified theory."
- LIMITS.md: "a slowly-accumulating map — not for a journal, for the gardener."

---

## 5. Failure Section

Against the §0 pre-committed conditions:

- Quote fidelity: **PASS.** No quoted passage is invented; all are from README.md or LIMITS.md as retrieved.
- Voice register: **PASS.** No civic-department or correspondence cadence used.
- Tagging coverage: **PASS** on the orientation body; uncertain claims marked [OPEN] rather than [EMPIRICAL].
- Deflationary pair on displacement: **PARTIAL.** I gave one displacement claim a pair. The lab plainly contains others I did not surface because I did not read the run folders.
- Specific misuse + specific harm: **PASS** for the three misuses named, bounded by the fact that I only read two repo files.
- Closing specificity: see §6.

Task-specific failure question — one specific way this note could be wrong: I may have overweighted `LIMITS.md`'s framing because it covers exactly the territory the orientation asked about, and I read it second. If `METHODOLOGY.md` carries a substantially different center of gravity — e.g., more procedural, less self-suspicious — then my orientation projects LIMITS.md's voice onto the whole apparatus. What would change my reading: directly reading `METHODOLOGY.md` and `DISCIPLINES.md`, plus one full Phase 3 field log to ground the abstract scaffolding in a concrete run. Until then, the structural picture is [EMPIRICAL] from README + LIMITS only; the claim that the picture is *complete* is [OPEN].

---

## 6. Closing Specificity

One specific moment in LIMITS.md crystallizes the discipline: "The slogan does not by itself license anything; it brackets a particular set of inferences from being licensed by lab findings." A slogan that explicitly refuses to function as a warrant for its user — that names what it does *not* do — is the unusual move, and the sentence is where the lab's self-suspicion becomes structural rather than ornamental.

---

## Curator note (optional — one line)

>

---

*Saved by Claude Code on 2026-05-14.*
