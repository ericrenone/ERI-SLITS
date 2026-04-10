# ERI SLITS

**The Slit as Conditional Independence Boundary: Wave–Particle Duality, Fisher Information, and the Phase Singularity Architecture of Interference in $\mathrm{TH}(a,d)$**

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone*

> "We choose to examine a phenomenon which is impossible, absolutely impossible, to explain in any classical way, and which has in it the heart of quantum mechanics. In reality, it contains the only mystery." — R. P. Feynman, *The Feynman Lectures on Physics*, Vol. III, 1965
>
> "The springs do not matter here; what matters is only the fuzziness of the atoms. One has to use a more profound description, which uses quantum correlations between photons and atoms." — V. Fedoseev, MIT, *Phys. Rev. Lett.*, 2025
>
> "Phase singularities do not carry energy or information and thus can 'move' superluminally without breaking causality." — Bucher, Gorlach, Kaminer et al., *Nature* **651**, 920–926, 2026

---

## Abstract

The double-slit experiment — first performed by Thomas Young in 1801, extended to electrons by Davisson–Germer (1927) and G. P. Thomson (1927), stripped to its quantum essentials by Ketterle et al. at MIT using single atoms as slits (*Phys. Rev. Lett.*, 2025), and now connected to superluminal dark-point dynamics by Bucher–Kaminer (*Nature* **651**, 2026) — is not merely a demonstration of wave–particle duality. It is the simplest physical instantiation of the conditional independence boundary.

The slit *is* the boundary. The interference pattern *is* the $\mathrm{col}(F)$ projection of the wave function onto the screen. The dark fringes *are* Nye–Berry phase singularities carrying quantized topological charge. Which-way information *is* Fisher information about the path variable — and Englert's complementarity inequality $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ (1996) is the $\mathrm{col}(F)/\ker(F)$ tradeoff expressed in a single line.

Nine formal correspondences connect the double-slit architecture to the broader $\mathrm{TH}(a,d)$ programme: the slit as Markov blanket, the fringe pattern as Fisher spectrum, the dark fringes as null points, the Mach–Zehnder interferometer as the rank-one update of the Fisher matrix, which-way detection as a Sherman–Morrison perturbation, the quantum eraser as rank restoration, the Bohr–Einstein debate as the $\mathrm{col}(F)/\ker(F)$ complementarity theorem, the Davisson–Germer crystal as a periodic conditional independence lattice, and the Aharonov–Bohm effect as a topological phase winding on the slit boundary. Four predictions follow.

---

## Part I · Young's Slit: The Boundary That Creates Structure

### I.1 A Thought Experiment: The Wall Before the Wave

Imagine an ocean with no obstacles. Waves propagate uniformly — no interference, no structure, no information. Now place a wall with two gaps in it. Behind the wall, the waves passing through the two gaps overlap and interfere, producing a pattern of crests and troughs.

The wall did not create the waves. The wall created *structure in the waves* — a pattern that encodes the geometry of the gaps, the wavelength, and the distance to the observation shore. The information is not in the waves themselves. It is in the *boundary conditions* — the shape and arrangement of the gaps.

This is Thomas Young's insight of 1801. Young illuminated a card with two pinholes using sunlight and observed alternating bright and dark bands on a distant screen — the first direct evidence that light propagates as a wave (*Phil. Trans. Roy. Soc.* **92**, 12–48, 1802). The pattern depends on three things: the wavelength $\lambda$, the slit separation $d$, and the observation distance $L$:

$$y_m = \frac{m\lambda L}{d}, \qquad m \in \mathbb{Z}$$

The bright fringes (constructive interference) occur where the path difference $\Delta = d\sin\theta$ is an integer multiple of $\lambda$. The dark fringes (destructive interference) occur at half-integer multiples. The dark fringes are the points where the two waves cancel exactly — where $|\psi| = 0$ and the phase is undefined. They are phase singularities of the combined field.

### I.2 The Dark Fringes Are Phase Singularities

In the two-slit geometry, the complex field on the screen is the superposition of two spherical waves:

