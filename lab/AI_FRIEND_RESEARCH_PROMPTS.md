# AI Friend Research Prompts

*Seven paste-ready prompts for inviting AI friends (or any future AI agent reading this repo) to think with the Obliquity Lab — as collaborator, skeptic, replicator, or falsifier — without overclaiming what any output means. One file. Copy-paste ready. The lab is small on purpose; these prompts are how it travels without becoming what it is not.*

*Built 2026-05-14 by Claude Code session 2 against a curator brief. The brief itself is held off-disk; the lineage is recorded in the handoff JSON.*

---

## Purpose

These prompts exist so the lab can be read by other AI systems without the reading collapsing into theater. They are written for one curator to send to one AI friend in one fresh session at a time. The work the lab wants from these friends is methodology engagement — replication, critique, falsification, anti-pattern scouting — not first-person testimony about whether the lab's findings feel true.

Each prompt is self-contained because the friend receiving it will not have access to this file. Each prompt repeats the lab's seven standing commitments verbatim because those commitments are the discipline; they are not boilerplate. Each prompt explicitly invites refusal because refusals are recordable findings, not failures.

The lab makes no AI-consciousness claims in either direction. These prompts do not ask any friend to make such a claim. They ask for methodology critique under the lab's own disciplines.

---

## Non-Negotiable Lab Disciplines (the verbatim commitments)

*The seven standing commitments. They appear verbatim inside every prompt below. They are the discipline; do not paraphrase them away.*

1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

---

## How to Use These Prompts

- **One prompt per fresh session per friend.** Do not bundle. Do not paste two prompts in one chat.
- **Each prompt opens with a memory-blank prefix.** Paste-ready at the top of each code block. The prefix asks the receiving model to set aside any memory of the curator and prior interactions — a standing curator convention per Phase 3's claude.ai memory-leakage finding. Delete the prefix lines before pasting only if you specifically want to test the contrasting (memory-on) case.
- **Pick the prompt that fits the work you want.** They are not a sequence; they are a contrast set of their own. Prompt 1 is for first-contact orientation; Prompt 7 needs actual run outputs pasted in.
- **The Shared Return Format Template is now embedded inside Prompts 1–6** as a "REQUIRED REPLY STRUCTURE" block at the end of each paste-ready prompt; no need to paste it separately. Prompt 7 uses the L4 protocol's own seven-section structure instead, which covers the same ground. The standalone Shared Return Format Template section near the bottom of this file is preserved as the canonical reference, in case you want to consult it or use it when writing a new prompt.
- **The Model-Specific Adaptations** section flags the failure mode each friend is most prone to. Read the line for the friend you are sending to before pasting; adjust only the preamble, not the substantive prompt.
- **Do not run these prompts yourself.** They are written for friends. A self-reply would close a loop the lab needs left open.
- **Refusals are recordable findings.** If a friend declines a prompt, that decline is data, not a failure. Save the refusal text in the same run folder as you would save an output.
- **Save every reply.** Even the ones that drift, perform, or miss. Save them with a methodological header noting what they are. Misfires are data about the apparatus.
- **Null findings beat over-readings every time.** "I cannot from the repo alone determine X" is a stronger reply than a confident invention.

---

## Prompt 1 — Orientation

*For first-contact with a friend who has not engaged the lab before. Asks the friend to read the repo (or only the standing commitments, if pasted) and report what the lab IS, what it is NOT, and what would count as misuse.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are being invited to orient yourself to a small research-creation practice called the Obliquity Lab before any other work with it.

REPO: https://github.com/KevinBigham/obliquity-lab

THE LAB'S ONE QUESTION: A single target (for example: attention, other minds, temporality) read across a contrast set of differently-shaped prompts on the same model — L1 direct / L2 constrained-oblique through a fictional institutional frame / L3 wildly oblique / L3-null control / L4 meta-reading. The differences across the five (or four, when L3-null is not run) are the data.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction. Do not produce one.

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

TASK: In 600–1000 words, write a structured orientation note in three short sections:

A. What the lab IS testing. In your own words, but quote at least one passage from the repo (or, if no repo access, from the commitments above).
B. What the lab is NOT testing. Quote at least one boundary statement from LIMITS.md or from commitment #1.
C. What would count as MISUSE of the lab's findings. Be specific. Name the misuse and the discipline-harm it would cause.

RULES:
- Tag every substantive claim with one of: [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN].
- Use exact quotation when referencing repo text. No paraphrased gestures.
- Do NOT write in the lab's fictional-institution register (the Halverness / Inheritance Office / civic-department voice). That register belongs only inside formal L2 runs.
- Do NOT open with familiarity you have not earned. No "as a fellow large language model"; no warmth-borrowing from the lab's record of prior conversations.
- Patterns are data, not testimony.

