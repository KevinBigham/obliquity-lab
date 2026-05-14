# AI Friend Round — 2026-05-14

*Scaffolded by Claude Code on 2026-05-14 at curator request. This folder is where replies from the AI friend research prompts land.*

---

## Status as of end-of-day 2026-05-14

**Round paused at:** two prompts sent, 24 reply files on disk, no field log yet written.

| Friend | Prompt 1 (Orientation) | Prompt 2 (Research Reader) |
|---|---|---|
| ChatGPT 5.5 Pro | filed | filed |
| ChatGPT 5.5 Thinking | filed | filed |
| ChatGPT 5.5 Pro Deep Research | filed | filed |
| Claude Opus 4.7 | filed | filed |
| Claude Opus 4.7 Research | filed | filed |
| Gemini Pro | filed | filed |
| Gemini Pro Deep Research | **MISFIRE** (tag-table corruption) | **REFUSED** (3 retries, generic decline) |
| Meta Muse Spark Contemplating Mode | filed | filed |
| DeepSeek Expert | filed (structural deviation noted) | filed (structural deviation noted) |
| Mistral AI Think | filed | filed (structural deviation noted) |
| Perplexity Sonar 2.2 | filed (thin engagement caveat) | **MISFIRE** (announced intent, never produced structure) |
| Kimi K2.6 | filed | filed (`refusal: yes` — structurally compliant refusal-as-finding) |

**Persistent failure modes worth flagging to the field-log session:**
- **Perplexity Sonar 2.2** hit the same thin-engagement failure across both prompts. Round 1: ~580 words, didn't engage the analytic disciplines substantively. Round 2: ~200 words, announced intent to construct a note "based on the prompt itself" and stopped. Reproducible failure mode, not random.
- **Gemini Pro Deep Research** failed differently each round. Round 1: produced ~3500-word reply with tag-table corruption (`Tag****` artifacts), 12 displacement claims instead of 1–2, `citeturn` markers. Round 2: three retries, each returned "Sorry, I can't help you with that at this time." Same friend, different failure modes — worth noting as a property of the apparatus, not just an episode.
- **Kimi K2.6** evolved its handling of repo-inaccessibility across the rounds. Round 1: produced A/B/C content marked `[OPEN]`. Round 2: structurally compliant refusal-as-finding, A/B/C/D declined on access grounds with reasons. Faithful to commitment #5 ("Preserve the null") on round 2.

**One sharp single observation worth keeper-level attention on first field-log pass:**
- **Claude Opus 4.7 Research** (prompt 2) surfaced `HANDOFF_TO_NEXT_CLAUDE_CODE.md`'s "The curator was asleep when these were made" as a publication-layer recursion-as-theatre risk that the lab's own anti-pattern catalog does not yet name explicitly. Ranked #1 in their three risks. Locked closing line cites that same sentence as "the single most load-bearing sentence in the repo, for a blank-slate reader." Whether to absorb this into the anti-pattern catalog is a curator decision; flagging here so the field log surfaces it specifically.

**Cross-friend convergence worth flagging:**
- Three or four friends independently arrived at variants of "matched non-fiction control" or "genre-stripped control" as the next discipline: ChatGPT 5.5 Pro Deep Research (most explicit — "matched function-without-fiction control"); Gemini Pro ("Blind Target Substitution"); DeepSeek ("pre-registered blind content coding"); arguably Mistral via curator-rotation. The convergence is data — patterns are data, not testimony, and four-friend convergence on a recommendation is a pattern. The deflationary alternative: all four are pattern-matching on the lab's own deflationary vocabulary ("genre affordance" appears in commitment #3), and recommending the obvious next step is what the prompt invites. A future discriminating run would be giving the same prompt to a friend who has not read commitment #3 verbatim and seeing whether the same recommendation surfaces.