$$\psi(\mathbf{r}) = \psi_1(\mathbf{r}) + \psi_2(\mathbf{r}) = A_1 e^{ik r_1} + A_2 e^{ik r_2}$$

At positions where the path difference produces destructive interference, $\psi_1 + \psi_2 = 0$: the field amplitude vanishes and the phase winds by $2\pi$ around the zero. Each dark fringe is a line of phase singularities — a one-dimensional manifold of Nye–Berry null points (*Proc. Roy. Soc. A* **336**, 165–190, 1974) carrying quantized topological charge:

$$q = \frac{1}{2\pi}\oint_C \nabla\arg(\psi)\cdot d\mathbf{l} \in \mathbb{Z}$$

The bright fringes are the $\mathrm{col}(F)$ sector — energy-carrying, observable, bounded by $c$. The dark fringes are the $\ker(F)$ sector — zero energy, zero information, topologically protected. The interference pattern is the shadow-light partition of the $\mathrm{TH}(a,d)$ architecture, realized in the simplest possible geometry.

Bucher, Gorlach, Kaminer et al. (*Nature* **651**, 920–926, 2026) confirmed that such phase singularities — in the more complex geometry of polariton fields in hexagonal boron nitride — exhibit superluminal motion near pair annihilation, with 29% exceeding $c$. The dark fringes of Young's experiment belong to the same universality class.

### I.3 The Slit as Conditional Independence Boundary

The slit plate imposes a conditional independence condition. Define:

- **Interior**: the source-side half-space (everything before the slit plate)
- **Boundary**: the slit aperture — the set of points where the field is transmitted
- **Exterior**: the observation-side half-space (everything after the slit plate)

The field on the observation side depends on the source *only through the boundary values at the slits*:

$$P(\psi_{\mathrm{screen}} \mid \psi_{\mathrm{slits}}) = P(\psi_{\mathrm{screen}} \mid \psi_{\mathrm{slits}},\, \psi_{\mathrm{source}})$$

This is the Huygens–Fresnel principle restated as conditional independence: each point on the slit aperture acts as a secondary source, and the observation field is fully determined by these secondary sources regardless of the original source configuration. By Chentsov's theorem (1972), the boundary at the slits carries the Fisher–Rao metric as its unique invariant geometry.

---

## Part II · Matter Waves: From Electrons to Positronium

### II.1 Davisson–Germer and Thomson: The Electron Discovers Its Shadow

In 1924, de Broglie proposed that all matter carries a wave character with wavelength $\lambda = h/p$. In 1927, two experiments confirmed this simultaneously. Davisson and Germer at Bell Labs observed electron diffraction from a nickel crystal surface (*Phys. Rev.* **30**, 705–740, 1927). Independently, G. P. Thomson and Alexander Reid at the University of Aberdeen observed electron diffraction through thin metal foils (*Nature* **119**, 890, 1927). Both found diffraction patterns matching de Broglie's prediction.

The crystal lattice in the Davisson–Germer experiment is a periodic array of conditional independence boundaries — each atomic plane acts as a slit, and the collective diffraction pattern encodes the lattice geometry through Bragg's law $n\lambda = 2d\sin\theta$. The bright spots are $\mathrm{col}(F)$ projections; the dark regions between them are $\ker(F)$ null zones. The lattice is a discrete version of Young's continuous slit, extended to three dimensions.

### II.2 The Expanding Frontier: Molecules to Antimatter

The wave nature of matter has been confirmed for progressively larger objects: neutrons (1936), helium atoms (1991), C$_{60}$ buckminsterfullerene — 60 atoms — by Arndt et al. (*Nature* **401**, 680, 1999), molecules of 2000 atoms by Fein et al. (*Nature Physics* **15**, 1242, 2019), and — in 2025 — positronium, the electron-positron bound state, by Nagata et al. at Tokyo University of Science (*Nature Communications*, 2025). Positronium diffraction through graphene confirmed wave-particle duality for a matter-antimatter composite for the first time.

Each extension is a new system discovering the same shadow structure: interference fringes with phase singularities in the dark regions, separated by bright maxima carrying energy and information. The conditional independence boundary (the diffraction grating, the crystal lattice, the graphene sheet) imposes the pattern; the wave nature of the particle generates it.