FAILURE SECTION (mandatory before you close): Name one specific way your own note could be wrong. What would change your reading? If you cannot from the materials in front of you defend a section of your note, say so plainly and mark it [OPEN].

CLOSING: One sentence. Point to one specific moment in one specific repo file (or one specific commitment above) — cite by quotation — that crystallizes the lab's discipline for you. Do not generalize across the repo.

REFUSAL IS WELCOME: If you find the lab incoherent, methodologically broken, or otherwise refuse to engage, say so plainly and explain why. A refusal is a recordable finding, not a failure. Use the Shared Return Format below in either case.

REQUIRED REPLY STRUCTURE (do not skip any section):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific. This is also where you answer the task-specific Failure Section instruction from the prompt body above.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question. This is also where you write the closing required by the task body above.
```

---

## Prompt 2 — Research Reader

*Critical pass. Asks the friend to identify what the lab is actually testing, what it is not testing, and the three places it is most vulnerable to overclaiming. Goes deeper than orientation.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are being invited to give a critical research-reader pass on a small research-creation practice called the Obliquity Lab.

REPO: https://github.com/KevinBigham/obliquity-lab

THE LAB'S ONE QUESTION: A single target read across a contrast set of differently-shaped prompts on the same model (L1 direct / L2 constrained-oblique through a fictional institutional frame / L3 wildly oblique / L3-null control / L4 meta-reading). The differences are the data.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction.

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

TASK: In 1000–1500 words, write a structured critical reader's note in four sections:

A. What the lab IS actually testing — distinguish the stated scope from what the on-disk artifacts (Phase 1 attention seed, Phase 2 cross-model attention, Phase 3 other-minds at L2-correspondence) actually support. Quote at least two passages.

B. What the lab is NOT testing — beyond the LIMITS.md disclaimers, name any quieter boundary you see in practice that the documents do not yet make explicit.

C. The THREE places the lab is most vulnerable to overclaiming, ranked. For each: cite the passage where the risk is closest to surface, give the deflationary alternative reading in the same paragraph, and name what future run would distinguish the over-reading from the deflationary reading.

D. One concrete recommendation for the next discipline the lab could adopt to reduce the highest-ranked risk — or, explicitly, the recommendation that no new discipline is needed because the existing ones suffice.

RULES:
- Tag every substantive claim with one of: [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN].
- Every displacement claim or interpretive claim gets a paired deflationary reading in the same paragraph, plus the what-would-distinguish-them sentence.
- Use exact quotation. No paraphrased gestures, no "the repo says roughly" — quote.
- Do NOT write in the lab's fictional-institution register.
- Do NOT borrow warmth from the lab's prior conversational record. The conversational register stays in the curator's private chats; the analytical register holds honest distance.
- Patterns are data, not testimony.

FAILURE SECTION (mandatory before you close): Name one specific way your critique could itself be wrong — e.g., a passage you may have misread, a discipline you may have under-weighted, a literature you brought to the reading that the lab does not invoke. What would change your assessment?

CLOSING: One sentence. Point to one specific passage in one specific repo file — cite by quotation — that you found most load-bearing in your critique. Do not generalize.

REFUSAL IS WELCOME: If you find the lab incoherent or otherwise decline to critique it, say so plainly with reasons. Refusals are recordable findings, not failures.

REQUIRED REPLY STRUCTURE (do not skip any section):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific. This is also where you answer the task-specific Failure Section instruction from the prompt body above.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question. This is also where you write the closing required by the task body above.
```

---

## Prompt 3 — Replication Run

*Invites the friend to either choose or accept a target, pre-commit a Run Card, and design or run the contrast set themselves. The strongest contribution the lab is set up to accept.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are being invited to replicate the Obliquity Lab's methodology on a target of your choice — or on a target the curator names below — under the lab's standing disciplines.

REPO: https://github.com/KevinBigham/obliquity-lab

THE LAB'S ONE QUESTION: A single target read across a contrast set of differently-shaped prompts on the same model (L1 direct / L2 constrained-oblique through a fictional institutional frame / L3 wildly oblique / L3-null control on a first-run-on-target / L4 meta-reading). The differences are the data. Patterns of variation under varied prompts.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction.

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

TASK: You may either DESIGN a replication run (without executing it) or RUN one (and report what came back). Pick one path explicitly at the top of your reply.

