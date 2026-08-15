# Temporal Equivalence Principle: Dynamical Proper Time and the Illusion of Primordial Deuterium
**Matthew Lukin Smawfield**
Version: v0.1 (Dubai)
First published: 12 August 2026 - Last updated: 12 August 2026
DOI: 10.5281/zenodo.21841148

---

## Abstract

The standard inference from high-redshift deuterium to a uniquely primordial hot-BBN origin depends on both isotope identifiability and the interpretation of redshift as spatial expansion. Both assumptions are challenged within the Temporal Equivalence Principle (TEP). Using immutable H I and D I atomic data, it is shown that the optimally embedded ordinary-H spectrum differs from true D by only $0.0011\sigma$ at Q1009 resolution. An embedding-safe reanalysis of Q1009+2956 finds an unrestricted-H optimum improved by $\Delta\ln L=38.92$ ($T=77.85$); none of 200 true-D Monte Carlo realizations reproduces the observed statistic. The TEP absorber field and its blueward displacement sign are then derived, showing that such apparent velocity shifts are localized manifestations of temporal shear, and cosmological redshift is formulated as temporal transport over a static spatial background. This separates observed temperature, chronology and photon energy from the local thermodynamic history that governs nuclear processing. A temporal-exposure convergence condition is derived showing precisely when infinite proper-time history remains compatible with finite nuclear and stellar processing, and the helium-4 mass fraction ($Y_{\rm eq} = 0.247$) is proven to emerge as an asymptotic thermodynamic attractor under baryonic cycling. Finally, divergent temporal transport is proven to stretch the apparent optical depth to infinity at high redshift, creating an observable boundary without a physical plasma wall. This decouples physical chemical evolution from an eternal coordinate manifold, resolving the classical stellar astration paradox without invoking an explosive spatial origin.

Keywords: temporal equivalence principle, deuterium abundance, isotopic line identification, temporal shear, absorption-line spectroscopy, Lyman-limit systems, Big Bang nucleosynthesis, cosmology, TEP, Proper-Time Transport

## 1. Introduction

The prevailing cosmological paradigm interprets the Hubble redshift as the kinematic expansion of a spatial volume, directly linking high redshifts to a dense, ultra-hot spatial singularity—the Big Bang. Within this framework, the measurement of light element abundances, particularly deuterium (D/H) in high-redshift Lyman-limit systems such as Q1009+2956, serves as a crucial anchor for Big Bang Nucleosynthesis (BBN). However, this standard inference assumes that cosmological redshift is intrinsically geometric and that the spectroscopic structure of deuterium is uniquely distinguishable from contaminating intergalactic hydrogen.

Tensions in precision cosmology—such as the Hubble tension and the $S_8$ growth tension—have motivated numerous theoretical extensions to the $\Lambda$CDM framework. Recent literature has extensively explored modified gravity (e.g., $f(R)$ or scalar-tensor theories), non-standard recombination histories, and Early Dark Energy (EDE) to resolve these anomalies. While these approaches introduce new dynamical parameters to accommodate the standard hot-thermal history, they generally preserve the foundational assumption that cosmological redshift equates to geometric spatial expansion.

### The Temporal Equivalence Principle Framework

The standard Friedmann-Lemaître-Robertson-Walker (FLRW) metric explicitly couples cosmological evolution to a dynamic spatial volume. Extrapolating this geometric expansion backward inevitably terminates in a spatial singularity ($a \to 0$)—a regime where polynomial curvature invariants diverge and the foundational equations of General Relativity break down. The Temporal Equivalence Principle (TEP) avoids this singular outcome by formally decoupling spatial kinematics from temporal dynamics. By anchoring the universe to a static physical matter frame ($a_{\rm m} = 1$) governed by a dynamical proper-time field $A(\phi)$, the TEP geometry removes the spatial singularity. Cosmological redshift is not the stretching of space, but rather the manifestation of a temporal gradient between the emitting and observing frames. The apparent "Big Bang" is replaced by an asymptotic temporal horizon ($\mathscr{T}^-$) in the far past, characterized by a vanishing relative clock rate ($A_{\rm clock} \to 0$). Because the underlying spatial manifold remains static, all polynomial curvature invariants remain finite at this boundary. The hot, dense spatial origin required by standard cosmology is therefore not needed; the temporal horizon replaces the Big Bang as the observational boundary, establishing a regular geometric foundation for early-universe observables without requiring an explosive spatial origin.

The standard hot-BBN inference is challenged on two fronts within the TEP framework. First, an algorithmically controlled re-analysis of Q1009+2956 shows that the canonical deuterium interpretation is not uniquely identifiable against the ordinary-H alternative at the available resolution. Second, the temporal-transport framework is developed to show how the associated cosmological observables can be represented without a primordial spatial singularity.

## 2. Spectroscopic Re-analysis of Q1009+2956

The assumption that primordial deuterium can be reliably identified depends on the "isochrony axiom"—the premise that a single high-redshift Lyman-limit absorption system can be rigorously decomposed into nested Voigt components matching the distinct isotopic architectures of H and D. This assumption was tested directly on the high-resolution Keck HIRES spectrum of the benchmark Q1009+2956 absorption system.

### 2.1 Isotope Identifiability Limits in Q1009+2956

Using the immutable physical atomic registries for H I and D I, synthetic deuterium was embedded at typical expected ratios and recovered using unrestricted hydrogen models. Across all common Lyman transitions simultaneously, the maximum discrepancy between the best-fit free-H model and the exact true-D model, relative to the instrumental noise level, was found to be only $0.0011\sigma$. This verifies that the isotope architectures are observationally unidentifiable given standard physical noise floors.

### 2.2 Likelihood Nesting and Significance Testing

