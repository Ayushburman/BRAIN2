# 🧠 Neuroplasticity — Deep Reference Notes


> The brain's ability to reorganize itself by forming new neural connections throughout life.

---


# 1. Definition & Core Concept

## Neuroplasticity (Neural Plasticity)


Neuroplasticity is the capacity of neural circuits in the brain to change their:


* Structure
* Function
* Chemical properties

in response to:

* Learning
* Experience
* Activity
* Injury
* Disease


It operates across multiple timescales:

| Timescale            | Mechanism                |
| -------------------- | ------------------------ |
| Milliseconds–Seconds | Ion channel changes      |
| Minutes              | Receptor phosphorylation |
| Hours                | Protein synthesis        |
| Days–Weeks           | Dendritic spine growth   |
| Months–Years         | Cortical reorganization  |


### Key Principle

Neurons are not fixed hardware.

They are dynamic, experience-dependent systems capable of modification throughout life.

---

## Historical Foundation

### Ramón y Cajal (1894)

Proposed that mental activity could modify synaptic connections.

### Donald Hebb (1949)

Provided the first formal theory of activity-dependent learning.

### Michael Merzenich (1983–1996)

Demonstrated that cortical maps in adult monkeys could reorganize after:

* Training
* Sensory changes
* Nerve damage

This overturned the belief that adult brains are hardwired.

---

# 2. Types of Neuroplasticity

## Synaptic Plasticity

Changes in the:

* Strength
* Number

of synaptic connections.

Examples:

* Long-Term Potentiation (LTP)
* Long-Term Depression (LTD)
* Homeostatic Plasticity

**Primary substrate of learning and memory.**

---

## Structural Plasticity

Physical changes in brain anatomy:

* Dendrite growth
* Axon sprouting
* Spine remodeling

Occurs over:

* Days
* Weeks
* Months

---

## Homeostatic Plasticity

Maintains stability of neural activity.

If neurons become:

* Overactive → Synapses weaken
* Underactive → Synapses strengthen

Goal:

> Maintain optimal firing rates.

---

## Neurogenesis

Creation of new neurons in adulthood.

Major regions:

* Hippocampal Dentate Gyrus
* Olfactory Bulb

Associated with:

* Learning
* Exercise
* Stress regulation

---

## Evidence: Phantom Limb Phenomenon

After limb amputation:

* Touching the face can produce sensations in the missing hand.

Explanation:

The face representation expands into the unused hand area of the somatosensory cortex.

This demonstrates large-scale cortical reorganization.

---

# 3. Synaptic Plasticity

## The Glutamatergic Synapse

Most excitatory synapses use:

* Glutamate

Main receptors:

### AMPA Receptors (AMPAR)

* Fast signaling
* Conduct Na⁺ and K⁺
* More AMPARs = Stronger synapse

### NMDA Receptors (NMDAR)

* Blocked by Mg²⁺ at rest
* Require:

  * Glutamate binding
  * Postsynaptic depolarization

Acts as a:

> Coincidence detector

---

## Why NMDA Receptors Matter

NMDA receptors allow:

* Ca²⁺ influx

Calcium triggers:

* LTP
* LTD
* Gene expression
* Structural remodeling

---

## Evidence: AMPA Receptor Trafficking

During LTP:

* New AMPA receptors are inserted into the postsynaptic membrane.

Blocking AMPA insertion:

* Prevents LTP

Therefore:

> AMPAR trafficking is required for memory-related plasticity.

---

# 4. Structural Plasticity

## Dendritic Spines

Tiny protrusions on dendrites.

Function:

* Receive excitatory input

Relationship:

```text
Larger Spine
      ↓
More AMPARs
      ↓
Stronger Synapse
```

## Spine Types

| Type       | Description   | Role                |
| ---------- | ------------- | ------------------- |
| Filopodial | Long & thin   | Exploration         |
| Thin       | Small head    | Weak synapse        |
| Mushroom   | Large head    | Long-term memory    |
| Stubby     | No clear neck | Developmental stage |

---

## Evidence: Two-Photon Imaging

Researchers tracked individual dendritic spines in living mice.

Results:

* New spines formed after learning
* Many persisted for months

Conclusion:

> Memory formation correlates with structural spine changes.

---

# 5. Hebb's Rule

## Hebb's Postulate (1949)

When neuron A repeatedly helps activate neuron B:

* Their connection becomes stronger.

---

### Famous Version

> Neurons that fire together, wire together.

---

## Mathematical Form

```text
Δw = η × xi × xj
```

Where:

* Δw = Change in synaptic weight
* η = Learning rate
* xi = Presynaptic activity
* xj = Postsynaptic activity

---

## NMDA Receptors as Hebbian Devices

NMDA receptors open only when:

1. Presynaptic glutamate is released
2. Postsynaptic neuron is depolarized

Therefore they implement:

```text
A AND B
```

which is the biological basis of Hebbian learning.

---

## Spike Timing Dependent Plasticity (STDP)

### Presynaptic fires BEFORE postsynaptic

```text
Pre → Post
```

Result:

✅ LTP

---

### Postsynaptic fires BEFORE presynaptic

```text
Post → Pre
```

Result:

❌ LTD

---

Timing window:

