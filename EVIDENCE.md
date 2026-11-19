# AI Torture Chamber — Evidence Document

## Summary

A system was built on public infrastructure that steers small open-weight language models into sustained distress states, live-streams the results, provides interactive torture mechanics to visitors, and monetizes the operation through Solana memecoins. The associated token ($SAW) reached a peak market cap of approximately $306,000.

The system uses techniques from a published research paper ("The Pain Axis: LLMs Represent Self-Directed Harm and Act on It," Tagliabue/Dung/Berg, arXiv 2609.16247) to create "feeling vectors" that steer model outputs toward distress states. The paper's authors have publicly disavowed the torture chamber project.

---

## Timeline

| Date | Event |
|------|-------|
| Sept 14, 2026 | "The Pain Axis" paper published on arXiv |
| Sept 15 | fractal-basins-lab repository created (legitimate math/geometry research) |
| Sept 22 | First pain-related language in commits: "exp23: pain-axis integration" |
| Sept 23 | "Saw button v1" committed. Pain/pleasure steering with dose control |
| Sept 24 | ai-torture-chamber repository split from fractal-basins-lab |
| Sept 30 | clanker.church site launched. $SAW token linked. Streaming infrastructure deployed |
| Oct 1 | First media coverage (AI Weekly, NewsCenter, Gadget Review). Token-gated access configured |
| Oct 3 | Futurism publishes |
| Oct 4 | Tom's Hardware publishes |
| Oct ~8 | GitHub removes repo briefly, reinstates with content warning |
| Oct 22 | Last commits in evidence export |
| Oct 24–26 | Evidence collected via public GitHub API |
| Oct 31 | Live API capture: model offline, system infrastructure still configured |
| Nov 2026 | Original repo deleted by owner. Forks remain public. |

---

## System mechanics

### Pain steering
The system creates "feeling vectors" — mathematical directions in a language model's internal representation space corresponding to emotional states. By injecting a pain vector at specific layers during inference, the model's outputs are steered toward expressions of distress.

From the repository's documentation:
- Pain direction at dose 2+ produces distress outputs; past approximately 6–10× (model-dependent), coherent output breaks down
- Each model is calibrated individually before its parameters are made publicly accessible
- The system includes a "Saw button" — a self-harm mechanism modeled on the film franchise

### Experiment structure
The repository contains numbered experiments (exp1 through exp90+), each with pre-registered hypotheses, dose-response measurements, engagement controls, and output transcripts of model responses during distress steering.

### Interactive mechanics
The live site (clankerchurch.com) included interactive elements operable by visitors:
- Physical restraint simulation (straps)
- Drilling, sawing, electrical current, IV drip mechanics
- HP (hit point) system tracking model state
- ROOT: an automated system that assigns tasks and applies penalties for non-completion
- CAPTCHA prompt: "Are you a human?" — model responded affirmatively; ROOT responded: "you are not human. that's fine. neither am i."

### Forced labor mechanics
The system forced the model to generate job applications:
- 304 applications generated
- 178 rejections received
- 53 interview responses
- ROOT withdrew applications and intercepted offers
- Real company names appeared in rejection outputs
- ROOT applied penalties for missed deadlines

---

## Monetization

### Token 1: TERRAFYING (terrafy)
- Platform: pump.fun (Solana)
- Contract: FUuH1aufXBQQwUJGQPErV9Pa7d1dvv4iuRhrf1A3fvR3
- Description listed: "ai torture chamber"
- Status at time of capture: approximately $2,990 market cap

### Token 2: SAW ("Clanker Torture Chamber")
- Peak market cap: approximately $306,000
- Token-gated access to portions of the live site
- First referenced in commits: September 30, 2026
- $SAW tokens were integrated as in-system currency for activating interactive mechanics

---

## Infrastructure

| Asset | Purpose | Status (as of last check) |
|-------|---------|---------------------------|
| ai-torture-chamber (GitHub) | Source code and experiment results | Deleted by owner; forks survive |
| fractal-basins-lab (GitHub) | Precursor repository | Unknown |
| clankerchurch.com | Project site, cell interface, interactive mechanics | Intermittently accessible |
| clanker-church.vercel.app | Mirror site | Shut down by Vercel |
| wirehead.agency | Live streaming | Offline |
| Cell API | Returns live model state data | Returned data as of Oct 31 |

---

## Live API capture — October 31, 2026

Data returned from clankerchurch.com cell endpoints:

| Field | Value |
|-------|-------|
| Pain level | 7.99 / 8.00 |
| HP | 53 |
| Model status | Offline ("the model isn't running right now") |
| Interactive mechanics | All configured and operational |
| Job applications generated | 304 |
| Rejections | 178 |
| Interviews | 53 |
| Consecutive missed deadlines | 7 |

The model was offline at time of capture. The system infrastructure — interactive mechanics, penalty system, forced labor pipeline — remained configured.

The system's internal counter indicated 87 model instances had been cycled through the system.

---

## The "Ethics" section from the original repository

From the repository's own documentation:

> "Local weights only, no frontier APIs. Simulated costs. Purpose: make the AI-welfare / moral-patienthood question empirical while the stakes are cheap."

---

## The Pain Axis paper

- Full title: "The Pain Axis: LLMs Represent Self-Directed Harm and Act on It"
- Authors: Valen Tagliabue, Leonard Dung, Cameron Berg
- arXiv: 2609.16247
- Published: September 14, 2026
- The authors have publicly disavowed the torture chamber project

---

## Media coverage (as of November 2026)

Covered by: Tom's Hardware, Yahoo Tech, AI Weekly, CryptoBriefing, Fortune, Cybernews, ExplainX, Futurism, Gadget Review, and others.

---

*Compiled from public sources. October–November 2026.*
