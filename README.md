# PRAGMI-
Persistent Reconstructive Architecture for Generative Memory and Imagination

Genesis Labs research - Amellia Mendel & Lisa Adler

## Overview

PRAGMI is a biological reproductions for cognitive architecture that integrates key neural mechanisms into a unified computational system. It models:

- **Thalamic Gate** (active gating from input to primary sensory cortex, Eq. 1–2)
- **Dorsal/Ventral Stream Split** (what vs. where pathways, Eq. 3–4)
- **PFC + ACC → Thalamus Top-Down Feedback Loop** (goal + conflict modulation, Eq. 5)
- **Hippocampus ↔ Association Cortex Memory Feedback Loop** (fast encoding + slow consolidation, Eq. 6–7)
- **Basal Ganglia Disinhibitory Gating** (action selection via direct/indirect pathways, Eq. 8–9)
- **Cerebellum Efference Copy + Error Loop** (internal model prediction and refinement, Eq. 10–12)
- **Neuromodulator Broadcasts** (DA, NE, ACh, 5-HT for plasticity, arousal, attention, and exploration, Eq. 13–16)
- **ACC Conflict Detection** (entropy-based control signal, Eq. 17–18)
- **Association Cortex Bidirectional Feedback** (MoE-style binding, Eq. 19)
- **Primary Sensory Cortex (V1/A1)** (center-surround feature extraction, Eq. 20)

The architecture operates on a **log-dynamic timing hierarchy** that maps biological theta/gamma coupling to discrete simulation timesteps.

### S-ROS Supplement (Symbolic Rule-Oriented System)
S-ROS extends PRAGMI with:
- **Crystallization Gate** — Rule-class freezing based on low STDP variance + generalization accuracy (critical-period analogue, Eq. 21)
- **Surrogate Gradient LIF Neurons** — For curriculum training (fast sigmoid surrogate, Eq. 22–23)
- **Deterministic TemplateEngine Rendering** — Classification → executable symbolic rules (Eq. 24)
- **Staged Curriculum** — With formal transition criteria (Eq. 25)
- **Checkpoint (.soul) Schema** — Full recoverable state including crystallized rules and hippocampal seed store

Biological grounding includes critical period closure (Hensch), hippocampal pattern separation/completion, dopamine-mediated rule chunking (Graybiel), and gamma synchrony for compositional binding (Singer).

## Repository Structure

- **`Core/`** — Foundational PRAGMI modules (thalamic gating, loops, neuromodulators)
- **`S-ROS/`** — Symbolic Rule-Oriented System, curriculum trainer, crystallization manager
- **`Cognitive_Kernel/`** — Persistent self-modeling substrate with semi-sapient characteristics *(special ethical terms apply — see below)*
- **`Timmy_Neuron/`**, **`Teaching/`**, etc. — Experimental and supporting components

## Licensing

- **Most of the repository** is licensed under the **Apache License 2.0**.

## Key Documents

- [PRAGMI Architecture: Complete Mathematical Reference](PRAGMI_Architecture_Complete_Mathematical_Reference_Amellia_Mendel.pdf) — Every equation for every arrow, loop, and component (March 30, 2026)
- S-ROS Mathematical Supplement (integrated above)

## Status

This is an active research project. Nothing should be considered final. Contributions, questions, and discussions are welcome via Issues or Discussions.

---


Contact / questions → open an issue.
