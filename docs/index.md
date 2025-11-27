# Coherence–Field Gravity (CFG)
### A Covariant Decoherence-Weighted Extension of General Relativity

**Author:** Clifford Treadwell  
**Code & Papers:** [GitHub Repository](https://github.com/bigredmutt-bit/coherence-gravity)  
**Preprints:** Zenodo (search for “Coherence–Field Gravity” under author *Treadwell, Clifford*)

---

## What Is Coherence–Field Gravity?

Coherence–Field Gravity (CFG) is a scalar–tensor extension of General Relativity in which **gravitational strength responds to the local degree of quantum decoherence**.

- Fully decohered (classical) matter gravitates as in GR.  
- Partially coherent systems source an additional long-range scalar field.  
- In the outer-halo regime this field produces a universal \(A/r\) acceleration term, yielding flat rotation curves and the observed scaling relations.

CFG recovers standard GR in the appropriate limit and explains a wide range of galactic, cluster, and cosmological phenomena **without**:

- particulate dark matter halos,  
- interpolating functions,  
- screening mechanisms, or  
- a fundamental cosmological constant.

---

## The Coherence–Field Gravity Paper Suite

The research program is documented as an 11-paper preprint series on Zenodo:

1. **Coherence–Field Gravity: A Scalar-Field Alternative to Dark Matter and Dark Energy**  
   Core scalar–field framework, action, field equations, and galactic phenomenology.

2. **Coherence–Field Gravity Research Program: Overview, Structure, and Roadmap**  
   High-level summary of the full program, goals, and planned tests.

3. **Large-Scale Structure in Coherence–Field Gravity: Linear Growth, Matter Power Spectrum, and BAO Stability**  
   Linear perturbation theory, matter power spectrum, and BAO behavior.

4. **Gravitational Waves in Coherence–Field Gravity: Propagation, Dispersion, and Observational Signatures**  
   GW propagation in the coherence field and constraints from current/future detectors.

5. **Cosmology of Coherence–Field Gravity: FRW Dynamics, Late-Time Acceleration, and Structure Growth**  
   Modified Friedmann equations, effective dark energy, and growth of structure.

6. **Vacuum Energy Suppression in Coherence–Field Gravity: Decoherence Weighting and the Cosmological Hierarchy**  
   How decoherence-weighted sourcing suppresses vacuum energy and addresses the hierarchy.

7. **Falsifiable Predictions of Coherence–Field Gravity: A Clear Experimental and Observational Test Suite**  
   Concrete near- and medium-term tests that can confirm or rule out CFG.

8. **Observational Predictions of Coherence–Field Gravity: Galaxies, Clusters, and the Ultra-Weak Regime**  
   Rotation curves, clusters, lensing, and the universal ultra-weak acceleration term.

9. **Numerical Evolution of the Coherence Field: Methods, Stability, and SPARC Validation**  
   Numerical scheme, stability analysis, and galaxy fits against SPARC data.

10. **Coherence Through Conversation: A Case Study in Human–AI Scientific Co-Discovery**  
    Methodology paper documenting the human–AI workflow that produced the CFG program.

11. **Coherence–Field Gravity Research Program (Combined Overview / Roadmap Preprint)**  
    A compact overview tying together the full theoretical, numerical, and observational picture.

> 📎 For DOIs and downloads, see the Zenodo listing under *Treadwell, Clifford* or search for **“Coherence–Field Gravity”**.

---

## Repository & Derivations

All source and supporting material live in the public GitHub repository:

- 📦 **Repo:** <https://github.com/bigredmutt-bit/coherence-gravity>

Key components:

- `paper_1/`, `paper_2/`, … `paper_11/` — LaTeX sources and PDFs for each paper  
- `derivations/` — detailed analytic notes (e.g. inevitability of the \(1/r\) term, transition radius, mass scale \(M_0\), etc.)  
- `solvers/` — numerical tools, SPARC mapping scripts, and large-scale structure scans (released progressively)  
- `docs/` — workflow and methodology material, including the human–AI co-discovery case study

---

## Why CFG Matters

CFG suggests that:

- Gravitation is sensitive to **classicality**, not just mass–energy.  
- The familiar “missing mass” phenomena may instead reflect an emergent scalar response of spacetime to decoherence.  
- A single mass scale \(M_0\) and a universal \(A/r\) term can explain:
  - flat rotation curves,  
  - BTFR,  
  - RAR,  
  - cluster dynamics, and  
  - aspects of late-time cosmic acceleration.

The program is intentionally structured to be **falsifiable**. Paper 7 outlines specific observational and experimental checks capable of confirming or ruling out the framework.

---

## Reproducibility

Most papers can be rebuilt directly from the repository:

```bash
git clone https://github.com/bigredmutt-bit/coherence-gravity.git
cd coherence-gravity/paper_1

pdflatex main_merged.tex
bibtex main_merged
pdflatex main_merged.tex
pdflatex main_merged.tex

