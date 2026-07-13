# FIGURE-INDEX

> **Structural Recognition above Metric Similarity (SRMS)**

This document provides a guide to all figures in the repository.

The figures are intentionally organized to mirror the progression of the SRMS paper series.

Reading the figures sequentially provides a concise overview of the entire recognition-centered AI architecture.

---

# Recommended Reading Order

```text id="jdd9q0"
Fig-000
        ↓
Fig-001
        ↓
Fig-002
        ↓
Fig-003
        ↓
Fig-004
        ↓
Fig-005
        ↓
Fig-006
        ↓
Fig-007
        ↓
Fig-008
```

Each figure introduces one major concept and prepares the next.

---

# Fig-000 — SRMS Overview

**Related Paper**

Repository Overview

**Purpose**

Introduces the overall paradigm shift from Similarity-Centered AI to Recognition-Centered AI.

Shows the complete SRMS pipeline at a glance.

**Key Message**

Recognition establishes the computational world.

Similarity optimizes inside that world.

---

# Fig-001 — From Metric Similarity to Structural Recognition

**Related Paper**

SRMS-001

**Purpose**

Explains why structural recognition should precede metric similarity.

Compares traditional similarity-first pipelines with recognition-first architectures.

**Key Message**

Recognition determines identity.

Similarity measures proximity.

---

# Fig-002 — The Base–Delta Asymmetry Principle

**Related Paper**

SRMS-002

**Purpose**

Illustrates why tiny structural deltas can dominate massive shared structural bases.

Introduces one of the central theoretical principles of SRMS.

**Key Message**

Small structural deltas often determine the entire decision.

---

# Fig-003 — Recognition-Gated Cosine Scoring

**Related Paper**

SRMS-003

**Purpose**

Introduces the core algorithm of this repository.

Shows how structural recognition constructs a valid candidate space before cosine ranking.

**Key Message**

Recognition gates similarity.

Similarity does not replace recognition.

---

# Fig-004 — Small but Decisive Structural Deltas

**Related Paper**

SRMS-004

**Purpose**

Illustrates typical categories of decisive structural differences.

Explains why engineering decision boundaries are structural rather than metric.

**Key Message**

Not every difference matters.

The decisive delta determines the outcome.

---

# Fig-005 — Structural Recognition as Runtime Intelligence

**Related Paper**

SRMS-005

**Purpose**

Shows that recognition activates runtime rather than merely assigning labels.

Connects structural recognition with Calling Graphs, Runtime Invariants, and executable computation.

**Key Message**

Recognition activates the computational world.

---

# Fig-006 — Structural Confidence Accumulation

**Related Paper**

SRMS-006

**Purpose**

Illustrates how structural confidence grows through accumulated evidence.

Contrasts structural confidence with statistical confidence.

**Key Message**

Recognition finds the structure.

Evidence builds confidence.

Confidence enables trusted decisions.

---

# Fig-007 — Certified Structural Components and Structural Assets

**Related Paper**

SRMS-007

**Purpose**

Explains how recognized and verified structures become reusable engineering assets.

Shows the lifecycle from recognition to certification and long-term reuse.

**Key Message**

Recognition builds infrastructure.

Certification enables reuse.

---

# Fig-008 — The Structural Recognition Pipeline for Future AI

**Related Paper**

SRMS-008

**Purpose**

Summarizes the complete SRMS computational architecture.

Integrates all previous concepts into a unified recognition-centered AI pipeline.

**Key Message**

Recognition organizes intelligent computation.

Similarity optimizes within recognized structures.

---

# Concept Progression

The figures collectively describe one continuous computational pipeline.

```text id="7yg77j"
Recognition
        ↓
Critical Delta
        ↓
Decision Boundary
        ↓
Runtime
        ↓
Runtime Invariants
        ↓
Structural Confidence
        ↓
Certification
        ↓
Structural Assets
        ↓
Similarity
        ↓
Decision
```

Each figure expands one stage of this progression.

Together they form the complete Structural Recognition Pipeline.

---

# Reading Suggestions

## New Readers

Read:

```text id="57fr2e"
Fig-000
        ↓
Fig-008
```

to obtain a high-level understanding of the repository.

---

## Researchers

Read sequentially:

```text id="okzpv4"
Fig-001
↓

Fig-002
↓

Fig-003
↓

Fig-004
↓

Fig-005
↓

Fig-006
↓

Fig-007
↓

Fig-008
```

to follow the theoretical development.

---

## Engineers

Focus on:

* Fig-003 — Recognition-Gated Cosine Scoring
* Fig-005 — Runtime Intelligence
* Fig-006 — Structural Confidence
* Fig-007 — Certified Structural Components
* Fig-008 — Structural Recognition Pipeline

These figures emphasize practical engineering architectures for reliable AI systems.

---

# Closing Remark

The figures in this repository are not independent illustrations.

They are designed as a progressive visual explanation of a single idea:

> **Recognition establishes identity, runtime, confidence, and reusable structural assets before similarity performs ranking and optimization.**

Taken together, they describe the transition from **Similarity-Centered AI** to **Recognition-Centered AI**, which forms the central contribution of the **Structural Recognition above Metric Similarity (SRMS)** repository.
