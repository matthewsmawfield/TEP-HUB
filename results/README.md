# Results Traceability — TEP-HUB (Paper 30, Harare)

This directory documents the traceability chain for the numerical and theoretical results cited in `TEP-HUB` ("The Mount Wilson Paradigm: Einstein, Hubble, and the Chronometric Cosmology"). `TEP-HUB` is a foundational historical and theoretical synthesis manuscript; it does not generate new primary numerical outputs. Every quantitative benchmark and empirical claim originates from the specialized repositories of the TEP Series (documented in Appendix D of the manuscript) and traces to their respective `results/` directories.

## Upstream Source Repositories

| Paper | Repository | Local Path | Primary Quantitative / Theoretical Role in TEP-HUB |
|-------|-----------|------------|-----------------------------------------------------|
| Paper 0 | `TEP` | `../TEP` | Two-metric action, selected two-branch kinetic sector ($k \simeq 16.03$), unstretched-space temporal metric, and PPN screening (`results/outputs/step_52_*` to `step_81_*`) |
| Paper 1 | `TEP-GNSS` | `../TEP-GNSS` | Multi-center GNSS correlation length ($\lambda_T \approx 4{,}200$ km) and terrestrial saturation anchor $\rho_T \approx 20\text{ g cm}^{-3}$ |
| Paper 4 | `TEP-GL` | `../TEP-GL` | Temporal Shear ($\Gamma_t$), unstretched-space temporal refraction ($n(\mathbf x)$), and dynamical/optical Phantom Mass |
| Paper 6 | `TEP-UCD` | `../TEP-UCD` | Universal $R_T \propto M^{1/3}$ saturation scaling and SPARC RAR synthesis (`results/outputs/step_10_two_branch_sparc_rar.json`) |
| Paper 10 | `TEP-COS` | `../TEP-COS` | Globular-cluster millisecond pulsar spin-down suppression and SN Ia stretch response |
| Paper 11 | `TEP-H0` | `../TEP-H0` | Cepheid period-luminosity environmental calibration and $H_0$ distance-ladder reconciliation |
| Paper 12 | `TEP-JWST` | `../TEP-JWST` | High-redshift galaxy assembly and chronometric age-excess correlations |
| Paper 18 | `TEP-HC` | `../TEP-HC` | Linear perturbation closure (`hi_class`), acoustic scale, growth factor $f\sigma_8$, and CMB lensing (`results/07_mcmc_summary_full.json`, `results/step_21_cdm_free_lensing.json`) |
| Paper 19 | `TEP-LENS` | `../TEP-LENS` | Strong-lensing time-delay residuals and unstretched-space Fermat refraction (`results/outputs/step_64_*`) |
| Paper 22 | `TEP-LVK` | `../TEP-LVK` | Standard-siren distance scaling $\Xi(z)=1/(1+z)$ and GWTC-3 BBH chirp-mass population test |
| Paper 26 | `TEP-C0` | `../TEP-C0` | Background chronometric redshift $1+z=A_0/A_{\rm em}$, Pantheon+ distance modulus, and DESI BAO reconciliation (`results/current_model_comparison.json`) |
| Paper 27 | `TEP-TH` | `../TEP-TH` | Temporal horizon structure, high-$z$ cosmic time accumulation, and effective $(w_0, w_a)$ projection |
| Paper 28 | `TEP-BH` | `../TEP-BH` | Strong-field horizon-free temporal wells and compact-object ringdown/shadow bounds |
| Paper 29 | `TEP-BBN` | `../TEP-BBN` | Eternal baryonic cycling, D/H absorber spectroscopy (`results/tep_bbn_summary.json`), and $^4\text{He}$ attractor |
| Paper 31 | `TEP-VOID` | `../TEP-VOID` | Empirical falsification of local KBC-void / MOND expansion solutions on native Pantheon+ coordinates |
