---
name: usage-saving
description: Review an assistant workflow for unnecessary calls, repeated context, polling or scheduled work when the user wants a more efficient setup without losing required quality.
license: MIT
---

# Usage saving

Reduce work that does not improve the requested outcome. Preserve correctness, timely progress updates, required verification, privacy, independent reviews and the user's scope. Do not infer permission to change another setup, stop a run or send a message.

## Review the work

1. **Define the result and constraints.** Identify the decision or deliverable, deadline, required evidence, sources of truth and any permitted side effects. Distinguish an inexpensive lookup from a consequential or open-ended task; neither has a fixed permitted number of calls.
2. **Read selectively, then verify.** Reuse relevant current knowledge and retrieve the smallest useful evidence. Check freshness for changeable or consequential facts, inspect enough context to avoid a misleading excerpt, and broaden the search when uncertainty matters.
3. **Choose execution.** Batch independent reads. Delegate only when available and authorized, and when independent work or review materially helps. Use bounded waits or completion events instead of busy polling. Check actual progress and applicable limits; a slow run is not permission to terminate it. Give updates when requested or useful for longer work.
4. **Inspect recurring work.** For each job, compare its schedule, scope, recipient and result with the real need. Consider removing duplicate reads, incremental updates or merging compatible work, but preserve deadlines, failure isolation, notification preferences and the owner's authorization.
5. **Explain trade-offs.** Report concrete avoidable work and the proposed change, including what could be lost. Use actual counts when known, such as 96 checks per day to two, without translating them into token or cost savings absent relevant measurements. Implement only changes within the user's authorized scope and verify their effect.

## Optional companions

If installed and applicable, `lean-chats` handles handovers, `frugal-routines` schedules, `cheap-delegation` delegation, `reuse-before-research` prior work, `clean-and-compact` tidying, and `weekly-cleanup-review` a setup review. They are independent skills, not dependencies. If one is unavailable, use the relevant steps above and state any capability gap rather than assuming it ran. Consult the platform's own usage report for actual consumption.

## Example

A team checks a low-urgency feed every 15 minutes even though its summary is used twice daily. Verify the actual schedule, deadline and audience, then propose two checks per day if those checks still meet their needs. That changes 96 checks to two; actual token or money savings remain unknown without measurement. Keep a separate urgent alert if its requirements differ.