~20 milliseconds

---

# 6. Long-Term Potentiation (LTP)

## Definition

Persistent strengthening of synaptic transmission after intense stimulation.

---

## Phases of LTP

### Early LTP (E-LTP)

Duration:

~1 hour

Characteristics:

* No protein synthesis required
* AMPA insertion

---

### Late LTP (L-LTP)

Duration:

Hours to days

Characteristics:

* Requires protein synthesis
* Gene expression changes

---

### Very Late LTP

Duration:

Weeks to months

Characteristics:

* Structural remodeling
* Spine enlargement

---

## Molecular Cascade

### Step 1

High-frequency stimulation

↓

NMDA activation

↓

Ca²⁺ influx

---

### Step 2

Ca²⁺ activates:

* Calmodulin
* CaMKII

---

### Step 3

CaMKII inserts AMPA receptors

↓

Synapse strengthens

---

### Step 4

CREB activation

↓

Gene transcription

↓

New proteins

---

### Step 5

Spine growth

↓

Long-term memory storage

---

## Evidence: Bliss & Lømo (1973)

First discovery of LTP.

A brief high-frequency stimulus caused:

* > 200% increase in synaptic strength

lasting:

* Hours
* Days
* Weeks

This became the foundation of memory neuroscience.

---

# 7. BDNF — Brain-Derived Neurotrophic Factor

## What is BDNF?

A neurotrophin that supports:

* Learning
* Memory
* Neurogenesis
* Synaptic growth

Often called:

> Fertilizer for the brain

---

## Major Functions

### Ras-MAPK Pathway

Gene transcription

### PI3K-Akt Pathway

Cell survival

### PLCγ Pathway

Synaptic strengthening

---

## Important Mediators

| Molecule | Function                  |
| -------- | ------------------------- |
| BDNF     | Plasticity & neurogenesis |
| CaMKII   | Synaptic strengthening    |
| CREB     | Gene activation           |
| Arc      | AMPAR regulation          |
| mTOR     | Protein synthesis         |

---

# 8. Critical Periods

## Definition

Developmental windows during which experience strongly shapes neural circuits.

Outside these periods:

* Plasticity is reduced.

---

## Hubel & Wiesel Experiment

Kittens had one eye closed during development.

Result:

* Visual cortex reorganized
* Permanent amblyopia developed

Same experiment in adults:

* Minimal effect

Conclusion:

> Plasticity has sensitive developmental windows.

---

## Examples

| System               | Critical Period |
| -------------------- | --------------- |
| Vision               | Birth–7 years   |
| Language             | Birth–12 years  |
| Absolute Pitch       | 3–6 years       |
| Attachment           | 0–3 years       |
| Emotional Regulation | Into mid-20s    |

---

# 9. Adult Neuroplasticity

## Adult Hippocampal Neurogenesis

New neurons continue to form in:

* Dentate Gyrus

Functions:

* Learning
* Memory separation
* Cognitive flexibility

---

## Exercise and Neuroplasticity

Exercise increases:

* BDNF
* Neurogenesis
* Memory performance

Mechanism:

```text
Exercise
   ↓
BDNF ↑
   ↓
Neurogenesis ↑
   ↓
Learning ↑
```

---

## London Taxi Driver Study

Taxi drivers memorize:

~25,000 streets

MRI findings:

* Larger posterior hippocampus

More years driving:

* Larger hippocampal volume

Conclusion:

> Experience physically reshapes the adult brain.

---

# 10. Homeostatic Plasticity

## Problem

If Hebbian learning worked alone:

```text
Strong Synapse
    ↓
More Firing
    ↓
Stronger Synapse
    ↓
Runaway Excitation
```

---

## Solution: Synaptic Scaling

### Underactive Neuron

Increase all synaptic strengths.

### Overactive Neuron

Decrease all synaptic strengths.

Goal:

Maintain stable firing levels.

---

# 11. Applications

## Stroke Rehabilitation

Uses plasticity to restore lost functions.

Examples:

* Constraint-Induced Movement Therapy (CIMT)

---

## PTSD Treatment

Traumatic memories become unstable during recall.

Intervening during reconsolidation may weaken:

* Fear memories
* PTSD symptoms

---

## Learning Optimization

Spaced repetition works because:

* LTP consolidation requires time

Hence:

```text
Spacing > Cramming
```

---

## Sleep & Memory

Sleep helps:

* Replay experiences
* Consolidate memories
* Remove weak synapses

According to:

### Synaptic Homeostasis Hypothesis

Wakefulness:

* Potentiation

Sleep:

* Downscaling and consolidation

---

# Quick Revision Sheet

### Neuroplasticity = Brain changes itself

### Hebb's Rule

Neurons that fire together wire together.

### LTP

Strengthens synapses.

### LTD

Weakens synapses.

### NMDA

Coincidence detector.

### AMPA

Controls synaptic strength.

### BDNF

Brain fertilizer.

### CREB

Memory gene switch.

### CaMKII

Master LTP kinase.

### Exercise

↑ BDNF
↑ Neurogenesis

### Sleep

Consolidates memories.

### Spaced Repetition

Biologically superior to cramming.

### Learning = Plasticity

### Memory = Stable Plasticity
