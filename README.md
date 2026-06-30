# Loeb Spider-Monotile Explorer
### Recursive Growth & The Search for Infinite Heesch Numbers

## Overview
This repository houses a computational search laboratory dedicated to exploring the boundaries of **Strictly Aperiodic Monotiles** and fractal space-filling curves. 

Inspired by **Heesch numbers**—the maximum number of times a shape can be completely surrounded by copies of itself before a tiling failure becomes mathematically inevitable—this project simulates a unique "Spider-like" growth model. The objective is to identify parametric configurations where recursive, self-similar expansion bypasses local "Heesch traps," effectively projecting toward a Heesch number of $\infty$.

---

## The Theory: The Spider & The Crystal
Traditional tiling research often analyzes how rigid polygons interlock along discrete boundaries. This project shifts the perspective toward **Biological & Crystallographic Growth Mechanics**:

* **The Spider Analogy:** We hypothesize a topological archetype featuring flexible "limbs" that dynamically nest into the concavities of adjacent generations.
* **Recursive Inflation:** The system explores quasi-self-similar scaling. If a clustering generation can perfectly bound a scaled-up macro-version of its fundamental unit, it implies a pathway to infinite global tiling.
* **Bypassing the Heesch Trap:** If the local collision rules yield a gapless, non-overlapping boundary at depth $d \to \infty$, the configuration represents a candidate for an unprecedented class of non-periodic plane-fillers.

---

## Technical Approach
The exploration engine leverages a high-performance **HTML5 Canvas / JavaScript** framework to simulate "Spider Growth" via three core pillars:

1. **Parametric L-Systems:** Recursive branching algorithms that map localized geometric transformations across scaling generations.
2. **Logarithmic Scaling & Rotation:** Utilizing precise scaling metrics $r \in (0, 1)$ and rotational offsets $\theta$ to optimize how successive generations nest into structural voids.
3. **Spatial Occupancy Hash-Mapping:** Real-time canvas pixel tracking via a high-precision discrete coordinate grid (`Set` hashing) to immediately flag self-intersection ("collisions") in red.



---

## Technical Parameters & Search Space

When launching the interactive laboratory, use the sidebar controls to manipulate the mutation matrix:

| Parameter | Range | Mathematical Function |
| :--- | :--- | :--- |
| **Leg Count** | $3 \to 12$ | Establishes the fundamental rotational symmetry ($2\pi / n$) |
| **Scale Factor** | $0.30 \to 0.70$ | Controls the decay rate of successive generation segment lengths |
| **Rotation** | $-\pi \to \pi$ | Sets the global angular twist applied to child nodes |
| **Knee / Ankle** | $-\pi \to \pi$ | Manipulates the localized internal folding and concavity layout |

---

## Roadmap & Research Goals
- [ ] **Catalog High Heesch Specimens:** Isolate and save slider configurations that survive to depth $d \ge 7$ without triggering global collision faults.
- [ ] **Map the "Sweet Spot" Phase Space:** Define the exact boundary boundaries where scale factors and angular transformations yield gapless, non-overlapping growth.
- [ ] **Rigorous Topological Proofs:** Determine whether a valid "Spider" boundary can be rigorously formalized as a strictly chiral aperiodic tile.

## Acknowledgments
This project is deeply indebted to the foundational work of **Dr. Casey Mann**, **Dr. Craig Kaplan**, and their co-authors during their historic 2023 discovery of the "Hat" and "Spectre" aperiodic monotiles (the Einstein tiles). 

---
**Author:** Franklin Loeb  
**Year:** 2026