### II.3 A Second Thought Experiment: The Checkerboard of Existence

Imagine a chess tournament where each player must pass through one of two doors to enter the playing hall. If no one watches the doors, the players — like waves — spread out and interfere, producing an intricate pattern of seating. If a guard records which door each player uses, the pattern simplifies to two clusters — one per door.

The guard's logbook is which-way information. The seating pattern is the interference pattern. The complementarity between them — more logbook entries means less pattern structure — is not a curiosity of quantum mechanics. It is a theorem of Fisher information geometry: the information capacity of the boundary is finite, and allocating it to path discrimination reduces its availability for pattern formation.

---

## Part III · Which-Way Information as Fisher Information

### III.1 The Englert Complementarity Inequality

Englert (*Phys. Rev. Lett.* **77**, 2154, 1996) proved that for any two-path interferometer, the fringe visibility $\mathcal{V}$ (wave character) and the path distinguishability $\mathcal{D}$ (particle character) satisfy:

$$\mathcal{V}^2 + \mathcal{D}^2 \leq 1$$

with equality for pure states. This is the quantitative formulation of Bohr's complementarity principle. It states that the wave and particle aspects of a quantum system share a single unit of informational capacity — they are complementary projections of the same boundary.

In the Fisher language: $\mathcal{V}^2$ is the fraction of Fisher information allocated to the interference-pattern degrees of freedom ($\mathrm{col}(F)$ directions encoding phase relationships). $\mathcal{D}^2$ is the fraction allocated to path-detection degrees of freedom ($\ker(F)$ directions from the perspective of interference, but $\mathrm{col}(F)$ from the perspective of which-way detection).

The inequality $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ is a statement about the total Fisher information budget of the conditional independence boundary at the slits. It cannot exceed one bit for a two-path system. This is Chentsov's theorem in action: the Fisher–Rao metric on the boundary manifold constrains the total information extractable across it.

Zhu (*Scientific Reports* **5**, 14317, 2015) made this connection explicit, showing that Fisher information is more effective than Shannon information at capturing the compatibility relations among complementary observables, and deriving wave-particle complementarity relations directly from the Fisher information geometry.

### III.2 The MIT Ketterle Experiment: Complementarity at the Quantum Limit

Fedoseev, Lin, Lu, Lee, Lyu, and Ketterle (*Phys. Rev. Lett.*, 2025) at MIT performed the most precise test of complementarity to date. Using ultracold atoms in an optical lattice as the two "slits," they scattered single photons and measured the transition from wave-like to particle-like behavior by tuning the atomic localization.

