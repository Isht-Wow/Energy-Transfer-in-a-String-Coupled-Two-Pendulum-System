# Energy Transfer in a String-Coupled Two-Pendulum System

This repository contains the full research article **“Energy Transfer in a String-Coupled Two-Pendulum System: Relation with String Slack and Pendulum Separation.”** The study investigates how geometric parameters influence energy transfer in a weakly coupled oscillatory system.

The article is provided as a static HTML document and can be viewed directly in a browser or through GitHub Pages.

---

## Overview

Coupled pendulum systems are classical models used to study **energy transfer, beat phenomena, and normal modes of oscillation** in mechanical systems. When two oscillators are weakly coupled, energy periodically transfers between them, producing observable amplitude modulation known as **beats**.

This investigation experimentally analyzes how the **configuration of the coupling string** affects the rate of energy exchange between two pendulums.

Two geometric parameters were systematically varied:

- **String Slack (S)** — the extra length of the horizontal coupling string relative to the separation of the supporting rods.
- **Pendulum Separation Distance (a)** — the horizontal distance between the suspension points of the two pendulums.

The primary measured quantity was **beat time**, defined as the time required for energy to transfer completely from one pendulum to the other and return.

---

![Experimental Setup](images/image1.png)
## Research Questions

The investigation was guided by the following hypotheses:

1. Increasing **string slack** reduces coupling strength and therefore **increases beat time**.
2. Increasing **pendulum separation distance** weakens the coupling force and therefore **increases beat time**.

---

## Experimental System

The apparatus consisted of:

- Two vertical support rods fixed parallel to each other  
- A horizontal **cotton coupling string** connecting the rods  
- Two identical pendulums suspended from this string  
- Pendulum length: **0.2 m**  
- Pendulum bob mass: **≈ 6.9 × 10⁻² kg**

Measurements were performed using a **digital stopwatch and smartphone timer**.

The system represents a **weakly coupled oscillator pair**, allowing observable beat phenomena without chaotic motion.

---

## Variables

### Independent Variables

**String Slack (S)**  
Difference between the coupling string length and the rod separation.

Range:
```
0 m → 0.40 m
```

**Pendulum Separation Distance (a)**  
Distance between suspension points.

Range:
```
0.04 m → 0.40 m
```

---

### Dependent Variable

**Beat Time (t)**  
Time required for complete energy transfer from one pendulum to the other and back.

Measurements were recorded in seconds.

---

### Controlled Variables

- Pendulum length
- Pendulum mass
- String material
- Knot configuration
- Initial displacement angle

Controlling these parameters ensured that changes in beat time resulted primarily from the two independent variables.

---

## Results

Experimental data indicated that beat time follows an **exponential relationship** with the system parameters:

```
t(S,a) = A e^k
```

where

```
k = αS + βa + γSa
```

and

- **S** = string slack  
- **a** = pendulum separation  
- **A** = system prefactor constant  

---

## Key Findings

### Effect of Pendulum Separation

As expected, increasing the distance between pendulums reduced the effective coupling strength and **increased beat time**, indicating slower energy transfer.

---

### Effect of String Slack

Contrary to the initial hypothesis, increasing slack **reduced beat time** in several trials.

This behavior suggests a transition between two coupling mechanisms:

1. **Tension-mediated coupling** (low slack)
2. **Wave-mediated coupling through string vibrations** (high slack)

Observations of increased string oscillations at large slack support this interpretation.

---

### Anomalous Behaviour

At low slack values combined with large separation distances, the system occasionally exhibited **two-cycle energy transfer patterns**. This behavior may arise from **resonance between pendulum motion and transverse string modes**.

---

## Significance

The experiment demonstrates that even simple mechanical systems can exhibit **complex coupling dynamics** when non-ideal elements such as flexible strings are introduced.

Understanding such behavior is relevant to several fields:

- nonlinear dynamics
- mechanical vibration systems
- energy transfer in coupled oscillators
- resonance phenomena in physical systems

---

## Repository Structure

```
.
├── ResearchArticle.html
└── images/
    ├── image1.png
    ├── image2.png
    ├── image22.jpg
    └── image24.jpg
```

All figures used in the paper are stored in the **images** directory and referenced using relative paths within the HTML document.

---

## Viewing the Article

You can view the research paper in two ways:

1. **Directly open the HTML file** in a web browser.
2. **Access the GitHub Pages site** once the repository is deployed.

Example URL:

```
https://USERNAME.github.io/REPOSITORY-NAME/
```

---

## Authors

- Siddharth Kamble  
- Kaushik Kanade  
- Advay Phadtare  
- Ishit Wavhal  

Supervisor: **Tushar Borotikar**

Jnana Prabodhini Prashala  
Sadashiv Peth, Pune, India

February 2026

---

## References

The study draws on prior research on coupled oscillators and nonlinear vibration systems, including work published in:

- *Physica A: Statistical Mechanics and its Applications*
- *Journal of Theoretical and Applied Mechanics*
- *Journal de Physique*
- *College Physics*