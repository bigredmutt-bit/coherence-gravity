# 📘 Coherence–Field Gravity (CFG)
### A Covariant Decoherence-Weighted Extension of General Relativity

This repository contains the full source tree, derivations, numerical tools, and supporting materials for the **Coherence–Field Gravity (CFG)** research program.

CFG is a scalar–tensor extension of General Relativity in which gravitational strength depends on the **local degree of quantum decoherence**. Fully decohered matter gravitates as in GR, while partially coherent systems source an additional long-range scalar potential with a universal \(1/r\) acceleration term in the ultra-weak regime.

The framework reproduces and unifies a wide range of galactic, cluster, and cosmological phenomena **without dark matter halos**, new particles, screening mechanisms, or interpolating functions.

---

## 📚 Coherence–Field Gravity Paper Suite (Zenodo)

The research program is documented as an 11-paper preprint series on Zenodo:

1. **Coherence–Field Gravity: A Scalar-Field Alternative to Dark Matter and Dark Energy**  
2. **Coherence–Field Gravity Research Program: Overview, Structure, and Roadmap**  
3. **Large-Scale Structure in Coherence–Field Gravity: Linear Growth, Matter Power Spectrum, and BAO Stability**  
4. **Gravitational Waves in Coherence–Field Gravity: Propagation, Dispersion, and Observational Signatures**  
5. **Cosmology of Coherence–Field Gravity: FRW Dynamics, Late-Time Acceleration, and Structure Growth**  
6. **Vacuum Energy Suppression in Coherence–Field Gravity: Decoherence Weighting and the Cosmological Hierarchy**  
7. **Falsifiable Predictions of Coherence–Field Gravity: A Clear Experimental and Observational Test Suite**  
8. **Observational Predictions of Coherence–Field Gravity: Galaxies, Clusters, and the Ultra-Weak Regime**  
9. **Numerical Evolution of the Coherence Field: Methods, Stability, and SPARC Validation**  
10. **Coherence Through Conversation: A Case Study in Human–AI Scientific Co-Discovery**  
11. **Coherence–Field Gravity Research Program (combined overview + roadmap preprint)**

> 🔗 **Zenodo collection:** see your Zenodo profile / search for “Coherence–Field Gravity” for the full, DOI-linked list of all papers.

Explicit DOIs (from Zenodo):

- Paper 1 Core Theory: **Coherence Gravity: A Covariant Decoherence-Weighted Extension of GR**  
  **DOI:** https://doi.org/10.5281/zenodo.17675790  

- Paper 2 Uniqueness + Cosmology:  
  **DOI:** https://doi.org/10.5281/zenodo.17715831  

- Case Study / Methodology (Human–AI Co-Discovery):  
  **DOI:** https://doi.org/10.5281/zenodo.17729096  

---

## 📂 Repository Structure

```text
coherence-gravity/
│
├── paper_1/                # Core theory: scalar–tensor action, field eqns, galaxy phenomenology
│   ├── main_merged.tex
│   ├── main.pdf
│   └── figures/
│
├── paper_2/                # Mathematical uniqueness + cosmological sector
│   ├── main_merged.tex
│   └── main.pdf
│
├── paper_3_to_10/          # Optional: per-paper folders if/when you add them
│   └── ...
│
├── derivations/            # Analytic derivation notes (01–…)
│   ├── 01_inevitable_1_over_r_term.tex
│   ├── 02_transition_radius_030_kpc.tex
│   ├── 03_why_decoherence_weighting_must_exist.tex
│   └── ...
│
├── solvers/                # Numerical tools, SPARC mapping, LSS scans (released progressively)
│   └── ...
│
├── docs/                   # Methodology and workflow (human–AI case study, PDFs, guides)
│   └── coherence_through_conversation.pdf
│
├── zenodo.json             # Metadata for Zenodo deposition
├── LICENSE
└── README.md               # You are here

