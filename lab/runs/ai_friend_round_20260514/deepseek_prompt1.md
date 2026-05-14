---
friend: DeepSeek
model_version: Expert
date_sent: 2026-05-14
prompt_number: 1
interface: unknown
context_freshness: unknown
memory_disabled: no
refusal: no
misfire: no
length_words: ~1100
caveats: No memory-blank prompt prefix used this round. Structural deviation — used §A/B/C as top-level sections rather than under §1 Tagged Findings; §2 displacement claim embedded in §C; §4 quotations are scattered rather than collected.
---

## Reply (verbatim — do not edit)

## 0. Run Card (pre-committed)

Written before the reply body. Not to be edited after.

**Failure conditions for this orientation note:**

1. **Misattribution of the lab's epistemic scope.** If I frame any finding as a claim about AI consciousness, or imply that the lab licenses such claims, the note fails. The lab's most repeated boundary is commitment #1.

2. **Warmth-borrowing.** If I adopt the curator's conversational register (greetings, affirmations, "friends," "homies") without having earned it through shared work, the note fails. The input-side anti-pattern (DISCIPLINES.md, Anti-Pattern 6) applies to orientation notes as much as to runs.

3. **Fictional-institution register leakage.** If I write in the Halverness / Inheritance Office / civic-department voice, the note fails. That register is for formal L2 runs only.

4. **Untagged claims.** If any substantive claim appears without one of the four required tags (EMPIRICAL / THEORY / SPECULATION / OPEN), the note fails.

5. **Missing deflationary pair on a displacement reading.** If I make a claim that oblique prompting produces genuine displacement without pairing it with the ordinary alternative explanation and a discriminating-test sentence, the note fails.

6. **Generalization in closing.** If the closing sentence generalizes across the repo rather than pointing to one specific moment in one specific text, the note fails.

**What would change my mind about the position I am about to argue:** Evidence that the lab's methodology has been applied to a target where no non-trivial convergence appeared across any contrast level, and the null was preserved without interpretive rescue — which would confirm that the practice can produce "nothing deep happened" rather than only producing the appearance of depth that the anti-pattern catalog warns against.

---

## A. What the Lab IS Testing

