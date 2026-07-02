# Crystal Instruction — Teacher Dashboard Redesign (Prototype)

A clickable prototype of a redesigned teacher Home dashboard for Crystal Instruction.

## 👉 Open the live prototype
**https://raw.githack.com/kennadyscott/crystal-instruction-dashboard/main/index.html**

Click through it — the next-step buttons, subject tabs, "More options," Attach to T-TESS, quick notes, and Launch ClassCade are all interactive.

## The idea
Turn Home from a rear-view mirror (usage stats + product news) into a **next-action cockpit**: for each subject, show the biggest gap and *one clear next step* to close it.

- **Subject tabs** — one subject at a time; the dot shows red (gap) / amber (stuck) / green (on track).
- **Action-forward cards** — lesson + plain diagnosis, a compact data strip (mastery donut, checkpoint → exit ticket read), then a labeled **Recommended next step** with alternatives under "More options."
- **Right rail (support)** — a motivational note, quick notes, **Practice in flight** (ClearSheets completion + accuracy), and **Attach today's response to T-TESS** + **ClearK12 PD** links.
- **Launch ClassCade** — top-right quick-launch, opens in a new tab.

## What's real vs. stubbed
- **Real logic:** the recommended next step flexes by the data — move on (≥85% mastery), small group (a subset missed it), whole-class reteach (most of the class), or switch approach (stuck: retaught with no gain).
- **Stubbed / needs building:** auto-tagging a low score to a specific skill and matching it to one Snap Lesson / ClearSheet / ClassCade round; the T-TESS evidence integration; live ClearSheets data wiring. All demo data is fake (no student PII).

## 💬 Leaving feedback
Please use the **[Issues tab](../../issues)** — one issue per piece of feedback is easiest to track. Or drop notes wherever the team prefers.
