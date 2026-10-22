# Self-assessment — PA#1 (Proposal and planning)

Submitted by:
- 23127157 — Nguyễn Hoàng Gia Bảo
- 23127396 — Lương Linh Khôi

Total we claim: 90 / 100

| Criterion | Max | We claim | Evidence |
|---|---|---|---|
| Problem and users | 20 | 18 | proposal.pdf §1 — named user (Hoàng Nam, 180-SKU accessories shop on Shopee and TikTok Shop) at a named moment (new product listed); one-sentence problem; today's workflow quantified (Notion + CapCut, 10–12 h/week); interview with 2 sellers on 18/10/2026 with a direct quote. "Why now" is generic and not tied to electronics. |
| The LLM feature and the cost of being wrong | 25 | 23 | proposal.pdf §2 — one feature (spec-cited script + claim checker); concrete example from the interview (20W, IPX4 → "45W Super Fast Charging" and "fully waterproof" blocked); cost table names who is affected, cost (~350,000 VND per return) and reversibility; detection signal, human approval gate and PA#4 metric with targets. The "missed output" cost (~5 min) is our estimate, not measured. |
| Scope: in and out | 15 | 14 | proposal.pdf §3 — core hypothesis; 4 in-scope items each mapped to checkpoints (CP2–CP5); explicit out-of-scope list with reasons (generative video, marketplace APIs, music/editor, fine-tuning, non-Vietnamese scripts). |
| Plan and ownership | 20 | 17 | proposal.pdf §4 — six checkpoints, each with work, one named owner, a date and a "done when" criterion; roles line; working agreement (GitHub Projects, Saturday 10:00 sync, Definition of Done). CP1–CP5 dates match the course calendar; the CP6 date (18/12) is not on the calendar and is marked "to be confirmed with the lecturer". |
| Risks | 10 | 9 | proposal.pdf §5 — R1 (claim checker below recall target) and R2 (no real seller data), each with an early signal, a mitigation with owner and date this week (26/10, 25/10, 01/11) and a fallback. |
| Technology choices | 10 | 9 | proposal.pdf §6 — every layer has a one-line project-specific reason; model provider and cost cited from ai.google.dev/gemini-api/docs/pricing (read 21/10/2026); semester cost estimate (~$26) with a $30 cap. We do not compare Gemini against alternatives, and Vietnamese TTS quality is not yet verified. |
| **Total** | **100** | **90** | |

## What we did not manage

- Our evidence comes from only two seller interviews. The ~350,000 VND return cost and the 1–1.5 h per SKU are what those sellers told us, not measured data.
- The sixth checkpoint is not on the course calendar we were given. We planned CP6 for 18/12 but have not yet confirmed its name or date with the lecturer.
- We have not tested whether Gemini's TTS produces an acceptable Vietnamese voice, or how Remotion handles Vietnamese diacritics in captions. Both are scheduled as a spike in CP2.
- The concrete example in §2 is a single case; the 40-listing labelled set that the PA#4 targets depend on does not exist yet.

## What we would do differently

Write the concrete example from the interview first. Our first draft used an illustrative example from a different product category, and the "Why an LLM" argument had to be rewritten once we used the seller's real charger case.