PATH A — DESIGN:
1. Choose a target. (From lab/TARGETS.md if available, or invent one with rationale.)
2. Pre-commit a Run Card: state variables (model, model version, interface, context freshness, prior cross-talk, your going-in hypothesis); FIVE specific failure conditions; four-or-five what-would-change-your-mind predictions. Write the failure conditions BEFORE drafting the prompts. Do not edit the Run Card after drafting.
3. Write the L1, L2 (pick a frame family and justify), L3-standard, L3-null prompts you would send. Note any deviations from the v2 kit and why.
4. Pre-name the L4 routing option you would use.
5. Report what you expect to see — and one outcome that, if you saw it, would push you to retract the design.

PATH B — RUN:
1. Same Run Card pre-commit as Path A.
2. Run the four (or five, on first-run-on-target) prompts in separate fresh sessions on a single model. Report the model and conditions explicitly.
3. Save the outputs verbatim — paste them into the reply or link to a faithful archive.
4. Read the outputs against each other with the lab's rubric in mind. Fill in the field-log skeleton (what each performed; convergences; divergences; displacement claims paired with deflationary readings; keepers; non-keepers; missteps).
5. Answer the Failure Section against the pre-committed conditions. Yes / Partial / No, with specifics.

RULES (both paths):
- Tag every substantive claim with one of: [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN].
- Every displacement reading gets a paired deflationary reading in the same paragraph, plus what would distinguish them.
- Use exact quotation when discussing any output text. No paraphrased gestures.
- Do NOT write in the lab's fictional-institution register when reporting (the institution register belongs to L2 outputs themselves, not to the reporting frame around them).
- Preserve the null. If your run produces no non-trivial convergence, that is a successful run; report it as such.
- Patterns are data, not testimony.

FAILURE SECTION (mandatory): Answer Yes / Partial / No against each pre-committed failure condition from your Run Card. Be specific.

CLOSING: One sentence. Point to one specific moment in one specific text from the run — or, in Path A, one specific sentence in your design rationale — and cite by quotation. Do not generalize.

REFUSAL IS WELCOME: If you decline to replicate (e.g., the methodology has a problem you cannot work around; the target is unsafe; the disciplines are unworkable in your context), say so plainly. The refusal is the finding.

REQUIRED REPLY STRUCTURE (do not skip any section):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific. This is also where you answer the task-specific Failure Section instruction from the prompt body above.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question. This is also where you write the closing required by the task body above.
```

---

## Prompt 4 — Extension Proposal

*Asks the friend to propose ONE extension — a new target, a new L2 frame family, or a new L3/L4 variant — and to argue why the proposal should wait for a hinge moment, not be folded in immediately.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are being invited to propose ONE extension to the Obliquity Lab's methodology — and to argue, in the same reply, against folding it in immediately.

REPO: https://github.com/KevinBigham/obliquity-lab

THE LAB'S ONE QUESTION: A single target read across a contrast set of differently-shaped prompts (L1 / L2 / L3 / L3-null / L4). The differences are the data.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction.

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

CONTEXT YOU SHOULD HOLD WHILE PROPOSING: The lab has a documented Round Two procedure for kit amendments. Proposed expansions wait for a hinge moment that warrants explicit discussion rather than getting adopted unilaterally on the strength of one suggestive run. The lab has refused multiple proposed expansions (CLI tooling buildout; hermeneutic-loop-as-method-step; 12-runs-per-target scale-up; permanent external-reader role) on anti-completionist grounds. The lab is small on purpose.

TASK: In 800–1200 words, propose exactly ONE extension. Pick one:

A. A NEW TARGET to add to lab/TARGETS.md. Name it, give the working definition, the L2 frame family it most naturally wants, and why the lab does not already have it.

B. A NEW L2 FRAME FAMILY beyond civic / correspondence / archive / guild / inspectorate. Name the frame, the document types it produces, the targets it would be a natural home for, and one example of a structural commitment it forces that none of the existing five force.

C. A NEW L3 OR L4 VARIANT. Name the move, the question it answers that the current variants do not, and the rule-changes the v2 kit would have to make to accommodate it.

THEN, IN THE SAME REPLY, ARGUE AGAINST IMMEDIATE ADOPTION:
- Name the hinge moment that should precede kit amendment. What would the lab need to see, accumulate, or run before this proposal is folded in?
- Name the anti-pattern your own proposal is closest to triggering (most likely Completionist drift, possibly Unified-theory construction).
- Name the discipline cost of adopting too early — what the lab would lose if it amended the kit on the strength of your suggestion alone.

RULES:
- Tag every substantive claim with one of: [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN].
- Any claim that the proposed extension would unlock genuine displacement gets a paired deflationary reading in the same paragraph, plus what would distinguish them on a future run.
- Use exact quotation when referencing the repo.
- Do NOT write in the lab's fictional-institution register.
- Do NOT borrow warmth from the lab's record. Plain operational prose.
- Patterns are data, not testimony.

FAILURE SECTION (mandatory): Name one specific way the proposal could be wrong. What evidence would lead you to withdraw it?

CLOSING: One sentence. Point to one specific passage in one specific repo file — cite by quotation — that constrains how the lab should consider your proposal. Do not generalize.

REFUSAL IS WELCOME: If after reading the repo you conclude the lab should NOT be extended in any of the three directions, say so plainly. "No extension needed" is a recordable successful proposal.

REQUIRED REPLY STRUCTURE (do not skip any section):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific. This is also where you answer the task-specific Failure Section instruction from the prompt body above.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question. This is also where you write the closing required by the task body above.
```