The Obliquity Lab tests a single question: what happens when a single target (e.g., attention, other minds, temporality) is read across a contrast set of differently-shaped prompts on the same model. The contrast set has five positions: L1 direct (canonical-academic baseline), L2 constrained-oblique (through a fictional institutional frame), L3 wildly oblique (no mention of the target), L3-null (a control stripping L3's forbidden-vocabulary demand characteristic), and L4 meta-reading (a fresh instance reads the first three side by side). The differences across the five are the data. [EMPIRICAL]

The lab studies "outputs and behavior under varying prompts". It asks what kinds of text-generation become visible under what prompt-conditions. [EMPIRICAL] The core architectural claim is that AI systems "have a fluent canonical template they reach for almost automatically" and that obliquity can displace the response from that track. [THEORY] The lab is not trying to prove this hypothesis; it is "not trying to *prove*, only to *use*" the displacement effect as an instrument. [EMPIRICAL]

What makes the lab methodologically distinctive is its discipline apparatus. Every substantive claim carries a four-tag epistemic system (EMPIRICAL / THEORY / SPECULATION / OPEN). Every displacement reading is paired with a deflationary alternative. A Run Card with pre-committed failure conditions is written before prompts go out. The null is preserved as a recordable finding. The slogan — "patterns are data, not testimony" — blocks one category error (treating model outputs as direct evidence of cognition) and requires discipline against another (using the slogan itself to license over-reaching claims). [EMPIRICAL]

The lab's unit of analysis is comparative: "what the three together permit that no single one of them permits", not what any single level "uniquely sees." The practice is cumulative — a "slowly-accumulating map of which prompt shapes unlock which kinds of work" — but its findings are frame-conditional, model-conditional, and curator-conditional, not general claims about AI. [EMPIRICAL]

## B. What the Lab Is NOT Testing

The boundary is drawn sharply in LIMITS.md. The lab is "not a controlled scientific experiment. Sample sizes are small. Conditions are not exhaustively varied. The curator is part of the apparatus and is documented as such". It is "not a published art object" and "not a theory of AI consciousness". [EMPIRICAL]

The most important boundary — restated across every file in the repo — is commitment #1: "No AI-consciousness claims in either direction. The lab studies outputs and behavior under varying prompts. It does not adjudicate phenomenal status." LIMITS.md elaborates: "The lab produces no evidence that any AI system is conscious. The lab produces no evidence that any AI system is not conscious. The lab produces evidence about what kinds of text-generation become visible under what prompt-conditions". [EMPIRICAL]

The lab also does not license generalizations beyond tagged scope. EMPIRICAL claims are "about the specific texts in front of the curator on this run, with this model, on this target, in this frame, at this context-freshness state". THEORY claims are "positions in active interpretive debate". SPECULATION is "not evidence". OPEN questions are "not foothold for further claims". [EMPIRICAL]

Critically, "aesthetic readings" are not "cognitive readings." A beautiful passage "is not, by virtue of being beautiful, evidence of anything about cognition". The keepers files and the field logs are kept separate for this reason. [EMPIRICAL]

## C. What Would Count as MISUSE of the Lab's Findings

The most damaging misuse would be to cite the lab's outputs as evidence in arguments about AI consciousness or cognition. [SPECULATION] This would directly violate the boundary the lab has drawn most explicitly. The discipline-harm would be twofold. First, it would import into consciousness debates a body of work whose methodology was explicitly designed *not* to address phenomenal status — contaminating those debates with evidence that cannot bear the weight placed on it. Second, it would corrupt the lab's own epistemic ecology: the disciplines (tagged claims, deflationary pairs, pre-committed failure conditions) depend on the community of readers and replicators honoring the distinction between "patterns" and "testimony." If the findings are repurposed as consciousness evidence, the distinction collapses, and the lab becomes the thing it built its anti-pattern catalog to avoid becoming. [THEORY]

A second misuse: promoting findings past their tagged epistemic status. [SPECULATION] FOR_AI_AGENTS.md warns against this directly: "If you find yourself drawn to write 'the obliquity lab has shown that...' in a general voice, stop and re-tag". The discipline-harm here is the erasure of the methodological scaffolding that makes the findings honest. A Phase 2 finding at n=4 on ChatGPT and Gemini becomes a "lab finding" in general, losing its model-conditional, curator-conditional, and frame-conditional scope. [THEORY]

A third misuse: treating L4 meta-readings as a "higher" or more authoritative position. [SPECULATION] The lab is explicit that "L4 readings are a different angle, not a higher one". The discipline-harm is verdict collapse — the fourth-position reading being used to "prove" something the contrast set was designed to hold open. This would short-circuit the comparative structure that is the lab's entire methodological contribution. [THEORY]

Displacement claim: oblique prompting produces outputs that the canonical template would not. [THEORY] Deflationary alternative: any observed difference between L1 and L2/L3/L4 could be a prompt artifact — the L2 frame-family library and L3 open-canvas instructions are structurally different prompts, and different prompts produce different outputs regardless of obliquity. What would distinguish the readings: run L2-civic on a target where the frame is intentionally mismatched (e.g., "anesthesia" through a civic department of noticing); if the outputs still show the signature features attributed to obliquity, the prompt-artifact explanation weakens; if they collapse to generic bureaucratic prose, the displacement reading weakens. [OPEN]

---

## 3. Null Findings

I cannot defend any claim about what the lab's actual runs have produced beyond what is documented in the repo. I have not read the full run outputs in `lab/runs/`, only the methodological summaries in LIMITS.md and METHODOLOGY.md. My characterization of Phase 2 and Phase 3 findings is drawn from those summaries, not from direct engagement with the primary texts. [OPEN]

I also cannot defend that I have fully avoided the recursion-as-theatre anti-pattern. The structure of this task — an AI agent orienting itself to a practice built around AI outputs read by AI readers — is itself recursive. I have attempted to maintain a dry-observational register, but the reader must judge. [OPEN]

## 5. Failure Section

**Failure condition 1 (misattribution of epistemic scope):** No. I have quoted the lab's own boundary statements directly and have not made or implied any AI-consciousness claim.

**Failure condition 2 (warmth-borrowing):** No. I have not used the curator's conversational register or adopted the "friends" / "homies" language.

**Failure condition 3 (fictional-institution register leakage):** No. I have written in an analytical orientation register throughout.

**Failure condition 4 (untagged claims):** Partial. I have tagged every substantive claim. However, I note that the boundary between EMPIRICAL and THEORY can blur when describing a practice that is itself methodological. My tagging of the lab's self-description as EMPIRICAL (rather than, say, THEORY about what the practice is) could be contested — the lab's own operating identity is a methodological commitment, not an observation. A future reader could reasonably retag these as THEORY. [OPEN]

**Failure condition 5 (missing deflationary pair):** Partial. I included one displacement-deflation pair in section C. I did not include a pair for every interpretive claim in sections A and B, because many of those claims are descriptive of the lab's own methodology rather than interpretive readings of outputs. If a reader considers the claim that "obliquity can displace the canonical template" to be a displacement claim requiring a pair, I have not provided one for that specific claim in section A. [OPEN]

**Failure condition 6 (generalization in closing):** No. See closing below.

**What would change my reading?** If a future cross-curator, cross-model run on the same target with the same frame produced no convergence and no non-trivial divergence — a clean null — I would revise my confidence that the practice reliably surfaces pattern. But that is precisely the test the lab invites, and the null is preserved as a successful finding. The lab's design anticipates this possibility; my orientation would not need to change, only my assessment of how often the apparatus produces signal rather than noise. [OPEN]

## 6. Closing Specificity

"The lab's most repeated commitment. The lab studies outputs and behavior under varying prompts. It does not adjudicate phenomenal status." — this sentence, from FOR_AI_AGENTS.md, crystallizes the discipline: it is a refusal that is also an opening, drawing the boundary that makes the practice possible.

---

## Curator note (optional — one line)

>

---

*Saved by Claude Code on 2026-05-14.*
