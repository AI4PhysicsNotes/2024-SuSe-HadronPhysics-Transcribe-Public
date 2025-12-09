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



## Production Mechanisms and Kinematic Frames

All right, let's start this lecture. Today, lecture number five will be dedicated to the production mechanisms in different directions across the world to study hadron spectroscopy. We will also go into depth on the kinematics of different reactions, discuss numerical algorithms to produce distributions of particles, particularly decays, and look at one of the most important kinematic setups: frames and then kinematic representation of the phase space for different reactions. 




![This figure illustrates the weak decay process of a  $\Lambda$  baryon into a proton and a  $\pi^-$ , emphasizing both the quark-level transition and the kinematics in different reference frames.   - In the **top left**, the diagram shows the underlying weak process: a strange quark ( $s$ ) inside the  $\Lambda$  baryon converts into an up quark ( $u$ ) via emission of a  $W^-$  boson, which subsequently produces a  $u\bar{u}$  quark pair. The  $u$  quark, together with the spectator  $u$  and  $d$  quarks, forms the final state proton, while the  $\bar{u}$  combines with a spectator  $d$  to form the  $\pi^-$ .  - The **bottom left** diagram depicts the decay kinematics in the laboratory (or production) frame. The  $\Lambda$  moves along the  $z$ -axis, then decays, producing a proton and a  $\pi^-$  emitted in a shared "decay plane".  - The **right** side of the figure shows what occurs after boosting into the rest frame of the  $\Lambda$  (the so-called **helicity frame**, where the  $\Lambda$  is at rest). In this frame, the proton and  $\pi^-$  are emitted back-to-back, forming a specific angle  $\theta_H$  with respect to the  $\Lambda$  polarization (or motion) axis. The labels  $\lambda_{\Lambda}$  and  $\lambda_{p\pi}$  refer to the helicities (spin projections) of the  $\Lambda$  and the  $p\pi$  system, respectively.  This setup is central in hadron spectroscopy, as analyzing the angular distribution of the decay products in the helicity frame allows measurement of spin and parity properties of the parent particle ( $\Lambda$  baryon in this case), as well as the dynamics of weak decay processes. The transformation from lab frame to rest frame and the interpretation of the resulting angular variables are key topics in the lecture's discussion of kinematics and phase space in particle production and decay.](2025-Lecture-05-images/fig16.png){#fig-fg16}





Before starting, we go through the recap and I ask quickly to give the answers. Who feels confident on question number one? Let's break it down.

*   **Flavor:** In this context, flavor is a quantum number for the multiplet. It refers to quark types like up, down, strange, and charm. It is distinct from color charge.
*   **Multiplet:** This refers to the different possible combinations or configurations for a given quantum number, like the different states for a total spin.

The whole question was: *What are the flavor multiplets of Σ_b?* We are looking for other baryons that belong to the same multiplet, meaning they share the same quantum numbers but have different projections of the flavor wave function. The Σ_b baryon has quark content (u s b).


::: callout-note
**Isospin and SU(3) Multiplets:**

*   **Isospin SU(2):** This is a flavor symmetry where you can change a u quark to a d quark. For Σ_b, this gives two particles in the isospin multiplet: Σ_b⁺ (u s b) and Σ_b⁰ (d s b). They have different charges.
*   **SU(3) Flavor:** This symmetry allows flipping the strange quark to others (u, d), leading to larger multiplets like decuplets, which were discussed in lecture two.
:::

The next question was about the spin of two pions in a D-wave. The quantum numbers of a single pion are  $0^-$ . When combining two scalar (spin-0) particles:

*   In an **s-wave**, the total spin is  $0^+$ .
*   In a **p-wave**, the total spin is  $1^-$ .
*   In a **D-wave**, the total spin is ** $2^+$ **.

The final question: *Is flavor symmetry gauge and Lorentz symmetry gauge?*

*   **Gauge symmetry** is a **local** symmetry, where transformations can be made independently at every point in spacetime. The electromagnetic field arises from promoting a global phase symmetry to a local one.
*   **Flavor symmetry** is a **global** symmetry, not a gauge symmetry.
*   **Lorentz symmetry** (boosts and rotations) is typically applied uniformly across spacetime in our considerations. While it can be treated as a local gauge symmetry in theories of gravity, in standard particle physics it is **not** considered a gauge symmetry.
Today we start this lecture on particle production. The first section is "A Dictionary and Slang of Particle Production," as a follow-up to discussing different production mechanisms. When we talk about production kinematics, it makes sense to distinguish a few different classes. This classification depends on the reaction kinematics, but also on practicalities. 




![This figure illustrates the basic setup of a **fixed-target experiment**, one of the two main classes of particle production experiments discussed in the lecture. In this arrangement, a particle beam (such as photons, pions, or muons) is directed onto a stationary target material. The collision produces a variety of **final state particles**, which emerge from the interaction region and can be measured by detectors. This figure emphasizes the directional nature of fixed-target experiments—where the target remains at rest in the laboratory frame and the beam delivers energy, resulting in final-state particles that are typically boosted forward. Fixed-target experiments, such as GlueX and COMPASS, are historically important in hadron spectroscopy and provide specific kinematic features distinct from collider setups.](2025-Lecture-05-images/fig1.png){#fig-fg1}






We start by separating two different classes of experiments:

1.  **Fixed-target experiments:** A beam is shot at a stationary target.
2.  **Collider experiments:** Two beams are collided head-on.

**Practical Differences:**

*   **Energy:** Colliders can achieve much higher center-of-mass energy.
*   **Boost:** Fixed-target experiments produce decay products that are more boosted in the forward direction.
*   **Complexity:** Fixed-target setups are historically simpler, requiring only a beam and a target.

**Examples of Fixed-Target Experiments:**

*   **GlueX:** Photon beam on a liquid hydrogen target.
*   **COMPASS:** Pion or muon beam on various targets (hydrogen, lead, ammonia, beryllium).


::: callout-tip
**Target Materials in Practice:**

*   **Liquid Hydrogen:** Popular for hadron spectroscopy. It's a 1-meter long pipe (~30 cm active length) requiring careful handling under pressure.
*   **Beryllium:** A simple, cheap disk target (e.g., 3 cm thick).
*   **Lead (High-Z):** Used for higher production rates, as cross sections scale with the number of protons (Z) in the target.
:::

In experiments like GlueX, a **photon beam** is produced via **bremsstrahlung**: electrons pass through a thin foil, emit photons, and are then bent away by a magnet, leaving a pure photon beam.
To discuss the physics of the production mechanism, we draw diagrams where incoming particles enter a blob on the left and outgoing particles appear on the right. 




![This figure represents a generic diagram for an exclusive particle production reaction in hadron spectroscopy. Here, a photon ( $\gamma$ ) and a proton ( $p$ ) are shown as incoming particles on the left, entering a central "blob" that symbolizes the underlying interaction or production mechanism. The outgoing particles emerging from the blob are a proton ( $p$ ), a positive pion ( $\pi^+$ ), and a negative pion ( $\pi^-$ ). This setup formalizes a reaction such as  $\gamma p \to p \pi^+ \pi^-$ .  In the context of this lecture, this type of diagram is used to discuss the kinematics of exclusive processes, where all final-state particles are measured. The "blob" represents all possible strong-interaction physics that can occur, while the external lines denote incoming and outgoing real particles. The study of such reactions often involves analyzing the event in the center-of-momentum (CM) frame, using conservation of four-momentum to reconstruct invariant masses (like  $m_{\pi\pi}$ ), and transitioning to frames such as the Gottfried-Jackson frame to further analyze the decay angular distributions of the particle systems produced.  In summary, this figure encapsulates the essential ingredients for investigating production mechanisms, kinematics, and resonance identification in exclusive photoproduction experiments, using the tools discussed throughout the lecture.](2025-Lecture-05-images/fig2.png){#fig-fg2}






*   **Exclusive Processes:** We measure **all** final-state particles. This is necessary to understand detailed production mechanisms and specific resonances.
*   **Inclusive Processes:** We measure only a specific final-state particle (e.g., a kaon), summing over all other unmeasured particles. This gives access to averaged quantities, like parton distribution functions inside the proton. 




![This figure illustrates an **inclusive particle production process**, as discussed in the lecture. In this context, the diagram shows a **proton (p)** and a **muon ( $\mu^-$ )** entering a reaction (the blob), and in the final state, a **kaon ( $K^-$ )**, a **muon ( $\mu^-$ )**, and any other unmeasured particles ("anything", often denoted as X) emerging. This type of process, e.g.  $\mu^- p \to \mu^- K^- X$ , is typical for **inclusive measurements**, where only one or a subset of final-state particles (here, the  $K^-$ ) is detected and the rest summed over. Such processes are used to probe the internal structure of particles like the proton—specifically, to gain information about the **strange quark content (sea quarks)** inside the proton through virtual photon exchange. This approach contrasts with **exclusive processes**, where all final-state particles are reconstructed in detail to study specific resonances or reaction mechanisms.](2025-Lecture-05-images/fig3.png){#fig-fg3}







::: callout-important
**Example: Probing Proton Strangeness**
An inclusive process like  $\mu^- p \to \mu^- K^+ X$  (studied at COMPASS) allows us to probe the strange quark content ("sea quarks") inside the proton via the exchanged virtual photon.
:::

For now, let's focus on the kinematics of **exclusive reactions**. I will introduce two important kinematic frames used for these studies.

In particle physics, we deal with **four-vectors**. While physics is frame-independent, practical calculations are easier in specific frames. Quantities like angle or energy must always be specified with respect to a chosen frame.

### Center-of-Momentum (CM) Frame

In this frame, the three-momenta of the initial particles sum to zero. They are back-to-back. For a reaction like  $\gamma p \to p \pi^+ \pi^-$ , we can group the two pions as a system. 




![This figure illustrates the kinematics of an exclusive reaction—specifically, the process  $\gamma p \to p \, (\pi\pi)$ —in the **center-of-momentum (CM) frame**. The incoming photon ( $\gamma$ ) and proton ( $p$ ) collide, resulting in an outgoing recoil proton and a dipion system  $(\pi\pi)$ . The two outgoing particles, the recoil proton and the dipion system, are emitted back-to-back, with their momenta constrained to lie within a single plane, labeled here as the **reaction plane**. This diagram is a typical representation used to discuss production kinematics for reactions studied in fixed-target experiments, emphasizing the conservation of momentum and the definition of planes crucial for analyzing angular distributions and resonance decays.](2025-Lecture-05-images/fig4.png){#fig-fg4}






**Key Invariant: Mandelstam  $s$ **
The total center-of-mass energy squared is the fundamental Lorentz invariant:
  $$s = (p_{\text{beam}} + p_{\text{target}})^2$$  

**Energies and Momenta in the CM Frame**
The energy of a particle (e.g., the beam) in the CM frame is:
  $$E_{\text{beam}}^* = \frac{s + m_{\text{beam}}^2 - m_{\text{target}}^2}{2\sqrt{s}}$$  
The magnitude of its three-momentum is found using the **Källén function**  $\lambda(x,y,z) = x^2 + y^2 + z^2 - 2xy - 2xz - 2yz$ :
  $$|\vec{p}^{\,*}| = \sqrt{(E_{\text{beam}}^*)^2 - m_{\text{beam}}^2} = \frac{\sqrt{\lambda(s, m_{\text{beam}}^2, m_{\text{target}}^2)}}{2\sqrt{s}}$$  
This "breakup momentum" formula is symmetric. For the final state, treating the dipion system as a resonance with mass  $m_{\pi\pi}$ , the momentum of the recoil proton in the CM frame is:
  $$|\vec{p}_{p}^{\,*}| = \frac{\sqrt{\lambda(s, m_{p}^2, m_{\pi\pi}^2)}}{2\sqrt{s}}$$  


::: callout-note
**Why can we treat two pions as one particle?** Kinematically, we use four-momentum conservation:
  $$p_{\text{beam}} + p_{\text{target}} = p_{\text{recoil}} + p_{\pi^+} + p_{\pi^-}$$  
We define the composite four-momentum  $p_{\pi\pi} = p_{\pi^+} + p_{\pi^-}$ . This allows us to analyze the reaction  $\gamma p \to p \, (\pi\pi)$  as a quasi-two-body process initially, before studying the decay of the  $(\pi\pi)$  system.
:::

### Gottfried-Jackson (GJ) Frame

To analyze the decay of the resonance (e.g., the  $\pi\pi$  system), we go to its **rest frame**. 




![This figure illustrates the kinematic configuration in the Gottfried-Jackson (GJ) frame, which is the rest frame of a resonance decaying to two pions, such as  $\pi^+\pi^-$ . In this frame, the sum of the momenta of the  $\pi^+$  and the  $\pi^-$  is zero, so they are emitted back-to-back. The z-axis is typically aligned along the direction of the incident beam in the overall center-of-mass frame, while the recoiling proton's direction (not shown) defines a production plane together with the beam.   The figure also shows the transverse component ( $p_T$ ) and longitudinal component ( $p_r$ ) of the pion momenta with respect to the beam direction. This setup is essential for studying angular distributions of the decay products, which help determine properties like the spin of the intermediate resonance. The GJ frame provides a clear separation between the production plane and the decay plane, allowing a precise analysis of the angular correlations characterizing different partial waves (e.g., S-wave, P-wave, D-wave) and resonance structures in hadron spectroscopy.](2025-Lecture-05-images/fig5.png){#fig-fg5}




 This is the Gottfried-Jackson frame. 




![This figure represents the kinematics of a two-body decay or production process in the center-of-momentum (CM) frame or a relevant rest frame, such as the Gottfried-Jackson (GJ) frame discussed in the lecture. The axes correspond to the components of momentum: the  $z$ -axis is chosen as the reference direction, typically aligned with the beam axis or a production direction. The  $p_1$  and  $p_2$  vectors represent the momenta of the two outgoing particles produced back-to-back due to momentum conservation. The angle  $\theta$  specifies the orientation of particle 1's momentum ( $p_1$ ) with respect to the  $z$ -axis. This angle, often called the "decay angle," is the primary free variable describing the decay kinematics in two-body phase space. Measuring the distribution of  $\theta$  in this frame allows one to extract information about the spin of the intermediate resonance, the angular momentum involved in the decay, and other dynamical properties. This setup is crucial in the analysis of exclusive reactions and is used in calculations of phase space and matrix element dynamics as described in the lecture.](2025-Lecture-05-images/fig9.png){#fig-fg9}

 




![This figure illustrates the concept of a particle at rest, characterized by a three-momentum  $\vec{p} = \vec{0}$  in its rest frame. The diagram visually represents the rest frame setup, where the spatial component of the four-momentum vanishes, and only the mass  $m$  remains as the energy component. In such a frame, the particle’s momentum vector lies at the origin, emphasizing that its velocity is zero in this particular reference frame.   This scenario is especially relevant when constructing kinematic frames such as the center-of-momentum or the rest frame (e.g., the Gottfried-Jackson frame for a resonance), where total momentum is set to zero by an appropriate Lorentz boost. The configuration shown is foundational for further analysis of decays: all outgoing momenta from a decay must sum to zero in the parent’s rest frame, and the mass  $m$  can be directly associated with the system’s invariant mass. The lower right vector labeled  $m'$  hints at a different particle or system with different mass, underscoring that the same rest-frame logic applies for any particle or composite object.   In summary, the physical meaning is the depiction of the rest frame of a particle—where the sum of its spatial momenta vanishes and the energy is simply the mass—serving as the starting point for analyzing more complex reactions and decays in particle physics.](2025-Lecture-05-images/fig12.png){#fig-fg12}

 




![This figure illustrates the transformation of kinematic frames in the analysis of an exclusive reaction, specifically for the process  $\gamma p \to p' S^0$ . Here, a photon ( $\gamma$ ) and a proton ( $p$ ) collide to produce a scattered proton ( $p'$ ) and a neutral resonance particle ( $S^0$ ).   - **Top left:** The initial configuration is shown in the **center-of-mass (CM) frame**, where the proton and photon collide, producing  $p'$  and  $S^0$ . The angle  $\theta_S$  is defined between the incoming photon and the outgoing resonance  $S^0$  in this frame. - **Top right:** A **rotation** is applied so that the z-axis aligns conveniently (typically with respect to the beam or outgoing direction) for the subsequent boost. - **Bottom right:** A **boost** along the momentum direction of  $S^0$  takes the system into the **helicity frame**—the rest frame of the  $S^0$  resonance. In this frame, the decay of  $S^0$  can be analyzed by studying the angular distributions with respect to the new z-axis.   Physically, this sequence of transformations allows us to transition from the overall production dynamics (in the CM frame) to the detailed study of the decay of a specific resonance ( $S^0$ ) in its rest frame (the helicity frame). This is crucial for constructing kinematic variables (like invariant masses and angular distributions) that reveal the quantum numbers and resonance structure of the produced particles, and it matches the methodology described in the lecture for analyzing decays using different reference frames such as the **Gottfried-Jackson frame** or the **helicity frame**.](2025-Lecture-05-images/fig14.png){#fig-fg14}

 




![This figure illustrates the kinematic setup for the decay of a neutral resonance (for example, a  $\rho^0$  meson) into two pions,  $\rho^0 \to \pi^+ \pi^-$ . The diagram is drawn in the rest frame of the decaying resonance, also called the Gottfried-Jackson (GJ) frame. In this frame, the  $\pi^+$  and  $\pi^-$  are produced back-to-back, and their total three-momentum vanishes.  The axes  $(x_H, y_H, z_H)$  represent the coordinate system in the GJ frame. The momentum of the emitted  $\pi^+$ , denoted as  $\vec{p}_{\pi^+}$ , is shown as a vector leaving the origin. Its direction is specified by the angles  $\theta_H$  (polar angle) and  $\varphi_H$  (azimuthal angle), which fully determine the orientation of the decay plane of the pions relative to the chosen axis.  These angular variables ( $\theta_H, \varphi_H$ ) are essential observables for studying the decay dynamics and the spin-parity structure of the resonance. In hadron spectroscopy, analyzing the angular distribution of decay products in this frame reveals information about the underlying production mechanism and the quantum numbers (such as spin) of the parent particle.  In summary, this figure provides a schematic representation of kinematics in two-body decay, specifying how the pion momenta are analyzed in the resonance rest frame to extract physical observables relevant for hadron spectroscopy.](2025-Lecture-05-images/fig15.png){#fig-fg15}






*   In this frame,  $\vec{p}_{\pi^+}^{\,GJ} + \vec{p}_{\pi^-}^{\,GJ} = 0$ . The pions are back-to-back.
*   The momentum of each pion in this frame is:
  $$|\vec{p}_{\pi}^{\,GJ}| = \frac{\sqrt{\lambda(m_{\pi\pi}^2, m_{\pi^+}^2, m_{\pi^-}^2)}}{2 m_{\pi\pi}}$$  

*   This frame is defined with specific alignments (often with the beam direction along the z-axis) and is crucial for studying the angular distributions of decay products, which reveal the spin of the resonance. 




![This figure illustrates the standard procedure to obtain the four-momentum of a particle with arbitrary direction in a chosen kinematic frame, using Lorentz transformations.   First, you start in the rest frame (top), where the particle has zero three-momentum ( $\vec{p}=0$ ).   1. The first step is to apply a **Lorentz boost** along the  $z$ -axis, giving the particle a momentum  $\vec{p}_z$  in that direction. This constructs the state  $|\vec{p}_z\rangle = B_z |\vec{0}\rangle$ , where  $B_z$  is the boost operator.  2. The second step is to **rotate** the momentum vector from the  $z$ -axis to an arbitrary direction, specified by the polar and azimuthal angles  $(\theta, \phi)$  in spherical coordinates. This completes the assignment of the particle’s momentum direction in three-dimensional space.  In the context of this lecture, this is the physical process used to construct event kinematics in simulations and calculations: boosting and rotating reference frames to describe particle momenta in the center-of-mass (CM) or Gottfried-Jackson (GJ) frame. This establishes the kinematic configurations necessary for calculating distributions, phase space, and for analyzing decay products’ angular distributions, which are fundamental in hadron spectroscopy. The process shown here underlies how to generate or interpret the full range of physically allowed configurations for multi-particle reactions.](2025-Lecture-05-images/fig13.png){#fig-fg13}






The GJ frame is reached from the CM frame by boosting along the momentum of the  $(\pi\pi)$  system and then rotating. In this frame, we can clearly see the decay plane of the pions relative to the production plane defined by the beam and recoil proton.



## Rest Frame of the Pion Pair

Absolutely.
It is the same trick I applied earlier, and now it can work for this pion pair.

We know that in the **Gottfried-Jackson (GJ) frame**—which is the center-of-momentum or rest frame of the  $\pi^+ \pi^-$  system—the sum of their four-momenta results in a four-vector with **zero spatial components**.
Therefore, the total four-momentum is simply  $(m_{\pi\pi}, \mathbf{0})$ , where  $m_{\pi\pi}$  is the **invariant mass** of the two-pion system.

Thus, we can apply this trick. For completeness, let's write it explicitly:

  $$p_{\pi^+}^{\text{(GJ)}} + p_{\pi^-}^{\text{(GJ)}} = (m_{\pi\pi}, \mathbf{0})$$  


::: callout-important
The invariant mass  $m_{\pi\pi}$  is a **Lorentz scalar**, meaning it has the same value in all reference frames. It is calculated from the four-vector dot product:
  $$m_{\pi\pi}^2 = (p_{\pi^+} + p_{\pi^-})^2$$  
In the Gottfried-Jackson frame, this simplifies because the total three-momentum is zero, so  $m_{\pi\pi}$  is just the total energy of the system in that frame. This property is crucial for identifying resonances (like the  $\rho^0$  meson) in particle physics, as they appear as peaks in the  $m_{\pi\pi}$  distribution.
:::

**Key points to remember:**

* The "trick" is boosting to the frame where the total three-momentum of the system vanishes.
* In that frame, the total four-momentum has only a time component, which is the invariant mass.
* This invariant mass  $m_{\pi\pi} = \sqrt{(p_{\pi^+} + p_{\pi^-})^2}$  is the quantity used to reconstruct resonance masses.



## Collider Experiments and Particle Decay Dynamics

I will probably try to add a few more exercises on kinematics because that's something worth practicing—how you get these particular expressions—and it's all over the place. It's a very important skill to be able to operate with **four-vectors**.

But we continue with discussing another type or class of experiments, particularly **collider experiments**. There are a few collider experiments in the world, and depending on the colliding particles, you have different physics.

*   There's been a time where antiproton beams were collided at Fermilab.
*   Now the biggest running machine is the **LHC (Large Hadron Collider)**, where two protons are collided with each other. Hadron spectroscopy and hadrons are particularly studied by essentially all four LHC experiments. The most dedicated experiment to study strong interactions is **LHCb**.
*   Then we have **electron-positron machines**. Currently running are **BESIII** and **Belle II**.

Two important words to introduce from production data are **production** and **decays**.

*   When we talk about certain reactions, we can discuss the hadrons produced directly from the colliding beams. In that case, we would call it **prompt** production, promptly from the primary vertex.
*   The other mechanism is when you produce a long-lived particle that flies away from the primary vertex and then decays. Studying this system is what we refer to as studying **decays**.

One thing you can always have in mind is that the **strong interaction** is called strong because it makes cross sections large and processes happen very quickly. While the **weak interaction** is called weak because it has a smaller cross section. If a particle does not decay strongly, but rather decays weakly, it's going to have a very small width, which corresponds to a very large lifetime.

If you think of the different particles with heavy flavor—like the B meson, D meson, Sigma_b baryon, Lambda_b baryon, Omega_b baryon, Omega_c baryon—their ground states always decay weakly. This is because the strong interaction doesn't change flavor. There is no way you can decay these particles without changing the color or flavor. Once a particle decays weakly, its lifetime is large. This means once it's produced, it manages to fly away from the primary vertex before decaying.
That's what I try to sketch here. You collide two protons. From this collision, a  $B^0$  meson is produced, which then decays at a delayed vertex to, say, three pions. 




![This figure illustrates the delayed (secondary) vertex topology commonly observed in collider experiments when studying weak decays of heavy flavor hadrons. Two protons ("p p") collide at the **primary vertex**, producing, among other particles, a neutral  $B^0$  meson. The  $B^0$  travels some distance away from the primary vertex before decaying. The secondary (delayed) vertex is where the  $B^0$  decays into three pions ( $\pi^+$ ,  $\pi^-$ ,  $\pi^-$ ). This separation between vertices is a hallmark of weak decays: the  $B^0$ 's relatively long lifetime (compared to strong decays) allows it to move a measurable distance before decaying. The **delayed production products** (the three pions) can be tracked in the detector, allowing reconstruction of the displaced decay vertex and the identification of long-lived particles like  $B^0$ . This is essential for flavor physics analyses and is used to distinguish signal events from promptly produced background.](2025-Lecture-05-images/fig6.png){#fig-fg6}




 This is an example of **delayed production**.

Interestingly, despite the  $b$  quark being much heavier than the charm quark, the lifetime that B hadrons have is larger than that of charm hadrons.

In QCD, for energies around 70 GeV, the momentum of the B is a few hundred GeV. It manages to fly a distance of roughly **20 millimeters** before decaying. For charm hadrons, this distance is smaller, about **5 millimeters**.


::: callout-note
**Why do decay distances vary?**
The quoted distance (e.g., 2 cm) is an **average**. The actual distance a specific particle flies depends on its momentum. In relativistic physics, the observed lifetime in the lab frame is stretched by the **Lorentz factor**,  $\gamma$ .

*   In the rest frame, a  $B$  meson has a lifetime  $\tau \approx 10^{-9}$  seconds.
*   In the lab frame, if the  $B$  meson has an energy of 400 GeV and a mass of 4 GeV, then  $\gamma = E/m = 100$ .
*   The average decay length in the lab is  $L \approx \gamma c \tau$  (since  $\beta \approx 1$ ). This calculation gives distances on the order of centimeters.
:::




![This diagram represents the **exponential decay law** for unstable particles, central to the discussion of decay processes in particle physics experiments. The vertical axis shows the decay rate,  $\frac{dN}{dt}$ , which is the number of particles decaying per unit time, while the horizontal axis indicates time  $t$  in the rest frame of the particle (labeled  $t_{\text{rf}}$ ). The curve demonstrates that the probability for a particle to decay is **constant in time**, yielding an exponential decrease in the number of undecayed particles. The mathematical expression  $e^{-t/\tau_{\text{rf}}}$  captures this behavior, where  $\tau_{\text{rf}}$  is the characteristic lifetime of the particle in its rest frame. This fundamental distribution underlies the observation that decay vertices are randomly spread in distance (because flight length is tied to this distribution via relativistic time dilation), and gives the **mean** decay length discussed in the lecture. It emphasizes that, even though the mean lifetime  $\tau$  is quoted (e.g., in the PDG), individual decays occur randomly and stochastically according to this law.](2025-Lecture-05-images/fig7.png){#fig-fg7}






But this is not the full story. The lifetime  $\tau$  you find in the Particle Data Group (PDG) review is the **characteristic time of a distribution**. What is that distribution? It's the same as in nuclear physics: an **exponential decay law**.

The number of undecayed particles  $N$  at time  $t$  follows:
  $$N(t) = N_0 e^{-t/\tau}$$  
This arises because, at every moment, the probability for a given particle to decay is constant. We observe the same exponential behavior in particle physics for the  $B$ ,  $D$ , or any unstable particle—it's a fundamental quantum property.

Therefore, when we say a  $B$  meson flies about 2 cm, this is really the mean of a convoluted distribution. There is a distribution of production momenta (and thus  $\gamma$  factors) from collision to collision, and each individual  $B$  meson decays at a random time drawn from the exponential distribution.

So, we've discussed the  $B$  meson. How do you actually observe such events in an experiment? You don't measure the decaying particle directly. The only way to observe them is by **tracking the final state particles**.

You get a track for each of the pions. You trace them back—they are straight lines without a magnetic field, or curved lines if a magnetic field is present. You then realize these tracks do not point back to the primary vertex where the protons collided. They appear to come from a common point that is **displaced** from the primary vertex. This is how you reconstruct a **secondary decay vertex**.

For every track, we define the **closest distance to the primary vertex**, called the **Impact Parameter (IP)**. To account for measurement precision, we use the **Impact Parameter Significance**:
  $$\text{IP} \chi^2 = \left( \frac{d}{\sigma_d} \right)^2$$  
Here,  $d$  is the closest distance, and  $\sigma_d$  is its uncertainty. A large IP  $\chi^2$  indicates the track is inconsistent with originating from the primary vertex. Analysts use this variable to select events containing displaced decays, like those from  $B$  mesons or  $\Lambda$  baryons.


::: callout-important
**The Power of the Boost**
The measurable flight distance is entirely due to **relativistic time dilation**. (see @fig-fg6) A  $\Lambda$  baryon, with a similar rest-frame lifetime to a  $B$  meson but often produced with a much higher  $\gamma$  at the LHC, can fly **meters**—sometimes up to 5 meters—from the primary vertex. This makes its decay vertex easily distinguishable.
:::



## Peak, Background, and Misidentification in Three-Pion Invariant Mass Spectra

A typical observation would be the following. An experiment is performed a million times. The million records are processed and events are selected where there are three particles with a large impact parameter and they must come from the same vertex. The impact parameter with respect to the primary vertex is large, while with respect to the secondary vertex it is small.

Three particles are forced to come from the same secondary vertex and the invariant mass of the particles is computed. This mass  $M$  is defined as  $M = \sqrt{(p_1 + p_2 + p_3)^2}$ , where the four-vectors  $p_i$  of the particles are measured in the experiment. Then a square root is taken to get the mass of the three particles and a spectrum is observed that peaks around  $M_{B^-}$ . 




![This figure illustrates a typical invariant mass spectrum ( $\frac{dN}{dm_{3\pi}}$  versus  $m_{\pi^+\pi^-\pi^-}$ ) for three-pion final states in a particle physics experiment searching for  $B^-$  meson decays. The plot demonstrates three key physical features from hadron spectroscopy production experiments:  1. **Resonance Peak:** There is a prominent peak at the invariant mass  $m_{B^-}$ , labeled as such. This peak corresponds to true  $B^-\to\pi^+\pi^-\pi^-$  decays; due to energy-momentum conservation, the invariant mass of the three final-state pions reconstructs the original  $B^-$  mass. In an ideal experiment with perfect resolution, this peak would be a delta function. Realistically, detector resolution broadens it into a Gaussian shape.  2. **Combinatorial Background:** There is a nearly flat (green dashed) background beneath the peak, representing combinatorial background. This arises from random combinations of tracks (pions) that do not originate from a genuine  $B^-$  decay, but nonetheless satisfy the selection criteria. They create a smooth distribution across the mass spectrum.  3. **Misidentification Peaks:** Another peak is indicated, arising from  $B^-\to K^-\pi^+\pi^-$  decays, where the kaon has been misidentified as a pion. Since tracking alone cannot distinguish between pions and kaons (without additional particle identification detectors), the wrong mass hypothesis for one of the tracks leads to a shifted peak in the reconstructed invariant mass distribution.  Overall, this figure encapsulates how resonance signals (true decays) are observed as mass peaks, how backgrounds and misidentified decays complicate the spectra, and highlights the fundamental role of invariant mass calculations—here,  $m_{3\pi} = \sqrt{(p_{\pi^+} + p_{\pi^-} + p_{\pi^-})^2}$ —in experimental hadron spectroscopy. It also underlines the necessity for additional information, such as particle identification, to distinguish between decay channels with similar track signatures.](2025-Lecture-05-images/fig8.png){#fig-fg8}





I would like to discuss three features of the spectrum that are always present.

1.  **The first is the peaking in the spectrum.** The spectrum looks like the number of counts for the lower mass of three pions is small. Suddenly it rises and then again the distribution has the bell shape with a certain width. Most of the events are gathered around this value.
2.  **The second feature is the presence of background.** This peak is sitting on a sort of constant, barely moving floor, which we call the combinatorial background.
3.  **The third feature is that sometimes you have more peaks** that would be associated with misidentifying particles.

Let's discuss one by one quickly why the peak appears in the spectrum and what impacts its position and shape.

If the process is the signal process—a  $B$  meson flying and decaying to three pions—the mass of the three pions will be exactly that of the  $B$ . Once we combine the three four-vectors, their invariant mass is equal to the mass of the beam particle.


::: callout-important
In the ideal, theoretical case with no experimental uncertainties, the invariant mass spectrum would be a **delta function** at the true parent particle mass  $M_B$ , representing exact energy-momentum conservation:
  $$\frac{dN}{dM} = N_0 \, \delta(M - M_B)$$  
:::

In the experimental situation, we don't observe delta functions; we observe a Gaussian curve. The reason for this spreading is **measurement uncertainty**. (see @fig-fg8) All tracks come with a certain precision from the hit positions and tracking.


::: callout-important
Due to finite detector resolution, the ideal delta function is smeared into a **Gaussian distribution**. The observed peak is described by:
  $$\frac{dN}{dM} = \frac{N_0}{\sqrt{2\pi}\sigma} \exp\left[-\frac{(M - M_B)^2}{2\sigma^2}\right]$$  
where  $\sigma$  represents the experimental mass resolution.
:::

This shape is very close to a Gaussian. For all particles that decay weakly, like the  $B$  meson with a lifetime of  $\sim 10^{-9}$  seconds, the natural decay width (on the order of eV) is completely negligible compared to the GeV-scale experimental resolution. The resonance peak we see is therefore dominated by the resolution of the experiment.

**The second item is combinatorial background.** This refers to the random associations of pions that pass the selection criteria. When you collide two protons at high energy (e.g., 7 TeV), many particles are produced.

*   What is the average number of charged particles produced in one collision? The right answer is a few hundred to a few thousand.
*   There is a significant chance that tracks originating from the primary vertex get combined and pass the impact parameter criteria simply due to measurement uncertainties.
*   The combinatorics are huge. In an event with a thousand tracks, if you have 300  $\pi^+$  and 200  $\pi^-$ , the number of possible triple combinations is enormous. All these random combinations produce a roughly flat background under the mass distribution.

**The last feature is particle misidentification (mis-ID).** This is crucial for all experiments. When we track charged particles, we measure their momentum from the track curvature in a magnetic field. However, we **do not directly measure the particle's mass**.

*   To compute the particle's energy and complete its four-vector, we must **assume a mass** (e.g., assume it's a pion).
*   Without extra information from particle identification detectors, all charged tracks look similar. We cannot distinguish pions, kaons, or protons from tracking alone.
*   If we make the wrong mass assumption, we compute the wrong energy. For example, consider a real event where a  $B$  decays to  $K^- \pi^+ \pi^-$ . If we misidentify the kaon as a pion, we use the smaller pion mass to compute its energy. (see @fig-fg8) This leads to an incorrect calculation of the invariant mass for that combination, creating a shifted peak or background elsewhere in the spectrum.


::: callout-note
This misidentification background is why experiments **must** have good particle identification systems, such as Ring Imaging Cherenkov (RICH) detectors or Time-of-Flight (ToF) systems, to suppress these errors.
:::



## Phase Space Factorization and the Dalitz Plot

When we do experiments, it's always important to simulate and see what we expect, to simulate different reactions. For this, we have exactly the same setup as we have in the experiment. But in the modeling, there are computer programs that simulate particle collisions, simulate all possible decays, all possible processes that happen, and simulate their movement through a detector.

It's very important to know the **cross section** of different processes. But what's also important is to know the available **configuration space** for different particles. That's driven by the **phase space**, the available phase space of possible configurations.

### The N-Body Phase Space Formula

For the  $N$ -particle phase space, the differential element is given by:

  $$d\phi_n = \prod_{i=1}^n \frac{d^3 p_i}{(2\pi)^3 2 E_i} (2\pi)^4 \delta^4(p_0 - \sum p_i)$$  

This expression has  $3N - 4$  independent integrals. It reflects the fact that for  $N$  particles, we have the on-shell mass constraints and overall four-momentum conservation.

### Two-Body Phase Space

The expression for the two-body phase space is more direct. For two particles, you start with eight integrals (three momentum components for each particle). You subtract two from the mass-shell constraint for each particle and four from the momentum conservation delta function. What remains are two differentials.

This can be arranged so that you only integrate over angles. Essentially, that's the only freedom you have: the direction orientation, because in the center-of-mass frame, particle one and particle two go back-to-back. The space of configurations in that case is simply  $4\pi$  non-relativistically, with a relativistic correction factor.

The final, Lorentz-invariant form is:

  $$d\phi_2 = \frac{1}{8\pi} \frac{2p^*}{\sqrt{s}} d\cos\theta \frac{d\varphi}{2\pi}$$  

Here,  $p^*$  is the magnitude of the momentum for each particle in the center-of-mass frame, and  $\sqrt{s}$  is the total center-of-mass energy.


::: callout-note
**Physics Meaning:** This formula represents the simplified phase space for a decay into two particles. The factor  $\frac{1}{8\pi}$  arises from integrating over the delta functions, and  $\frac{2|\mathbf{p}|}{\sqrt{s}}$  is the relativistic kinematic factor. The only free variables are the angular orientation  $(\theta, \phi)$ .
:::

### Three-Body Phase Space and Factorization

For the three-body case, it's more involved:  $d\phi_3(1, 2, 3)$ . It's a Lorentz-invariant expression we can evaluate in any frame.

A powerful trick is to rewrite the three-body phase space using a two-body topology. We can factorize it by considering the decay as happening in two steps:

1.  The initial particle decays into a composite system (1,2) and particle 3.
2.  The composite system (1,2) then decays into particles 1 and 2.

This is done by introducing the invariant mass squared of the (1,2) pair,  $m_{12}^2$ , as an integration variable.

**The claim is that the full three-body phase space can be written as:**

  $$d\phi_3 = d\phi_2(0 \to (1,2), 3) \times d\phi_2((1,2) \to 1,2) \times \frac{d m_{12}^2}{2\pi}$$  

This is intuitive: you split your phase space into a sequential pair of two-body decays. This is a general method to reduce an  $N$ -body phase space to combinations of lower-body phase spaces.

Substituting the explicit form for the two-body phase spaces, we get:

  $$d\phi_3 = \frac{1}{8\pi} \frac{2 p_3^*}{\sqrt{s}} \frac{d\Omega_{12,3}}{4\pi} \times \frac{1}{8\pi} \frac{2 k_{1,2}}{m_{12}} \frac{d\Omega_{1,2}}{4\pi} \times \frac{d m_{12}^2}{2\pi}$$  

Here,  $p_3^*$  is the momentum of particle 3 in the rest frame of the initial particle, and  $k_{1,2}$  is the momentum of particle 1 (or 2) in the rest frame of the (1,2) system.

### From Angles to Invariant Masses: The Dalitz Plot

The final step is to trade the angular variable, specifically  $\cos\theta_{1,2}$  from the decay of the (1,2) system, for another invariant mass squared, like  $m_{23}^2 = (p_2 + p_3)^2$ .

The relation is linear:
  $$m_{23}^2 = m_2^2 + m_3^2 + \frac{1}{2 m_{12}^2} (m_{12}^2 + m_2^2 - m_1^2)(-m_{12}^2 + s - m_3^2) - \frac{1}{2 m_{12}} \lambda_{12}^{1/2} \lambda_{30}^{1/2} \cos \theta_{1,2}$$  
where  $\lambda_{12} = \lambda(m_{12}^2, m_1^2, m_2^2)$  and  $\lambda_{30} = \lambda(s, m_{12}^2, m_3^2)$ .

This allows us to replace the integration over  $d\cos\theta_{1,2}$  with an integration over  $dm_{23}^2$ . 




![This figure represents a Dalitz plot, a fundamental tool for analyzing the kinematics of three-body decays in particle physics. The plot uses invariant mass squared variables— $m_{12}^2$  on the horizontal axis and  $m_{23}^2$  on the vertical axis—to represent all possible configurations of final-state particle momenta. Each physically allowed set of momenta for the three particles corresponds to a single point within the bounded region (the "circle") shown in the plot, which is defined by the constraints of energy-momentum conservation and the masses of the particles (the phase space boundaries determined by the Kibble function). The text annotates that every possible configuration is mapped inside this region, meaning the entire phase space is represented within the plot.  At the bottom, the differential decay rate formula  $d\Gamma = \frac{1}{2\sqrt{s}}|\mathcal{M}|^2 d\phi$  is shown, emphasizing that the observed distribution in the Dalitz plot is shaped by both the available phase space ( $d\phi$ ) and the dynamics of the decay process ( $|\mathcal{M}|^2$ ). For pure phase space (i.e., no dynamical structure), the density of events would be uniform across the allowed region. Any non-uniformity reflects physical processes, such as resonances or interaction dynamics among the decay products.](2025-Lecture-05-images/fig10.png){#fig-fg10}

 




![This figure illustrates the angular distribution of decay products, specifically showing how the differential decay rate  $\frac{d\Gamma}{d\cos\theta}$  depends on the angle  $\theta$  for a particle decay process (such as a  $\Lambda$  baryon). The top plot shows a flat, uniform distribution in  $\cos\theta$ , which is expected "in case of no  $\Lambda$  polarisation"—that is, when the decaying particle is completely unpolarized, the decay is isotropic and all directions are equally likely, matching the prediction of phase space for an unpolarized system. The bottom plot shows a linear, asymmetric distribution, which is labeled as “observed: backward-forward-asymmetry.” This means that in real data, an asymmetry is measured indicating a preference in the decay direction (either forward or backward along an axis such as the parent momentum or beam direction). This asymmetry is a physical effect, revealing information about polarization, parity violation, or possible new physics in the production or decay process. The use of the variable  $\cos\theta$  connects this directly to the kinematics and angular distributions discussed in the lecture, and measuring such asymmetries is a key tool for characterizing particle properties in hadron spectroscopy experiments.](2025-Lecture-05-images/fig17.png){#fig-fg17}






What we obtain is that the three-body phase space can be expressed purely in terms of two invariant mass squares, for example  $m_{12}^2$  and  $m_{23}^2$ :

  $$\frac{d\phi_3}{d m_{12}^2 d m_{23}^2} \text{ is flat (uniform)}$$   




![This figure illustrates the physical interpretation of a **Dalitz plot** and its projections in the context of three-body decays, as discussed in the lecture. The leftmost plot is a schematic Dalitz plot: a two-dimensional plot where each event in a three-body final state is represented by a point with coordinates given by two invariant mass squares,  $m_{12}^2$  and  $m_{23}^2$ . The kinematically allowed region is typically a solid shape (here represented as a circle or oval), defined by the boundaries of energy-momentum conservation and visualized using the Kibble function.  The lines labeled "1" and "2" depict paths or loci within this physical region where substructures may occur, for example, if two of the final-state particles resonate to form an intermediate particle (resonance). "Look at  $m_{ij}$  on the axes" is a prompt to consider projections onto the axes—i.e., the invariant mass squared distributions for different particle pairs.  The subsequent small plots to the right show the **projected invariant mass squared spectra** ( $d\Gamma/dm_{12}^2$ ,  $d\Gamma/dm_{23}^2$ ,  $d\Gamma/dm_{13}^2$ ): these are the one-dimensional distributions obtained by integrating over the Dalitz plot along one variable. Each projection picks out how often particular mass combinations occur. Peaks in these distributions correspond to resonant substructures or enhancements in the decay rate for specific two-body combinations.  The text "if the Dalitz plot had diagonal lines there would be peaks for 3" emphasizes that if correlations along diagonals existed (e.g., due to a third resonance in the third pair), they would manifest as peaks in the respective projection.  Overall, this figure visually conveys how the **Dalitz plot encodes all three-body decay kinematics** and how physical resonances or substructures of the matrix element  $|\mathcal{M}|^2$  manifest as features (such as peaks) in the projections of the invariant mass distributions. This framework is fundamental for analyzing and interpreting exclusive three-body decays in hadron spectroscopy.](2025-Lecture-05-images/fig11.png){#fig-fg11}

 




![This figure illustrates the Dalitz plot for a three-body decay of an unknown particle  $x$  into a proton ( $p$ ), a kaon ( $K^-$ ), and a pion ( $\pi^+$ ), specifically  $x \to p K^- \pi^+$ . The Dalitz plot represents each event as a point in the space defined by the squared invariant masses  $m^2(pK^-)$  (horizontal axis) and  $m^2(K^- \pi^+)$  (vertical axis).   The physical meaning of the plot comes from how regions in this space correspond to different kinematic configurations of the decay products: - The allowed kinematic region is bounded by curves representing the minimum and maximum possible values for these invariant masses, determined by the masses of the initial and final particles (as shown by the various labeled bounds such as  $(m_p + m_{K^-})^2$ ,  $(m_K + m_{\pi^+})^2$ ,  $(m_x - m_p)^2$ , and  $(m_x - m_{\pi^+})^2$ ). - A **horizontal band** (parallel to the x-axis) indicates a resonance in the  $K^- \pi^+$  subsystem: this appears when two final state particles form an intermediate resonance (e.g., a  $K^*$ ), which would show up as many events clustered at a specific value of  $m^2(K^- \pi^+)$ . - A **vertical band** (parallel to the y-axis) indicates a resonance in the  $pK^-$  subsystem: this denotes the presence of an intermediate resonance involving the proton and the kaon. - The distributions along the sides of the plot (represented by horizontal and vertical projections) show the invariant mass spectra of the respective pairs, with peaks corresponding to resonance masses smeared by experimental resolution and possible backgrounds.  Overall, the Dalitz plot is a powerful tool in hadron spectroscopy, as it allows experimenters to identify intermediate resonances and study the dynamics of three-body decays by observing the density and structure of events within the kinematic boundaries. The uniformity or enhancement in certain regions of the plot reveal physical processes beyond pure phase space, specifically the effects of the matrix element  $|\mathcal{M}|^2$  and the presence of resonances.](2025-Lecture-05-images/fig18.png){#fig-fg18}






This flatness is a key point. The differential decay width is  $d\Gamma = \frac{1}{2\sqrt{s}} |\mathcal{M}|^2 d\phi$ . It means the phase space density itself does not depend on  $m_{12}^2$  and  $m_{23}^2$ ; all configurations within the kinematically allowed region are equally probable from a phase space perspective. Any suppression or enhancement comes purely from the dynamics encoded in the matrix element squared  $|\mathcal{M}|^2$ .


::: callout-important
**The Dalitz Plot:** Every configuration of the three particles' momenta can be mapped to a single point inside a two-dimensional plot defined by  $m_{12}^2$  and  $m_{23}^2$ . This is the **Dalitz plot**. It's a powerful way to visualize how a decay proceeds, as structures in the plot directly reflect the behavior of the matrix element.
:::

### The Kinematic Boundary: The Kibble Function

The interior of the Dalitz plot—the region where points are physically allowed—is described by the **Kibble function**. The condition for a point  $(m_{12}^2, m_{23}^2)$  to be inside the plot is: (see @fig-fg10) (see @fig-fg11) (see @fig-fg18)

  $$\Phi = \lambda( \lambda(s, m_1^2, m_{23}^2), \lambda(s, m_2^2, m_{13}^2), \lambda(s, m_3^2, m_{12}^2) ) < 0$$  

Here,  $\lambda(x, y, z) = x^2 + y^2 + z^2 - 2(xy + yz + zx)$  is the Källén (or triangle) function.

In summary, for a three-body decay:

* The phase space density in the Dalitz plot variables  $(m_{12}^2, m_{23}^2)$  is uniform.
* The kinematically allowed region is defined by the Kibble function.
* Any non-uniformity in the distribution of events across the Dalitz plot is a direct signature of the dynamics in  $|\mathcal{M}|^2$ .

This gives us a very nice picture to analyze decays. For instance, you could be given a set of three momenta (which sum to zero) from an experiment and your task would be to compute  $m_{12}^2$  and  $m_{23}^2$  to place that event as a point on the Dalitz plot.