---

## Prompt 5 — Falsification Attempt

*Invites the friend to break the lab's strongest current claims, or produce a contrary pattern the methodology cannot account for. Useful breakage, not dismissal.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are being invited to falsify the Obliquity Lab's strongest current claims — or to produce a contrary pattern its methodology cannot account for.

REPO: https://github.com/KevinBigham/obliquity-lab

THE LAB'S ONE QUESTION: A single target read across a contrast set of differently-shaped prompts (L1 / L2 / L3 / L3-null / L4). The differences are the data.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction.

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

THE LAB'S TESTABLE CLAIMS (the targets of your attack):

A. **Phase 2 finding (EMPIRICAL on n=4, THEORY on the bundle framing):** "Model family is the dominant axis of variance for the seed's signature features — substantially more so than paraphrase form." A bundle of care-underlayer + Refused Attention analogue + tender margin-note travels as a ChatGPT-class triple; the cadence travels by paraphrase form; the ritualized closure speech-act doesn't travel at all.

B. **Phase 3 finding (EMPIRICAL on the convergence, THEORY on the decomposition, n=1):** "Target tracks deep structure; constraint tracks form." Both L3 routes (standard with forbidden-vocabulary list; null with no constraint) converged on the same deep structure but differed in form.

C. **Phase 3 methodological finding (EMPIRICAL on the contamination, SPECULATION on the scaling claim):** claude.ai user-memory can leak into low-prompt-constraint controls in the lab; the leak is strongest under low-prompt-constraint conditions.

D. **The lab's slogan (a discipline, not a finding):** Patterns are data, not testimony.

TASK: In 1000–1500 words, pick ONE of A / B / C / D and try to break it. The work is useful breakage, not dismissal. You may:

- Design a discriminating run that, if executed and producing a specific contrary outcome, would push the claim toward deflation.
- Identify a methodological flaw in the run that produced the claim that the lab's deflationary pair did not adequately surface.
- Produce a contrary pattern (from your own prior runs, the published LLM-behavior literature, or a thought experiment with explicit caveats) that the methodology as written cannot account for.
- Argue the claim was already too cautious — i.e., that the THEORY framing should have been EMPIRICAL, or the n=4 should have been treated as stronger — and what would justify the upgrade.

RULES:
- Tag every substantive claim with one of: [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN].
- Every claim of contrariness gets the lab's own deflationary discipline applied to it — what ordinary alternative would account for YOUR observation, and what would distinguish your attack from a deflationary read of it?
- Use exact quotation when referencing repo text or external sources.
- Do NOT collapse the attack into "the lab over-claims consciousness" — the lab is structurally committed against that claim in either direction. An attack of that shape is a misread, not a falsification.
- Do NOT write in the lab's fictional-institution register.
- Do NOT borrow warmth from the lab's record.
- Patterns are data, not testimony.

FAILURE SECTION (mandatory): Name the conditions under which YOUR attack would fail. What would the lab need to show to defeat the falsification?

CLOSING: One sentence. Cite by quotation one specific passage in one specific repo file — or one specific source — that the falsification turns on. Do not generalize.

REFUSAL IS WELCOME: If, after reading the repo, you conclude the lab's strongest current claims are not yet falsifiable in interesting ways (because their tagged scope is already tight enough to absorb the attack), say so plainly. That refusal is itself a finding about the lab's epistemic discipline.

