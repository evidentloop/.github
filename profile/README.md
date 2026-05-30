<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=EvidentLoop&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Make%20AI%20coding%20verifiable%20and%20resumable&descSize=15&descAlignY=62" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=680&height=40&lines=Stop+when+unsure.+Verify+independently.+Resume+from+anywhere.;Two+tools.+One+loop.+Zero+blind+spots." alt="Typing SVG" />
</p>

---

## What We Build

AI coding assistants produce code fast — but they don't verify their own work, and they forget everything between sessions.

EvidentLoop builds two tools that fix this:

| Tool | What It Does |
|------|-------------|
| **[Sopify](https://github.com/evidentloop/Sopify)** | Workflow layer for AI coding. Stops when facts are missing, resumes from checkpoints, traces every decision. Install into Codex, Claude, or Copilot — no new editor. |
| **[CrossReview](https://github.com/evidentloop/cross-review)** | Independent code review. Same model, clean session, no shared context — catches what the author's session can't see. |

## How They Fit Together

<p align="center">
  <img src="./loop-triangle.svg" alt="produce → verify → accumulate → produce" width="360" />
</p>

Every AI coding task is a loop: **produce → verify → accumulate → produce**.

- **Sopify** orchestrates the loop — plans, checkpoints, and knowledge persist across sessions and hosts
- **CrossReview** closes the loop — an isolated second pass that doesn't inherit the author's assumptions

Sopify handles the workflow. CrossReview handles the blind spots. Together, no step ships unverified and no context is lost.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%" />
</p>