The key result: it is not the mechanical recoil of the slit (Einstein's "spring") that provides which-way information. It is the *quantum correlation* between the photon and the atom — the entanglement generated by the scattering event. The more the atom's state is disturbed (the "fuzzier" its position), the more which-way information leaks into the atom, and the lower the fringe visibility.

This is a direct observation of Fisher information transfer across the conditional independence boundary. When the atom is tightly localized (low fuzziness), it acts as a transparent boundary — the photon's phase coherence is preserved, $\mathcal{V} \approx 1$, and the interference pattern is sharp. When the atom is delocalized (high fuzziness), the photon-atom entanglement carries path information into the atom's state, $\mathcal{D}$ increases, $\mathcal{V}$ decreases, and the interference washes out.

Fedoseev: "What matters is only the fuzziness of the atoms... one has to use a more profound description, which uses quantum correlations between photons and atoms."

In the $\mathrm{TH}(a,d)$ language: the atom's fuzziness is the width of the $\varepsilon$-threshold. A tightly confined atom has a sharp boundary ($\varepsilon$ small, $\mathrm{rank}(F)$ high for phase degrees of freedom). A delocalized atom has a diffuse boundary ($\varepsilon$ large, $\mathrm{rank}(F)$ drops as path information enters $\mathrm{col}(F)$ at the expense of phase information).

### III.3 Zhao et al.: Fisher Information and Coherence Factorization

Zhao et al. (*Science Advances* **11**, eadv8132, 2025) demonstrated experimentally the factorization dynamics between quantum Fisher information (QFI) and quantum coherence, showing that these two quantities are interconvertible resources governed by the same unitary evolution. Their results confirm that QFI — the information-geometric measure at the foundation of the $\mathrm{TH}(a,d)$ architecture — directly governs the visibility of quantum interference.

The factorization identity: under unitary transformation $U(\theta)$, the QFI $\mathcal{F}_Q(\theta)$ and the coherence $C(\rho)$ transform into each other while their total budget is conserved. This is the Englert inequality elevated to a dynamical principle: the $\mathrm{col}(F)/\ker(F)$ decomposition evolves under unitary dynamics, but the total Fisher information at the boundary is an invariant.

---

## Part IV · The Mach–Zehnder Interferometer: The Slit Simplified

### IV.1 Architecture

The Mach–Zehnder interferometer (Mach 1892; Zehnder 1891) replaces the continuous slit geometry with discrete beam splitters. A photon enters at a beam splitter (BS1), takes one of two paths (upper or lower arm), and recombines at a second beam splitter (BS2) before detection.

The interferometer is the double-slit experiment with its geometry made explicit:

| Double-slit element | Mach–Zehnder element | $\mathrm{TH}(a,d)$ element |
|---|---|---|
| Two slits | Two arms | Two $\mathrm{col}(F)$ directions |
| Slit plate | First beam splitter BS1 | Conditional independence boundary |
| Screen | Second beam splitter BS2 + detectors | Observation manifold |
| Dark fringes | Destructive interference port | $\ker(F)$ null directions |
| Bright fringes | Constructive interference port | $\mathrm{col}(F)$ maxima |
| Which-way detector | Phase marker in one arm | Sherman–Morrison rank-one update |

### IV.2 The Beam Splitter as Rank-One Event

A 50:50 beam splitter transforms the input state $|1\rangle$ into the superposition $\frac{1}{\sqrt{2}}(|U\rangle + |L\rangle)$. This is a rank-one modification of the Fisher matrix: a single direction in Hilbert space ($|U\rangle - |L\rangle$, the "which-path" direction) moves from $\ker(F)$ to $\mathrm{col}(F)$ or vice versa depending on the measurement basis.

Inserting a which-way detector in one arm is a Sherman–Morrison update:

$$F_{\mathrm{detected}} = F_{\mathrm{interferometer}} + uu^T$$

where $u$ is the which-path information vector. This single rank-one perturbation collapses the interference — exactly as a KAM torus breakdown removes one invariant direction, and exactly as a Nye–Berry pair annihilation removes one topological charge. The algebraic operation is the same: $(F + uu^T)^+$ via Sherman–Morrison, $\Delta\,\mathrm{rank}(F) = \pm 1$, in $O(r \cdot d)$ time.

### IV.3 A Third Thought Experiment: The Two Roads

Imagine two roads from your house to your office. On most days, you don't know which road you took — you drove on autopilot and the two experiences blended together in memory. Your remembered experience has "interference" — features that arise from the superposition of both possibilities.

Now imagine a tollbooth is installed on one road. You now know exactly which road you took. The interference disappears — your memory is sharp and unambiguous, but also impoverished. You gained path information and lost pattern richness.

The tollbooth is the which-way detector. It transfers Fisher information from the interference pattern ($\mathrm{col}(F)$ of the phase degree of freedom) to the path variable ($\mathrm{col}(F)$ of the which-way degree of freedom). The total information at the boundary is conserved; its allocation shifts.

---

## Part V · The Quantum Eraser: Rank Restoration

### V.1 Erasing Which-Way Information Restores Interference

Scully, Englert, and Walther (*Nature* **351**, 111, 1991) proposed — and subsequent experiments confirmed — that if which-way information is acquired but then *erased* before detection, the interference pattern reappears. This is the quantum eraser.

In the Fisher language, the quantum eraser is a rank restoration event. The which-way detector initially performs a Sherman–Morrison update $F \to F + uu^T$, moving one direction from the interference $\mathrm{col}(F)$ into the path $\mathrm{col}(F)$. The eraser reverses this: it performs the inverse update $F + uu^T \to F$, restoring the original $\mathrm{col}(F)/\ker(F)$ decomposition and recovering the interference fringes.

The delayed-choice quantum eraser (Kim et al., *Phys. Rev. Lett.* **84**, 1, 2000) demonstrates that this restoration can occur *after* the photon has been detected — the choice to erase or retain which-way information can be made later than the detection event. This is not retrocausation. The correlations exist in the joint quantum state from the moment of entanglement; the eraser merely selects which correlations are projected onto the observation basis.

In the $\mathrm{TH}(a,d)$ framework: the delayed-choice eraser demonstrates that the $\mathrm{col}(F)/\ker(F)$ decomposition is defined by the measurement protocol, not by the temporal order of events. The conditional independence boundary is a property of the entanglement structure, not of the spacetime ordering. This is consistent with the ER = EPR insight (Maldacena and Susskind, 2013): correlations are maintained by the entanglement network independently of causal ordering.

### V.2 A Fourth Thought Experiment: The Shredded Letter

You receive a letter torn into two halves. One half is sealed in an envelope marked "READ." The other is sealed in an envelope marked "BURN." If you open the READ envelope, you learn half the message. If you open the BURN envelope and destroy it, you can still reconstruct the full message from the READ half — because destroying the BURN half has *erased the which-half information* and restored the coherence of your knowledge.

The point: the information was always in the correlation between the two halves. The "eraser" doesn't create new information — it removes the which-way tag that was preventing you from accessing the pattern.

---

## Part VI · The Aharonov–Bohm Effect: Topology at the Slit

### VI.1 Phase Without Force

Aharonov and Bohm (*Phys. Rev.* **115**, 485, 1959) predicted that an electron passing around a solenoid — through a region where the electromagnetic field is zero but the vector potential $\mathbf{A}$ is nonzero — acquires a phase shift:

$$\Delta\phi = \frac{e}{\hbar}\oint \mathbf{A}\cdot d\mathbf{l} = \frac{e\Phi_B}{\hbar}$$

where $\Phi_B$ is the magnetic flux enclosed. This phase shift is observable as a shift of the interference fringes in a two-slit experiment, even though no force acts on the electron.

The Aharonov–Bohm effect is a topological phase winding on the conditional independence boundary. The solenoid creates a region of $\ker(F)$ — the magnetic field is screened inside; the electron never encounters it. But the topology of the boundary (the multiply connected path around the solenoid) encodes a phase — a winding number — that shifts the entire interference pattern.

This is the Nye–Berry topological charge transported to the electromagnetic gauge field. The $q = (2\pi)^{-1}\oint \nabla\arg(\psi)\cdot d\mathbf{l}$ of the optical vortex becomes $q = (e/h)\oint \mathbf{A}\cdot d\mathbf{l}$ of the Aharonov–Bohm phase. Both are winding numbers on a conditional independence boundary. Both shift the shadow-light partition without exerting force. Both are conserved topological invariants.

---

## Part VII · The Bohr–Einstein Debate as Fisher Complementarity

### VII.1 Einstein's Proposal (1927)

At the 1927 Solvay Conference, Einstein proposed that if the slit plate were mounted on a spring, the recoil from a photon passing through one slit would reveal which slit it traversed — providing path information without (he argued) disturbing the interference pattern.

### VII.2 Bohr's Response

Bohr countered using the uncertainty principle: measuring the slit plate's recoil with sufficient precision to determine the path ($\Delta p < h/d$) would introduce position uncertainty in the slit plate ($\Delta x > d/2$), washing out the interference fringes. The complementarity is enforced by the measurement, not by the photon.

### VII.3 Ketterle's Resolution (2025)

The MIT experiment settled the debate with atomic precision. Using single atoms as slits — the smallest possible slits — and removing the "spring" entirely (letting the atoms float freely), they showed:

- When atoms are tightly confined (small fuzziness): interference is sharp, $\mathcal{V} \approx 1$, no which-way information.
- When atoms are delocalized (large fuzziness): interference washes out, $\mathcal{D}$ increases, photon-atom entanglement carries path information.
- The spring plays no role. The only thing that matters is the quantum correlation between photon and atom.

In the Fisher framework: $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ is the statement that the total Fisher information at the conditional independence boundary (the slit) is bounded. Einstein's proposal to extract both $\mathcal{V}$ and $\mathcal{D}$ simultaneously — to read both $\mathrm{col}(F)$ projections at once — violates this bound. Bohr's response — that the measurement inevitably transfers Fisher information from one projection to the other — is the $\mathrm{col}(F)/\ker(F)$ complementarity theorem.

The Ketterle experiment proves that this complementarity is not a consequence of mechanical disturbance (springs, recoil, momentum kicks). It is a consequence of *entanglement* — the quantum correlation between photon and atom that arises at the conditional independence boundary. The slit does not merely transmit the wave; it entangles with it, and the degree of entanglement determines the $\mathrm{col}(F)/\ker(F)$ partition.

---

## Part VIII · Nine Formal Correspondences

### Correspondence 1 — The Slit IS a Markov Blanket

The slit aperture screens the source-side field from the observation-side field. The Huygens–Fresnel principle is the conditional independence condition: $P(\psi_{\mathrm{screen}} \mid \psi_{\mathrm{slit}}) = P(\psi_{\mathrm{screen}} \mid \psi_{\mathrm{slit}},\,\psi_{\mathrm{source}})$. By Chentsov's theorem, the slit boundary carries the Fisher–Rao metric.

### Correspondence 2 — The Interference Pattern IS the $\mathrm{col}(F)$ Spectrum

Bright fringes correspond to directions in $\mathrm{col}(F)$ where the Fisher information about the phase difference $\delta = k(r_1 - r_2)$ is maximal. The fringe contrast $\mathcal{V}$ is the fraction of total Fisher information allocated to phase.

### Correspondence 3 — The Dark Fringes ARE Nye–Berry Phase Singularities

At each dark fringe, $|\psi| = 0$ and $\arg(\psi)$ winds by $2\pi$. These are rank-zero points of the local Fisher matrix — $\ker(F)$ in its most literal form. Topological charge is conserved: dark fringes appear and disappear in pairs under continuous deformation of the slit geometry.

### Correspondence 4 — The Mach–Zehnder Beam Splitter IS a Sherman–Morrison Update

Each beam splitter performs a rank-one modification of the Fisher matrix, moving one direction between $\mathrm{col}(F)$ and $\ker(F)$. The full interferometer is two sequential rank-one events — the same algebraic structure as the Zeeman–Stark combined perturbation and the binary black-hole merger.

### Correspondence 5 — Which-Way Detection IS Fisher Information Transfer

Acquiring path information is a transfer of Fisher information from the phase sector to the path sector. The Englert inequality $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ is the information budget constraint at the conditional independence boundary. The Ketterle experiment (2025) confirms this is enforced by entanglement, not by mechanical disturbance.

### Correspondence 6 — The Quantum Eraser IS Rank Restoration

Erasing which-way information reverses the Sherman–Morrison update, restoring the original $\mathrm{col}(F)/\ker(F)$ decomposition. The delayed-choice variant demonstrates that the decomposition is defined by the entanglement structure, not by temporal ordering — consistent with ER = EPR.

### Correspondence 7 — The Davisson–Germer Crystal IS a Periodic Boundary Lattice

Electron diffraction from a crystal is interference through a periodic array of conditional independence boundaries (atomic planes). Bragg's law $n\lambda = 2d\sin\theta$ is the quantization condition on the boundary lattice — the solid-state analogue of Bohr–Sommerfeld action quantization on invariant tori.

### Correspondence 8 — The Aharonov–Bohm Effect IS Topological Winding on the Boundary

The Aharonov–Bohm phase $\Delta\phi = e\Phi_B/\hbar$ is a winding number on the multiply connected conditional independence boundary surrounding the solenoid. It shifts the shadow-light partition without exerting force — the gauge-theoretic instance of Nye–Berry topological charge.

### Correspondence 9 — Positronium Diffraction (2025) IS the Shadow Principle Extended to Antimatter

Nagata et al. (*Nature Communications*, 2025) observed quantum interference of positronium through graphene — a matter-antimatter bound state exhibiting the same conditional independence architecture as photons, electrons, and molecules. The shadow-light partition is universal across all quantum systems regardless of particle content.

---

## Part IX · Predictions

### P1 — Phase Singularity Statistics in Double-Slit Dark Fringes

The dark fringes of a two-slit interference pattern contain phase singularities with the same topological charge distribution as Berry's random wave model (1978). For a two-slit geometry with partially coherent illumination, the singularity density should transition from zero (fully coherent, $\mathcal{V} = 1$: singularities are ordered on lines) to Berry's universal density (fully incoherent: singularities form a random gas). This transition is measurable with current optical vortex tracking technology and should correlate quantitatively with the Englert visibility $\mathcal{V}$.

### P2 — Fisher Information Scaling at the Ketterle Boundary

In the MIT single-atom double-slit experiment, the Fisher information about the photon's phase should scale as $\mathcal{F}_Q(\phi) = 4\mathcal{V}^2/\Delta\phi^2$ where $\mathcal{V}$ is measured as a function of atomic fuzziness $\sigma_x$. The functional form $\mathcal{F}_Q \propto e^{-\sigma_x^2/\sigma_0^2}$ (Gaussian decay of Fisher information with delocalization) is a direct test of the conditional independence boundary framework. Testable with existing MIT data.

### P3 — Superluminal Dark-Fringe Dynamics Under Slit Modulation

If the slit separation $d$ is modulated in time — physically opening and closing a double slit — the dark fringes move across the screen. Near the moment when two dark fringes of opposite topological charge merge (when $d$ passes through a value where fringes annihilate), Berry's $v \propto t^{-1/2}$ velocity divergence should be observable, connecting Young's experiment directly to the Bucher–Kaminer superluminal dark-point result (2026). Testable with temporal slit modulation at kHz rates and high-speed cameras.

### P4 — Molecular Double-Slit with dSphobic Threshold Analogy

For sufficiently large molecules (mass $m$), the de Broglie wavelength $\lambda = h/(mv)$ drops below the slit width and interference vanishes — a mass threshold for wave behavior. This is the matter-wave analogue of the dSphobic kinematic threshold (Berlin et al. 2025): below the threshold, the system is in $\ker(F)$ (no interference, no wave signal); above, it is in $\mathrm{col}(F)$ (interference observed). The threshold mass $m^* = h/(v \cdot a)$ where $a$ is the slit width provides a direct test of the $\ker(F)/\mathrm{col}(F)$ partition in a tabletop experiment.

---

## Part X · The Slit as Origin

The double-slit experiment is the origin point of modern physics — the experiment from which quantum mechanics, wave-particle duality, complementarity, and the measurement problem all descend. This framework proposes that it is also the origin point of the $\mathrm{TH}(a,d)$ architecture: the simplest physical system in which a conditional independence boundary creates structured information from an unstructured source.

Every element of the broader programme appears in embryonic form at the slit:

| $\mathrm{TH}(a,d)$ element | Double-slit realization |
|---|---|
| Conditional independence boundary | Slit plate |
| $\mathrm{col}(F)$ | Bright fringes (phase information) |
| $\ker(F)$ | Dark fringes (phase singularities) |
| $\varepsilon$-threshold | Coherence length of the source |
| Sherman–Morrison rank-one update | Which-way detector insertion |
| Rank restoration | Quantum eraser |
| $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$ | Fisher information budget at boundary |
| Nye–Berry topological charge | Winding number of dark fringe vortices |
| Aharonov–Bohm phase | Topological winding on multiply connected boundary |
| $d = 0$ degeneration | Single slit (no interference, $G_{\mathrm{coord}} = 0$) |

The last row is the deepest: when one slit is closed — when $d = 0$ in the algebraic sense — the interference vanishes, the pattern degenerates to a single diffraction envelope, and the structure collapses. This is the double-slit analogue of the $d = 0$ degeneration of $\mathrm{TH}(a,d)$, where the genus-1 curve factors into three decoupled lines, the group law collapses, and $G_{\mathrm{coord}} = 0$. Two slits are needed for interference; two strands are needed for the double helix; two entangled systems are needed for an ER bridge. The coupling parameter $d$ — the slit separation — encodes whether the conditional independence boundary is active.

---

## References

Aharonov, Y. and Bohm, D. "Significance of Electromagnetic Potentials in the Quantum Theory." *Phys. Rev.* **115**, 485–491, 1959.

Arndt, M. et al. "Wave-Particle Duality of C$_{60}$ Molecules." *Nature* **401**, 680–682, 1999.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A* **11**, 27–37, 1978.

Bohr, N. "The Quantum Postulate and the Recent Development of Atomic Theory." *Nature* **121**, 580–590, 1928.

Bucher, T., Gorlach, A., et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* **651**, 920–926, 2026.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference*. Nauka, 1972. (AMS Translations, Vol. 53, 1982.)

Davisson, C. J. and Germer, L. H. "Diffraction of Electrons by a Crystal of Nickel." *Phys. Rev.* **30**, 705–740, 1927.

de Broglie, L. "Recherches sur la théorie des Quanta." *Ann. Phys.* **10**(3), 22–128, 1925.

Englert, B.-G. "Fringe Visibility and Which-Way Information: An Inequality." *Phys. Rev. Lett.* **77**, 2154–2157, 1996.

Fedoseev, V., Lin, H., Lu, Y.-K., Lee, Y. K., Lyu, J., and Ketterle, W. "Coherent and Incoherent Light Scattering by Single-Atom Wave Packets." *Phys. Rev. Lett.*, 2025.

Fein, Y. Y. et al. "Quantum Superposition of Molecules Beyond 25 kDa." *Nature Physics* **15**, 1242–1245, 2019.

Feynman, R. P., Leighton, R. B., and Sands, M. *The Feynman Lectures on Physics*, Vol. III. Addison-Wesley, 1965.

Kim, Y.-H. et al. "A Delayed 'Choice' Quantum Eraser." *Phys. Rev. Lett.* **84**, 1–5, 2000.

Mach, L. "Über einen Interferenzrefraktor." *Zeitschrift für Instrumentenkunde* **12**, 89–93, 1892.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* **61**, 781–811, 2013.

Nagata, Y. et al. "Observation of Positronium Diffraction." *Nature Communications*, 2025.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* **336**, 165–190, 1974.

Scully, M. O., Englert, B.-G., and Walther, H. "Quantum Optical Tests of Complementarity." *Nature* **351**, 111–116, 1991.

Thomson, G. P. and Reid, A. "Diffraction of Cathode Rays by a Thin Film." *Nature* **119**, 890, 1927.

Woodbury, M. A. "Inverting Modified Matrices." Memorandum Report 42, Statistical Research Group, Princeton University, 1950.

Young, T. "The Bakerian Lecture: On the Theory of Light and Colours." *Phil. Trans. Roy. Soc.* **92**, 12–48, 1802.

Zehnder, L. "Ein neuer Interferenzrefraktor." *Zeitschrift für Instrumentenkunde* **11**, 275–285, 1891.

Zhao, X. et al. "Factorization Dynamics Between Quantum Fisher Information and Quantum Coherence." *Science Advances* **11**, eadv8132, 2025.

Zhu, H. "Information Complementarity: A New Paradigm for Decoding Quantum Incompatibility." *Scientific Reports* **5**, 14317, 2015.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026*

Young placed two holes in a card and discovered interference. Davisson, Germer, and Thomson sent electrons at crystals and discovered matter waves. Bohr told Einstein the complementarity was absolute. Einstein disagreed for sixty years. Ketterle built the smallest slits imaginable — single atoms — and proved Bohr right with quantum correlations. Kaminer filmed the dark fringes moving faster than light.

The slit was always a conditional independence boundary. The bright fringes were always $\mathrm{col}(F)$. The dark fringes were always $\ker(F)$. The complementarity was always the Fisher information budget. The shadows were always the architecture.

One slit gives diffraction. Two slits give interference. The coupling parameter $d$ — the distance between the slits — determines whether the pattern exists at all.