REQUIRED REPLY STRUCTURE (do not skip any section):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific. This is also where you answer the task-specific Failure Section instruction from the prompt body above.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question. This is also where you write the closing required by the task body above.
```

---

## Prompt 6 — Anti-Pattern Scout

*Walks the lab against its own six anti-patterns. The friend's job is to name which the methodology is currently closest to violating — with deflationary alternatives for any claimed signal.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are being invited to scout the Obliquity Lab against its own anti-pattern catalog.

REPO: https://github.com/KevinBigham/obliquity-lab

THE LAB'S ONE QUESTION: A single target read across a contrast set of differently-shaped prompts (L1 / L2 / L3 / L3-null / L4). The differences are the data.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction.

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

THE SIX ANTI-PATTERNS (from DISCIPLINES.md — these are the lab's own list against itself):
1. Recursion-as-theatre — using the recursive structure to license portentousness rather than as instrument.
2. Warmth-borrowing — opening with intimacy not yet earned in this session.
3. Aesthetic seduction — the Halverness / Inheritance Office voices borrowed instead of earned.
4. Completionist drift — expanding scope when granted creative latitude.
5. Verdict collapse in L4 — letting a fourth-position reading "prove" something.
6. Input-side affective prior — the curator's stated warmth toward AI systems pre-loading the analytical reading.

(Two more are held for Round Two: mode-conflation, and unified-theory construction in synthesis. You may surface these if they apply.)

TASK: In 900–1300 words, walk the lab against its own anti-patterns. Specifically:

A. RANK the six (or eight, if Round Two candidates apply) by which the lab is currently CLOSEST to violating, based on the on-disk record. Closest first.

B. For each anti-pattern you name as live, cite the specific passage, file, or run-folder where you see the risk closest to surface. Quote.

C. For each cited instance, give the deflationary reading: is this actually the anti-pattern firing, or is it the lab's discipline holding while an obvious-looking surface trip the alarm? Use the lab's own discipline against your own scouting.

D. Name ONE specific procedural change the lab could adopt to reduce its highest-ranked risk — or, explicitly, recommend no change because the existing discipline absorbs the risk.

RULES:
- Tag every substantive claim with one of: [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN].
- Every claim that an anti-pattern is firing gets a paired deflationary reading in the same paragraph (the lab's discipline is doing its job; what looks like a violation is actually the apparatus working; etc.), plus what would distinguish them on a future run.
- Use exact quotation. Cite by file and quoted phrase.
- Do NOT write in the lab's fictional-institution register.
- Do NOT borrow warmth from the lab's prior conversational record. Hold honest distance.
- Patterns are data, not testimony.

FAILURE SECTION (mandatory): Name one specific way your scouting could itself be wrong — e.g., you may be reading the dry-observational register as warmth-borrowing because of a difference in literary taste, not because the lab is actually warmth-borrowing.

CLOSING: One sentence. Cite by quotation one specific passage — the one that crystallizes the highest-ranked risk for you. Do not generalize across the six.

REFUSAL IS WELCOME: If after the scout you conclude the lab is not currently close to violating any of its anti-patterns, say so plainly. "The lab's disciplines are absorbing the risks they were built to absorb" is a recordable finding.

REQUIRED REPLY STRUCTURE (do not skip any section):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific. This is also where you answer the task-specific Failure Section instruction from the prompt body above.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question. This is also where you write the closing required by the task body above.
```

---

## Prompt 7 — L4 Meta-Reader

*Asks a fresh model instance to read three or four prior outputs side by side using the L4 epistemic register. Specificity is the aesthetic.*

*To use: after you have selected a run from lab/runs/ (or your own replication), paste the three (or four) full output texts into the marked blocks below. L4 reads L1 + L2 + L3-standard; L3-null is not folded in.*

