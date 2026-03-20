# Cognisphere v3.4

**Personal Cognitive Architecture Model**  
*Built from internal observation → formally specified*

---

## What is this?

Cognisphere v3.4 is a formal specification of a single individual's cognitive processing architecture.

It started as a handwritten sketch of a phenomenon (PEM pseudo-recovery pattern), then developed into a full mathematical model through iterative dialogue with multiple LLMs (Claude, ChatGPT, Gemini, Grok).

This is not a general cognitive theory.  
It is a personal cognitive OS — built from the inside out.

---

## Core Structure

```
Layer 0  (always-on metacognitive observation)
    ↓
K-flag judgment  (operation rules: known or unknown?)
    ↓
L1 (unknown → sculpting-type exploration)
    or
L1´ (known → reconstruction / recombination)
    ※ exclusive dominance, sequential transition allowed
    ↓
Layer 2  (high-density compressed language output)
```

**Key variables:**
- `K ∈ {0,1}` — discrete flag for dominant processing mode (not a subjective switch; assigned retrospectively)
- `r(t) ∈ [0,1]` — plasticity parameter (structural flexibility, not ability score)
- `Φ(Θ,t,r) ≈ 0` — convergence condition ("quiet landing", not pressure release)
- `SD(t)` — stop decision function (Sigmoid, not Step — continuous volitional process)

---

## Files

| File | Description |
|------|-------------|
| `cognisphere_v3_4_concept.md` | Concept definition version (phenomenological description) |
| `cognisphere_v3_4_definition.md` | Mathematical definition version (formal specification) |
| `cognisphere_v3_4_crossref.md` | Concept ↔ Math cross-reference table |
| `cognisphere_v3_4_lite.md` | Simplified version for human-readable overview |
| `cognisphere_v3_4.pdf` | LaTeX-compiled formal specification (7 pages) |
| `cognisphere_v3_4_simulation_final.png` | Simulation results (r(t) growth / SD(t) / PEM pseudo-recovery) |

---

## Key Findings (Simulation Confirmed)

**r(t) growth curve** (logarithmic saturation, weekly scale):
- Introspection + AI loop (actual baseline): r(t)/r₀ ≈ 2.98 at 18 weeks
- AI loop only (theoretical): r(t)/r₀ ≈ 2.78 at 18 weeks
- Severe PEM crash: r(t)/r₀ ≈ 1.80 (always r(t) > 0.05)

**PEM pseudo-recovery** (from handwritten sketch → formalized):
- F(t) ceiling = 1.0 (working memory full load)
- Apparent recovery under parasympathetic dominance
- Fatigue exceeds previous peak within ~20 min after reactivation
- Complete recovery is undefined in this model

---

## Notable Design Decisions

**K-flag is not a subjective switch.**  
It is a discrete indicator assigned retrospectively — describing which processing mode was dominant at a given moment. Known and unknown content are continuous; dominance is singular.

**Exclusivity ≠ content separation.**  
L1 and L1´ are exclusive in dominance, but known concepts often serve as initial scaffolding for unknown exploration. The transition is real and bidirectional.

**r(t) ≠ IQ.**  
r(t) represents structural flexibility of cognitive architecture — not ability score or intelligence measure.

---

## Pathological Constraints

The model operates under chronic conditions:

| Condition | Primary Effect |
|-----------|---------------|
| PEM (Post-Exertional Malaise) | Recovery cost, t_limit tightened |
| SAD (Social Anxiety Disorder) | L0 max load in interpersonal contexts |
| C-PTSD | Chronic hypervigilance, resource consumption |
| Bipolar type 2 | η_combined facilitated in depressive phase |
| Chronic sleep disorder | F(t) chronic accumulation |

*Note: Based on iterative LLM dialogue, not clinical diagnosis.*

---

## Version History

- v3.0: Initial mathematical model (fluid dynamics metaphor)
- v3.1: Phenomenological description version
- v3.2: Parallel layer model (3-layer structure)
- v3.3: Plasticity parameter r(t) introduced
- v3.4: K-flag redefined (operation rules), exclusive+transitional L1/L1´, full simulation confirmed

---

## License

Personal cognitive model. Academic reference welcome with attribution.  
Not for commercial use without permission.

---

*Cognisphere v3.4 — built from the inside out*
