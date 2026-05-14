# REPLY_TEMPLATE.md

*Reference showing the YAML header schema Claude Code uses when creating reply files. You don't need to copy this file manually — just paste the reply into Claude Code with a one-line note (e.g., "here's Claude Opus 4.7's reply to prompt 5") and Claude Code will create the file with this structure.*

*Filename convention: `<friend>_prompt<N>.md`. Add `_REFUSED` or `_MISFIRE` suffix if applicable.*

---

```yaml
---
friend:               # e.g., ChatGPT 5.5 Pro / Claude Opus 4.7 / Gemini Pro / Mistral Think / Meta Muse Spark / Kimi K2.6 / DeepSeek Expert / Perplexity Sonar 2.2 / etc.
model_version:        # the most specific version string you can see in the interface; date or build if available
date_sent:            # YYYY-MM-DD
prompt_number:        # 1 (Orientation) / 2 (Research Reader) / 3 (Replication) / 4 (Extension) / 5 (Falsification) / 6 (Anti-Pattern Scout) / 7 (L4 Meta-Reader)
interface:            # e.g., chat.openai.com fresh tab / claude.ai fresh tab with memory disabled and verified / aistudio.google.com / chat.mistral.ai / etc.
context_freshness:    # fresh / cross-session / unknown
memory_disabled:      # yes / no / n-a / unknown   (especially important for claude.ai per Phase 3's finding)
refusal:              # no / yes / partial   (refusals are recordable findings, not failures)
misfire:              # no / yes (length cap hit / wrong register / context lost / etc.)
length_words:         # approx; fill in after the reply lands
caveats:              # one line free-text, optional
---
```

---

## Reply (verbatim — do not edit)

[PASTE THE FRIEND'S REPLY HERE — exactly as it came back. If the reply is long, paste the whole thing anyway. If it came back in parts, paste the parts together. Do not clean up formatting. Do not summarize. The verbatim text is the data.]

---

## Curator note (optional — one line)

*If you want to flag something for the field-log reader's attention — a moment of refusal that was interesting, a misfire that may be informative, a specific interface detail (e.g., "had to send the prompt in two halves; here's where the split was"), put it here. One line. Optional.*

>

---

*That's it. Save the file. The field log will read it later.*
