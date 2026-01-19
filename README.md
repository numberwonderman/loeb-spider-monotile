# Loeb Spider-Monotile Explorer
### Recursive Growth & The Search for Infinite Heesch Numbers

## Overview
This repository is dedicated to the computational search for a **Strictly Aperiodic Rep-tile Monotile**. 

Inspired by the study of **Heesch numbers**—the number of times a shape can be completely surrounded by copies of itself before a tiling failure occurs—this project explores a unique "Spider-like" growth model. The goal is to identify a shape that uses recursive, self-similar expansion to bypass the "Heesch trap," effectively reaching a Heesch number of **infinity**.

## The Theory: The Spider & The Crystal
Traditional tiling research often focuses on how shapes interlock like puzzle pieces. This project approaches the problem through the lens of **Biological/Crystal Growth**:

* **The Spider Analogy**: We hypothesize a shape with "limbs" that reach into the concavities of its neighbors.
* **Recursive Inflation**: Unlike standard tiles, this shape is a "rep-tile." It tiles around itself to create a larger version of itself (a "metatile").
* **Infinite Heesch Numbers**: If a shape can perfectly form a larger version of itself, it can, by definition, be surrounded infinitely, creating a fractal-like tiling of the entire plane.

## Technical Approach
The exploration uses a **JavaScript/HTML5 Canvas** engine to simulate "Spider Growth" through:
1.  **L-Systems (Lindenmayer Systems)**: Using recursive functions to define how "legs" sprout and rotate.
2.  **Logarithmic Scaling**: Applying scaling factors ($ln$) and rotational offsets to ensure that each generation of the shape "nests" into the previous one.
3.  **Visual Verification**: Real-time rendering of the boundary complexity to check for overlaps or gaps.

## How to Run the Experiment
1.  Clone this repository.
2.  Open `index.html` in any modern web browser.
3.  Adjust the constants in the script to evolve the shape:
    * `LEG_COUNT`: Changes the symmetry of the "Spider."
    * `SCALE_FACTOR`: Adjusts the "Inflation" rate.
    * `ROTATION`: Changes how the limbs interlock.

## Goals
- [ ] Catalog shapes with high Heesch numbers.
- [ ] Identify the "Sweet Spot" parameters for gapless recursive growth.
- [ ] Mathematically prove if a specific "Spider" shape is strictly aperiodic.

## Acknowledgments
This project was inspired by the work of **Casey Mann** and the discovery of the **"Einstein" (Aperiodic Monotile)** in 2023. Special thanks to the **Numberphile** community for fostering the obsession with Heesch numbers.

---
**Author:** Franklin Loeb  
**Year:** 2026
