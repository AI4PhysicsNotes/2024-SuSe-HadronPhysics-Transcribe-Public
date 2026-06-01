---
title: (2025) Lecture 5
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Flavor Multiplets, Kinematics, and Symmetries in Hadron Spectroscopy

### Lecture 5 




![This figure illustrates the basic setup of a **fixed-target experiment**, one of the two main classes of particle production experiments discussed in the lecture. In this arrangement, a particle beam (such as photons, pions, or muons) is directed onto a stationary target material. The collision produces a variety of **final state particles**, which emerge from the interaction region and can be measured by detectors. This figure emphasizes the directional nature of fixed-target experiments—where the target remains at rest in the laboratory frame and the beam delivers energy, resulting in final-state particles that are typically boosted forward. Fixed-target experiments, such as GlueX and COMPASS, are historically important in hadron spectroscopy and provide specific kinematic features distinct from collider setups.](2025-Lecture-05-images/fig1.png){#fig-fg1}

 




![This figure illustrates an **inclusive particle production process**, as discussed in the lecture. In this context, the diagram shows a **proton (p)** and a **muon ( $\mu^-$ )** entering a reaction (the blob), and in the final state, a **kaon ( $K^-$ )**, a **muon ( $\mu^-$ )**, and any other unmeasured particles ("anything", often denoted as X) emerging. This type of process, e.g.  $\mu^- p \to \mu^- K^- X$ , is typical for **inclusive measurements**, where only one or a subset of final-state particles (here, the  $K^-$ ) is detected and the rest summed over. Such processes are used to probe the internal structure of particles like the proton—specifically, to gain information about the **strange quark content (sea quarks)** inside the proton through virtual photon exchange. This approach contrasts with **exclusive processes**, where all final-state particles are reconstructed in detail to study specific resonances or reaction mechanisms.](2025-Lecture-05-images/fig3.png){#fig-fg3}

 




![This figure illustrates a typical invariant mass spectrum ( $\frac{dN}{dm_{3\pi}}$  versus  $m_{\pi^+\pi^-\pi^-}$ ) for three-pion final states in a particle physics experiment searching for  $B^-$  meson decays. The plot demonstrates three key physical features from hadron spectroscopy production experiments:  1. **Resonance Peak:** There is a prominent peak at the invariant mass  $m_{B^-}$ , labeled as such. This peak corresponds to true  $B^-\to\pi^+\pi^-\pi^-$  decays; due to energy-momentum conservation, the invariant mass of the three final-state pions reconstructs the original  $B^-$  mass. In an ideal experiment with perfect resolution, this peak would be a delta function. Realistically, detector resolution broadens it into a Gaussian shape.  2. **Combinatorial Background:** There is a nearly flat (green dashed) background beneath the peak, representing combinatorial background. This arises from random combinations of tracks (pions) that do not originate from a genuine  $B^-$  decay, but nonetheless satisfy the selection criteria. They create a smooth distribution across the mass spectrum.  3. **Misidentification Peaks:** Another peak is indicated, arising from  $B^-\to K^-\pi^+\pi^-$  decays, where the kaon has been misidentified as a pion. Since tracking alone cannot distinguish between pions and kaons (without additional particle identification detectors), the wrong mass hypothesis for one of the tracks leads to a shifted peak in the reconstructed invariant mass distribution.  Overall, this figure encapsulates how resonance signals (true decays) are observed as mass peaks, how backgrounds and misidentified decays complicate the spectra, and highlights the fundamental role of invariant mass calculations—here,  $m_{3\pi} = \sqrt{(p_{\pi^+} + p_{\pi^-} + p_{\pi^-})^2}$ —in experimental hadron spectroscopy. It also underlines the necessity for additional information, such as particle identification, to distinguish between decay channels with similar track signatures.](2025-Lecture-05-images/fig8.png){#fig-fg8}






This lecture continues the exploration of production mechanisms in different directions across the world for studying hadron spectroscopy. 




![This figure represents a generic diagram for an exclusive particle production reaction in hadron spectroscopy. Here, a photon ( $\gamma$ ) and a proton ( $p$ ) are shown as incoming particles on the left, entering a central "blob" that symbolizes the underlying interaction or production mechanism. The outgoing particles emerging from the blob are a proton ( $p$ ), a positive pion ( $\pi^+$ ), and a negative pion ( $\pi^-$ ). This setup formalizes a reaction such as  $\gamma p \to p \pi^+ \pi^-$ .  In the context of this lecture, this type of diagram is used to discuss the kinematics of exclusive processes, where all final-state particles are measured. The "blob" represents all possible strong-interaction physics that can occur, while the external lines denote incoming and outgoing real particles. The study of such reactions often involves analyzing the event in the center-of-momentum (CM) frame, using conservation of four-momentum to reconstruct invariant masses (like  $m_{\pi\pi}$ ), and transitioning to frames such as the Gottfried-Jackson frame to further analyze the decay angular distributions of the particle systems produced.  In summary, this figure encapsulates the essential ingredients for investigating production mechanisms, kinematics, and resonance identification in exclusive photoproduction experiments, using the tools discussed throughout the lecture.](2025-Lecture-05-images/fig2.png){#fig-fg2}




 We will go into depth on the kinematics of different reactions, discuss numerical algorithms to produce distributions of particles (particularly decays), and examine one of the most important kinematic setups—frames—along with the kinematic representation of phase space for different reactions. 




![This figure illustrates the kinematics of an exclusive reaction—specifically, the process  $\gamma p \to p \, (\pi\pi)$ —in the **center-of-momentum (CM) frame**. The incoming photon ( $\gamma$ ) and proton ( $p$ ) collide, resulting in an outgoing recoil proton and a dipion system  $(\pi\pi)$ . The two outgoing particles, the recoil proton and the dipion system, are emitted back-to-back, with their momenta constrained to lie within a single plane, labeled here as the **reaction plane**. This diagram is a typical representation used to discuss production kinematics for reactions studied in fixed-target experiments, emphasizing the conservation of momentum and the definition of planes crucial for analyzing angular distributions and resonance decays.](2025-Lecture-05-images/fig4.png){#fig-fg4}

 




![This figure illustrates the kinematic configuration in the Gottfried-Jackson (GJ) frame, which is the rest frame of a resonance decaying to two pions, such as  $\pi^+\pi^-$ . In this frame, the sum of the momenta of the  $\pi^+$  and the  $\pi^-$  is zero, so they are emitted back-to-back. The z-axis is typically aligned along the direction of the incident beam in the overall center-of-mass frame, while the recoiling proton's direction (not shown) defines a production plane together with the beam.   The figure also shows the transverse component ( $p_T$ ) and longitudinal component ( $p_r$ ) of the pion momenta with respect to the beam direction. This setup is essential for studying angular distributions of the decay products, which help determine properties like the spin of the intermediate resonance. The GJ frame provides a clear separation between the production plane and the decay plane, allowing a precise analysis of the angular correlations characterizing different partial waves (e.g., S-wave, P-wave, D-wave) and resonance structures in hadron spectroscopy.](2025-Lecture-05-images/fig5.png){#fig-fg5}

 




![This figure illustrates the delayed (secondary) vertex topology commonly observed in collider experiments when studying weak decays of heavy flavor hadrons. Two protons ("p p") collide at the **primary vertex**, producing, among other particles, a neutral  $B^0$  meson. The  $B^0$  travels some distance away from the primary vertex before decaying. The secondary (delayed) vertex is where the  $B^0$  decays into three pions ( $\pi^+$ ,  $\pi^-$ ,  $\pi^-$ ). This separation between vertices is a hallmark of weak decays: the  $B^0$ 's relatively long lifetime (compared to strong decays) allows it to move a measurable distance before decaying. The **delayed production products** (the three pions) can be tracked in the detector, allowing reconstruction of the displaced decay vertex and the identification of long-lived particles like  $B^0$ . This is essential for flavor physics analyses and is used to distinguish signal events from promptly produced background.](2025-Lecture-05-images/fig6.png){#fig-fg6}

 




![This diagram represents the **exponential decay law** for unstable particles, central to the discussion of decay processes in particle physics experiments. The vertical axis shows the decay rate,  $\frac{dN}{dt}$ , which is the number of particles decaying per unit time, while the horizontal axis indicates time  $t$  in the rest frame of the particle (labeled  $t_{\text{rf}}$ ). The curve demonstrates that the probability for a particle to decay is **constant in time**, yielding an exponential decrease in the number of undecayed particles. The mathematical expression  $e^{-t/\tau_{\text{rf}}}$  captures this behavior, where  $\tau_{\text{rf}}$  is the characteristic lifetime of the particle in its rest frame. This fundamental distribution underlies the observation that decay vertices are randomly spread in distance (because flight length is tied to this distribution via relativistic time dilation), and gives the **mean** decay length discussed in the lecture. It emphasizes that, even though the mean lifetime  $\tau$  is quoted (e.g., in the PDG), individual decays occur randomly and stochastically according to this law.](2025-Lecture-05-images/fig7.png){#fig-fg7}

 




![This figure represents the kinematics of a two-body decay or production process in the center-of-momentum (CM) frame or a relevant rest frame, such as the Gottfried-Jackson (GJ) frame discussed in the lecture. The axes correspond to the components of momentum: the  $z$ -axis is chosen as the reference direction, typically aligned with the beam axis or a production direction. The  $p_1$  and  $p_2$  vectors represent the momenta of the two outgoing particles produced back-to-back due to momentum conservation. The angle  $\theta$  specifies the orientation of particle 1's momentum ( $p_1$ ) with respect to the  $z$ -axis. This angle, often called the "decay angle," is the primary free variable describing the decay kinematics in two-body phase space. Measuring the distribution of  $\theta$  in this frame allows one to extract information about the spin of the intermediate resonance, the angular momentum involved in the decay, and other dynamical properties. This setup is crucial in the analysis of exclusive reactions and is used in calculations of phase space and matrix element dynamics as described in the lecture.](2025-Lecture-05-images/fig9.png){#fig-fg9}

 




![This figure represents a Dalitz plot, a fundamental tool for analyzing the kinematics of three-body decays in particle physics. The plot uses invariant mass squared variables— $m_{12}^2$  on the horizontal axis and  $m_{23}^2$  on the vertical axis—to represent all possible configurations of final-state particle momenta. Each physically allowed set of momenta for the three particles corresponds to a single point within the bounded region (the "circle") shown in the plot, which is defined by the constraints of energy-momentum conservation and the masses of the particles (the phase space boundaries determined by the Kibble function). The text annotates that every possible configuration is mapped inside this region, meaning the entire phase space is represented within the plot.  At the bottom, the differential decay rate formula  $d\Gamma = \frac{1}{2\sqrt{s}}|\mathcal{M}|^2 d\phi$  is shown, emphasizing that the observed distribution in the Dalitz plot is shaped by both the available phase space ( $d\phi$ ) and the dynamics of the decay process ( $|\mathcal{M}|^2$ ). For pure phase space (i.e., no dynamical structure), the density of events would be uniform across the allowed region. Any non-uniformity reflects physical processes, such as resonances or interaction dynamics among the decay products.](2025-Lecture-05-images/fig10.png){#fig-fg10}

 




![This figure illustrates the physical interpretation of a **Dalitz plot** and its projections in the context of three-body decays, as discussed in the lecture. The leftmost plot is a schematic Dalitz plot: a two-dimensional plot where each event in a three-body final state is represented by a point with coordinates given by two invariant mass squares,  $m_{12}^2$  and  $m_{23}^2$ . The kinematically allowed region is typically a solid shape (here represented as a circle or oval), defined by the boundaries of energy-momentum conservation and visualized using the Kibble function.  The lines labeled "1" and "2" depict paths or loci within this physical region where substructures may occur, for example, if two of the final-state particles resonate to form an intermediate particle (resonance). "Look at  $m_{ij}$  on the axes" is a prompt to consider projections onto the axes—i.e., the invariant mass squared distributions for different particle pairs.  The subsequent small plots to the right show the **projected invariant mass squared spectra** ( $d\Gamma/dm_{12}^2$ ,  $d\Gamma/dm_{23}^2$ ,  $d\Gamma/dm_{13}^2$ ): these are the one-dimensional distributions obtained by integrating over the Dalitz plot along one variable. Each projection picks out how often particular mass combinations occur. Peaks in these distributions correspond to resonant substructures or enhancements in the decay rate for specific two-body combinations.  The text "if the Dalitz plot had diagonal lines there would be peaks for 3" emphasizes that if correlations along diagonals existed (e.g., due to a third resonance in the third pair), they would manifest as peaks in the respective projection.  Overall, this figure visually conveys how the **Dalitz plot encodes all three-body decay kinematics** and how physical resonances or substructures of the matrix element  $|\mathcal{M}|^2$  manifest as features (such as peaks) in the projections of the invariant mass distributions. This framework is fundamental for analyzing and interpreting exclusive three-body decays in hadron spectroscopy.](2025-Lecture-05-images/fig11.png){#fig-fg11}

 




![This figure illustrates the standard procedure to obtain the four-momentum of a particle with arbitrary direction in a chosen kinematic frame, using Lorentz transformations.   First, you start in the rest frame (top), where the particle has zero three-momentum ( $\vec{p}=0$ ).   1. The first step is to apply a **Lorentz boost** along the  $z$ -axis, giving the particle a momentum  $\vec{p}_z$  in that direction. This constructs the state  $|\vec{p}_z\rangle = B_z |\vec{0}\rangle$ , where  $B_z$  is the boost operator.  2. The second step is to **rotate** the momentum vector from the  $z$ -axis to an arbitrary direction, specified by the polar and azimuthal angles  $(\theta, \phi)$  in spherical coordinates. This completes the assignment of the particle’s momentum direction in three-dimensional space.  In the context of this lecture, this is the physical process used to construct event kinematics in simulations and calculations: boosting and rotating reference frames to describe particle momenta in the center-of-mass (CM) or Gottfried-Jackson (GJ) frame. This establishes the kinematic configurations necessary for calculating distributions, phase space, and for analyzing decay products’ angular distributions, which are fundamental in hadron spectroscopy. The process shown here underlies how to generate or interpret the full range of physically allowed configurations for multi-particle reactions.](2025-Lecture-05-images/fig13.png){#fig-fg13}

 




![This figure illustrates the transformation of kinematic frames in the analysis of an exclusive reaction, specifically for the process  $\gamma p \to p' S^0$ . Here, a photon ( $\gamma$ ) and a proton ( $p$ ) collide to produce a scattered proton ( $p'$ ) and a neutral resonance particle ( $S^0$ ).   - **Top left:** The initial configuration is shown in the **center-of-mass (CM) frame**, where the proton and photon collide, producing  $p'$  and  $S^0$ . The angle  $\theta_S$  is defined between the incoming photon and the outgoing resonance  $S^0$  in this frame. - **Top right:** A **rotation** is applied so that the z-axis aligns conveniently (typically with respect to the beam or outgoing direction) for the subsequent boost. - **Bottom right:** A **boost** along the momentum direction of  $S^0$  takes the system into the **helicity frame**—the rest frame of the  $S^0$  resonance. In this frame, the decay of  $S^0$  can be analyzed by studying the angular distributions with respect to the new z-axis.   Physically, this sequence of transformations allows us to transition from the overall production dynamics (in the CM frame) to the detailed study of the decay of a specific resonance ( $S^0$ ) in its rest frame (the helicity frame). This is crucial for constructing kinematic variables (like invariant masses and angular distributions) that reveal the quantum numbers and resonance structure of the produced particles, and it matches the methodology described in the lecture for analyzing decays using different reference frames such as the **Gottfried-Jackson frame** or the **helicity frame**.](2025-Lecture-05-images/fig14.png){#fig-fg14}

 




![This figure illustrates the kinematic setup for the decay of a neutral resonance (for example, a  $\rho^0$  meson) into two pions,  $\rho^0 \to \pi^+ \pi^-$ . The diagram is drawn in the rest frame of the decaying resonance, also called the Gottfried-Jackson (GJ) frame. In this frame, the  $\pi^+$  and  $\pi^-$  are produced back-to-back, and their total three-momentum vanishes.  The axes  $(x_H, y_H, z_H)$  represent the coordinate system in the GJ frame. The momentum of the emitted  $\pi^+$ , denoted as  $\vec{p}_{\pi^+}$ , is shown as a vector leaving the origin. Its direction is specified by the angles  $\theta_H$  (polar angle) and  $\varphi_H$  (azimuthal angle), which fully determine the orientation of the decay plane of the pions relative to the chosen axis.  These angular variables ( $\theta_H, \varphi_H$ ) are essential observables for studying the decay dynamics and the spin-parity structure of the resonance. In hadron spectroscopy, analyzing the angular distribution of decay products in this frame reveals information about the underlying production mechanism and the quantum numbers (such as spin) of the parent particle.  In summary, this figure provides a schematic representation of kinematics in two-body decay, specifying how the pion momenta are analyzed in the resonance rest frame to extract physical observables relevant for hadron spectroscopy.](2025-Lecture-05-images/fig15.png){#fig-fg15}

 




![This figure illustrates the weak decay process of a  $\Lambda$  baryon into a proton and a  $\pi^-$ , emphasizing both the quark-level transition and the kinematics in different reference frames.   - In the **top left**, the diagram shows the underlying weak process: a strange quark ( $s$ ) inside the  $\Lambda$  baryon converts into an up quark ( $u$ ) via emission of a  $W^-$  boson, which subsequently produces a  $u\bar{u}$  quark pair. The  $u$  quark, together with the spectator  $u$  and  $d$  quarks, forms the final state proton, while the  $\bar{u}$  combines with a spectator  $d$  to form the  $\pi^-$ .  - The **bottom left** diagram depicts the decay kinematics in the laboratory (or production) frame. The  $\Lambda$  moves along the  $z$ -axis, then decays, producing a proton and a  $\pi^-$  emitted in a shared "decay plane".  - The **right** side of the figure shows what occurs after boosting into the rest frame of the  $\Lambda$  (the so-called **helicity frame**, where the  $\Lambda$  is at rest). In this frame, the proton and  $\pi^-$  are emitted back-to-back, forming a specific angle  $\theta_H$  with respect to the  $\Lambda$  polarization (or motion) axis. The labels  $\lambda_{\Lambda}$  and  $\lambda_{p\pi}$  refer to the helicities (spin projections) of the  $\Lambda$  and the  $p\pi$  system, respectively.  This setup is central in hadron spectroscopy, as analyzing the angular distribution of the decay products in the helicity frame allows measurement of spin and parity properties of the parent particle ( $\Lambda$  baryon in this case), as well as the dynamics of weak decay processes. The transformation from lab frame to rest frame and the interpretation of the resulting angular variables are key topics in the lecture's discussion of kinematics and phase space in particle production and decay.](2025-Lecture-05-images/fig16.png){#fig-fg16}

 




![This figure illustrates the angular distribution of decay products, specifically showing how the differential decay rate  $\frac{d\Gamma}{d\cos\theta}$  depends on the angle  $\theta$  for a particle decay process (such as a  $\Lambda$  baryon). The top plot shows a flat, uniform distribution in  $\cos\theta$ , which is expected "in case of no  $\Lambda$  polarisation"—that is, when the decaying particle is completely unpolarized, the decay is isotropic and all directions are equally likely, matching the prediction of phase space for an unpolarized system. The bottom plot shows a linear, asymmetric distribution, which is labeled as “observed: backward-forward-asymmetry.” This means that in real data, an asymmetry is measured indicating a preference in the decay direction (either forward or backward along an axis such as the parent momentum or beam direction). This asymmetry is a physical effect, revealing information about polarization, parity violation, or possible new physics in the production or decay process. The use of the variable  $\cos\theta$  connects this directly to the kinematics and angular distributions discussed in the lecture, and measuring such asymmetries is a key tool for characterizing particle properties in hadron spectroscopy experiments.](2025-Lecture-05-images/fig17.png){#fig-fg17}

 




![This figure illustrates the Dalitz plot for a three-body decay of an unknown particle  $x$  into a proton ( $p$ ), a kaon ( $K^-$ ), and a pion ( $\pi^+$ ), specifically  $x \to p K^- \pi^+$ . The Dalitz plot represents each event as a point in the space defined by the squared invariant masses  $m^2(pK^-)$  (horizontal axis) and  $m^2(K^- \pi^+)$  (vertical axis).   The physical meaning of the plot comes from how regions in this space correspond to different kinematic configurations of the decay products: - The allowed kinematic region is bounded by curves representing the minimum and maximum possible values for these invariant masses, determined by the masses of the initial and final particles (as shown by the various labeled bounds such as  $(m_p + m_{K^-})^2$ ,  $(m_K + m_{\pi^+})^2$ ,  $(m_x - m_p)^2$ , and  $(m_x - m_{\pi^+})^2$ ). - A **horizontal band** (parallel to the x-axis) indicates a resonance in the  $K^- \pi^+$  subsystem: this appears when two final state particles form an intermediate resonance (e.g., a  $K^*$ ), which would show up as many events clustered at a specific value of  $m^2(K^- \pi^+)$ . - A **vertical band** (parallel to the y-axis) indicates a resonance in the  $pK^-$  subsystem: this denotes the presence of an intermediate resonance involving the proton and the kaon. - The distributions along the sides of the plot (represented by horizontal and vertical projections) show the invariant mass spectra of the respective pairs, with peaks corresponding to resonance masses smeared by experimental resolution and possible backgrounds.  Overall, the Dalitz plot is a powerful tool in hadron spectroscopy, as it allows experimenters to identify intermediate resonances and study the dynamics of three-body decays by observing the density and structure of events within the kinematic boundaries. The uniformity or enhancement in certain regions of the plot reveal physical processes beyond pure phase space, specifically the effects of the matrix element  $|\mathcal{M}|^2$  and the presence of resonances.](2025-Lecture-05-images/fig18.png){#fig-fg18}





<hr>
#### Recap

### Question 1: Flavor and Multiplets of Σₓ

<b>Q:</b> What does *flavor* mean in the context of the multiplet?

<b>A:</b> “The charge of the strong interaction.”
Flavor refers to the quantum number for the multiplet. There are many quantum numbers—here we mean the flavor quantum number. Flavor is not color (like red, green, blue); it corresponds to the quark types: up, down, strange, charm. Do not mix them up.

<hr>

<b>Q:</b> What is a multiplet?

<b>A:</b> A multiplet is the set of different possible combinations for one quantum number. For example, with one total spin, multiple configurations form a spin multiplet. In the context of flavor multiplets, we talk about different combinations of quark flavors.

<hr>

<b>Q:</b> What are the flavor multiplets of Σₓ?

<b>A:</b> The Σₓ baryon has a bottom quark and two light quarks. The flavor multiplets include:

- **Isospin multiplet (SU(2))**: Changing an *u* quark to a *d* quark yields a different isospin projection. This gives two particles: Σₓ⁰ (with a *d* quark, charge 0) and Σₓ⁻ (charge –1). Both contain a bottom quark and belong to the same isospin multiplet.
- **SU(3) multiplet**: When also changing the strange quark, the multiplet becomes a decuplet. The decomposition for two quarks in SU(3) is 3 ⊗ 3 = 6 ⊕ 3̄.

Note: Replacing only one quark with an antiquark is not allowed because the baryon number must be preserved (three quarks). The antiparticle would involve replacing all three quarks.

<hr>

### Question 2: Spin of the ππ System in D‑Wave

<b>Q:</b> What is the spin of the ππ system in a D‑wave?

<b>A:</b> The pion has quantum numbers Jᴾ = 0⁻. Two pions have total spin 0 and parity +. Coupling with different orbital angular momenta gives:

| Orbital wave | Resulting Jᴾ |
|--------------|--------------|
| S‑wave       | 0⁺           |
| P‑wave       | 1⁻           |
| D‑wave       | 2⁺           |

Thus, the spin of the D‑wave two‑pion system is **2**.

<hr>

### Question 3: Gauge vs. Flavor and Lorentz Symmetry

<b>Q:</b> Is flavor symmetry gauge? Is Lorentz symmetry gauge?

<b>A:</b> Gauge symmetry is a **local** symmetry—it can be adjusted independently at each spacetime point. Global symmetries are not gauge. Flavor symmetry is global, not gauge. Lorentz symmetry in our consideration is also **not gauge**; we boost and rotate all of spacetime simultaneously. However, one can consider Lorentz transformations as a local gauge symmetry, which leads to the gravitational field—but that is not done in the standard treatment of strong interactions.



## Fixed Target Experiments and Target Materials

#### Lecture 5: Particle Production – Dictionary and Slang (see @fig-fg3)

Today is 8/6/2006. We start with a follow-up to last time on different production mechanisms. (see @fig-fg2) (see @fig-fg4) (see @fig-fg14)

When discussing production kinematics, it is useful to distinguish several classes of experiments, based on both reaction kinematics and practical considerations. (see @fig-fg1)

### Production Experiments: Fixed Target vs. Collider

| Feature | Fixed Target | Collider |
|---------|--------------|----------|
| **Setup** | Beam directed at a stationary target | Two beams collide head-on |
| **Energy reach** | Lower (center-of-mass energy is limited) | Higher (all beam energy is available in the center-of-mass) |
| **Boost of decay products** | Less boosted | More boosted (forward decay products) |
| **Historical ease** | Easier – only beam production needed; target is a simple fixed setup | More complex |
| **Example** | GlueX (photon beam on hydrogen target), COMPASS (pion/proton beam; also kaon/nucleon beam mixture; targets include lead, ammonia, hydrogen) | — |

Choice between the two depends on whether you want higher collision energy or more forward-boosted decay products.

<hr>

### Target Types for Hadron Spectroscopy

In fixed-target experiments, several target materials are used. The most common for hadron spectroscopy is hydrogen.

| Target | Description | Notes |
|--------|-------------|-------|
| **Liquid hydrogen** | ~1 m long pipe, 30 cm diameter, filled with liquid hydrogen under high pressure | Highly explosive. At CERN, COMPASS took several years to pass security inspections. A major disaster could result if it exploded. |
| **Ammonia** | Used as a polarized target | — |
| **Beryllium** | ~3 cm disk, a few cm thick | Cheap and simple. With this thickness it gives a significant production rate. |
| **Lead** | Similar geometry, higher Z | Cross section scales with Z (number of protons). Used for physics programs requiring high-Z targets. |

The beam interacts with a proton inside the target. By reconstructing final-state particles and tracing them back, you find the interaction vertex. After a few days of data collection, the vertex distribution shows the shape of the target.

One observation: the target was not filled to 100%. In XY-coordinate plots, vertices appear in some regions but not others, showing the transverse cut of the target.

The beam profile is Gaussian. In COMPASS, the beam width is slightly larger than the target, so part of the beam passes outside the target. This wastes beam particles. Ideally, the beam should be focused to match the target size.

<hr>

### Photon Beam Production

To create a photon beam, electrons are sent through a thin foil (few hundred micrometers). Bremsstrahlung photons are emitted. The now-lower-momentum electrons are bent away by a magnetic field placed after the foil, while the photon beam continues to the main target.



## Kinematic Frames and Exclusive vs. Inclusive Reactions

In the Center‑of‑Momentum Frame description, after the sentence "In this frame, the beam and target four‑vectors are back‑to‑back:
  $$\vec{p}_T^* + \vec{p}_B^* = 0.$$  "
insert the explicit statement: (see @fig-fg2) (see @fig-fg3) (see @fig-fg4) (see @fig-fg5) (see @fig-fg9) 




![This figure illustrates the concept of a particle at rest, characterized by a three-momentum  $\vec{p} = \vec{0}$  in its rest frame. The diagram visually represents the rest frame setup, where the spatial component of the four-momentum vanishes, and only the mass  $m$  remains as the energy component. In such a frame, the particle’s momentum vector lies at the origin, emphasizing that its velocity is zero in this particular reference frame.   This scenario is especially relevant when constructing kinematic frames such as the center-of-momentum or the rest frame (e.g., the Gottfried-Jackson frame for a resonance), where total momentum is set to zero by an appropriate Lorentz boost. The configuration shown is foundational for further analysis of decays: all outgoing momenta from a decay must sum to zero in the parent’s rest frame, and the mass  $m$  can be directly associated with the system’s invariant mass. The lower right vector labeled  $m'$  hints at a different particle or system with different mass, underscoring that the same rest-frame logic applies for any particle or composite object.   In summary, the physical meaning is the depiction of the rest frame of a particle—where the sum of its spatial momenta vanishes and the energy is simply the mass—serving as the starting point for analyzing more complex reactions and decays in particle physics.](2025-Lecture-05-images/fig12.png){#fig-fg12}

 (see @fig-fg13) (see @fig-fg14) (see @fig-fg15) (see @fig-fg16)

"For the final state, the recoil proton and the ππ system are also back‑to‑back with equal momentum magnitude, forming a reaction plane."

All other content remains unchanged.



## Lifetime and Displaced Vertex of Weakly Decaying Heavy-Flavor Particles

#### Strong and Weak Interactions

<b>Strong interaction</b> gets its name because it produces large cross sections and causes processes to happen very quickly. **Weak interaction** is called weak because it has a smaller cross section.
If a particle does not decay strongly but rather decays weakly, it will have a very small decay width and a very large lifetime.

For heavy-flavor particles, the ground states always decay weakly because the strong interaction cannot change flavor. (see @fig-fg16) The following particles all decay weakly, since any decay would require changing flavor:

-  $B$  mesons
-  $D$  mesons
-  $\Sigma_b$  baryons
-  $\Lambda_b$  baryons
-  $\Omega_b$  baryons
-  $\Omega_c$  baryons

Once a particle decays weakly, its lifetime is large. That means after production it flies away from the primary vertex before decaying.


::: callout-important
Weak decays produce **displaced vertices**: because the lifetime is large, the particle travels a measurable distance before decaying.
:::

<hr>
#### Example of Displaced Vertex (see @fig-fg6)

Two protons collide. A  $B^0$  meson is produced and decays at a displaced vertex into, say, three pions ( $\pi^+\pi^-\pi^-$ ).

Interestingly, despite the  $b$  quark being much heavier than the  $c$  quark, the lifetime of  $b$  baryons is larger than that of  $c$  baryons.
In QCD at 7 TeV, the momentum of a  $B$  meson is a few hundred GeV, and it flies roughly **20 mm**.
For charm the distance is smaller, about **5 mm** – a factor of about three.

| Particle | Approximate flight distance |
|----------|-----------------------------|
|  $B$  meson | 20 mm |
|  $D$  meson (charm) | 5 mm |

<hr>
#### How Is the Distance Distributed?

<b>Q:</b> How is the distance distributed? Is it always 2 cm, or sometimes smaller and sometimes larger? What does it depend on?
<b>A:</b> It depends on the momentum. It’s probably a mean free path.

<b>Q:</b> Right, it’s absolutely correct that depending on the momentum – it’s relativistic physics. The particle in its rest frame lives a certain amount of time. In the lab frame we observe time dilation, so it lives longer.
The PDG lists a lifetime of about  $10^{-9}$  s, but because of the high boost – say 500 GeV – the gamma factor is

  $$\gamma = \frac{E}{m}$$  

If the energy is 400 GeV and the mass is 4 GeV,  $\gamma = 100$ . That means the particle lives 100 times longer in the lab frame. So instead of  $10^{-9}$  s we get  $10^{-7}$  s, and multiplying by the speed of light gives about **2 cm**.

<hr>
#### Exponential Decay Law

But that is not the full story. The  $10^{-9}$  s is the **characteristic lifetime** in the rest frame, but in an experiment it is not a constant.
What  $10^{-9}$  s means is the characteristic of a **distribution**.

<b>Q:</b> What is that distribution? Think of nuclear physics – it’s exponential.
<b>A:</b> Exponential. (see @fig-fg12)

<b>Q:</b> Exactly. (see @fig-fg7) (see @fig-fg10)

It is the same exponential decay law:

  $$\frac{dN}{dt} = e^{-t/\tau}$$   (see @fig-fg17)

The fact that it comes from a Poisson process – we do not know at which moment a given particle decays. If you collect thousands of  $B$  mesons at rest in a box, they do not know about each other, and at every moment the probability of decaying is the same. From that you get an exponential decrease in the number of particles:

  $$N(t) = N_0 \, e^{-t/\tau}$$  

That is the exponential decay law, and the same thing is observed in particle physics for  $B$ ,  $D$ , and any particle. It is just the quantum nature of states.

So when you are told the  $B$  meson flies 2 cm from the primary vertex, that is really a **convoluted distribution**. There is a distribution of production momentum (hence  $\gamma$ ), plus each  $B$  decides for itself where along the exponential it decays. Together these determine the mean travel distance – the lab-frame distance between primary and secondary vertex.

<hr>
#### Experimental Method

In the experiment you do not measure the decaying particle directly. You observe the final-state tracks.

For each track you define the **closest distance to the primary vertex** – the **impact parameter (IP)** – and compute an **IP chi-squared**, which is the distance divided by its uncertainty. This number shows how inconsistent a track is with the primary vertex.

You can select events where tracks have a large IP chi-squared, indicating they come from a displaced vertex. Then you force three such tracks to come from a common secondary vertex and compute their invariant mass:

  $$M = \sqrt{(p_{\pi^-} + p_{\pi^+} + p_{\pi^-})^2}$$  

using the measured four‑vectors of the pions. The resulting spectrum peaks around the  $B$  mass.

<hr>
#### Three Features of the Mass Spectrum (see @fig-fg8) (see @fig-fg11) (see @fig-fg18)

1. **A peak** – The number of counts is small at low mass, then rises, and the distribution has a bell shape with a certain width, with most events gathered around that mass.
<b>Why?</b> If the true process is  $B \to \pi^+\pi^-\pi^-$ , the mass of the three pions should exactly equal the  $B$  mass – theoretically a delta function. Experimentally we do not observe a delta function but a Gaussian curve. The spreading comes from **measurement uncertainties** (hit positions, tracking with finite precision).
For particles that decay weakly, the natural width is negligible (eV scale compared to GeV), so the observed width is entirely from the **detector resolution**.

2. **Combinatorial background** – Random combinations of pions that pass the selection criteria.
Because the number of particles per event is large (a few hundred, sometimes up to a thousand), the combinatorics are huge. For example, with 300  $\pi^+$  and 200  $\pi^-$ , the number of possible three-pion combinations is enormous. Many of those combinations come from primary-vertex tracks that have a large impact parameter only due to resolution. They produce a smooth background under the peak.

3. **Misidentification peaks** – Sometimes additional peaks appear due to misidentification of particles (e.g., a kaon labelled as a pion).



## Mass Identification and Phase Space in Decay Kinematics

### Mass Identification

The last feature to discuss is **mass identification**. It is important for all experiments. When we track particles, we do not measure their mass directly. The momentum is measured from the curvature of the track in the magnetic field. I know how to solve the differential equations for charged particles in a magnetic field, so I can adjust the momentum to fit the measured points. Thus I know the momentum.

The four-vector has energy and momentum components. I measure the momentum, and I compute the energy under a mass assumption. I must assume that the particle is a pion in order to compute its energy. So all charged particles look similar to me unless I use extra information from the tracking. Without information from particle identification detectors, which I will discuss later, I have to assume a mass. Part of the background comes from this assumption.

Consider an example: an event where a  $B$  meson decays to  $\mathrm{K}^- \pi^+ \pi^-$ . This has all the characteristics of my event of interest: a secondary decay to  $\mathrm{K}^- \pi^+ \pi^-$ . The only difference is the particle type, but the tracks look identical. Without identification, I incorrectly compute the energy of the particle. Momentum is measured correctly, but energy is not. This leads to an incorrect invariant mass. Instead of the  $B$  mass, I observe a different value.

Is there an intuition? The reflection of this reaction should be on the left or right. (see @fig-fg8) This could be a homework problem: take an event, compute the kaon momentum, assume it is a pion, and recompute the invariant mass. You will find a different value, either larger or smaller. I believe the computed mass shifts because the kaon mass is larger; using the smaller pion mass shifts the invariant mass.

Without particle identification, we would have significant backgrounds. We need good particle identification detectors, such as the ring‑imaging Cherenkov detector or time‑of‑flight systems. These are essential to suppress misidentification.

<hr>
### Phase Space and Simulation (see @fig-fg6)

In experiments, we simulate to see what we expect. We use the same setup as in the experiment, with computer programs that simulate particle collisions, decays, and interactions in the detector. It is important to know cross sections, but also the available configuration space for different particles, which is determined by phase space.

For  $N$  particles, the phase space is given by a differential with  $3N-4$  integrals. This reflects that  $N$  particles have mass constraints and four energy‑momentum conservation constraints. The counting of degrees of freedom after applying all constraints is:

| Case | Number of integrals (differential) | Comments |
|------|-----------------------------------|----------|
|  $N$  particles |  $3N-4$  | After all constraints |
| Two‑body decay | 2 | Resolving  $\delta$  functions leaves only angular integration |
| Three‑body decay | 4 | Final result expressed in two squared masses |

For two‑body phase space, after resolving the energy‑momentum conservation delta functions, we have eight integrals, minus two mass constraints, minus four conservation constraints, leaving two differentials. This can be arranged so that we integrate only over angles; the only freedom is the orientation, because the two particles go back‑to‑back in the rest frame. The configuration space is  $4\pi$ , and the prefactor gives a relativistic factor:  $\frac{1}{8\pi} \cdot \frac{2p}{\sqrt{s}}$ .

For three‑body phase space it is more involved. The Lorentz‑invariant expression for  $d\Phi_3$  is
  $$d\Phi_3 = \frac{d^3p_1}{2E_1 (2\pi)^3} \frac{d^3p_2}{2E_2 (2\pi)^3} \frac{d^3p_3}{2E_3 (2\pi)^3} (2\pi)^4 \delta^4(p_0 - p_1 - p_2 - p_3).$$  

We can rewrite this using the two‑body topology. The claim is that
  $$d\Phi_3 = d\Phi_2(0 \to (1,2),3) \, d\Phi_2((1,2) \to 1,2) \, \frac{d m_{12}^2}{2\pi}.$$   (see @fig-fg5) (see @fig-fg12) (see @fig-fg13)

This decomposition is intuitive: we split the phase space by introducing the invariant mass  $m_{12}$  of the pair  $(1,2)$  and integrating over it with a delta function that enforces the mass constraint. (see @fig-fg9) This trick relates an  $n$ -body phase space to an  $(n-1)$ -body and a two‑body phase space. (see @fig-fg15)

After substituting the expressions for the two‑body phase spaces, we obtain
  $$d\Phi_3 = \left(\frac{1}{8\pi}\right)^2 \frac{1}{2\pi} \frac{d\Omega_{12,3}}{4\pi} d\varphi_{1,2} \frac{d m_{12}^2}{2\pi} \frac{d m_{23}^2}{s}.$$  

The number of integrals remains the same; we have simply resolved all delta functions. The first factor is expressed in the rest frame of the  $(1,2)$  pair, giving the momentum  $p_{123}$  of particle 3 in that rest frame. The second factor gives the momentum  $k$  of particle 1 or 2 in the  $(1,2)$  rest frame. (see @fig-fg17) The last step is to express the cosine of the scattering angle in terms of  $m_{23}^2$ .

We want to compute  $m_{23}^2 = (p_2+p_3)^2$ . The scattering angle in the  $(1,2)$  rest frame determines  $m_{23}^2$  linearly. Thus we can trade the angular integration for an integration over  $m_{23}^2$ . The phase space then becomes flat in the two squared masses:
  $$\frac{d\Phi_3}{d m_{12}^2 d m_{23}^2} = \text{constant}.$$  

The differential decay width is
  $$d\Gamma = \frac{1}{2\sqrt{s}} |\mathcal{M}|^2 d\Phi_3,$$  
so the only variation in the Dalitz plot comes from the matrix element. (see @fig-fg10) (see @fig-fg11) (see @fig-fg18)

Every configuration of the three momenta can be mapped to a point inside the Dalitz plot, whose boundary is described by the Källén function. The interior satisfies  $\lambda(\lambda_1, \lambda_2, \lambda_3) < 0$ , where
  $$\lambda(x,y,z) = x^2 + y^2 + z^2 - 2xy - 2yz - 2zx.$$  
Here  $\lambda_1 = \lambda(s, m_3^2, m_{12}^2)$ ,  $\lambda_2 = \lambda(s, m_1^2, m_{23}^2)$ , etc. The Dalitz plot is a powerful way to visualize how a decay proceeds and to see the effect of the matrix element.


::: callout-tip
As a fun exercise, given three momenta that sum to zero, one can map the configuration to a point in the Dalitz plot. The coordinates are the squared masses of two pairs. Also, look at an example from the COMPASS measurement. Another problem is to compute the distribution of a variable like the mass.
:::

