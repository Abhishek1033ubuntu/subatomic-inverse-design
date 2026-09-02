# Inverse Material Design via Sub-Atomic Vector Screening (IMD-SACS)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22250331.svg)](https://doi.org/10.5281/zenodo.22250331)
[![Framework Architecture](https://img.shields.io/badge/Architecture-Sub--Atomic%20Vector%20Engine-blue.svg)](https://github.com/Abhishek1033ubuntu/subatomic-inverse-design)
[![Co-Authored with AI](https://img.shields.io/badge/Co--Authored%20with-Gemini%20Thought%20Partner-7057ff.svg)](#acknowledgements)
[![Feasibility](https://img.shields.io/badge/Feasibility-Practically%20Achievable-brightgreen.svg)](#technical-disclosure--feasibility-boundaries)

---



## Overview
This repository provides a 5-phase first-principles heuristic framework designed to screen, identify, and invert candidate elements, alloys, and bio-organic matrices for targeted macroscopic properties (e.g., thermal phase stability, melting point, elastic modulus).

The engine parameterizes atomic and molecular constituents using a 5-dimensional **Sub-Atomic State Vector** ($\vec{S}$):

$$\vec{S} = \begin{bmatrix} Z^* \\ \text{Valence Topology} \\ \Delta\chi \\ \alpha \\ r_0 \end{bmatrix}$$

Phase stability and state transitions are governed by the cohesive scaling ratio $\Gamma(T) = \frac{E_{\text{cohesion}}}{k_B T}$, where $\Gamma \ge 15.0$ indicates solid-state phase stability.

---

## Technical Disclosure & Feasibility Boundaries

> **PRACTICALLY FEASIBLE - EXISTING TECH:** All material matches screened by this engine (such as structural carbon steel alloys and photopolymerized GelMA hydrogel scaffolds) correspond to real-world materials manufacturable via conventional pyrometallurgy, chemical reduction, or bio-fabrication techniques.
> 
> **THEORETICAL MODEL:** The unified sub-atomic state vector equation and scaling ratio $\Gamma$ represent a lightweight computational heuristic designed for rapid first-pass screening before executing high-level Density Functional Theory (DFT) or laboratory synthesis.

---

## Core Features & Case Studies

1. **Inorganic Metallurgy Synthesis (Soil-to-Steel Matrix):**
   - Deconstructs raw oxide feeds ($\text{Fe}_2\text{O}_3$, $\text{SiO}_2$, trace $\text{C}$) to isolate constituent vectors.
   - Re-engineers an interstitial carbon-steel matrix targeting $T_m = 1510^\circ\text{C}$ ($\Gamma = 759.01$ at $25^\circ\text{C}$).

2. **Bio-Organic Scaffold Mapping (Articular Cartilage Graft):**
   - Adapts vector space for aqueous biological hydrogel environments ($\vec{S}_{\text{bio}}$).
   - Matches articular cartilage targets ($E_{\text{modulus}} = 1050\text{ kPa}$, $45\text{-day}$ degradation) to photocrosslinkable GelMA hydrogel networks ($\Gamma_{\text{bio}} = 15.0$).

---

## Requirements & Installation

- Python 3.8+
- NumPy
- Pandas

```bash
pip install numpy pandas

```
## Acknowledgements & Collaboration

This repository and its mathematical state-vector engine were co-developed through an iterative theoretical synthesis between **Abhishek Singh** and **Google Gemini** acting as an R&D Thought Partner. 

* **Theoretical Formulation & Project Strategy:** Abhishek Singh
* **Mathematical Derivations & Code Architecture:** AI Assistance via Gemini (Google AI)
