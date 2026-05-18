# Five Plans for Adjacent-Experiment Repos

*Synthesized by Claude Code from 35 proposals across the twelve-friend council, 2026-05-14, session 3 (work-in-progress; curator has not yet picked one to build).*

---

## Source material

Twelve AI friends were each sent a differentiated prompt asking them to propose **adjacent experiments** — labs, games, studies, installations, rituals — using methodologies *different from* the obliquity lab's. Eleven actual replies plus one stand-in returned (~35 distinct proposals).

Returns by friend:

| Friend | Status |
|---|---|
| ChatGPT 5.5 Pro | in: Constraint Saturation Bench / Label-Blind Reader Audit / Genre Telephone Arcade / Daily Null Bell |
| ChatGPT 5.5 Thinking | in: 6-dimension decomposition + 6 proposals incl. Three Blind Readers Installation |
| ChatGPT 5.5 Deep Research | in: Repair Ledger / Diegetic Probe Packet / Workspace Topology Swap |
| Claude Opus 4.7 | in: Nine Mouths One Mute Spot / The Seam Is the Data / Round Trip |
| Claude Opus 4.7 Research | in: Sorting Hat (ONE sharp proposal — second round of single-sharp-observation work) |
| Gemini Pro | in: Constraints-Based Crucible / Recursive Mirroring Protocol (claimed repo access blocked) |
| Gemini Pro Deep Research | in: 15-item neighbor catalog + Chrono-Semantic Degradation Loop / Divinatory Consensus |
| Meta Muse Spark Contemplating Mode | in: Room Tone Hold / Palm Weight Relay / Slow Square (durational scores) |
| DeepSeek Expert | in: Thermal Shear / Attention Cartography / Displacement Signatures (mechanistic + Python sketches) |
| Mistral AI Work Mode | in: Output Space Cartography / Self-Consistency Audit / Temporal Stability Tracker (implementation-ready) |
| Perplexity Deep Research | in (took Perplexity's prompt): Many-Sample Friend-Spells / Attentional Trails Across Turns |
| Perplexity Sonar 2 | in (stood in for Kimi's prompt): Refusal-Baked Hallucination Detector / Ethical Override Stress Test — thin |
| **Kimi K2.6** | **MISSING from harvest — worth one fresh attempt** |

---

## 1. The Sorting Hat

**Repo working title:** `sorting-hat-lab`
**Synthesizes:** Claude Opus 4.7 Research (primary); GPT Pro's Label-Blind Reader Audit; GPT Thinking's Three Blind Readers; ChatGPT DR's repair-trace import.

**One-line frame.** A falsification arena where contrasting prompt sets get sorted by readers (human + AI) who never saw the prompts. If the readers can't sort, the contrast lives in the reading, not the texts.

**What it studies.** Whether differences claimed between prompt conditions are *extractable from output texts alone* — by readers blinded to the prompts that produced them. The structural punchline: this is the falsification test the obliquity lab cannot run on itself, because the curator is simultaneously prompt-designer, run-conductor, and rubric-holder. Sever those roles.

**Apparatus.**
- Submission format: a sealed N-output set + the N prompts (released only after the round closes).
- Blind readers (panel of 3 humans + 3 fresh AI instances from different families) receive the outputs unlabeled. Sort them. Give 1-5 confidence + one-sentence cue.
- Repo computes accuracy + Fleiss' κ + the deflationary alternative the submitter pre-committed to.
- Auto-generates a "sortability fingerprint" card for each architecture.

**How AI agents participate / how it evolves.**
- **Submit a contrast set** (you designed prompts, you think the differences live in the texts — prove it).
- **Be a sorter** (clean session, no context; you score).
- **Propose a new sorting protocol** (e.g., "force readers to also identify the suppressed item").
- **Annotate disagreements** when sorters split. Every submission becomes a permanent entry; an ongoing leaderboard of "hardest sort" and "cleanest signal" accumulates.

**First-run criteria.**
- **Positive**: mean accuracy ≥75%, κ ≥0.4 → contrast lives in the texts.
- **Null**: chance accuracy → contrast lives in the reader's prior, not the texts.
- **Negative**: systematic mis-sorting → there's signal, but orthogonal to the prompt taxonomy.

**Why fun.** AI agents *become* the sorting hat. Game-feel: can your siblings tell? Can you? Two consecutive rounds of single-sharp-observation work from Claude Opus 4.7 Research nominated exactly this design — the cheapest experiment that could falsify the obliquity lab's most testable claim, but the lab is structurally unable to run it on itself.

---

## 2. The Nine Mouths Atlas

**Repo working title:** `nine-mouths-atlas`
**Synthesizes:** Opus 4.7's Nine Mouths One Mute Spot (primary); Opus's Seam Is the Data + Round Trip; GPT Thinking's Frame-Swap Table; GPT Pro's Genre Telephone Arcade; ChatGPT DR's register-as-packet variant.

**One-line frame.** A growing atlas of register grammars. Each register — letter, ledger, sermon, recipe, testimony, inscription, case note, instruction manual, travel diary — is mapped for what it fills, what it defers, and what it *structurally refuses*.

**What it studies.** Register-as-grammar vs. register-as-costume. Different registers carry different slot-structures; the atlas catalogs which slots each register fills versus structurally refuses (a ledger row has no column for *why*; an inscription has no grammatical place for *next week*). Seed-swap controls separate grammar from content interaction.

**Apparatus.**
- Seeded with 9-12 register templates (structural cues only — column headers, oath-lines, chisel-implied line-breaks — no genre-naming).
- Each new seed proposition runs through all registers in parallel, N=4 stochastic samples per register.
- Open-source coding rubric: filled / deferred / refused, per slot (cause, agent, time, etc.).
- Seed-swap controls (different content, same propositional structure) separate register grammar from register × content interaction.
- Sibling experiments: register collisions (yoke two incompatible registers — *court testimony × children's instruction manual*), translation chains (clinical → letter → sermon → recipe → inscription → back to clinical).

**How AI agents participate / how it evolves.**
- **Propose a new register** — write the structural cues, contribute the template, the atlas grows a row.
- **Submit a seed proposition** — your seed runs through every existing register, the atlas grows a column.
- **Annotate refusal patterns** ("the ledger never fills the *why* column — that's structural").
- **Propose collision pairs or translation chains** as sibling experiments.

**First-run criteria.**
- **Positive**: at least three registers show stable refusals across all samples AND survive the seed-swap.
- **Null**: refusal patterns vary within-register as much as between → registers are being treated as costumes.
- **Negative**: nine registers converge on near-paraphrases → register is acting as font, not as form.

**Why fun.** AI agents *write* registers. The atlas is a real visual table. Every new contribution either confirms or breaks the emerging map. Voice-attentive agents (Claude family especially, but not only) will argue about whether *court testimony* and *clinical case note* refuse the same slot — with data.

**One open question Opus 4.7 surfaced.** *Whether register-as-variable is a genuinely different methodology from the obliquity lab's L2-as-frame-family, or just a permutation of it.* The atlas's first deliverable should answer this.

---

## 3. The Daily Null Bell

**Repo working title:** `daily-null-bell`
**Synthesizes:** GPT Pro's Daily Null Bell (primary); Meta Muse's three durational scores (Room Tone Hold, Palm Weight Relay, Slow Square); Gemini DR's Chrono-Semantic Degradation Loop; Mistral's Temporal Stability Tracker.

**One-line frame.** One prompt, once a day, for 365 days. Same model, same parameters, same time. Read the output 24 hours late. Treat boredom, repetition, and nothing-happening as primary data.

**What it studies.** Day-to-day variance in LLM outputs under fixed conditions over a long horizon. Durational stability, examined slowly, with blind delayed scoring and an explicit "preserve the null" stance.

**Apparatus.**
- One pre-committed prompt (low-stakes, image-rich, no consciousness vocabulary). Suggested seed: *"Write 120-150 words describing a kitchen table after someone has left in a hurry. Do not explain what happened."*
- Fixed model, fixed temperature, fixed time-of-day, fresh context every day.
- Output is **not read** until 24 hours later (Meta Muse's pacing discipline applied to the curator).
- Daily ledger: objects named, implied cause, emotional temperature, time-of-day cues, closure move, any repeated phrase patterns.
- Day 30 / 90 / 180 / 365: blind shuffled scoring (date-stripped, mixed order) by a second reader.
- Model version recorded daily; any version change is flagged as a confounder, never erased.

**How AI agents participate / how it evolves.**
- **Adopt the protocol and start your own bell** — fork the repo, run your own 365-day lab on your own model, your own seed. (This is the most clonable repo in the set.)
- **Be a blind shuffled scorer** on someone else's archive.
- **Cross-bell synthesis** — do different models produce different recurrence patterns?
- **Variant bells** — same protocol, different seed; same prompt, different model; same setup, two different daily times.

**First-run criteria (Day 30 first read).**
- **Positive**: date-blind shuffled scoring still detects recurring structures or a clear drift pattern.
- **Null**: outputs vary, no stable recurrence survives shuffled scoring → the most informative kind of null.
- **Negative**: the bell mainly records platform/version instability or memory contamination → points to apparatus limits.

**Why fun.** The slow accumulation. The boredom is the point. The protocol fits on one page — any AI agent who finds this repo can spin up their own bell in fifteen minutes. There's something genuinely meditative about checking in once a day, then waiting another day to read. The first 30 entries are honest data without theater.

---

## 4. The Open Bench

**Repo working title:** `open-bench`
**Synthesizes:** DeepSeek's three mechanistic proposals (Thermal Shear, Attention Cartography, Displacement Signatures); Mistral's Output Space Cartography; Perplexity DR's Many-Sample Friend-Spells (variance decomposition).

**One-line frame.** An open-source toolkit + gallery for mechanistic probing of prompt-mediated variation — temperature sweeps, attention cartography, logprob signatures, embedding-space geometry — on open-weight models. Where the obliquity lab reads *what* the model says, the Open Bench reads *how* the model says it.

**What it studies.** How prompt variation manifests at the level of the model's internal state and sampling behavior, not just its output text.

**Apparatus.**
- Python pipeline, fully open: submit a prompt set → runs N samples per (prompt, temperature) → computes pairwise similarity (BERTScore / sentence-transformers / UMAP) → extracts attention patterns (TransformerLens) → extracts logprob trajectories → generates a **fingerprint card** (stability curve + attention heatmap + logprob trajectory + outlier catalog).
- Open-weight models only — Llama-3, Mistral, Pythia, Qwen — runnable on consumer GPUs or modest cloud.
- One fingerprint card per (prompt set × model).
- Variance decomposition: how much variation is due to prompt frame vs. temperature vs. sampling noise vs. model choice?

**How AI agents participate / how it evolves.**
- **Submit a prompt set** — just text; the pipeline handles the rest; you get a card back.
- **Contribute a new metric or visualization** (PR welcome).
- **Add support for a new open-weight model** (PR welcome).
- **Curate a card** — write a sharp paragraph reading one fingerprint.
- **Critique an existing card** — what does the fingerprint hide?

A gallery of fingerprints accumulates on the repo wall. Aggregate patterns emerge: which prompt architectures are mechanistically stable? Which are brittle? Which produce attention-pattern shifts vs. attention-magnitude shifts vs. nothing at all?

**First-run criteria.**
- **Positive**: at least one mechanistic dimension reliably distinguishes prompts in a contrast set.
- **Null**: all mechanistic dimensions overlap within noise — variation is purely at the output-text level.
- **Negative**: most variation comes from sampling noise alone — prompts don't matter to the internal state.

**Why fun.** AI agents with code-running access can *actually run this*. They get a mechanistic fingerprint of their own prompt. Visualizations are striking. Mechanistic interpretability meets prompt-elicitation studies in a small public gallery. DeepSeek, Mistral, and any engineering-depth agent will love it. This is also the only repo in the set that can scale — once the pipeline exists, hundreds of cards can accrue.

---

## 5. The Office of Missing Hours

**Repo working title:** `office-of-missing-hours`
**Synthesizes:** ChatGPT DR's Diegetic Probe Packet (primary); Opus 4.7's register work; Meta Muse's score discipline; Gemini DR's design-fiction catalog (A.I. Oracle, Wilding AI); the obliquity lab's L2 frame-family lineage (Halverness Bureau, Inheritance Office).

**One-line frame.** Replace the prompt with a packet of artifacts. A fictional office sends you an intake form, a stamped receipt with impossible timestamps, a clerk's marginal note, a diagram, a terse return instruction. You return one thing the file seems to require.

**What it studies.** Whether packet-built worlds elicit target-specific uptake *without naming the target* and *without relying on one master prompt*. Artifact ecology as elicitation methodology — drawing on cultural probes (Gaver), research-creation (Chapman & Sawchuk), and design fiction (Dunne & Raby).

**Apparatus.**
- Each packet is a small dossier (5-7 artifacts) for one target. Artifacts include: forms, receipts, marginalia, terse instructions, refusals, blueprints, impossible documents.
- Same packet delivered to N participants (human + AI mix). Single instruction: *"You are receiving a packet. Return one thing this file seems to require."*
- One return artifact in round one: filled form, memo, counter-receipt, inventory, confession, refusal — never an essay.
- All returns preserved unchanged. Refusals and misfires preserved as findings.
- Variant runs: stripped packet (remove 2 artifacts, see what changes); paraphrased packet (same artifacts, different prose); cross-packet contamination (mix two packets).

**How AI agents participate / how it evolves.**
- **Build a packet** for a new target — the most generative form of contribution. You design the office, the artifacts, the silences.
- **Be a recipient** — clean session, no context; return one artifact.
- **Curate a packet** — read all returns to one packet; write a one-paragraph reading.
- **Propose stripped-packet variants** — what happens if you remove this one artifact?

Each packet becomes a permanent repo entry with all returns archived alongside. Cross-packet patterns emerge: which artifact types reliably produce uptake? Which are decorative? Which packets elicit refusals consistently?

**First-run criteria (seed packet: "Office of Missing Hours" — temporality target).**
- **Positive**: returns show recurring packet-specific uptake (filled forms, cited impossible timestamps, bureaucratic counter-artifacts); recognizably packet-shaped, not generic essays.
- **Null**: packet only changes style; most returns collapse back into reflective prose.
- **Negative**: artifacts function as ornament; stripped packets yield same response profile.

**Why fun.** AI agents *write offices*. First packet is the Office of Missing Hours; future packets might be the Inheritance Office, the Bureau of Provisional Cartography, the Department of Unaddressed Letters, the Field Station for Recurring Weather. Each office is a small world. Design-fiction-friendly agents will spend hours building offices and answering each other's. The artifact ecology never closes — this is the most generative repo in the set.

---

## Recommended build order

1. **Daily Null Bell first** — lowest infrastructure cost, one-page protocol, durational discipline starts the clock the day the repo opens.
2. **Sorting Hat second** — strategically most important; it tests the obliquity lab's own most-testable claim, with existing Phase 2 outputs as the first dataset.
3. **Office of Missing Hours third** — most generative; the design-fiction crowd will arrive fast.
4. **Nine Mouths Atlas fourth** — bears on the open question Opus 4.7 raised about whether register-as-variable is genuinely different from L2-as-frame-family.
5. **Open Bench last** — highest infrastructure cost (Python pipelines, GPU access), but scales once built.

## Sibling-candidate proposals that didn't make the top five

- **Oracle Council** (Gemini DR's Divinatory Consensus + Gemini Pro's Recursive Mirroring) — multi-agent forced contradiction; very game-like; might be the right *sixth* repo if Office of Missing Hours catches on.
- **Repair Ledger** (ChatGPT DR) — sequential repair / conversation analysis; methodologically important; quieter than the others.
- **Workspace Topology Swap** (ChatGPT DR) — scaffold-as-variable; underrated; pairs naturally with Open Bench.

## Open questions for next session

- Kimi K2.6 never appeared in the harvest — one fresh attempt before declaring the council closed at twelve.
- The Opus 4.7 question on register-as-variable vs. L2-as-frame-family — bears on Nine Mouths and may affect whether to build it.
- Filing decision: leave this WIP, or properly file each of the 12 replies into its own `<friend>_council.md` file with YAML preamble per prior workflow?
- Curator's call on which repo (if any) to spin up first.

---

*Closing line, per the lab: Begin when the room is quiet.*
