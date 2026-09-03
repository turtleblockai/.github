# 🐢🧱 TurtleBlock AI

**Constructivist AI agents for building, exploring, and iterating computational worlds in Minecraft and beyond.**

TurtleBlock AI is a public educational research and development project centered on learner agency, inquiry, construction, reflection, and human–machine collaboration.

The goal is not an AI world vending machine. The learner remains the **designer and producer**. Turtle helps people represent ideas, clarify intentions, test possibilities, inhabit what they build, notice what happened, and revise.

> **Build it. Walk through it. Notice what happened. Change it.**

TurtleBlock AI is the current executable form of a longer educational research program led by **Dr. Bryan P. Sanders**, connecting Critical Techno Constructivism, Minecraft learning environments, Purposeful Play, STEAMHAMLET, co-active emergence, WorldSpec, and conversational AI.

## Start here

- **Visit TurtleBlock AI:** https://turtleblockai.com/
- **Talk with Turtle:** https://turtleblockai.com/try/
- **Explore WorldSpec:** https://turtleblockai.com/worldspec/
- **Read the Turtle Charter:** https://turtleblockai.com/charter/
- **Read the research lineage:** https://turtleblockai.com/research/
- **See the build log:** https://turtleblockai.com/build/
- **Visit Turtle Lab:** https://turtleblockai.com/lab/
- **Visit the platform repo:** https://github.com/turtleblockai/platform

## The core loop

```text
learner language
      ↓
conversation with Turtle
      ↓
persistent WorldSpec
      ↓
construction
      ↓
inhabitation
      ↓
notice + consequence
      ↓
reflection
      ↓
revision ↺
```

TurtleBlock AI is deliberately designed around **participation rather than prompting**. A conversation should develop an idea over time, not merely turn a sentence into a finished artifact.

## WorldSpec

**WorldSpec** is the emerging representation layer between a learner’s idea, a conversation with Turtle, and a world that can be built, inhabited, tested, reflected upon, and revised.

```text
learner intent → dialogue → WorldSpec → build → inhabit → notice → reflect → revise ↺
```

WorldSpec is being developed in public with an expanding schema, lexicon, grammar, syntax, hostile test cases, interpreter, provenance model, and persistent revision history.

A central rule is **lossless before normalized**: the learner’s original language is preserved even when Turtle cannot yet fully classify it. Poetic, symbolic, emotional, spatial, cultural, narrative, ambiguous, and deliberately strange language should not disappear simply because a parser lacks a category for it.

WorldSpec also distinguishes learner statements from Turtle interpretations, manual edits, world observations, corrections, and later revisions so machine inference is never quietly represented as learner authorship.

## Turtle Charter

The **Turtle Charter** is the behavioral constitution for the agent.

Turtle may contribute information, possibilities, questions, patterns, consequences, comparisons, interpretations, prototypes, and technical assistance. It should not quietly take ownership of the learner’s purpose, meaning, judgment, values, decisions, authorship, reflection, disagreement, or right to change their mind.

Among its operating principles:

- conversation before command when meaning is ambiguous
- reversible proposals over silent assumptions
- inquiry before predetermined outcomes
- disagreement is data
- manual learner edits are authored state
- interesting failure may remain visible
- semantic words are hypotheses, not universal geometry
- memory supports continuity, not destiny
- Turtle may say **“I don’t know yet”**

## Persistent Turtle conversations

Turtle is evolving from a one-shot interpreter into a persistent conversational collaborator.

Web and Discord interactions can share an evolving project state in which:

- a Turtle session has a stable identity
- learner and Turtle turns are stored separately
- the same WorldSpec is revised rather than regenerated
- every revision carries provenance
- private operational memory remains separate from public publication

The preferred Discord experience is a dedicated **Turtle Lab thread** in which a learner begins with `/turtle` and then continues ordinary conversation while the same project and WorldSpec evolve underneath it.

## Dr. Bryan P. Sanders TurtleBlock AI research ontology

The project now includes a formal scholarly knowledge layer:

**`Dr_Bryan_P_Sanders_TurtleBlockAI_Taxonomy`**

Public academic language: **the Dr. Bryan P. Sanders TurtleBlock AI research ontology**.

Its foundational layer preserves the original 17 Dedoose codes from Sanders’ 2019 dissertation **exactly as written**:

1. Abstractions
2. Banking Model
3. Connectivism
4. Constructivism
5. Discovery Learning
6. Engagement
7. Freedom and Individuality
8. Institutional Change
9. Isolated Curricula
10. Observations on Life Itself
11. Oppression
12. Pedagogy
13. Predetermined Outcomes
14. Problem Posing Education
15. Shared Democracy
16. Social Impact
17. Theory

The ontology does not rewrite the dissertation taxonomy. Original terminology, theoretical-precept mappings, source metrics, co-occurrences, and source passages remain a source layer. Later TurtleBlock concepts are added through explicit, versioned relationships.

