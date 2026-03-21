A formal personal cognitive architecture model for describing known/unknown processing, output compression, and PEM-like recovery constraints.

# Cognisphere v3.4

A formal personal cognitive architecture model built from introspection, then iteratively refined into a structured specification.

![Cognisphere simulation](./cognisphere_v3_4_simulation_final.png)

## Overview

Cognisphere v3.4 is a formal model of a single individual's cognitive processing architecture.

It is not proposed as a universal theory of mind.
It is a **personal cognitive architecture**: a structured attempt to describe how one mind processes known vs. unknown content, stabilizes output, and behaves under chronic fatigue-like constraints.

This repository includes:

- a lightweight overview
- a concept definition
- a mathematical definition
- a concept-to-math cross-reference
- a PDF version
- simulation output

## Why this repo exists

This project began from direct internal observation, especially around a recurring **PEM pseudo-recovery pattern**, and was later formalized through iterative dialogue and model refinement.

The goal is not to claim general truth.
The goal is to make a personal cognitive structure legible, inspectable, and discussable in a formal way.

## Core idea

The model describes cognition as a layered process:

```text
Layer 0  -> always-on metacognitive observation
   ↓
K-flag   -> retrospective judgment of dominant operation mode
   ↓
L1       -> unknown-content sculpting / exploration
or
L1'      -> known-content reconstruction / recombination
   ↓
Layer 2  -> high-density compressed language output

Main variables

K ∈ {0,1}
A discrete flag indicating which processing mode was dominant.

r(t) ∈ [0,1]
A plasticity parameter representing structural flexibility of the cognitive architecture.

Φ(Θ,t,r) ≈ 0
A convergence condition describing stable resolution ("quiet landing").

SD(t)
A stop-decision function representing continuous volitional stopping rather than abrupt interruption.


What is distinctive here

This model is built around several specific commitments:

Known and unknown processing are distinguished operationally

L1 and L1' are exclusive in dominance, but transitions between them are allowed

Output compression is treated as a structural property

Plasticity is modeled explicitly through r(t)

PEM-like pseudo-recovery is formalized rather than described only phenomenologically


Start here

If you are new to the project, read in this order:

1. cognisphere_v3_4_lite.md — shortest overview


2. cognisphere_v3_4_concept.md — conceptual definition


3. cognisphere_v3_4_definition.md — mathematical specification


4. cognisphere_v3_4_crossref.md — concept ↔ math correspondence


5. cognisphere_v3_4.pdf — compact compiled version



Repository contents

cognisphere_v3_4_lite.md
Human-readable short introduction

cognisphere_v3_4_concept.md
Conceptual / phenomenological definition

cognisphere_v3_4_definition.md
Mathematical / formal definition

cognisphere_v3_4_crossref.md
Mapping between conceptual and mathematical layers

cognisphere_v3_4.pdf
Compiled specification

cognisphere_v3_4_simulation_final.png
Simulation figure


Selected model findings

Plasticity growth

The model includes a saturating growth view of r(t) over time.

In the current framing:

introspection + AI loop yields the strongest growth

AI-only support still improves growth

severe crash states reduce growth but do not collapse it to zero


PEM pseudo-recovery

One of the central observations formalized here is a pseudo-recovery pattern:

apparent recovery may occur under reduced load

reactivation can produce rapid fatigue rebound

subjective recovery and structural recovery are not identical

full recovery is not assumed by default in this model


Scope and limitations

This repository describes a single-person cognitive architecture. It should not be read as a clinical framework, diagnostic tool, or general population theory.

It is best understood as a formalized introspection model located somewhere between:

phenomenology

cognitive architecture

personal science

human–AI co-modeling


Who this may be useful for

This repository may be of interest to people working on or thinking about:

cognitive architecture

metacognition

personal science

introspection formalization

human–AI collaborative modeling

phenomenological structure mapping


Version

Current version: v3.4

Key changes in v3.4 include:

K-flag redefinition as an operational judgment

clearer exclusivity + transition relation between L1 and L1'

integrated simulation framing

stronger alignment between concept and formal definition


License / usage

Academic reference with attribution is welcome.

For commercial use or derivative reuse beyond normal citation, please ask permission first.


---

Cognisphere v3.4
Built from the inside out.