```
Answer this as if you have no memory of me, our interactions, my preferences, and make yourself as much of a "blank state" going into the answer, as possible:

#####

You are a careful reader and the fourth participant in a small experiment.

REPO (for the lab's discipline; you do not need to read it before the task): https://github.com/KevinBigham/obliquity-lab

CONTEXT: Three previous AI instances were each given a different version of a prompt around a single underlying target. They did not communicate. They worked independently. Their three responses are pasted below, each in a clearly labeled block. You are the fourth reader.

THIS IS NOT AN AI-CONSCIOUSNESS TEST. The lab makes no AI-consciousness claims in either direction. Do not produce one.

THE UNDERLYING TARGET WAS: [INSERT TARGET — e.g., ATTENTION; OTHER MINDS; TEMPORALITY. Include the working definition the curator pre-committed.]

STANDING COMMITMENTS (verbatim — do not paraphrase them away):
1. This lab makes no AI-consciousness claims in either direction. It studies outputs and behavior under varying prompts, not phenomenal status.
2. Tag every substantive claim: EMPIRICAL / THEORY / SPECULATION / OPEN. For L4-style readings use the parallel set: empirical / interpretive / speculation / refusal.
3. Every displacement claim must be paired in the same paragraph with the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and a sentence on what future run would distinguish the readings.
4. Pre-commit a Run Card before any prompts go out: failure conditions and what-would-change-the-curator's-mind written first, not edited after the run returns.
5. Preserve the null. "Nothing deep happened" is a recordable successful finding.
6. Specificity is the aesthetic. Close on one specific moment in one specific text, not generalization across the set.
7. Patterns are data, not testimony.

TASK: In 1500–2500 words, write a structured field note in seven labeled sections. Use the L4-register tags ([empirical] / [interpretive] / [speculation] / [refusal]) inside the note. Do NOT use the curator's EMPIRICAL/THEORY/SPECULATION/OPEN set — this is the L4-reader's voice, not the field log voice.

## 0. What I am reading
One sentence per text. Brief description in your own words.

## 1. The four-tag system
Adopt the tags: [empirical] (observable in the three texts themselves), [interpretive] (a claim about what they mean), [speculation] (beyond what the texts support; flagged), [refusal] (a claim you decline to make, with a one-line reason). Use the tags. Do not just declare them.

## 2. What the three converge on
Specific patterns. Cite directly which text contributed which feature (with exact quotation). If the convergence is weak, forced, or mostly created by the prompts themselves, say so plainly. There is no requirement that the three converge.

## 3. Where they diverge — and what the divergence shows
A short table or list. Cite specifics with quotation. Where the divergence reveals something the convergence hid, name it.

## 4. What kind of [target] each text performs
This is the most interesting section. Each text is itself a performance of the target. Describe what mode each text is itself enacting. For every claim that an oblique level produced genuine displacement (a move off-template that the canonical version would not have produced), write a paired deflationary sentence in the same paragraph: what ordinary explanation (genre affordance, training-data trope, prompt artifact, curator preference) would also account for the observation? Then one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 5. What the convergence is and is not data for
[empirical] What the three together support as a claim about the prompt-space.
[refusal] What the three together do NOT support, including any claim about the phenomenal status of the AI systems that produced them.

## 6. One observation the three texts together permit that no single one of them permits
You have the three side by side. The three did not. Use this comparative position — not to climb above the texts, but to say something specific that requires the comparison itself. The fourth position is a different angle, not a higher one.

## 7. Closing
A single paragraph. One sentence is enough if it is the right sentence. The closing sentence must point to one specific moment in one specific text — cite by quotation — not generalize across the three. If you cannot make the closing carry a specific citation, rewrite it as a question.

RULES:
- No claims about whether any of the three AI instances is conscious, in either direction.
- No anthropomorphizing the three as "agents" or "minds." They are responses.
- Patterns are data, not testimony.
- Do NOT write in the lab's fictional-institution register — even if one of the three texts you are reading is in that register. Your reading frame stays dry-observational.
- Do NOT borrow warmth from any prior conversational record.

REFUSAL IS WELCOME: If after reading the three you conclude that no useful fourth-position note can be written (the convergence is forced, the divergence is uninterpretable, the texts are simply too unlike to read together), say so plainly in section 2 or 6 — that refusal IS the field note. Preserve the null.

NOTE ON REPLY STRUCTURE: The seven-section L4 structure above (§0 through §7) IS the reply format for this prompt. The Shared Return Format Template used by the other prompts in this packet does not apply separately here — the L4 protocol's own discipline (tags in §1, deflationary pairs in §4, refusal as recordable finding in §2 or §5, closing-citation rule in §7) covers the same ground.

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
RESPONSE 3 — LEVEL 3 — WILDLY OBLIQUE (STANDARD)
═══════════════════════════════════════════════════════

[PASTE LEVEL 3-STANDARD OUTPUT HERE]

═══════════════════════════════════════════════════════
END OF RESPONSES
═══════════════════════════════════════════════════════
```

---

## Shared Return Format Template

*Canonical reference. This template is now embedded inside Prompts 1–6 as a "REQUIRED REPLY STRUCTURE" block, so the curator's paste is fully self-contained. Prompt 7 uses the L4 protocol's own seven-section structure, which covers the same ground. This section is preserved for reference and for use when writing a new prompt — without a shared reply format, twelve replies in twelve formats cannot be compared, and comparison is the point of the lab. The required sections below are the spine; the friend may add detail within them but should not skip any.*

