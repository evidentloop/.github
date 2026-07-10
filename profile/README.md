# EvidentLoop

**Infrastructure for resumable, auditable AI coding.**

AI coding moves fast. EvidentLoop keeps the work resumable and the evidence inspectable.

| Project | What It Does |
|---------|--------------|
| **[Sopify](https://github.com/evidentloop/sopify)** | Resumable workflow protocol for AI coding. Keeps requirements, plans, checkpoints, decisions, and verification evidence with the repo across sessions and hosts. |
| **[change-audit](https://github.com/evidentloop/change-audit)** | Traceable review for AI-generated changes. Anchors findings to the real diff and publishes validated `audit.json` and self-contained `audit.html` reports. |

## The Evident Loop

<p align="center">
  <img src="./loop-triangle.svg" alt="produce → verify → accumulate → produce" width="360" />
</p>

AI hosts produce. **change-audit** turns review into traceable evidence. **Sopify** preserves workflow context so work can resume across sessions and hosts.

Together, they cover two complementary problems: continuity while work is happening, and evidence after a change.
