# The Mount Wilson Paradigm: Restoring the Eternal Universe via the Temporal Equivalence Principle

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21954258.svg)](https://doi.org/10.5281/zenodo.21954258)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

![TEP-HUB: The Mount Wilson Paradigm](site/public/image.webp)

**Author:** Matthew Lukin Smawfield  
**Version:** v0.2 (Harare)  
**First published:** 15 August 2026 · **Last updated:** 30 September 2026  
**Status:** Preprint  
**DOI:** [10.5281/zenodo.21954258](https://doi.org/10.5281/zenodo.21954258)  
**Website:** [https://mlsmawfield.com/tep/hub/](https://mlsmawfield.com/tep/hub/)  
**Paper Series:** TEP Series: Paper 30 (TEP Hub)

## Abstract





Cosmological redshift is standardly interpreted as a geometric signature of spatial expansion. This interpretation requires a fundamental assumption that is defined herein as the Isochrony Axiom: the premise that, after gravitational and kinematic effects derived from the spacetime metric have been included, the calibration of every matter clock is fully exhausted by that single metric, so that no independently dynamical field may rescale matter proper time across cosmological epochs. Standard single-metric cosmology closed the temporal sector before the redshift was interpreted. In this paper, it is demonstrated that when matter-clock calibration is permitted an independent dynamical scalar degree of freedom (ϕ), the measured cosmological redshift (z) can be rigorously derived from the ratio of matter-clock calibrations between emission and observation on a static spatial manifold. The scalar field defines a spatiotemporal clock geometry—the Temporal Topology—whose homogeneous evolution governs cosmological calibration and whose inhomogeneous disformal connection can become non-integrable, producing synchronization holonomy. Using the canonical matter metric of the Temporal Equivalence Principle (TEP), tilde g_μν = A²(ϕ) g_μν + B(ϕ) nabla_μϕ nabla_νϕ, the Mount Wilson Equivalence Theorem is proven: on a homogeneous, static gravitational background, with universal matter coupling and A² - Bdotϕ² > 0, the endpoint redshift 1+z = A_0/A_em is observationally degenerate with the FLRW relation 1+z = a_0/a_em at the level of the redshift observable alone. TEP is distinguished from a mere conformal rewriting by its separate matter and gravitational propagation sectors, making multi-messenger observations a principal inter-sector discriminator. The historical data from Mount Wilson Observatory are re-examined to separate the documented spectral displacements from the subsequent spatial inferences, demonstrating that the observed dynamics are consistent with a temporal reinterpretation on a static spatial manifold; the historical analysis is an argument for underdetermination — redshift alone does not select between the interpretations — not an argument for TEP. The theorem itself establishes an observational degeneracy, not an empirical discrimination: the Isochrony Axiom is a consequence of the standard minimally coupled action rather than an arbitrary closure, the static gravitational ansatz (a = 1) is imposed on the homogeneous branch rather than derived from the gravitational field equations, and the empirical distinction between TEP and a conformal rewriting requires a dimensionless inter-sector observable — the standard-siren deviation Δ_siren(z) = d_L GW(z)/d_L EM(z) - 1 — whose canonical radiation rule is Ξ(z)=1/(1+z), hence Δ_siren=1/(1+z)-1 (Paper 22). The full canonical population likelihood, including mass and selection mapping, remains to be evaluated; this paper supplies the redshift-degeneracy theorem. Precision GNSS chronometry, pulsar scintillation, and Lunar Laser Ranging are identified as the empirical instruments capable of testing the temporal sector locally. The eternal-branch completion is assembled from companion analyses (TEP-BBN, TEP-TH, and Papers 11, 12, 18, 26), each of which must independently stand; the contribution of the present paper is the degeneracy theorem, the identification of the discriminating observables, and the resulting globally consistent framework for an eternal, deterministic continuum, supplying the common mathematical resolution to the questions that Einstein separated.


## About TEP-HUB

This repository serves as the central hub and capstone synthesis for the Temporal Equivalence Principle (TEP) research program. It outlines the historical and theoretical rationale that necessitates the transition from a standard ΛCDM expanding spatial metric to a static, eternal universe governed by a dynamical proper time field.

## Manuscript Sections

1. Abstract
2. Prologue: The Photograph
3. 1. The Evidence
4. 2. The Interpretation
5. 3. The Hidden Closure
6. 4. The Mount Wilson Equivalence Theorem
7. 5. Einstein's Unfinished Continuum
8. 6. From Degeneracy to the Eternal Branch
9. 7. The Arrival of Chronometric Astronomy
10. Epilogue: Return to Mount Wilson
11. Appendices
12. References
13. Data Availability & Reproducibility

## Site Build

```bash
cd site
npm run build
```

This generates:
- `site/dist/index.html` — static manuscript
- `30-TEP-HUB-v0.2-Harare.md` — root markdown manuscript

## PDF Generation

```bash
python scripts/generate_site_pdf.py --quality high --wait-time 8
```

Generates `30-TEP-HUB-v0.2-Harare.pdf` in both the root and `site/public/docs/`.

## Project Structure

```
TEP-HUB/
├── scripts/              # PDF generation and utility scripts
│   ├── generate_site_pdf.py
│   └── utils/            # PDF processing and metadata utilities
├── site/                 # Manuscript site
│   ├── components/       # HTML components (edit these)
│   ├── dist/             # Built static site (auto-generated)
│   ├── public/           # Static assets, PDF, sitemap
│   ├── build.js          # Site build script
│   ├── html-to-markdown.js
│   ├── index.html        # Source HTML template
│   └── manifest.json     # Site manifest
├── manuscripts/          # Markdown manuscripts synced from the TEP series
├── 30-TEP-HUB-v0.2-Harare.md  # Auto-generated root manuscript
└── 30-TEP-HUB-v0.2-Harare.pdf # Generated PDF
```

## License

Creative Commons Attribution 4.0 International License (CC BY 4.0) — see the [LICENSE](LICENSE) file.

## The TEP Research Program

| Paper | Repository | Title | DOI |
|-------|-----------|-------|-----|
| **Paper 0** | [TEP](https://github.com/matthewsmawfield/TEP) | Temporal Equivalence Principle: Dynamic Time & Emergent Light Speed | [10.5281/zenodo.16921911](https://doi.org/10.5281/zenodo.16921911) |
| **Paper 1** | [TEP-GNSS](https://github.com/matthewsmawfield/TEP-GNSS) | Global Time Echoes: Distance-Structured Correlations in GNSS Clocks | [10.5281/zenodo.17127229](https://doi.org/10.5281/zenodo.17127229) |
| **Paper 2** | [TEP-GNSS-II](https://github.com/matthewsmawfield/TEP-GNSS-II) | Global Time Echoes: 25-Year Analysis of CODE Precise Clock Products | [10.5281/zenodo.17517141](https://doi.org/10.5281/zenodo.17517141) |
| **Paper 3** | [TEP-GNSS-RINEX](https://github.com/matthewsmawfield/TEP-GNSS-RINEX) | Global Time Echoes: Raw RINEX Consistency Test | [10.5281/zenodo.17860166](https://doi.org/10.5281/zenodo.17860166) |
| **Paper 4** | [TEP-GL](https://github.com/matthewsmawfield/TEP-GL) | Temporal-Spatial Coupling in Gravitational Lensing: A Reinterpretation of Dark Matter Observations | [10.5281/zenodo.17982540](https://doi.org/10.5281/zenodo.17982540) |
| **Paper 5** | [TEP-GTE](https://github.com/matthewsmawfield/TEP-GTE) | Global Time Echoes: Empirical Synthesis | [10.5281/zenodo.18004832](https://doi.org/10.5281/zenodo.18004832) |
| **Paper 6** | [TEP-UCD](https://github.com/matthewsmawfield/TEP-UCD) | Temporal Topology Saturation Scale: Cross-Scale Consistency of $\rho_T$ | [10.5281/zenodo.18064365](https://doi.org/10.5281/zenodo.18064365) |
| **Paper 7** | [TEP-RBH](https://github.com/matthewsmawfield/TEP-RBH) | The Soliton Wake: Exploring RBH-1 as a Temporal Topology Candidate | [10.5281/zenodo.18059250](https://doi.org/10.5281/zenodo.18059250) |
| **Paper 8** | [TEP-SLR](https://github.com/matthewsmawfield/TEP-SLR) | Global Time Echoes: Optical-Domain Consistency Test via Satellite Laser Ranging | [10.5281/zenodo.18064581](https://doi.org/10.5281/zenodo.18064581) |
| **Paper 9** | [TEP-EXP](https://github.com/matthewsmawfield/TEP-EXP) | What Do Precision Tests of General Relativity Actually Measure? | [10.5281/zenodo.18109760](https://doi.org/10.5281/zenodo.18109760) |
| **Paper 10** | [TEP-COS](https://github.com/matthewsmawfield/TEP-COS) | Temporal Equivalence Principle: Suppressed Density Scaling in Globular Cluster Pulsars | [10.5281/zenodo.18165798](https://doi.org/10.5281/zenodo.18165798) |
| **Paper 11** | [TEP-H0](https://github.com/matthewsmawfield/TEP-H0) | The Cepheid Bias: Resolving the Hubble Tension | [10.5281/zenodo.18209702](https://doi.org/10.5281/zenodo.18209702) |
| **Paper 12** | [TEP-JWST](https://github.com/matthewsmawfield/TEP-JWST) | Temporal Equivalence Principle: A Unified Resolution to the JWST High-Redshift Anomalies | [10.5281/zenodo.19000827](https://doi.org/10.5281/zenodo.19000827) |
| **Paper 13** | [TEP-WB](https://github.com/matthewsmawfield/TEP-WB) | Temporal Equivalence Principle: Temporal Shear Recovery in Gaia DR3 Wide Binaries | [10.5281/zenodo.19102061](https://doi.org/10.5281/zenodo.19102061) |
| **Paper 14** | [TEP-GNSS-MGEX](https://github.com/matthewsmawfield/TEP-GNSS-MGEX) | Global Time Echoes: MGEX Multi-GNSS Clock Replication, 2025–2026 | [10.5281/zenodo.20572726](https://doi.org/10.5281/zenodo.20572726) |
| **Paper 15** | [TEP-EFA](https://github.com/matthewsmawfield/TEP-EFA) | Temporal Equivalence Principle: Temporal Shear in the Earth Flyby Anomaly | [10.5281/zenodo.19454862](https://doi.org/10.5281/zenodo.19454862) |
| **Paper 16** | [TEP-J0437](https://github.com/matthewsmawfield/TEP-J0437) | Temporal Equivalence Principle: Synchronization Holonomy in Pulsar Scintillation | [10.5281/zenodo.19454620](https://doi.org/10.5281/zenodo.19454620) |
| **Paper 17** | [TEP-LLR](https://github.com/matthewsmawfield/TEP-LLR) | Temporal Equivalence Principle: Lunar Laser Ranging and the Nordtvedt Effect | [10.5281/zenodo.19446028](https://doi.org/10.5281/zenodo.19446028) |
| **Paper 18** | [TEP-HC](https://github.com/matthewsmawfield/TEP-HC) | Temporal Equivalence Principle: Native hi_class Conformal Implementation, Linear Perturbation Closure, and CMB Acoustic Peak Preservation | [10.5281/zenodo.20572722](https://doi.org/10.5281/zenodo.20572722) |
| **Paper 19** | [TEP-LENS](https://github.com/matthewsmawfield/TEP-LENS) | Temporal Equivalence Principle: A Blind-Prediction Residual Test in Multiply-Imaged Supernovae | [10.5281/zenodo.20572720](https://doi.org/10.5281/zenodo.20572720) |
| **Paper 23** | [TEP-QF](https://github.com/matthewsmawfield/TEP-QF) | Temporal Equivalence Principle: The Dirac Limit of Dynamical Proper Time | [10.5281/zenodo.20572697](https://doi.org/10.5281/zenodo.20572697) |
| **Paper 26** | [TEP-C0](https://github.com/matthewsmawfield/TEP-C0) | Temporal Equivalence Principle: A Covariant Alternative to Cosmic Expansion | [10.5281/zenodo.20370143](https://doi.org/10.5281/zenodo.20370143) |
| **Paper 27** | [TEP-TH](https://github.com/matthewsmawfield/TEP-TH) | Temporal Equivalence Principle: Temporal Horizon Cosmology and the Absence of a Physical Big Bang Singularity | [10.5281/zenodo.20723059](https://doi.org/10.5281/zenodo.20723059) |
| **Paper 28** | [TEP-BH](https://github.com/matthewsmawfield/TEP-BH) | Temporal Equivalence Principle: Black Holes and the Temporal Horizon | [10.5281/zenodo.21677826](https://doi.org/10.5281/zenodo.21677826) |
| **Paper 29** | [TEP-BBN](https://github.com/matthewsmawfield/TEP-BBN) | Temporal Equivalence Principle: Dynamical Proper Time and the Illusion of Primordial Deuterium | [10.5281/zenodo.21841147](https://doi.org/10.5281/zenodo.21841147) |
| **Paper 30** | [TEP-HUB](https://github.com/matthewsmawfield/TEP-HUB) | The Mount Wilson Paradigm: Restoring the Eternal Universe via the Temporal Equivalence Principle | [10.5281/zenodo.21954258](https://doi.org/10.5281/zenodo.21954258) |