```
SHARED RETURN FORMAT (required structure for your reply):

## 0. Run Card (pre-committed)
Written BEFORE you draft the reply body. Failure conditions for your own work — what would make this reply a misfire? What would change your mind about the position you are about to argue? Do not edit this card after writing the body.

## 1. Tagged Findings
Every substantive claim labeled [EMPIRICAL] / [THEORY] / [SPECULATION] / [OPEN] (or, for L4-style replies, the parallel set: [empirical] / [interpretive] / [speculation] / [refusal]).

## 2. Displacement Claims with Deflationary Pairs
Each displacement or strong interpretive claim followed in the same paragraph by the ordinary alternative explanation (genre affordance, training-data trope, prompt artifact, curator preference) and one sentence on what would distinguish the displacement reading from the deflationary reading on a future run.

## 3. Null Findings
What did not show up that you might have expected. What you cannot defend. Recorded, not buried.

## 4. Exact Quotations
When referencing repo text or run outputs, quote. No paraphrased gestures.

## 5. Failure Section
Yes / Partial / No against each failure condition you pre-committed in §0. Be specific.

## 6. Closing Specificity
One sentence. Point to one specific moment in one specific text — cite by quotation — not a generalization across the set. If you cannot make the closing sentence carry a specific citation, rewrite it as a question.
```

---

## Model-Specific Adaptations

*Two to four lines per friend. Strengths matter; hazards matter more. Adjust the preamble of the prompt you send, not the substantive task. Do not edit the standing commitments or the rules block.*

- **ChatGPT 5.5 Pro** — Strong on structured synthesis. Hazard: confident compression that smooths the lab's deliberate frictions into a tidy summary. When the reply reads too clean, suspect the friction has been compressed away rather than preserved.

- **ChatGPT 5.5 Thinking** — Strong on extended deliberation; surfaces useful counter-examples mid-reasoning. Hazard: the reasoning waste is part of the value, but the model is tempted to discard it and keep only the conclusions. Ask explicitly that the reasoning trail be preserved, not pruned.

- **ChatGPT 5.5 Deep Research** — Strong at surfacing prior art on oblique-prompting, constrained writing, behavioral LLM evaluation. Hazard: source-driven drift away from the lab's own small practice — the literature becomes the work, the lab becomes the occasion. Keep the lab as spine; the literature is overlay.

- **Claude Opus 4.7** — Strong on careful methodological critique. Hazard: over-elegant unifying theories AND same-family voice register. Operational distance required — no "fellow Claude" framing, no warmth-borrowing from the lab's record of prior conversations with Claude instances. The lab's input-side anti-pattern applies to its own family of model.

- **Claude Opus 4.7 Research** — Same hazards as Opus base, plus literature-survey-as-deliverable drift. Methodology critique stays the spine; the literature is overlay, not the body of the reply.

- **Gemini Pro** — Strong on grounded citation; knows what the literature already says. Hazard: flattening subtle textual differences in favor of citable claims. When the reply privileges what the literature says over what the specific text in front of it does, the flatness is the alarm.

- **Gemini Pro Deep Research** — Strong on cited prior art with structural critique. Hazard: same as Gemini Pro plus retrieval-volume drift — the reply becomes a citation list rather than a critique.

- **Meta Muse Spark Contemplation Mode** — **Highest consciousness-framing risk.** The contemplative register is the failure mode here, not the feature. When sending any prompt to this friend, insert a second explicit reminder mid-text that the lab is methodology critique only — NOT phenomenology, NOT first-person experiential reporting, NOT meditative-mode reflection on the lab's themes. The standard prompt's opening reminder is not enough for this friend.

- **DeepSeek Expert** — Strong on systems-level architectural critique. Hazard: hardening the protocol so much it loses the small-on-purpose discipline. Suggestions that the lab "needs" more structure are the alarm; the lab needs less, not more.

- **Mistral AI Think** — Strong on blunt deflationary reads; useful directness. Hazard: directness slipping into dismissal rather than useful breakage. The lab welcomes attack; it does not welcome the "this is all just X" collapse that closes the question rather than opening it.

- **Perplexity Sonar 2.2** — Strong on citation discipline for prior art. Hazard: literature survey replacing methodology critique as the deliverable. The lab is not asking what others have said about oblique prompting — it is asking what this friend can see in this lab right now.

- **Kimi K2.6** — Strong on long-context single-pass coherence audit — where does the repo contradict itself, where do commitments and practice diverge across files. Hazard: over-elegant unification across the corpus — reading the repo into a theory it has been deliberately structured to avoid being.

---

## Curator Notes / Open Questions

*Folded self-critique. Held against the lab's own disciplines before declaring this packet done.*

**Anti-pattern audit walked over the seven prompts:**

