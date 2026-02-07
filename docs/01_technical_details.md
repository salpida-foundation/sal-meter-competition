# Technical Overview  
## Sal-Meter Open Competition  
### CAIS-Based Consciousness-Like Signal Measurement

This document provides a **technical orientation** for researchers considering participation in the Sal-Meter Open Competition.

It is not a full specification, protocol, or implementation guide.  
Its purpose is to help a technical reader understand **what is being measured, how it is measured, and where contribution boundaries exist**.

Authoritative definitions and compliance requirements reside exclusively in the DOI-registered canonical documents referenced below.

---

## What is being measured (at a high level)

The Sal-Meter project focuses on **objective, reproducible measurement of consciousness-like signals**, defined as structured, measurable correlates of mental state dynamics.

These signals are **not claims about subjective experience itself**, but experimentally observable patterns derived from biological and physical processes.

The system targets three canonical indices:

- **VCE (Vital Coherence Estimate)**  
- **CRI (Cognitive Resilience Index)**  
- **CFI (Consciousness Flux Index)**  

Each index is defined mathematically and operationally in canonical documents.

This repository does not redefine them.

---

## Measurement principle (CAIS Layer-0)

At the core of CAIS (Consciousness–Aptamer Interface System) is a **biochemical-to-signal transduction layer**.

### Core elements

- **Aptamer–iodine multi-oxidation sensing**
- **Redox state dynamics (including GSH/GSSG coupling)**
- **Time-resolved signal extraction**
- **Non-subjective, sensor-derived data**

The system converts biochemical state transitions into stable, analyzable signal streams suitable for computational processing.

---

## System abstraction (non-exhaustive)

A CAIS-compatible Sal-Meter system can be abstracted into five layers:

1. **Biochemical interface**  
   Aptamer–iodine sensing and redox interaction

2. **Signal acquisition**  
   Electrochemical, optical, or hybrid sensing pathways

3. **Signal processing**  
   Noise reduction, normalization, temporal feature extraction

4. **Index computation**  
   Mapping signals to VCE / CRI / CFI

5. **Validation interface**  
   Reproducibility checks and independent assessment readiness

Teams may contribute to **any single layer** without implementing the full stack.

---

## What counts as a valid technical contribution

Valid contributions include, but are not limited to:

- Sensor chemistry refinement or characterization
- Signal-processing algorithms
- Hardware or firmware modules
- Calibration or normalization methods
- Statistical validation pipelines
- Data integrity or reproducibility tooling

A contribution does **not** need to claim superior performance across all indices.

Partial, bounded improvements are explicitly acceptable.

---

## What does not count (common misconceptions)

The following are **explicitly excluded**:

- EEG-only, HRV-only, or questionnaire-based systems
- Black-box “consciousness scores” without CAIS index mapping
- Self-validated systems without independent assessment readiness
- Closed designs blocking inspection of core mechanisms

These exclusions are formally defined in the Sal-Meter Negative Definition (canonical DOI).

---

## Validation expectations (research phase)

During the competition phase:

- Systems are **research-only**
- No medical or clinical claims are permitted
- Performance targets are statistical, not diagnostic

Minimum expectations include:

- Reproducibility across sessions
- Sensitivity and specificity benchmarks (defined canonically)
- Readiness for independent CRO validation (Phase 3)

---

## How this document relates to other materials

This file is intentionally **non-canonical**.

For authoritative reference, consult:

- **Sal-Meter System Overview v1.0** (Figshare, DOI)  
  Device concept and index overview

- **Sal-Meter Open Competition — Technical & Governance Snapshot v2.0** (Figshare, DOI)  
  Tracks, evaluation, and funding structure

- **CAIS Compliance Boundary v1.0** (Zenodo, DOI)  
  Mandatory technical constraints

If you are reading this file alone, you are only seeing the **orientation layer**, not the specification.

---

## How to use this document

Use this file to:

- Decide whether your lab’s expertise maps to any CAIS layer
- Identify a bounded module suitable for Track C exploration
- Frame internal technical discussion without overcommitment

Do **not** use this file as a substitute for canonical documents.

---

## Suggested next step

If this technical framing appears compatible with your lab:

1. Review the canonical CAIS documents (DOI-registered).
2. Identify one layer where your existing work aligns.
3. Evaluate whether a 3–6 month exploratory contribution is feasible.

No application or declaration is required to begin internal exploration.

---

## Authority Notice

Canonical definitions, requirements, and governance for the Sal-Meter Open Competition are fixed exclusively in DOI-registered records.

This document is a **non-authoritative technical orientation**.

For authoritative references, see:  
https://github.com/salpida-foundation/salpida-canonical

