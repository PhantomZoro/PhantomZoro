# Phaneendra Bheesetti

**Senior Software Engineer · 6+ years · Bangalore, India**

I solo-architect enterprise platforms that move real money and real throughput — then I go build my own products from scratch. Six years in, that's the pattern: own the system end-to-end, ship it, watch it outlive me, repeat. Currently a Senior Software Engineer contracted to Airbus, and solo-founding [KodeRyu](https://koderyu.com). IIT Madras alum. I care as much about the trade-off behind a decision as the code that implements it.

- Open to **Senior / Full-Stack Software Engineer** roles (Bangalore or remote)
- TypeScript-first — React · Node · Next.js · Postgres — with Python where it fits

---

## Track record in numbers

| System | Scale | Impact |
| --- | --- | --- |
| **ABAcS** — budgeting platform, *sole architect* | €500M+/yr governed · €1.5B+ cumulative · 1,500 users · 5 countries | **70% faster** allocation cycles · audit prep **days → hours** · work conventionally staffed by a 3–5 engineer team, delivered solo |
| **ECM** — document publishing desktop app | 2,000+ classified docs published to date | **2–3 hrs → 10–15 min** per doc (≈90%) · **≈4,700 specialist hours eliminated** · one publisher does a manual team's work |
| **MPO** — maintenance-program optimization (Skywise/Palantir Foundry) | 8,000+ operator accounts · a multi-million-euro annual cost-avoidance & service-revenue business case | Owned the digitally-signed PDF dossier — **the revenue-carrying deliverable** operators receive · incident focal, **15+ critical defects** resolved |
| **Quality Tracker** — supply-chain quality | 500+ users · 5 countries · solo build in 2 months | Approval cycle **1–2 days → 2–3 hrs** (≈85–92%) · zero bug-induced downtime · handed to a team that extended it |
| **CCT** — composite compatibility | Aircraft manufacturing · 2-engineer build | Composite-material testing cycle **cut 80%** |
| **MyMetrics** — PnL/risk platform (Société Générale) | 60K-line codebase · global bank's Finance Risk division | SonarQube **D → A+ in 10 months**, single-handed · 5 new risk-dashboard APIs |

*Airbus work is under Alten contracts in internal repositories — described here, not linked. Exact internal business-case figures stay private; the public numbers above are sanitized.*

---

## Now building — [KodeRyu](https://koderyu.com)

An AI voice interview-prep platform (voice, DSA, and system-design practice). Feature-complete, production deployment in progress. Solo-built end to end — this is the scalability-engineering proof that I still ship hard systems now, not just years ago:

- **Sandboxed code executor** — Docker + nsjail + a BullMQ worker pool running untrusted code with **sub-second cold starts across 5 languages** (Python, JavaScript, Java, C++, Go).
- **4,000+ automated tests** — API, web, and Playwright E2E, shipped through an AI-native workflow of 14 specialist agents and 15 automation hooks.
- **LLM-as-judge eval pipeline** — weighted kappa **κ=0.92** against a human-labeled truth set across a 13-criterion rubric, validated by a 12-persona candidate simulator.
- **Real-time voice engine** — Deepgram STT + Kokoro TTS + a streaming LLM driven by a phase-based finite state machine, with rupture detection and an adaptive multi-level hint ladder.
- **Production infra** — Clerk auth, Razorpay tier-gated payments, an OWASP security audit, and PostHog + Sentry + GA4 telemetry.

> KodeRyu's source is private during beta — the live app is at [koderyu.com](https://koderyu.com). A public case study lands here at launch.

---

## How I work

Solo, end-to-end — from the first architecture sketch to the on-call rotation. The systems I own tend to share three traits: they move real money or throughput, they cut cycle times by an order of magnitude, and they outlive me — handed to teams, extended, still in production.

*Because most of my strongest work is enterprise and behind internal git, my public contribution graph doesn't tell the whole story — the track record above and the pinned repos below do.*

---

## Tech

**Languages & data** — TypeScript · JavaScript · Python · Java · SQL · PostgreSQL · MongoDB · Redis · Kafka

**Frameworks & infra** — React · Next.js · Node · Express · FastAPI · Electron · Angular · Prisma · Redux Toolkit · Zustand · Tailwind · Docker · nsjail · BullMQ · AWS · Jenkins

**AI / voice** — Claude API · Claude Code · MCP · Deepgram STT · Kokoro TTS

**Testing & telemetry** — Vitest · Playwright · Jest · PostHog · Sentry · GA4 · SonarQube

---

## Contact

- **LinkedIn** — [linkedin.com/in/phaneendra-bheesetti](https://linkedin.com/in/phaneendra-bheesetti)
- **Email** — phaneendra.bheesetti36@gmail.com
- **Portfolio** — [phaneendra-portfolio.pages.dev](https://phaneendra-portfolio.pages.dev)
