<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=EvidentLoop&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Infrastructure%20for%20trustworthy%20AI%20coding%20workflows&descSize=15&descAlignY=62" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=680&height=40&lines=produce+%E2%86%92+verify+%E2%86%92+accumulate+%E2%86%92+produce;Loops+compose.+Wires+connect.+Surfaces+remember." alt="Typing SVG" />
</p>

---

## The Problem

AI coding assistants are effective producers. But they're not reliable self-verifiers.

A shared session accumulates local assumptions, abandoned approaches, and retry artifacts — each reinforcing "the previous call was right." When review reuses that context, it inherits the author's framing instead of independently re-deriving correctness.

**You can verify every diff and still miss the bigger picture.**

## Philosophy

Every meaningful AI coding task is a closed loop:

```mermaid
graph LR
    produce --> verify
    verify --> accumulate
    accumulate --> produce
```

- **Loop-first** — No step is done until independently verified
- **Wire-composable** — Loops connect through machine contracts, not chat history
- **Surface-shared** — Knowledge persists across sessions, models, and hosts

CrossReview implements **verify**. Sopify implements **wire** and **surface**.

## Two Products, One Loop

| Loop Role | What It Does | Project |
|-----------|-------------|---------|
| **verify** | Context-isolated cross-review — same model, clean session, independent second pass | [CrossReview](https://github.com/evidentloop/cross-review) |
| **wire + surface** | Full workflow orchestration — checkpoints, blueprints, traceable decision chains | [Sopify](https://github.com/evidentloop/Sopify) |

**[CrossReview](https://github.com/evidentloop/cross-review)** — Verification primitive for AI coding. Same model, clean session, independent second pass on your output. Atomic and composable — runs standalone or as a verification step inside broader workflows.

**[Sopify](https://github.com/evidentloop/Sopify)** — AI coding workflow orchestration layer. Manages state, plans, and decisions across the full lifecycle — checkpoints when facts are missing, resumes from state, not from scratch. CrossReview is designed to slot in as its verification step.

---

CrossReview is the **verify** — atomic, isolated, independent.  
Sopify is the **wire + surface** — connecting loops, accumulating knowledge.  
Together, they close the loop.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%" />
</p>
