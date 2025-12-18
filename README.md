# Bridge Paper 3 — Gravity from Geometric Non-Closure

**Title:** *Gravity from Geometric Non-Closure*  
**Subtitle:** *A φ-Scaled Scalar-Attractor Framework for Curvature, Entropy, and the Arrow of Time*  
**Date:** December 4, 2025  
**Author:** Lee Smart (Vibrational Field Dynamics Institute)  
**Contact:** contact@vibrationalfielddynamics.org • X: @vfd_org

## What this repository contains

This repository hosts **Bridge Paper 3 (BP3)**: a conservative, academic bridge paper that proposes an **effective/emergent** origin for gravitational curvature from **geometric non-closure** in locally symmetric cell complexes.

BP3 connects:
- **BP2** (geometric contraction / configurational entropy) → continuum lift via Laplace–Beltrami flow  
- **Defect accumulation** (non-closure density) → an **effective curvature response** compatible with Einstein limits  
- A **geometric arrow of time** arising from monotonic configurational entropy production and irreversible defect history

This work is framed as **effective** and **Einstein-compatible** (not a replacement for GR).

## Paper

- **PDF:** `paper/Gravity_from_Geometric_Non_Closure.pdf`
- **LaTeX source:** `paper/bridge_paper_3.tex`
- **Figures:** TikZ figures are included inline (or under `paper/figures/` if separated).

## Repository structure

.
├── paper/
│ ├── Gravity_from_Geometric_Non_Closure.pdf
│ ├── bridge_paper_3.tex
│ ├── figures/ # optional (if TikZ sources are split out)
│ └── bibliography.bib # optional
├── CHANGELOG.md
├── CITATION.cff
├── LICENSE
└── README.md

nginx
Copy code

## Build instructions (LaTeX)

From `paper/`:

```bash
pdflatex bridge_paper_3.tex
bibtex bridge_paper_3.aux   # only if bibliography is enabled
pdflatex bridge_paper_3.tex
pdflatex bridge_paper_3.tex
If you use latexmk:

bash
Copy code
latexmk -pdf bridge_paper_3.tex
Relationship to Bridge Papers 1 & 2
BP1: Harmonic field model of consciousness (Orch-OR extension)

BP2: Geometric contraction conjecture (configurational entropy, φ scaling)

BP3 (this paper): Gravity from geometric non-closure (effective curvature response)

BP3 is written to stand alone; it does not require the reader to have followed online posts.

Scope and non-claims
This paper does not claim:

a replacement of General Relativity

a complete theory of quantum gravity

cosmological dynamics (e.g., no Friedmann expansion history)

biological consciousness mechanisms or wavefunction collapse derivations

It proposes an effective correspondence between defect density and curvature and provides a roadmap toward full discrete-to-continuum rigor (Regge/DEC).

How to cite
See CITATION.cff. For convenience:

Lee Smart, Gravity from Geometric Non-Closure: A φ-Scaled Scalar-Attractor Framework for Curvature, Entropy, and the Arrow of Time, Bridge Paper 3, December 4, 2025.

License

Text and figures are released under Creative Commons Attribution 4.0 International (CC BY 4.0) unless otherwise noted. See LICENSE.

Links

X / Twitter: @vfd_org

Contact: contact@vibrationalfielddynamics.org
