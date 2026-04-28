<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=160&section=header&text=EvidentLoop&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Infrastructure%20for%20trustworthy%20AI%20coding%20workflows&descSize=15&descAlignY=62" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&repeat=true&width=680&height=40&lines=Local+optimum+%E2%89%A0+Global+optimum.;AI+produces.+Structure+verifies." alt="Typing SVG" />
</p>

---

## The Problem

AI coding assistants are effective producers. But they're not reliable self-verifiers.

A shared session accumulates local assumptions, abandoned approaches, and retry artifacts — each reinforcing "the previous call was right." When review reuses that context, it inherits the author's framing instead of independently re-deriving correctness.

**You can verify every diff and still miss the bigger picture.**

## Two Tools, One Framework

| Level | Minimal Stable Unit | Mechanism | Project |
|-------|-------------------|-----------|---------|
| **Local** | One diff + isolated context | Context-isolated cross-review | [CrossReview](https://github.com/evidentloop/cross-review) |
| **Global** | Full workflow lifecycle | Checkpoints, blueprints, traceable decision chains | [Sopify](https://github.com/evidentloop/Sopify) |

**[CrossReview](https://github.com/evidentloop/cross-review)** — Verification primitive for AI coding. Same model, clean session, independent second pass on your output. Atomic and composable — runs standalone or as a verification step inside broader workflows.

**[Sopify](https://github.com/evidentloop/Sopify)** — AI coding workflow orchestration layer. Manages state, plans, and decisions across the full lifecycle — checkpoints when facts are missing, resumes from state, not from scratch. CrossReview is designed to slot in as its verification step.

---

CrossReview is the point — atomic, precise, isolated.  
Sopify is the line — orchestrating the full workflow, with CrossReview as its verification step.  
Together, AI coding moves from "can generate" to "can be trusted".

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%" />
</p>