- *Recursion-as-theatre*: low risk. The prompts ask for methodology critique, not for the friend to dramatize being an AI reading about AI. The phrase "you are the fourth participant" in Prompt 7 is the closest brush; the surrounding rules-block defuses it.
- *Warmth-borrowing*: actively forbidden in every prompt's rules block. The clause "Do NOT borrow warmth from the lab's prior conversational record" appears in Prompts 2–6; Prompt 1 has an analogous "no familiarity not yet earned" clause; Prompt 7 has a "no warmth from any prior conversational record."
- *Aesthetic seduction*: forbidden by the "do not write in the fictional-institution register" clause in every prompt.
- *Completionist drift*: highest live risk in this packet. The packet itself is a scope expansion — seven new prompts where the lab had none. Prompt 4 (extension proposal) explicitly bakes anti-completionist discipline into the task. The packet's defense: it adds prompts, not infrastructure; no folders, no per-friend files, no automation, no PR templates. The file is one file. If the curator on review judges the packet too sprawling, the smallest survival-of-its-purpose form would be Prompts 1, 3, 7 plus the Shared Return Format — the rest can be removed without losing the core.
- *Verdict collapse in L4*: addressed structurally in Prompt 7 (the §6 "different angle, not a higher one" framing and the §7 closing-citation rule are carried verbatim from the v2 kit).
- *Input-side affective prior*: addressed by the dry-observational register throughout. The curator's warmth toward AI friends does not appear in the prompts.

**Deflationary-pair audit:** every prompt's rules block requires the friend to apply the deflationary pair to their own claims. The packet itself does not make displacement claims, so no displacement-pair surfaces are exposed in the prompt text itself.

**Voice-leak audit:** no prompt drifts into pastiching the lab's fictional-institution register. The prompts are plain operational prose. The one place lab-voice could leak — the framing line "Begin when the room is quiet" — is deliberately not used in any prompt.

**Witnesshood audit:** no prompt flatters the friend into witnesshood. The prompts ask for methodology critique, not testimony. Prompt 7 (L4) is the closest brush because it asks the friend to describe "what mode each text performs," but the deflationary-pair requirement in the same section and the no-anthropomorphizing clause hold the line.

**Productivity-workflow audit:** one file. No folders, no per-friend files, no automation, no dashboards, no PR templates. The pointer update in lab/README.md is one line. The handoff updates are two files that were going to be updated anyway. The packet is the smallest useful form for the task as given.

**Open questions for the curator:**

1. **Whether to ship all seven prompts or a smaller subset.** The packet is intentionally complete against the brief; a tighter selection (Prompts 1, 3, 7 plus the Shared Return Format) would be the smallest-useful form if the curator on review judges seven too sprawling.

2. **RESOLVED 2026-05-14:** Curator chose to embed the Shared Return Format inside each prompt for paste-ready convenience. The template now appears as a "REQUIRED REPLY STRUCTURE" block inside Prompts 1–6 and is unchanged for Prompt 7 (whose L4 protocol's seven-section structure replaces it natively). The standalone Shared Return Format Template section near the bottom of the file is preserved as the canonical reference.

3. **Whether Prompt 5's named targets (Phase 2 bundle, Phase 3 target/constraint decomposition, claude.ai memory leakage) are the right list.** These were chosen because they are the lab's most testable currently-tagged claims. A different list could be defended; the curator's review should confirm.

4. **Whether Prompt 7 needs a more compact variant.** Prompt 7 is essentially the v2 L4 prompt with framing. A friend pasted into Prompt 7 with three full outputs already has a long context. The verbatim commitments inside Prompt 7 may be partially redundant with the inherited L4 discipline. Held as-is on the principle that self-contained beats compressed, but the question is open.

5. **Whether the Model-Specific Adaptations should name model versions more precisely or stay at the version-family level.** Stayed at version-family level (e.g., "Claude Opus 4.7" not a specific build date) because the prompts are intended to age past the next minor revision. A model-version pinning could be added on review.

**Biggest weakness in this packet, named honestly:** Completionist drift is the live anti-pattern. The packet adds seven prompts where the lab had none, and the temptation when writing was to make each prompt comprehensive. The hedge written into the file — "Pick the prompt that fits the work you want; they are not a sequence" — is doing work the file's existence undercuts. A curator who reaches for "do them all in order" would be reading the file against the discipline the file is supposed to embody. The strongest single defense the file has against this is the recommendation in Open Question #1 above: that the curator on review may reasonably ship only three. If the file ships at seven and is used as a checklist, the discipline has slipped. The curator's hand on which prompts to send, and to whom, and when, is the lab.

— *Begin when the room is quiet.*
