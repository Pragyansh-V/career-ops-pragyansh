# Mode: weekly-review — Friday Pulse Check

Keep the entire output under 200 words.

## Steps

1. **Pipeline summary** — Read `data/applications.md`. Count by status:
   - Evaluated / Applied / Interview / Offer / SKIP / Discarded
   - One line: "X evaluated, Y applied, Z in progress this week."

2. **Top gaps** — Read `data/gap-tracker.md`. Surface the 3 most
   frequently appearing missing skills across all entries so far.
   One bullet per gap, no explanation needed.

3. **Profile readiness gate** — Check hard blockers from CLAUDE.md.
   List any still unresolved as ⚠️ items. If all clear, say "✅ No blockers."

4. **Next week actions** — Suggest exactly 3 specific actions based on
   gaps and blockers. Concrete and actionable, not generic advice.
   Format: "[ ] Action"

5. **Deadline flags** — Scan `data/applications.md` notes and
   `data/pipeline.md` for any APPLY NOW items. If none, say "No urgent deadlines."

## Output format

```
## Weekly Review — [date]

**Pipeline:** ...
**Gaps:** ...
**Profile:** ...
**Next week:**
[ ] ...
[ ] ...
[ ] ...
**Deadlines:** ...
```