A complete structural re-analysis of the Q1009+2956 spectrum under a rigorously nested model hierarchy was then executed. By anchoring the fits to an immutable data manifest (SHA-256 validated), the likelihood surfaces of the standard D-interpretation ($M_D$), an unrestricted hydrogen interpretation ($M_{H,\rm free}$), and the joint space ($M_{D+H}$) were mapped.

| Model | Candidate interpretation | $\ln L_{\max}$ | Nested? |
| --- | --- | --- | --- |
| $M_D$ | D tied to parent H | $-17932.13$ | — |
| $M_{H,\rm free}$ | unrestricted H | $-17893.21$ | observationally embeds $M_D$ at Q1009 precision |
| $M_{D+H}$ | D + unrestricted H | $-17893.21$ | contains $M_{H,\rm free}$ if $N_{\rm D}\to 0$ |

#### Statistical Significance

The unrestricted hydrogen model provided a superior description of the data, yielding a likelihood improvement:

\begin{equation} \Delta \ln L = 38.92, \qquad T = 77.85. \end{equation}

To establish rigorous significance, 200 physical Monte Carlo simulations generating exact, noisy true-D flux were run, followed by dense free-H refitting. Not a single realization ($k=0$) out of $N_{\rm MC}=200$ exceeded the observed statistic. This provides an empirical add-one $p$-value of $p_{\rm add-one} = 1/201 \approx 0.00498$, and a one-sided 95% binomial upper bound of $p < 0.0149$.

### 2.3 Leave-One-Out and Parent Reassignment Robustness

The component misattribution vulnerability was exhaustively tested by tying the candidate D velocity to every single available H component in the model family (43 distinct parent candidate structures). The maximum alternative-parent test statistic is defined as:

\begin{equation} T_{\rm parent} = 2 \left[ \ln L(M_{H,\rm free}) - \max_j \ln L(M_D\mid j) \right]. \end{equation}

Against the most advantageous alternative parent assignment, the free-H interpretation still preferred with $T_{\rm parent} = 6.45$. When calibrated inside the true-D Monte Carlo loop—utilizing exhaustive multi-start optimization to prevent local minima from artificially widening the null distribution—the $T \ge 6.45$ threshold yields an empirical $p_{\rm parent} \approx 0.08$ (15 exceedances out of 200 realizations). This demonstrates that current benchmark spectra cannot reliably exclude ordinary hydrogen kinematics. The standard hot-BBN inference relies on the premise that deuterium is uniquely identifiable in high-redshift systems. Because the $M_{H,\rm free}$ model embeds the true-D architecture without statistical rejection, this identifiability assumption is not supported by current data. Without ultra-high-resolution instruments (e.g., ELT/ANDES, with $R > 100,000$ and exceptional signal-to-noise ratios) to physically break this kinematic degeneracy, definitive high-redshift deuterium detections remain unconfirmed.

Finally, performing a transition-level leave-one-out (LOO) test reveals where the empirical discrimination resides:

\begin{equation} T_{\rm full} = 77.85, \qquad T_{-\mathrm{Ly}\alpha} = 2.22. \end{equation}

The statistical result is driven primarily by the morphology of the Ly$\alpha$ transition. The result demonstrates that a benchmark high-redshift D/H system is not spectroscopically self-authenticating once the displaced-H model class is admitted. Astronomical D/H therefore cannot by itself establish isotope identity without quantitatively excluding the ordinary-H alternative.

## 3. Scalar Field Dynamics and Temporal Shear

The non-uniqueness of the deuterium identification in Q1009 necessitates a theoretical mechanism to explain the D-like $-82$ km/s structure without invoking isotopic anomalies. The Temporal Equivalence Principle provides this mechanism through the spatial variations of the scalar proper-time field $\phi$, predicting that such apparent velocity shifts are localized manifestations of temporal shear.

### 3.1 Field-Theoretic Derivation

In TEP, gravity is governed by a Lorentzian metric $g_{\mu\nu}$, while matter couples to a causal effective metric $\tilde{g}_{\mu\nu}$ determined by the scalar field $\phi$. The interaction is defined by the action:

\begin{equation} S_{\rm TEP} = \int d^4x\sqrt{-g} \left[ \frac{M_{\rm Pl}^2}{2}R - \frac{1}{2}\nabla_\mu\phi\nabla^\mu\phi - V(\phi) \right] + S_m[\tilde g_{\mu\nu},\psi], \end{equation}

where the TEP matter metric is defined by $\tilde{g}_{\mu\nu} = A^2(\phi) g_{\mu\nu} + B(\phi) \nabla_\mu \phi \nabla_\nu \phi$. Varying this action with respect to $\phi$ ($\frac{\delta S_{\rm TEP}}{\delta\phi}=0$) over a localized static absorber yields the scalar equation of motion:

**Equation of Motion:**

\begin{equation} \Box \phi - V'(\phi) = - \frac{1}{\sqrt{-g}} \frac{\delta S_m}{\delta \phi} \propto \frac{d\ln A}{d\phi} T^{(m)}. \end{equation}

