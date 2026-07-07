<div align="center">

# Dylan Taylor

### Founder and developer building auditable AI systems for high-stakes decisions.

**Legal intelligence · Aviation risk · Scientific recommendation**

[![Website](https://img.shields.io/badge/dylantaylor.xyz-111111?style=for-the-badge\&logo=vercel\&logoColor=white)](https://www.dylantaylor.xyz/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111111?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/dylan-tayl0r/)
[![Littman](https://img.shields.io/badge/Littman.ai-111111?style=for-the-badge)](https://littman.ai/)

</div>

---

## About

I'm Dylan, a 17-year-old founder and developer in the San Francisco Bay Area.

I build AI systems for decisions where an unsupported answer is worse than no answer at all.

My work focuses on making model outputs:

* **Grounded** in inspectable evidence
* **Cited** back to their original sources
* **Evaluated** rather than assumed correct
* **Uncertainty-aware** when evidence is incomplete
* **Escalatable** to a human when confidence is low
* **Auditable** after the decision has been made

I work across the full product stack—from parsing, retrieval, orchestration, and evaluation to interfaces, infrastructure, security, and deployment.

```typescript
const dylan = {
  role: "Founder & Developer",
  focus: "Auditable AI for high-stakes decisions",
  domains: ["legal intelligence", "aviation safety", "scientific recommendation"],

  builds: [
    "retrieval and knowledge systems",
    "citation and claim verification",
    "evaluation pipelines",
    "human-in-the-loop workflows",
    "probabilistic decision tools",
    "full-stack products",
  ],

  principles: {
    evidenceOverFluency: true,
    uncertaintyIsAFeature: true,
    demosMustBecomeProducts: true,
  },
};
```

---

## Building

### [Littman](https://littman.ai/) — Auditable legal intelligence

Littman turns a law firm's documents, precedent, and internal standards into cited, reviewable legal work.

Instead of treating legal AI as a general-purpose chatbot, Littman is designed as an execution layer for firm knowledge: retrieve the relevant authority, apply the firm's rules, produce inspectable work, and escalate ambiguity rather than hide it.

**System components include:**

* Hybrid semantic and keyword retrieval
* Structured document parsing and extraction
* Source-linked legal answers
* Claim-level citation validation
* Confidence-aware human escalation
* Firm playbook and precedent application
* Secure document workspaces
* Reviewable workflow outputs
* Decision and activity audit trails

`TypeScript` `Next.js` `React` `Python` `FastAPI` `PostgreSQL` `pgvector` `LLM APIs`

---

### [FlightReady](https://flightready.ai/) — Explainable preflight risk

FlightReady is a decision-support system for general aviation go/no-go planning.

It combines route conditions, weather, aircraft considerations, pilot context, and historical risk into several explainable risk views rather than compressing everything into one unexplained score.

**The system includes:**

* Multiple independent risk models
* Monte Carlo scenario simulation
* Tail-risk analysis inspired by financial risk modeling
* Route- and condition-specific explanations
* Thirteen-section structured flight briefings
* Explicit stale-data and missing-input warnings
* Versioned model and briefing metadata
* Safety-focused decision records
* More than 200 automated tests across the product

The core idea is simple: a flight decision should account for the worst plausible outcome—not merely the average one.

`Next.js` `TypeScript` `Python` `Probabilistic Modeling` `Monte Carlo Simulation` `Geospatial Data`

---

### [OENRA](https://oenra.vercel.app/) — Molecular taste intelligence

OENRA is a research prototype exploring whether wine preference can be modeled from both chemical composition and individual sensory perception.

The system represents a wine's measurable characteristics and a person's palate across a shared sensory space, then estimates whether the person will enjoy the wine—and explains the predicted match.

**Research areas include:**

* GC-MS and LC-MS chemical feature representation
* Multidimensional sensory modeling
* Individual palate embeddings
* Preference prediction
* Explainable recommendation
* Uncertainty and model limitation analysis
* Cold-start personalization

The goal is not to replace sommeliers or critics. It is to investigate what chemistry and machine learning can add to their understanding.

`Python` `TypeScript` `Next.js` `Scientific Data Modeling` `Recommendation Systems`

---

## How I Think About AI

### Evidence before eloquence

A fluent answer is not necessarily a correct one. Systems should expose the evidence behind their conclusions.

### Uncertainty is information

A model that can abstain is often more useful than one forced to answer every question.

### Evaluation is part of the product

Accuracy, citation quality, retrieval coverage, latency, and failure modes should be measured continuously—not checked once before launch.

### Humans should remain legible in the loop

Escalation should preserve the evidence, reasoning state, source material, and uncertainty that caused the system to ask for review.

### The interface is part of the safety system

Confidence indicators, source previews, stale-data warnings, and review controls are not decorative UI. They directly shape how people interpret model output.

---

## Technical Focus

<table>
<tr>
<td valign="top" width="33%">

### AI Systems

* Retrieval-augmented generation
* Hybrid search
* Agent orchestration
* Tool-using models
* Structured generation
* Citation grounding
* Claim verification
* Model evaluation
* Confidence calibration
* Human escalation

</td>
<td valign="top" width="33%">

### Product Engineering

* TypeScript
* Python
* React
* Next.js
* FastAPI
* Node.js
* REST APIs
* Authentication
* Testing
* Observability

</td>
<td valign="top" width="33%">

### Data & Infrastructure

* PostgreSQL
* pgvector
* Supabase
* Vector search
* Document pipelines
* Vercel
* Linux
* Docker
* CI/CD
* Secure data handling

</td>
</tr>
</table>

---

## What I Optimize For

```text
Correctness        over confident presentation
Inspectable output over black-box automation
Real workflows     over isolated AI demos
Measured behavior  over model-provider claims
Useful software    over technical theater
```

---

## Current Questions

Some of the problems I am actively interested in:

* How should an AI system determine that it does not have enough evidence to answer?
* How can citations be verified at the individual-claim level?
* How should retrieval quality be evaluated before generation begins?
* How can internal organizational knowledge become executable without becoming opaque?
* How should probabilistic risk be communicated to nontechnical decision-makers?
* What should remain human-controlled as AI systems become more autonomous?

---

## Working With Me

I am especially interested in:

* High-trust AI systems
* Applied AI research
* Retrieval and evaluation infrastructure
* Legal technology
* Decision-support software
* Probabilistic modeling
* Difficult products with real operational consequences

Most of my current product repositories are private while the companies are in active development. Public research, product demonstrations, and technical writing live at **[dylantaylor.xyz](https://www.dylantaylor.xyz/)**.

---

<div align="center">

### I started by taking systems apart. Now I build systems people can defend.

[Website](https://www.dylantaylor.xyz/) ·
[LinkedIn](https://www.linkedin.com/in/dylan-tayl0r/) ·
[Littman](https://littman.ai/)

</div>