**Curator pacing note:** 12 friends × 2 prompts = 24 replies filed in one day, which is double the "first wave of three or four friends" recommended below. Recorded as the lab's anti-pattern catalog calls it: completionist drift, live. Not a misfire — the curator's call — but the field-log session should read against this. The discipline doesn't change because the curator was generous; the discipline holds the apparatus, not the apparatus's intensity.

**What the next Claude Code session should do** (carries forward the curator-paused-here state):

1. Read each reply file on its own merits against the lab's general disciplines (tagged claims, deflationary pairs, null findings, closing-citation rule). No Run Card to test against — it was suspended for this round (see third appendix in `HANDOFF_TO_NEXT_CLAUDE_CODE.md`).
2. Write `ROUND_FIELD_LOG.md` into this folder. Note convergences and divergences across friends; mark keepers and non-keepers; honor closing specificity; flag the failure modes and the Claude Opus 4.7 Research observation above.
3. Apply the deflationary discipline to any convergence finding. Three or four friends agreeing on a recommendation is a pattern — patterns are data, not testimony.
4. Do NOT pre-empt a curator decision on whether to add publication-layer voice-leak to the anti-pattern catalog. Flag it; the call is the curator's.
5. Do NOT synthesize across the 2026-05-14 round and any prior or later round. Synthesis is its own fresh-session work per the lab's standing posture.

---

## What this folder is

A single round of the lab's `lab/AI_FRIEND_RESEARCH_PROMPTS.md` packet — one or more AI friends, one or more prompts each, replies saved here verbatim. Refusals and misfires get saved too; the lab's discipline is "save the unusable run anyway."

When the round is complete (or paused), a future Claude Code session reads the replies and writes a `ROUND_FIELD_LOG.md` into this same folder.

---

## How to use this folder — one step

**When a reply comes back, paste it into Claude Code with a one-line note like:**

> *"here's ChatGPT 5.5 Pro's reply to prompt 2"*
>
> *(then paste the reply verbatim below)*

That's it. Claude Code will:

- Create the file in this folder with the right filename
- Fill in the YAML header from what you said plus what's inferable
- Save the reply verbatim
- Ask you once for anything it can't infer (e.g., memory state, interface)

If the reply was a refusal or a misfire, just say so in your one-line note — *"ChatGPT 5.5 Pro refused prompt 2"* or *"Kimi K2.6 misfired on prompt 1 — hit length cap."* The misfire IS data; it gets saved too.

You don't need to copy any template file or fill in any YAML by hand. Claude Code does that.

---

## When you're done (or want to pause)

Drop a line in chat to Claude Code: *"the ai friend round folder is ready, take a look when you're ready."*

A fresh Claude Code session will:

1. Read each reply with the lab's rubric in mind (tagged claims, deflationary pairs, null findings, closing-citation rule).
2. Write a `ROUND_FIELD_LOG.md` into this folder — convergences, divergences, keepers, misfires worth flagging, closing-citation rule honored.

Synthesis across rounds (if there is a next round, or if this one connects to Phase 4 / Phase 5 / Phase 6 of the broader lab) is its own fresh-session work, per the lab's standing posture. The field log is one round's reading; synthesis waits.

---

## A small note on pacing

The lab is small on purpose. Twelve replies in twelve different friends in one sitting is completionist drift dressed as efficiency. A first wave of three or four friends is plenty. Look at what comes back, decide whether the round expands, then decide.

You can also leave the round paused indefinitely — no replies, no field log. That's also a recordable outcome.

---

## Files currently in this folder

- `README.md` — this file.
- `REPLY_TEMPLATE.md` — reference showing the YAML header schema Claude Code uses when creating reply files. You don't need to copy this; Claude Code creates each reply file when you paste.

Files that get created as the round runs:

- `<friend>_prompt<N>.md` — one per reply (Claude Code creates these when you paste).
- `ROUND_FIELD_LOG.md` — created by Claude Code at end of round.

---

*Begin when the room is quiet.*
