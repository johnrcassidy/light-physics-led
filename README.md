# Light Physics for LED Placement in Controlled Environment Agriculture

**Author**: John Cassidy  
**Organisation**: Archipelagos Labs  
**Year**: 2026

---

## Overview

This repository contains educational documentation on light physics as it applies to LED placement and measurement in controlled environment agriculture (CEA), with a focus on glasshouse vertical growing systems.

The documentation explains the inverse square law, ePAR measurement, sensor head importance, and practical considerations for optimising light in multi-level growing environments.

---

## Documents

### 1. Simple Guide
**File**: `led-placement-diminishing-returns-simple.md`

**Audience**: Growers, technicians, and stakeholders who need practical guidance without deep technical detail.

**Purpose**: Provides clear, accessible explanations of:
- Why LED distance matters (inverse square law)
- How natural sunlight differs from artificial lighting
- Basic glasshouse vertical growing considerations
- Why sensor quality is critical

**Use when**: You need a quick reference, are explaining concepts to non-technical colleagues, or want practical checklists without mathematical detail.

---

### 2. Detailed Technical Guide
**File**: `led-placement-diminishing-returns.md`

**Audience**: Engineers, agronomists, researchers, and technical decision-makers who require comprehensive understanding.

**Purpose**: Provides in-depth coverage including:
- Historical context and physics principles
- Mathematical formulations and code implementations
- Detailed glasshouse dynamics (solar progression, photoperiod, shading)
- Shade avoidance syndrome and plant physiology
- Misting effects on light transmission
- Sensor head technology and data alignment requirements
- Implementation algorithms (pseudocode, JavaScript, Python)

**Use when**: You need to understand the underlying science, implement calculations in software, specify sensor requirements, or make data-driven decisions about lighting infrastructure.

---

## Key Topics Covered

| Topic | Simple Guide | Technical Guide |
|-------|--------------|-----------------|
| Inverse square law | Explained simply | Full derivation and code |
| ePAR (400-750nm) | What it is and why it matters | Spectral details and crop requirements |
| Glasshouse dynamics | Overview of seasonal effects | Solar geometry, shadow calculations |
| Multi-level shelving | Light percentages by level | Aspect dynamics, attenuation factors |
| Shade avoidance | Symptoms to watch for | Physiological mechanisms |
| Misting effects | Practical timing advice | Scattering physics, DLI impact |
| Sensor heads | Why quality matters | Lux vs PPFD, data alignment protocol |
| Apogee sensors | Recommendation | Technical specifications |

---

## Why Two Documents?

Different audiences require different levels of detail:

- **Operational staff** need to know what to do, not necessarily why at a physics level
- **Technical staff** need to understand the science to specify equipment and validate data
- **Stakeholders** need clear summaries without jargon
- **Researchers** need mathematical foundations and implementation details

A single document attempting to serve all audiences becomes unwieldy. Separating simple and technical versions allows each to be optimised for its purpose.

---

## Core Principles

1. **Measurement before assumption**: All light management decisions should be based on measured ePAR data, not visual assessment or assumptions.

2. **Sensor quality is foundational**: Every derived metric (DLI, PPFD, supplemental light requirements) inherits the accuracy or inaccuracy of the primary sensor measurement.

3. **Context matters**: The same LED fixture behaves differently at different heights, and the same glasshouse receives fundamentally different light in summer versus winter.

4. **Data alignment is critical**: When comparing measurements from different sources, sensor specifications, conversion methods, and timestamps must all be verified.

---

## Recommended Equipment

These documents reference **Apogee Instruments ePAR sensors** as the recommended measurement equipment:

- [Apogee ePAR Sensors](https://www.apogeeinstruments.com/epar-sensors/)

Apogee sensors directly measure photons in the 400-750nm range without lux-to-PPFD conversion, providing accurate data for horticultural applications.

---

## Licence

© 2026 Archipelagos Labs. All rights reserved.

---

## Contact

For questions about this documentation or Archipelagos Labs services, contact through the appropriate channels.
