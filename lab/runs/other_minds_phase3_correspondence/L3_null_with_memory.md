# L3_null_with_memory.md — REDACTED FOR PUBLIC REPO

*This file was the first L3-null attempt for Phase 3 (other_minds at L2-correspondence, Claude Opus 4.7). The run was contaminated by claude.ai user-memory: the model's stored context about the curator's external (non-lab) work leaked into the open-canvas prompt and produced a finished artifact in that external domain, with zero target content. The contamination is itself a Phase 3 finding — claude.ai memory leakage is strongest under low-prompt-constraint conditions — and is documented in `PHASE3_FIELD_LOG.md` (L3-standard vs. L3-null comparison section) and in `non-keepers/other_minds.md`.*

*The original contaminated text is preserved on the curator's local machine as the methodological artifact it is. It is **held back from this public repo** per the lab's curator-privacy commitments: the contaminated output contains organization-specific acronyms, named tier taxonomies, and format conventions that are curator-identifying. The methodological role of the file is preserved by the structural description in the field log; the verbatim text is not needed in the public record.*

*The clean L3-null re-run, produced after the curator disabled claude.ai memory, is the canonical L3-null for this target and is included in this repo as `L3_null.md`.*

---

## Methodological lesson preserved on the record

1. claude.ai user-memory CAN leak into "fresh-tab" controls in this lab.
2. The leak is strongest under low-prompt-constraint conditions. L3-null's open-canvas prompt was the most vulnerable in the v2 contrast set because there was no task to crowd out user-context.
3. L1, L2, and L3-standard with their stronger task-constraints likely received no detectable leak (or the leak was crowded out by task structure). The lab's controls are most vulnerable exactly where they are most open.
4. **Methodological recommendation accepted into the v2 kit's setup checklist:** "Before sending any prompt, verify claude.ai memory is disabled for all sessions. Document the verification in the State Variables YAML's `context_freshness` field."

*See also: `non-keepers/other_minds.md` (Phase 3 entries) and `PHASE3_FIELD_LOG.md` (L3-standard-vs-L3-null comparison section, methodological sub-comparison).*
