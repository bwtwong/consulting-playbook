# The Consulting Playbook
## A Living Framework Repository

A curated, practitioner-oriented collection of consulting frameworks — built to be used, not just read.

**Live site:** `https://bwtwong.github.io/consulting-playbook` *(update once deployed)*

Part of a series alongside the [Health Commercialisation & Innovation Playbook](https://bwtwong.github.io/health-innovation-playbook), the [Impact Investing Playbook](https://bwtwong.github.io/impact-investing-playbook), and the [Implementation Science & MEL Cheatsheet](https://bwtwong.github.io/implementation-science-cheatsheet). See the full series at the [notebook hub](https://bwtwong.github.io/notebooks).

---

## What this is

A personal learning notebook for consulting frameworks, organised across six practice areas:

- **Entering Consulting** — problem structuring, communication, industry analysis, org design
- **Implementation** — RACI, change management, work planning, value chain
- **Evaluation** — logic models, Kirkpatrick, SWOT, Balanced Scorecard, CBA
- **Scale-Up** — Ansoff Matrix, scaling readiness
- **Monitoring & Impact** — OKRs, Theory of Change, SROI, KPI design
- **Case Interviews** — profitability, market sizing, BCG portfolio matrix

Every framework includes explanation, application guidance, pitfalls, and a **practice scenario with AI coaching feedback**.

---

## Frameworks (v2.1 — 31 total)

### Entering Consulting (13)
- MECE Principle
- Issue Tree
- Hypothesis-Driven Thinking
- The Pyramid Principle (SCQA)
- The 2×2 Matrix
- Stakeholder Mapping
- Porter's Five Forces
- McKinsey 7S Framework
- Business Model Canvas
- Three Horizons of Growth
- PESTLE Analysis
- Root Cause Analysis (5 Whys & Fishbone)
- Gap Analysis

### Implementation (4)
- RACI Matrix
- Kübler-Ross Change Curve
- The Consulting Work Plan
- Value Chain Analysis

### Evaluation (5)
- Logic Model
- Kirkpatrick Four-Level Model
- SWOT Analysis
- Balanced Scorecard
- Cost-Benefit Analysis

### Scale-Up (2)
- Ansoff Matrix
- Scaling Readiness Assessment

### Monitoring & Impact (4)
- OKRs (Objectives & Key Results)
- Theory of Change
- Social Return on Investment (SROI)
- KPI Framework Design

### Case Interviews (3)
- Profitability Framework
- Market Sizing
- BCG Growth-Share Matrix

---

## A note on what's deliberately excluded

This playbook only includes frameworks — structured ways of *thinking about* information you already have. It deliberately excludes gathering methods (document review, stakeholder interviews, direct observation) which are real and necessary skills but aren't frameworks in the same sense — there's no clever structure to rehearse, just rigour and curiosity. The Entering Consulting section opens with a short note on this distinction.

## Planned next pages

- **Health Commercialisation & Innovation** — TRL/CRL, Valley of Death, HTA, HEOR, TGA/PBAC pathways, Stage-Gate, reimbursement mapping
- **Impact Investing** — IMP Five Dimensions, IRIS+, blended finance, SIBs, impact thesis, ESG vs impact, deal structuring, due diligence

---

## How to add a framework

Copy an existing card block inside the correct `fw-grid` section. Add a `frameworkContexts['yourid']` entry in the JS block at the bottom — this is the AI coaching prompt.

---

## Tech

Plain HTML, CSS, JavaScript. No build step. AI feedback via Claude API (Anthropic).

*Built as a personal learning tool. Frameworks drawn from McKinsey, BCG, Bain, and public sector practice.*
