# UniCORE.Signal

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 14:50 UTC.**

---

## What this repository is

`bryanunitek/UniCORE.Signal` is the **Signal** family member: On-prem-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source secure messaging server. End-to-end encrypted messaging with on-premise deployment capability for law-firm-grade secure communications.

**Role in UniCORE:** Secure messaging substrate — UniCORE.GVB substrate-services explore on-premise Signal-Server deployments for enterprise-grade secure communications where data sovereignty requires messages to never leave customer-controlled infrastructure.

---

## Upstream

- **Upstream project:** [https://github.com/signalapp/Signal-Server](https://github.com/signalapp/Signal-Server)
- **Upstream licence:** AGPL-3.0
- **Our relationship:** Fork-and-extend. Upstream codebase is consumed verbatim under its original licence; our code additions carry the same AGPL-3.0 (strong copyleft requirement); our documentation additions sit under CC BY 4.0.

**Copyleft note:** AGPL-3.0 requires that any modified version of the server, when offered as a network service, must make the complete source code available to users of that service. This is a stronger requirement than GPL-2.0 and shapes how UniCORE deploys Signal-Server modifications.

The merge discipline that governs how this repository absorbs upstream changes is documented in [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md).

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

UniCORE.Signal is published as a **four-repo family**:

- `bryanunitek/UniCORE.Signal` — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Signal` — public SaaS-deployment-shape gift surface
- `bryanunitek/UniCORE.Signal-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Signal-Claw` (private) — SaaS-shape working repository

**This repository is the `UniCORE.Signal` member of the family.**

Sister repos:

- [`UniSaaS.UniCORE.Signal`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.Signal) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.Signal))
- `UniCORE.Signal-Claw (private)`
- `UniSaaS.UniCORE.Signal-Claw (private)`

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04 14:50 UTC. See [`STATUS.md`](STATUS.md) for the full status breakdown.

---

## Files in this scaffold commit

- [`README.md`](README.md) — this file
- [`LICENSE.md`](LICENSE.md) — UniCORE additions licence (AGPL-3.0 code + CC BY 4.0 docs)
- [`LICENSE.upstream.md`](LICENSE.upstream.md) — verbatim upstream AGPL-3.0 licence
- [`README.upstream.md`](README.upstream.md) — verbatim upstream README (renamed)
- [`STATUS.md`](STATUS.md) — scaffold-anchor status
- [`UPSTREAM-MERGE-DISCIPLINE.md`](UPSTREAM-MERGE-DISCIPLINE.md) — canonical merge discipline
- [`AI-AUTHORSHIP.md`](AI-AUTHORSHIP.md) — AI authorship disclosure

---

## Related repositories — UniCORE programme

**Foundation triad (gift, public, CC BY 4.0):**
- [`UniVERSE`](https://git.unitek-systems.com/UniCORE/UniVERSE) (mirror: [GitHub](https://github.com/bryanunitek/UniVERSE)) — programme
- [`TrueAI`](https://git.unitek-systems.com/UniCORE/TrueAI) (mirror: [GitHub](https://github.com/bryanunitek/TrueAI)) — Foundation (Nine Invariants)
- [`UniCORE-AI`](https://git.unitek-systems.com/UniCORE/UniCORE-AI) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE-AI)) — reference architecture (12 Levels)

**Implementation reference (deployment-shape pair):**
- [`UniCORE`](https://git.unitek-systems.com/UniCORE/UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE)) — on-prem-shape
- [`UniSaaS.UniCORE`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE)) — SaaS-shape

**Substrate-services layer (deployment-shape pair):**
- [`UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.GVB)) — on-prem-shape
- [`UniSaaS.UniCORE.GVB`](https://git.unitek-systems.com/UniCORE/UniSaaS.UniCORE.GVB) (mirror: [GitHub](https://github.com/bryanunitek/UniSaaS.UniCORE.GVB)) — SaaS-shape

**Forked-upstream building blocks:**
- UniCORE.Avalonia family (4 repos) — cross-platform UI
- UniCORE.DNN family (4 repos) — CMS platform
- UniCORE.Asterisk family (4 repos) — telephony
- UniCORE.Jitsi family (4 repos) — video conferencing
- UniCORE.Signal family (4 repos) — secure messaging ← **this family**
- UniCORE.XCP family (4 repos) — virtualisation

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniCORE.Signal/discussions) (public repos only)
- **Private contact / connection request:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