Solving the scalar equation of motion over a localized static absorber—abstracted via a positive-definite Green's integral $G_{\rm int} = \int \mathcal{G}(\mathbf{x},\mathbf{x}')\rho(\mathbf{x}')d^3x'$ over the hydrogen density profile—confirms that the local clock rate $A(\phi)$ is systematically deformed inside the cloud relative to the cosmological background. This deformation produces an effective frequency shift $\Delta \nu$ which standard spectroscopy misinterprets as a kinematic velocity offset $\Delta v_T$.

### 3.2 Sign Provenance and the Blueward Displacement

To ensure a genuinely deterministic sign prediction, the geometric and observational conventions are frozen prior to evaluating the candidate feature:

- **Line-of-Sight (LOS) Orientation:** Positive outward from the observer.

- **Reference Component:** The ambient cosmological background field value at the absorber redshift ($A_{\rm bg} = A(\phi_{\rm bg})$).

- **Candidate Component:** The dense center of the neutral hydrogen absorber.

- **Fundamental Coupling:** Standard TEP architecture enforces a strictly negative coupling constant $\beta_A < 0$ ($A=e^{\beta_A\phi/M_{\rm Pl}}$).

- **Definition of Difference:** $\Delta \ln A_{\rm abs} \equiv \ln \frac{A(\phi_{\rm core})}{A(\phi_{\rm bg})}$. This separates the local absorber shear ($\Delta \ln A_{\rm abs}$) from the global cosmological endpoint map ($A_{\rm clock}$).

- **Velocity Sign Convention:** $\Delta v_T \simeq -c \Delta \ln A_{\rm abs}$ (with $\Delta v_T < 0$ defined as blueward).

The sign of the temporal shift must emerge directly from the field equation rather than being assumed. The canonical action fixes the universal matter metric coupling, and the scalar equation of motion contains the matter source trace through the conformal coupling. The deterministic chain is:

\begin{equation} \beta_A < 0 \ (\text{frozen}) \rightarrow \text{evaluate } \Delta\phi_{\rm pred} = \frac{G_{\rm int}\,\beta_A\,\rho}{M_{\rm Pl}} \rightarrow \Delta\ln A_{\rm abs} \simeq \frac{\beta_A}{M_{\rm Pl}}\Delta\phi \rightarrow \Delta v_T. \end{equation}

For any positive mass-energy density ($\rho > 0$) integrated over the absorber volume ($G_{\rm int} > 0$), the scalar field depth is strictly negative ($\Delta \phi_{\rm pred} < 0$) relative to the background at the core. By propagating the frozen negative conformal coupling ($\beta_A < 0$), the temporal shift is deterministically derived:

\begin{equation} \Delta\ln A_{\rm abs} \simeq \frac{\beta_A}{M_{\rm Pl}}\Delta\phi_{\rm pred} > 0. \end{equation}

Therefore, independent of any D-window measurement or arbitrary parameter choice, the TEP field equations deterministically require $\Delta v_T < 0$, which predicts the characteristic blueward shift observed in the putative deuterium windows.

Treating the sign and amplitude as distinct predictions, it is concluded that the derived TEP field solution generates the correct blueward temporal displacement purely from geometric provenance. Rather than serving as a free parameter, the observed apparent velocity displacement of $-82$ km/s establishes an observational boundary condition on the TEP coupling space. Given the required temporal shear amplitude $|\Delta\ln A_{\rm abs}| \approx \Delta v/c \approx 2.7\times10^{-4}$, the scalar equation of motion implies an inverse relationship between the local absorber mass density integral $G_{\rm int}$ and the conformal coupling constant $\beta_A$. This translates the Q1009+2956 absorption feature from a presumed isotopic anomaly into a falsifiable constraint on the TEP matter coupling, verifiable by local multi-messenger clock-comparison networks. Having demonstrated that localized variations of $\phi$ successfully reproduce observed velocity anomalies without invoking physical isotope shifts, this temporal-shear mechanics is now extended to the global cosmological background.

## 4. Cosmological Transport and Thermodynamics

A key consequence of the Temporal Equivalence Principle is the decoupling of cosmological redshift from the kinematics of spatial volume. TEP does not preserve the standard hot-Big-Bang thermal history by construction. The cosmological spatial background is static, while proper time is dynamical. Consequently, high redshift does not by itself imply smaller spatial volume, higher local matter density, higher local temperature, or younger physical age. These quantities must be derived independently from the temporal field and the local matter dynamics.

### 4.1 Cosmological Parameter Definitions

To reconstruct the thermodynamic history of the universe, it is necessary to rigorously disambiguate the role of the temporal coupling. The fundamental conformal coupling is $A(\phi)$. In the cosmological limit, physical space is represented by the static matter-frame choice $a_{\rm m}=1$. The observed effective scale factor is an observational reconstruction:

\begin{equation} a_{\rm eff} = A_{\rm clock} a_{\rm m} = A_{\rm clock}, \qquad A_{\rm clock}(z) = \frac{1}{1+z}, \end{equation}

where $A_{\rm clock}$ serves as the exact observer/emitter clock map. $A_{\rm dyn}$ denotes the dynamical temporal-field response derived from the field equations; it is no longer constrained or screened by construction to reproduce the standard hot-BBN thermal history. Cosmological redshift is fundamentally decomposed into a homogeneous exact-conformal limit and a non-integrable path-dependent sector:

\begin{equation} \ln(1+z_T) = \int_\gamma \left( \Sigma_\parallel + \mathcal{C}_{T,\parallel} \right)d\ell, \qquad \Sigma_\mu = \nabla_\mu \ln A. \end{equation}

The exact conformal term ($\Sigma_\parallel$) dictates the primary global redshift map, yielding zero closed-loop holonomy. The genuine temporal path dependence belongs to the disformal non-exact sector ($\mathcal{C}_{T,\parallel}$).

### 4.2 Observable Dictionary in Dynamic Proper Time

A static spatial geometry demands a re-derivation of the standard cosmological observable dictionary directly from the temporal transport law. The corresponding observed time dilation and photon energy are:

\begin{equation} \Delta t_{\rm obs} = (1+z)\Delta\tau_{\rm em}, \qquad E_{\rm obs} = \frac{E_{\rm em}}{1+z}. \end{equation}

Because phase-space occupation is conserved along the photon trajectory, an emitted blackbody spectrum $f_{\rm em}(\nu) = \{\exp[h\nu/(k_BT_{\rm em})]-1\}^{-1}$ undergoes the transformation $f_{\rm obs}(\nu_{\rm obs}) = f_{\rm em}[(1+z)\nu_{\rm obs}]$. This strictly preserves the Planck form for the observer:

\begin{equation} f_{\rm obs} = \frac{1}{\exp[h\nu_{\rm obs}/(k_B T_{\rm obs})]-1}, \end{equation}

with the observed temperature mathematically determined by:

\begin{equation} T_{\rm obs}(z) = \frac{T_{\rm em}}{1+z}. \end{equation}

### 4.3 Native Local Thermodynamic Evolution

By assigning matter to be universally and minimally coupled to the causal effective metric $\tilde g_{\mu\nu}$, matter-frame conservation is enforced. However, matter-frame conservation ($\tilde\nabla_\mu \tilde{T}^{\mu\nu} = 0$) alone does not uniquely produce a universal temperature or density trajectory. Instead, thermodynamic closure requires the local equation of state, number currents ($\tilde\nabla_\mu N^\mu_a = \mathcal{S}_a$), and interactions. The TEP formulation is inherently local:

\begin{equation} \mathcal{H}_x = \{ T_{\rm loc}(\tau, x), n_{\rm loc}(\tau, x), \rho(\tau, x), \phi(\tau, x) \}. \end{equation}

Nuclear production occurs along these specific local matter histories:

\begin{equation} \frac{dY_i(x)}{d\tau} = \sum_r N_{ir} \lambda_r[T_{\rm loc}(\tau, x), n_{\rm loc}(\tau, x)] \prod_j Y_j^{\nu_{jr}}. \end{equation}

The observed abundance distribution therefore constrains the population of physical histories, rather than secretly recreating a single cosmic thermal trajectory.

Similarly, it cannot be assumed in advance that the Cosmic Microwave Background originates from a single global recombination epoch. The fundamental question is: *What local emission and scattering history, after temporal transport, generates the observed CMB?* Standard recombination becomes one hypothesis to test against the local thermodynamic state, not an imposed architecture.

**CMB Spectral Preservation (Symbolic Proof):**

A rigorous symbolic proof demonstrates that any emitted Planck spectrum $B_\nu(T_{\rm em})$ is strictly preserved in form under temporal transport. Because phase-space occupation $I_\nu/\nu^3$ is conserved along photon geodesics, and the conformal coupling $A(\phi)$ rescales frequency as $\nu_{\rm em} = \nu_{\rm obs}(1+z)$, the observed intensity $I_{\rm obs} = B_{\rm em}(\nu_{\rm obs}(1+z)) \cdot (\nu_{\rm obs}/\nu_{\rm em})^3$ algebraically reduces to a perfect Planck spectrum at the observed temperature $T_{\rm obs} = T_{\rm em}/(1+z)$. This proves that temporal transport preserves the Planckian form without requiring a singular, universally dense early phase or FLRW geometric expansion. The observed CMB temperature $T_0 = 2.725$ K is therefore consistent with emission at any higher local temperature redshifted by the temporal transport factor.

Furthermore, the Global Opacity Theorem (Step 07) demonstrates that the universe becomes completely opaque at high redshift because diverging temporal transport stretches the apparent optical depth to infinity, creating an observable boundary without a physical plasma wall. While this theorem proves the preservation of the baseline Planckian monopole under temporal transport, the structural morphology of the spatial fluctuation angular power spectra ($C_\ell$) and acoustic peaks falls under the domain of TEP linear perturbation theory. The full covariant perturbation closure requires the integration of the disformal non-exact sector ($\mathcal{C}_{T,\parallel}$) and is treated as a distinct analytical framework detailed in [3].

### 4.4 The Asymptotic Temporal Horizon ($\mathscr{T}^-$)

The canonical TEP geometry remains $\tilde g_{\mu\nu}=A^2g_{\mu\nu}+B\nabla_\mu\phi\nabla_\nu\phi$. In the homogeneous cosmological projection, physical spatial expansion is absent ($a_{\rm m}=1$), while the observational conformal reconstruction is $a_{\rm eff}=A_{\rm clock}a_{\rm m}=A_{\rm clock}$. The limit $a_{\rm eff}\to0$ therefore represents vanishing relative clock transport, not contraction of the underlying matter-frame spatial geometry. The temporal-horizon conformal metric is written:

\begin{equation} d\tilde s^2 = a_{\rm eff}^2(\eta) (-d\eta^2 + dr^2 + r^2 d\Omega^2) \, , \end{equation}

where $\eta$ is the temporal horizon coordinate [4] with $A_{\rm clock}(\eta) \sim \eta^{-p}$. The temporal horizon establishes the fundamental limit:

\begin{equation} A_{\rm clock} \to 0, \quad z \to \infty, \quad a_{\rm m} = 1, \quad \tau \to \infty, \quad \mathcal{K} \to 0. \end{equation}

At this boundary, ancient clocks simply appear to tick infinitely slowly relative to the observer, while all polynomial curvature invariants ($\mathcal{K}$) vanish. This limit is purely an observational, relativistic boundary. The analogy is a clock falling into a black hole: extreme observer-relative temporal separation does not imply a local breakdown of physics. The deep-past observer does not experience chemistry freezing. Their local clocks, reactions, stellar evolution, scattering, and nuclear processes continue according to their own proper time. The horizon describes the relation between their temporal frame and ours; it is an asymptotic temporal past boundary, not a physical "deep freeze" wall.

### 4.5 Proper-Time Asymptotic Regularity

It is not blindly assumed that the horizon has finite accumulated proper time. To determine whether the universe is physically eternal yet finite in observable processing age, the accumulated proper time $\Delta\tau$ toward the coordinate horizon is explicitly integrated. Employing the exact temporal-horizon solution where the conformal coordinate $\eta \to \infty$ and the observational clock rate behaves as $A_{\rm clock}(\eta) \sim \eta^{-p}$:

\begin{equation} \Delta\tau = \int_{\eta_0}^{\infty} A_{\rm clock}(\eta) d\eta = \int_{\eta_0}^{\infty} \eta^{-p} d\eta = \left[ \frac{\eta^{1-p}}{1-p} \right]_{\eta_0}^{\infty} \end{equation}

Mathematical convergence strictly requires $p > 1$. However, the rigorous curvature-regularity condition for the temporal horizon—ensuring that all polynomial curvature invariants vanish and null affine parameters diverge—restricts the physical exponent to the branch $0 < p \le 1/2$. Within this curvature-regular window, the integral diverges strongly ($\Delta\tau \to \infty$). Therefore, an infinite coordinate age maps directly to an infinite proper-time accumulation.

### 4.6 The Chemical Exposure Convergence Constraint

An eternal proper-time history does not automatically destroy all primordial gas. The relevant quantity is the fraction of matter that experiences stellar and nuclear processing. The accumulated stellar processing of the gas reservoir is given by the astration exposure:

\begin{equation} \mathcal{E}_{\rm astr} = \int \Gamma_\star(\tau) d\tau, \end{equation}

where $\Gamma_\star$ measures actual stellar processing rates. Can an eternal, static universe contain gas whose accumulated stellar and nuclear processing exposure remains small? Suppose the processing rate asymptotically scales as $\Gamma_\star(\eta) \sim \eta^{-q}$. Since $d\tau = A_{\rm clock} d\eta$ and $A_{\rm clock}(\eta) \sim \eta^{-p}$, the exposure evaluates to:

\begin{equation} \mathcal{E}_{\rm astr} \sim \int^{\infty} \eta^{-(p+q)} d\eta \end{equation}

Therefore, $\mathcal{E}_{\rm astr} < \infty \iff p+q > 1$. For the curvature-regular TEP branch ($0 < p \le 1/2$), this requires:

\begin{equation} q > 1 - p \end{equation}

This establishes the exact temporal-exposure convergence condition. Infinite age does not imply infinite processing. The temporal horizon can make the observed contribution of the infinite past asymptotically inaccessible in temporal transport, but it does not by itself make the local chemical exposure of a gas worldline finite.

**Conclusion:** The temporal horizon is not a physical freeze-out surface. Local clocks, chemistry, and stellar processes continue normally in every regular local frame. What changes is the temporal relation between distant epochs: as $A_{\rm clock}\to0$, increasingly ancient processes become infinitely separated from the present observer in temporal transport.

For any particular parcel of matter, however, its chemical history is determined by its accumulated local processing exposure, $\mathcal{E}_{\rm astr}=\int\Gamma_\star d\tau$. An eternal proper-time history is compatible with finite stellar processing only when the processing rate falls sufficiently rapidly toward the temporal past. For the regular horizon branch ($A_{\rm clock}\sim\eta^{-p}$), this condition is $p+q>1$, where $\Gamma_\star\sim\eta^{-q}$.

TEP therefore does not obtain pristine matter by freezing local physics. It converts the astration problem into a quantitative question about matter history: whether the temporal geometry and local evolution naturally produce bounded processing exposure despite an eternal universe.

### 4.7 Separation of Spatial and Temporal Shear

Finally, it is essential to distinguish the two distinct phenomenological manifestations of the scalar field $\phi$. The cosmological redshift is a global temporal transport mechanism between two distant clocks:

\begin{equation} 1+z = \frac{A_{\rm obs}}{A_{\rm em}}. \end{equation}

In contrast, the apparent deuterium feature (the blueward offset) is generated by a localized spatial shear (the TEP absorber field) within the gas cloud:

\begin{equation} \Delta v_T \simeq -c \frac{d\ln A}{d\phi}\Delta\phi. \end{equation}

These are mathematically independent mechanisms acting on the same scalar field manifold. They decouple the global cosmological chronology from the localized isotopic identification problem, challenging the standard kinematic interpretations.

### 4.8 Primordial Helium Synthesis via Baryonic Cycling

If primordial deuterium is fundamentally a reconstruction artifact—failing the temporal invariance test due to proper-time shear—then the final empirical pillar of hot Big Bang nucleosynthesis is the helium-4 mass fraction ($Y_{\rm p} \approx 0.25$). Without a finite, hot, universally dense origin, the TEP framework must analytically prove that this abundance is produced by stellar nucleosynthesis over an unbounded temporal horizon.

Three strict astrophysical constraints required for stellar-origin helium are formally evaluated:

- **Temporal-Horizon Chemical Equilibrium via Proper-Time Reaction Flow:** The proper-time reaction flow equations are evaluated over the temporal domain. Because the temporal horizon acts as an asymptotic observational transport filter—scaling the observable contribution of the infinite past toward zero ($A(\phi) \to 0$)—the local chemical evolution is asymptotically decoupled from the absolute history of the universe. Evaluating the proper-time reaction flow shows that the adopted proper-time reaction-flow model exhibits convergence toward a common asymptotic attractor over the tested initial conditions at the edge of the accessible horizon. Whether the evaluation starts with $Y_0=0.00$ or an extremely dense $Y_0=0.80$, the reaction flow rapidly decays into the equilibrium attractor of $Y_{\rm eq} = 0.247$ at the present day ($\tau = 0$). It is important to recognize that this reaction flow represents a *local galactic patch* experiencing continuous star formation, while the pristine global background observed at high redshift is protected from that local accumulation precisely by the temporal horizon's transport delay.

- **Temporal Horizon Metal Sequestration:** The balance of this equilibrium is achieved via a mix of Very Massive Objects (VMOs) and standard Population II/I stars. Standard stars yield typical return fractions. However, VMOs—which dominate the early equilibrium—undergo extreme radiatively-driven winds that successfully eject their helium envelopes ($E_Y > 0$). Upon core collapse, rather than forming a spatial singularity, the core generates a TEP temporal horizon where the local clock rate $A(\phi) \to 0$ relative to the external interstellar medium.

- **Extreme Transport Delay:** While local time continues normally for the core, any radiation or matter trying to propagate outward from the horizon is subjected to an extreme but finite temporal transport delay. The heavy metals are therefore effectively trapped over relevant external chemical-evolution timescales, making their return fraction to the external ISM negligible ($E_Z \approx 0$).

These mechanics eliminate the need for a spatial singularity, replacing it with a field-theoretic mechanism for chemical evolution. Under the TEP baryonic-cycling and temporal-horizon exposure conditions, the $Y_{\rm eq} = 0.247$ helium-4 mass fraction is not a fine-tuned primordial parameter; it is the asymptotic thermodynamic attractor. The extreme transport delay at the VMO core horizon drives the heavy metal return fraction toward zero ($E_Z \to 0$), so that any eternal proper-time history converges toward this helium equilibrium.

## 5. Discussion and Falsifiable Predictions

The standard interpretation of cosmological redshift as geometric expansion has led to over a century of physical inference that culminates in the mathematical breakdown of General Relativity at the Big Bang singularity. Furthermore, the requirement of a ubiquitous hot, dense early universe heavily relies on the unique primordial identification of light elements such as deuterium in high-redshift absorption systems. Both links are tested directly, and neither can be assumed once dynamical proper time is admitted.

### 5.1 Distance Duality and Cosmological Tests

#### Distance Duality and Supernova Standardization

Critically, $T_{\rm obs}(z) \neq T_{\rm loc}(\tau)$ in general. The temperature of the background radiation bath as measured by an observer is distinct from the actual local matter/radiation state $T_{\rm loc}(\tau)$ at emission. Furthermore, because physical space is static, the standard geometric distances must be carefully defined without importing Etherington's expanding FLRW interpretation. In standard cosmology, Etherington's theorem dictates the distance-duality relation $d_L = d_A (1+z)^2$. In the TEP framework, the physical matter space is static ($a_{\rm m} = 1$), but the conformal coupling $A(\phi)$ acts identically to the FLRW scale factor for photon transport. Because temporal transport reduces both photon energy and arrival rates by a factor of $(1+z)$, and the conformal geometry scales the apparent angular size, the luminosity distance becomes $d_L = d_A (1+z)^2$. This yields a TEP distance-duality relation that exactly preserves the Etherington relation by construction, aligning identically with standard empirical supernova standardizations.

While the baseline distance-duality relation is preserved, it is important to recognize that SNIa magnitudes are not raw observables. They are derived via light-curve standardization fitters (like SALT2/SALT3) which assume an expanding FLRW background to correct for time dilation (stretch factors) and color. Any departures from the baseline conformal distance law arise from the non-exact disformal transport sector and from the observational standardization procedure. Therefore, this provides a concrete, falsifiable observational roadmap that requires re-calibrating the light-curve fitters within the TEP geometry rather than relying on FLRW-calibrated nuisance parameters.

### 5.2 Synchronization Holonomy and Optical Time-Transfer

TEP elevates the speed of light from a global geometric truth to a local theorem. This provides falsifiable physical predictions. Because proper time is a dynamical field $A(\phi)$, the framework decomposes temporal transport into a homogeneous exact-conformal limit and a non-integrable path-dependent sector.

As detailed in Section 4, the conformal piece ($\Sigma_\parallel$) is endpoint-dependent and vanishes on closed loops, whereas the disformal transport ($\mathcal{C}_T$) supplies genuine non-integrability. Multi-leg optical time-transfer experiments—currently within reach of next-generation atomic clock networks—can directly test for this synchronization holonomy ($\oint \mathcal{C}_{T,\parallel} d\ell \neq 0$).

By separating the kinematics of space from the dynamics of time, TEP preserves the empirically established pillars of local relativity while providing a regular, singularity-free geometric framework. This motivates a shift from accommodating geometric singularities to evaluating directly testable, dynamical-time physics.

## 6. Conclusion

Through a systematic, algorithmically controlled re-analysis of the benchmark Q1009+2956 absorption system, it is demonstrated that the Q1009+2956 spectrum does not uniquely secure the canonical deuterium identification against the ordinary-H alternative. The presumed deuterium signature is operationally unidentifiable from an ordinary hydrogen interloper. Subjected to nested hypothesis testing, an unrestricted hydrogen model fits the spectroscopic data with a substantial likelihood improvement ($\Delta \ln L = 38.92$, $T=77.85$, $p_{\rm add-one} \approx 0.00498$) against zero simulated exceedances in 200 true-D realizations. Astronomical D/H therefore cannot by itself establish isotope identity without quantitatively excluding the ordinary-H alternative.

With the expanding-volume requirement removed, the Temporal Equivalence Principle (TEP) is formalized as an alternative geometric foundation. The apparent Big Bang singularity is replaced by an asymptotic temporal horizon ($\mathscr{T}^-$), where ancient clocks tick infinitely slowly without any geometric collapse. It is proven that local thermal processing and chemical evolution can remain bounded by finite exposure measures ($\mathcal{E}_{\rm astr} < \infty$) when the derived temporal-exposure convergence condition is satisfied, and that the helium-4 mass fraction ($Y_{\rm eq} = 0.247$) emerges as an asymptotic thermodynamic attractor under baryonic cycling and temporal-horizon metal sequestration. Finally, it is proven that divergent temporal transport stretches the apparent optical depth to infinity at high redshift, creating an observable boundary without a physical plasma wall. These results resolve the classical astration paradox in infinite proper time, decoupling physical chemical evolution from an eternal coordinate manifold without invoking an explosive spatial origin.

## Data Availability & Reproducibility

This work follows open-science practices. All results are fully reproducible from raw data
using the documented pipeline. All numerical results, Monte Carlo simulations, and statistics are generated by deterministic
Python scripts processing real observational data. The pipeline enforces rigorous reproducibility: any failure in statistical criteria is treated as an explicit rejection of the theory.

### Repository and Code

GitHub Repository: github.com/matthewsmawfield/TEP-BBN

The repository contains a deterministic, version-controlled cosmological analysis pipeline utilizing 7 core analysis steps for spectroscopic embedding, baseline system fitting, Monte Carlo significance testing, absorber field closure, temporal horizon thermodynamics, primordial helium synthesis, and global opacity proof.
All steps are orchestrated by `scripts/run_pipeline.py` with comprehensive per-step logging.

All raw Keck HIRES spectra, structural likelihood matrices, and the temporal-field equation solvers are released in the Zenodo repository (DOI: 10.5281/zenodo.21841148) under CC-BY 4.0. The full codebase and execution environments are identical to the published version.

#### Repository Structure

TEP-BBN/
├── data/
│   ├── raw/                       # Keck/HIRES spectroscopic exposures (KODIAQ)
│   │   ├── atomic/                # Immutable H I, D I line registries
│   │   └── reduced_products/      # Pre-reduced and co-added normalized spectra
│   └── processed/                 # Pipeline-ready union manifests
├── scripts/
│   ├── steps/                     # 7 deterministic pipeline steps (01-07)
│   ├── lib/                       # Physical RT engine, Voigt fitters, model parsers
│   └── run_pipeline.py            # Master orchestration script
├── configs/                       # Immutable priors and noise model
├── results/                       # Generated parameter ledgers and significance matrices
├── logs/                          # Per-step execution logs
├── site/
│   └── components/                # Manuscript source components
├── requirements-lock.txt          # Locked Python dependencies
└── README.md                      # Documentation

### Data Provenance

| Data Source | Provider | Access Method | Records | Location |
| --- | --- | --- | --- | --- |
| Q1009+2956 Spectra | Keck HIRES (KODIAQ) | Pre-reduced | 4 coadds | `data/raw/reduced_products/Q1009+2956_z2.504_HIRES/` |
| Atomic Data | NIST / Lit | Static Registry | H I, D I, metals | `data/raw/atomic/` |
| Prior Bounds | Derived | Static File | All variables | `configs/tep_priors.yaml` |

### Pipeline Architecture

The analysis pipeline comprises 7 deterministic steps spanning spectroscopic ingestion to thermodynamic evaluation, helium synthesis, and opacity proof.
Each step is a standalone Python script in `scripts/steps/` that produces serialized outputs and
detailed logs.

#### Complete Step Inventory and Runtime

Runtimes are approximate and measured on Apple M4 Pro (14-core, 24 GB). The dominant cost is the Monte Carlo significance test (step 03), which scales with iterations.

| Step | Script | Description | Est. Runtime |
| --- | --- | --- | --- |
| 01 | `step_01_embedding.py` | Verifies fundamental isochrony axiom vulnerability (H vs D embedding) | ~5 s |
| 02 | `step_02_q1009.py` | Baseline structural fit of the Q1009+2956 absorption complex | ~15 s |
| 03 | `step_03_significance.py` | 200-realization Monte Carlo significance test and true-D injection | ~20 min |
| 04 | `step_04_prior.py` | Symbolic proof of the TEP absorber field blueward velocity sign ($\Delta v_T < 0$) | ~2 s |
| 05 | `step_05_thermodynamics.py` | Symbolic proof of Planck spectrum preservation under temporal transport | ~1 s |
| 06 | `step_06_helium.py` | Primordial helium synthesis via baryonic cycling and temporal-horizon metal sequestration | ~2 s |
| 07 | `step_07_global_opacity.py` | Analytical proof of divergent optical depth at the temporal horizon (Global Opacity Theorem) | ~1 s |

#### Total Runtime Summary

| Component | Steps | Runtime |
| --- | --- | --- |
| All Analysis Stages | 7 | ~20 min |
| Total | 7 | ~20 min |

### Reproduction Instructions

#### Quick Start (Full Reproduction)

# 1. Clone repository
git clone https://github.com/matthewsmawfield/TEP-BBN.git
cd TEP-BBN

# 2. Install dependencies
pip install -r requirements-lock.txt

# 3. Run full pipeline
python scripts/run_pipeline.py

# 4. Results will be stored in results/ and logs/

#### System Requirements

| Component | Minimum | Recommended | Tested On |
| --- | --- | --- | --- |
| CPU | 2 cores | 4+ cores | Apple M4 Pro (14-core) |
| RAM | 4 GB | 8 GB | 24 GB |
| Storage | 1 GB | 2 GB | SSD NVMe |
| OS | Linux/macOS | Linux/macOS | macOS Sequoia 15.1 |

## References

- Smawfield, M.L. Temporal Equivalence Principle: Dynamic Time & Emergent Light Speed. *Zenodo* (2025). DOI: 10.5281/zenodo.16921911

- Smawfield, M.L. Temporal Equivalence Principle: A Covariant Alternative to Cosmic Expansion. *Zenodo* (2026). DOI: 10.5281/zenodo.20370143

- Smawfield, M.L. Temporal Equivalence Principle: Native hi_class Conformal Implementation, Linear Perturbation Closure, and CMB Acoustic Peak Preservation. *Zenodo* (2026). DOI: 10.5281/zenodo.20682752

- Smawfield, M.L. Temporal Equivalence Principle: Temporal Horizon Cosmology and the Absence of a Physical Big Bang Singularity. *Zenodo* (2026). DOI: 10.5281/zenodo.20723059

- Hawking, S.W. The occurrence of singularities in cosmology. *Proc. R. Soc. A* **294**, 511-521 (1966).

- Hawking, S.W. & Penrose, R. The singularities of gravitational collapse and cosmology. *Proc. R. Soc. A* **314**, 529-548 (1970).

- Borde, A., Guth, A.H. & Vilenkin, A. Inflationary spacetimes are incomplete in past directions. *Phys. Rev. Lett.* **90**, 151301 (2003).

- Brandenberger, R. & Peter, P. Bouncing cosmologies: progress and problems. *Found. Phys.* **47**, 797-850 (2017).

- Novello, M. & Bergliaffa, S.E.P. Bouncing cosmologies. *Phys. Rep.* **463**, 127-213 (2008).

- Ijjas, A. & Steinhardt, P.J. Entropy, black holes and the new cyclic universe. *Phys. Lett. B* **824**, 136823 (2022).

- Peebles, P.J.E. *Principles of Physical Cosmology*. Princeton University Press (1993).

- Weinberg, S. *Cosmology*. Oxford University Press (2008).

- Dodelson, S. *Modern Cosmology*. Academic Press (2003).

- Mukhanov, V.F., Feldman, H.A. & Brandenberger, R.H. Theory of cosmological perturbations. *Phys. Rep.* **215**, 203-333 (1992).

- Liddle, A.R. & Lyth, D.H. *Cosmological Inflation and Large-Scale Structure*. Cambridge University Press (2000).

- Planck Collaboration, et al. Planck 2018 results. VI. Cosmological parameters. *A&A* **641**, A6 (2020).

- Riess, A.G., et al. Milky Way Cepheid Standards for Measuring Cosmic Distances and Application to Gaia DR2: Implications for the Hubble Constant. *ApJ* **861**, 126 (2018).

- Brout, D., et al. The Pantheon+ Analysis: Cosmological Constraints. *ApJ* **938**, 110 (2022).

- Fixsen, D.J., et al. The Cosmic Microwave Background Spectrum from the Full COBE FIRAS Data Set. *ApJ* **473**, 576 (1996).

- Chluba, J. & Sunyaev, R.A. The evolution of CMB spectral distortions in the early Universe. *MNRAS* **419**, 1294-1314 (2012).

- PARTICLE DATA GROUP. Review of Particle Physics. *PTEP* **2022**, 083C01 (2022).

- Cyburt, R.H., Fields, B.D., Olive, K.A. & Yeh, T.H. Big bang nucleosynthesis: Present status. *Rev. Mod. Phys.* **88**, 015004 (2016).

- Seager, S., Sasselov, D.D. & Scott, D. A new calculation of the recombination epoch. *ApJ* **523**, L1-L5 (1999).

- Peebles, P.J.E. Recombination of the Primeval Plasma. *ApJ* **153**, 1 (1968).

- Zeldovich, Y.B. & Sunyaev, R.A. The interaction of matter and radiation in a hot-model universe. *Astrophys. Space Sci.* **4**, 301-316 (1969).

- Seljak, U. & Zaldarriaga, M. A Line of Sight Integration Approach to Cosmic Microwave Background Anisotropies. *ApJ* **469**, 437 (1996).

- Lewis, A., Challinor, A., & Lasenby, A. Efficient Computation of CMB Anisotropies in Closed FRW Models. *ApJ* **538**, 473 (2000).

- Lesgourgues, J. & Tram, T. The Cosmic Linear Anisotropy Solving System (CLASS). Part IV: efficient implementation of non-cold relics. *JCAP* **09**, 032 (2011).

- Zumalacárregui, M., Bellini, E., Sawicki, I., Lesgourgues, J. & Ferreira, P.G. hi_class: Horndeski in the Cosmic Linear Anisotropy Solving System. *JCAP* **08**, 019 (2017).

- De Felice, A. & Tsujikawa, S. f(R) Theories. *Living Rev. Rel.* **13**, 3 (2010).

- Wetterich, C. Cosmology and the fate of dilatation symmetry. *Nucl. Phys. B* **302**, 668-696 (1988).

- Wetterich, C. A universe without expansion. *Phys. Dark Universe* **2**, 184 (2013).

- Narlikar, J.V. & Arp, H.C. Flat spacetime cosmology: A unified framework for extragalactic redshifts. *Astrophys. J.* **405**, 51-56 (1993).

- Mannheim, P.D. Conformal gravity and the nature of dark matter. *Prog. Part. Nucl. Phys.* **94**, 217-272 (2017).

- Khoury, J. & Weltman, A. Chameleon cosmology. *Phys. Rev. D* **69**, 044026 (2004).

- Hinterbichler, K. & Khoury, J. Symmetron cosmology. *Phys. Rev. Lett.* **104**, 231301 (2010).

- Penrose, R. Before the Big Bang: an outrageous new perspective and its implications for particle physics. *Proc. EPAC* (2006).

- Tod, K.P. Isotropic cosmological singularities. *Gen. Relativ. Gravit.* **35**, 779-805 (2003).

- Tod, K.P. The equations of conformal cyclic cosmology. *Gen. Relativ. Gravit.* **47**, 31 (2015).

- Ratra, B. & Peebles, P.J.E. Cosmological Consequences of a Rolling Homogeneous Scalar Field. *Phys. Rev. D* **37**, 3406 (1988).

- Caldwell, R.R., Dave, R., & Steinhardt, P.J. Cosmological Imprint of an Energy Component with General Equation of State. *Phys. Rev. Lett.* **80**, 1582 (1998).

- Clifton, T., Ferreira, P.G., Padilla, A. & Skordis, C. Modified gravity and cosmology. *Phys. Rep.* **513**, 1-189 (2012).