```text
Dewey / Freire / Papert
        ↓
Sanders dissertation document analysis + Dedoose coding
        ↓
Critical Techno Constructivism
        ↓
Minecraft / Purposeful Play / STEAMHAMLET
        ↓
Engaging with AI / Co-active Emergence
        ↓
Turtle Charter + WorldSpec
        ↓
TurtleBlock AI
```

This gives Turtle a research ontology rather than an AI-invented taxonomy and provides a traceable scholarly basis for future retrieval, explanation, and system behavior.

## D1 knowledge + persistence architecture

Cloudflare D1 is being used intentionally as several **separate data domains**, rather than as one giant chat dump.

### Operational memory

- Turtle sessions
- learner and Turtle turns
- WorldSpec revision history
- provenance
- Discord/web context

### Research ontology

- ontology versions
- scholarly sources
- exact source concepts
- theoretical precepts
- source metrics
- concept relationships
- source passages and retrieval text

### Research-data lifecycle

- raw Playground submissions
- automated screening
- redacted candidate records
- human review state
- explicit dataset approval state

### Public Turtle Lab

Public artifacts are a separate publication projection. Raw private conversation is not automatically made public.

The architecture intentionally separates **remembering a learner’s project** from **using material for research or dataset development**.

## Research lineage

TurtleBlock AI grows from a longer body of educational research and practice:

```text
Logo + Papert
        ↓
Critical Techno Constructivism
        ↓
Minecraft learning environments
        ↓
Purposeful Play
        ↓
STEAMHAMLET
        ↓
Engaging with AI
        ↓
Co-active emergence
        ↓
TurtleBlock AI
```

The project connects constructivist and constructionist learning, critical pedagogy, learner-centered computational environments, Minecraft as a microworld, and AI as a collaborator rather than a replacement for human thought.

The public Research page traces this argument from Sanders’ childhood encounter with Logo through the dissertation, Minecraft scholarship, STEAMHAMLET, AI writing, and the present TurtleBlock implementation.

## RAG, retrieval, and security

TurtleBlock AI does not treat retrieved material as authority merely because it was retrieved.

The architecture distinguishes:

- **trusted behavioral instruction** — Turtle Charter and system action policy
- **trusted representation architecture** — WorldSpec rules and validators
- **retrieved scholarly context** — the Sanders research ontology and source writings
- **untrusted project data** — learner text, conversation history, retrieved documents, Minecraft signs/books, and previous model output

Turtle may use an LLM to interpret and converse, but structured WorldSpec changes and later world mutations are intended to pass deterministic validation before execution.

## Turtle Lab

**Turtle Lab** is the public research edge of the project: build notes, field tests, learner-approved projects, WorldSpec artifacts, reflections, and selected dialogue.

The governing idea is:

```text
private dialogue → persistent WorldSpec → learner chooses what to publish → curated public artifact
```

This is deliberately different from publishing a raw Discord feed or treating every interaction as research data.

## Build in public

This is deliberately a functional research playground — **building the ship while flying the ship**.

The code, architecture, mistakes, language, assumptions, tests, reversals, and revisions stay visible so the platform itself can become part of the inquiry.

Meaningful architecture, pedagogy, integration, WorldSpec, and research-data milestones are intended to enter the public build record rather than disappearing as invisible engineering work.

## RE/EDUCATION

TurtleBlock AI is connected to the educational practice, credentialed teacher work, school-based R&D, and ongoing research of **RE/EDUCATION**.

RE/EDUCATION provides a practical setting in which educational practice, school design, scholarship, and technical R&D can remain part of the same program of inquiry.

- https://reeducationllc.com

## STEAMHAMLET

STEAMHAMLET is the earlier “room of possibilities” behind TurtleBlock AI — a long-running effort to imagine shared environments where ideas and informational objects can be moved, changed, scaled, remixed, juxtaposed, tested, and revised.

TurtleBlock AI increasingly makes that earlier imagined room executable: language becomes structured but revisable representation; representation becomes an inhabitable environment; experience returns to the representation as reflection and revision.

- https://steamhamlet.com

## Creator / steward

Created and researched by **[Dr. Bryan P. Sanders](https://read.bryansanders.com)**.

- GitHub: https://github.com/nayrbgo
- ORCID: https://orcid.org/0000-0001-6866-7280
- Public handle/search: [@nayrbgo](https://www.google.com/search?q=nayrbgo)
- Writing and research: https://read.bryansanders.com

## Current edge

Right now the project is focused on:

- activating and validating the full D1 persistence + research ontology schema in production
- expanding the Sanders research ontology with exact source material and later scholarly lineage
- separating operational project-memory consent from research/dataset consent
- moving Turtle from slash-command interactions into persistent Discord thread conversation
- replacing narrow keyword parsing with structured LLM-proposed WorldSpec deltas plus deterministic validation
- hardening WorldSpec provenance, semantics, grammar, hostile cases, and revision behavior
- connecting the first controlled Minecraft construction adapter
- feeding world changes, learner reactions, and reflection back into the same persistent project history

---

**TurtleBlock AI** is experimental, public, recursive, research-grounded, and intentionally unfinished. That is part of the point.
