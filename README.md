# The Mount Wilson Paradigm: Restoring the Eternal Universe via the Temporal Equivalence Principle

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

![TEP-HUB: The Mount Wilson Paradigm](site/public/image.webp)

**Author:** Matthew Lukin Smawfield  
**Version:** v0.1 (Harare)  
**Date:** First published: 15 August 2026
**Status:** Preprint  

## Abstract

For nearly a century, the standard cosmological model ($\Lambda$CDM) has interpreted extragalactic redshift as a signature of spatial expansion. This interpretation, originating from Hubble's initial spatial projection of Humason's spectrographic data, relies entirely upon the unverified isochrony axiom—the assumption that the baseline chronometry of proper time is universally static across all cosmological epochs. This paper demonstrates that by adhering to a rigid temporal parameter, standard cosmology enforces a mathematical degeneracy that artificially projects temporal dynamics onto spatial geometry.

Utilizing the Temporal Equivalence Principle (TEP)—a bi-metric scalar-tensor framework where proper time is treated as a dynamical scalar field ($\Phi_\tau$)—this work formally dismantles the necessity of spatial expansion. An effective metric is derived wherein the matter Lagrangian couples to the temporal gradient, generating a local temporal amplification factor $\chi(\Phi_\tau, \Gamma_t)$. Under this formulation, cosmological redshift ($z$) is reinterpreted not as a spatial velocity or scale-factor stretching, but as the accumulated synchronization holonomy of photons crossing a gradient in the proper time field ($1+z = \chi_{\rm obs}/\chi_{\rm emit}$).

By reassigning these dynamics from the spatial metric ($g_{ij}$) to the temporal field, TEP offers a classical, field-based resolution to multiple modern astrophysical crises without requiring the invention of dark physics. We show that the $H_0$ tension naturally dissolves as an artifact of miscalibrated epoch-dependent chronometry. Furthermore, violating the isochrony axiom drastically extends the local physical time available in high-redshift ($z>10$) environments, elegantly resolving the anomalous overmassive galaxy assemblies recently observed by the JWST without breaking standard baryonic limits. The spatial expansion of the universe is thus reframed as the kinetic evolution of proper time.

## About TEP-HUB

This repository serves as the central hub and capstone synthesis for the Temporal Equivalence Principle (TEP) research program. It outlines the historical and theoretical rationale that necessitates the transition from a standard $\Lambda$CDM expanding spatial metric to a static, eternal universe governed by a dynamical proper time field.

### Core Manuscript

The manuscript source code is built via a componentized HTML pipeline located in `site/components/`. 
To build the static site locally:

```bash
cd site
npm run build
```

This compiles the final manuscript and updates the `dist/` directory.
