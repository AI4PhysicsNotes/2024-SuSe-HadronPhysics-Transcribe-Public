---
title: (2025) Lecture 7
author: ''
presenter: Mikhail Mikhasenko
note_taker: Anna Zimmer
date: '2025'
format: html
---

**Presenter**: {{< meta presenter >}}

**Note Taker**: {{< meta note_taker >}}



## Weak Interaction in Hadron Decays and Isospin Rotations

### Seventh Meeting on Hadron Physics

The lecture expands on the previous helicity formalism discussion. We will cover partial wave expansion (already seen in the homework) and then move to general principles: the Mandelstam plane and analyticity. 




![This figure illustrates the basic kinematic structures for two-to-two particle scattering processes ( $A + B \to C + D$ ) as discussed in the lecture. At the top, it shows a generic  $2 \to 2$  scattering diagram with incoming particles  $A$  and  $B$  and outgoing particles  $C$  and  $D$ . Below, it shows two specific "channel" diagrams labeled  $s$  and  $t$ :  - The ** $s$ -channel** (left diagram) corresponds to the situation where particles  $A$  and  $B$  annihilate or interact to form an intermediate state, which subsequently decays into  $C$  and  $D$ . This configuration is directly related to the Mandelstam variable  $s = (p_A + p_B)^2$ , which represents the square of the total energy in the center-of-mass frame.  - The ** $t$ -channel** (right diagram) illustrates a different process where  $A$  exchanges a particle with  $B$ , resulting in  $C$  and  $D$ . Here the relevant Mandelstam variable is  $t = (p_A - p_C)^2$ , representing the squared momentum transfer between the initial and final states.  Physically, these diagrams represent different ways the scattering can occur, or equivalently, different regions of the Mandelstam plane. The figure emphasizes how the full amplitude for the process can receive contributions from multiple kinematic configurations, each characterized by its corresponding Mandelstam variable ( $s$ ,  $t$ , or  $u$  channels, with  $u$  not shown). These considerations are fundamental to the partial wave expansion, crossing symmetry, analyticity, and the broader analytic structure of the scattering amplitude being discussed in the lecture.](2025-Lecture-07-images/fig6.png){#fig-fg6}

 




![This figure represents the **Mandelstam plane**, a key tool in scattering theory used to visualize and analyze the kinematics of  $2 \to 2$  scattering processes. The axes correspond to two of the three Mandelstam variables  $(s, t, u)$ , which are Lorentz-invariant quantities that fully specify the kinematics.   The colored regions indicate the physically allowed regions for different scattering channels: - The **upper blue shaded region** labeled "s-channel" corresponds to physical values where  $s$  is positive and the process describes direct  $2 \to 2$  scattering. - The **left blue shaded region** labeled "t-channel" corresponds to kinematics where  $t$  is positive and describes exchange processes. - The **right red shaded region** labeled "u-channel" represents the physical region for the  $u$  channel.  The lines labeled  $s=0$ ,  $t=0$ , and  $u=0$  denote the boundaries between different kinematic regions. The areas marked "unphysical" lie outside the regions allowed by energy-momentum conservation for real particles, but can be accessed in analytic continuations of the scattering amplitude. The central green region indicates an overlap of physical boundaries.  Physically, the Mandelstam plane illustrates the domains where each scattering channel (s, t, u) is physical, a concept crucial for understanding particle processes, crossing symmetry, and the analytic properties of scattering amplitudes discussed in this lecture.](2025-Lecture-07-images/fig7.png){#fig-fg7}

 




![This figure shows the physical setup of a generic  $2 \to 2$  scattering process, which is a fundamental context for partial wave expansion and the use of Mandelstam variables in hadron physics.  - **Left Panel:** This diagram represents a generic scattering process, where particles with initial 4-momenta  $p_1$  and  $p_2$  scatter via some interaction (potentially mediated by resonances, as in strong interaction processes) into final-state particles with 4-momenta  $p_1'$  and  $p_2'$ . The blob indicates that the interaction can be complex and model-independent.  - **Right Panel:** This is the same process drawn in the center-of-mass frame and projected onto the scattering plane. It shows how the initial particle momenta are oriented, and how, after the collision, the outgoing particles are deflected by an angle  $\theta$ . This angle  $\theta$  is the **scattering angle**, a key variable in describing differential cross sections and in the **partial wave expansion** of the amplitude:     $$f(E, \theta) = \frac{1}{k} \sum_\ell (2\ell+1) e^{i\delta_\ell(E)} \sin\delta_\ell(E) P_\ell(\cos\theta)$$     The scattering angle is thus fundamental in decomposing the amplitude into components of definite orbital angular momentum.  This image provides the kinematic basis for introducing the **Mandelstam variables** ( $s$ ,  $t$ , and  $u$ ), which are Lorentz-invariant and fully characterize the process. It underpins the analysis of resonance production, angular distributions, and the formal structure of amplitudes discussed in the lecture, including their expansion in terms of Legendre polynomials as dictated by rotational symmetry.](2025-Lecture-07-images/fig8.png){#fig-fg8}

 




![This figure represents the expansion of the scattering amplitude  $\mathcal{M}$  in terms of multiple contributions, illustrating both the mathematical series and the corresponding Feynman diagrams. The first term shows a direct transition from the initial ( $i$ ) to final ( $f$ ) state, corresponding to the simplest process, often called the "Born term." The subsequent terms add the effects of intermediate states: the second term represents a process with a single intermediate state ("rescattering" or "loop" correction), and the third term includes two such intermediate interactions, and so on.   Physically, this expansion encodes the idea that the total amplitude for a scattering process includes not only the direct transition but also all possible pathways involving one or more intermediate states, corresponding to multiple exchanges or rescatterings. This iterative structure is central to the understanding of **unitarity** and **analyticity** in quantum scattering theory, as each term contributes to the full, analytic amplitude in line with principles discussed in the lecture, such as the requirements imposed by the Lorentz group and the Mandelstam plane. The formalism shown here lays the groundwork for constructing amplitudes that respect these fundamental symmetries, providing the basis for resonance models and partial wave expansions described throughout the lecture.](2025-Lecture-07-images/fig10.png){#fig-fg10}

 




![This figure illustrates the characteristic behavior of a resonance amplitude’s real and imaginary parts as a function of the Mandelstam variable  $s$ , which typically denotes the invariant mass squared of a two-body subsystem in a decay or scattering process.   On the left, the plot shows the imaginary part of the amplitude,  $\text{Im}(a)$ . It displays a peak at  $s = m_R$ , where  $m_R$  is the mass of the resonance. This reflects the fact that, according to the Breit-Wigner parameterization, the imaginary part of the amplitude becomes largest when the invariant mass of the system matches the resonance mass, representing the maximal probability for the resonance to be produced on-shell.  On the right, the plot shows the real part of the amplitude,  $\text{Re}(a)$ , versus  $s$ . Here, as  $s$  increases through the resonance region, the real part exhibits a characteristic "phase motion," smoothly crossing zero at  $s = m_R$  and changing sign. This behavior is a direct consequence of the analytic properties of the Breit-Wigner (or more generally, resonant) amplitude and is closely related to the unitarity and analyticity constraints discussed in the lecture. The total amplitude thus traces out a circular trajectory in the complex plane as  $s$  varies, resulting in a rapid change in phase (typically by about  $\pi$ ) as the system passes through the resonance.  Physically, these features—peak in  $\text{Im}(a)$  and phase motion in  $\text{Re}(a)$ —are signatures of resonant behavior and are used to identify and characterize hadronic resonances in Dalitz plot analyses and partial wave expansions. The figure matches the lecture’s context, where these generic features of resonance line shapes and their relation to analytic properties of amplitudes are discussed as foundational concepts for parameterizing dynamic functions using the Breit-Wigner form.](2025-Lecture-07-images/fig11.png){#fig-fg11}

 




![This figure is an Argand diagram illustrating the complex scattering amplitude  $f$  in partial wave analysis, key to understanding resonance behavior in hadron physics. The horizontal axis represents the real part of  $f$ , Re( $f$ ), and the vertical axis represents the imaginary part, Im( $f$ ). The black circle, centered at  $(0,\,1/2)$  with radius  $1/2$ , reflects the unitarity condition for the scattering amplitude in a single partial wave. This means that as energy varies, the amplitude  $f$  must remain within or on this circle, encoding probability conservation.   The arc  $\mathcal{R}$  drawn in red shows how the amplitude associated with a resonance moves through the complex plane as a function of energy. As the energy sweeps through the resonance, the point representing  $f$  traces out this characteristic arc. In the context of the lecture, this geometric representation is fundamental for visualizing how resonances manifest in scattering: the circular trajectory and its tangency to the unitarity circle demonstrate crucial connections between analytic properties, unitarity, and resonance phenomenology, all of which underpin the Breit-Wigner parameterizations and the more advanced analytic models discussed.](2025-Lecture-07-images/fig12.png){#fig-fg12}

 




![This figure illustrates the **Mandelstam plane** for the three-body decay process  $\pi^-(1800) \to \pi^- \pi^0 \omega$ . The axes represent the squared invariant masses of two different pairs in the final state:  $m^2_{\omega\pi^-}$  and  $m^2_{\omega\pi^0}$ . The Mandelstam variables  $s$ ,  $t$ , and  $u$  are labeled along corresponding directions in this plane. The hatched red regions denote the **kinematical boundaries** associated with each channel—these are the physically accessible regions for the respective invariant mass combinations.   The diagram emphasizes how the amplitude for this process is defined over the entire Mandelstam plane but physical decay events are restricted to a particular domain (with the allowed phase space marked). Internal loops or resonant contributions, depicted by circles with arrows, indicate the presence of intermediate resonances or rescattering effects in specific channels. This setup is crucial for understanding the analytic structure of the amplitude, as discussed in the lecture, especially when considering **partial wave expansions** and analytic continuation across the Mandelstam variables. Such visualization is foundational for modern approaches to amplitude analysis, like the **Khuri-Treiman formalism**, where constraints of analyticity and crossing symmetry are imposed using the geometry of the Mandelstam plane.](2025-Lecture-07-images/fig13.png){#fig-fg13}

 




![This figure illustrates the unitarity condition for the scattering amplitude in quantum field theory, specifically showing how the **imaginary part of the two-to-two scattering amplitude** is related to the sum over all possible **on-shell intermediate states**.   On the left, "Im" denotes the imaginary part of the full amplitude (indicated by the blob diagram with two incoming and two outgoing legs), which is fundamentally connected to the physical processes allowed by the system's quantum numbers and kinematics.  On the right, the diagram shows this imaginary part decomposed into a product of amplitudes for **all possible intermediate state contributions**, where the amplitude  $A$  for the process is paired with its complex conjugate  $A^*$ , and the intermediate states are indicated by a vertical cut through the loop. This cut signifies that the particles in the loop go on-shell—a process known as "cutting" the diagram in the context of the **optical theorem** or **Cutkosky rules**.  In the context of the lecture, this is a graphical representation of a **unitarity relation** or **discontinuity equation** for the scattering amplitude. It states that the imaginary part (or discontinuity across the real axis in the complex energy plane) can be expressed as a sum over products of amplitudes involving all possible intermediate states. This underpins the concept of **analyticity** in the Mandelstam plane: the physical amplitude is constrained by the requirement of unitarity and is analytic except for known cuts and poles corresponding to physical processes like particle production and resonances.  This relation is fundamental in constructing **partial wave expansions** and in understanding the analytic structure of amplitudes, and serves as the starting point for more sophisticated theoretical models such as the **Khuri-Treiman model**, which imposes these constraints on three-body decays using dispersion relations.](2025-Lecture-07-images/fig14.png){#fig-fg14}






The lecturer begins by recapping with three questions. Look at the problems to recap the material from the previous lecture. Five minutes to think, then discussion.

<hr>
#### Recap Questions 




![This figure represents a typical **cascade decay process** in hadron physics involving resonances and intermediate states, as discussed in the lecture. The initial interaction is a **photon ( $\gamma$ ) scattering off a proton ( $p$ )**, which leads to the production of an **intermediate resonance**—in this case, the ** $\Delta$  baryon** (illustrated by the triangle symbol in the diagram). The  $\Delta$  resonance then decays into a **proton ( $p$ )** and a **pion ( $\pi$ )**.   Physically, this diagram illustrates a  $2\to 2$  scattering process ( $\gamma p \to \Delta \to p\pi$ ), which is a concrete example of a reaction where a resonance (here, the  $\Delta$  with isospin  $I=3/2$ , spin  $J=3/2$ ) appears as an **intermediate state**. In the context of the lecture, this process is used to motivate the **helicity formalism** and the **factorization of amplitudes**: the total matrix element is constructed by combining the production amplitude of the  $\Delta$  (via  $U(\theta, \hat{n})$ , rotational properties, and group theory) with the decay amplitude of the resonance, which is characterized by its **Breit-Wigner propagator** and spin-dependent angular distributions (Wigner  $D$  or  $d$  functions).  The diagram shows how the **partial wave expansion** and resonance modeling (using Breit-Wigner distributions for the propagator and Wigner matrices for the angular structure) are applied in hadron spectroscopy, connecting the discussion of isospin, angular momentum conservation, and resonance dynamics from the lecture to an explicit scattering scenario.](2025-Lecture-07-images/fig5.png){#fig-fg5}






<b>Q:</b> Which interaction is responsible for the decay  $\Lambda \to p \pi^-$ ? Is isospin conserved? Is parity conserved? Is angular momentum conserved?

<b>Q:</b> Demonstate that the rotations discussed last time are not different from isospin rotations — they are all represented by an  $SU(2)$  group. For example, a 30‑degree isospin rotation about the  $y$ -axis acts on an isospin state as

  $$R_y(\theta) |I,m\rangle = \sum_{m'=-I}^{I} d^I_{m'm}(\theta) |I,m'\rangle,\qquad
d^I_{m'm}(\theta) = \langle I,m'| e^{-i\theta I_y} |I,m\rangle.$$  

What is the 30‑degree isospin rotation about the  $y$ -axis, and how does it act on the  $\Delta^+$  state?

<b>Q:</b> I gave you a Dalitz plot, and you could figure out which particle decays.

<hr>
#### Discussion of Question 1: Weak Interaction and Flavor Change

The answer to the first question: **weak interaction** is responsible for  $\Lambda \to p \pi^-$ . This is because there is a flavor change — the  $\Lambda$  contains a strange quark, and the final state ( $p, \pi^-$ ) has no strange quarks. Weak interaction always changes flavor.

This example contrasts with a scenario often discussed in the context of **neutron stars**:


::: callout-note
In neutron stars, one might argue that a neutron‑neutron collision produces a  $\Lambda$  and neutrons — that involves a flavor change. However, weak interaction is **too weak** to act in such a production process. If flavor changes are seen in a strong medium, it indicates a mistake (e.g., missing kaons must have been present). Weak interaction is only relevant for decays of ground‑state baryons, like the  $\Lambda$ .
:::

| Process | Interaction | Flavor change? | Remark |
|---------|-------------|----------------|--------|
|  $\Lambda \to p \pi^-$  | Weak | Yes | Decay of a strange baryon |
| Neutron‑neutron collision →  $\Lambda$  + neutrons | Strong (if it occurred) | Yes (implausible) | Would require flavor change in production — impossible for strong interaction; weak is too weak |

<b>Key point:</b> For decay processes, weak interaction is present for most ground‑state baryons. Most of them decay weakly.



## Weak Decays and Conservation Laws in a Dalitz Plot Analysis

#### Parity Conservation

On the left side, the proton has  $J^P = \frac12^+$  and the pion has  $0^-$ . Parity is conserved through angular momentum. The required orbital angular momentum is  $L = 1$ . That works, so the process can proceed as a parity-conserving one. However, parity is not conserved in that decay because it also happens in  $S$ -wave ( $L = 0$ ). The sensitivity to the polarization of the  $\Lambda$  in this decay arises from two components: a parity-conserving and a parity-violating one.

In weak decays, parity is always broken. It does **not** have to be 100% broken — in this case, 99% proceeds as a parity-conserving reaction, but there will always be a small fraction (e.g., 1%) of the parity-violating part. So weak decays do not conserve parity; they violate it.

<hr>
#### Angular Momentum Conservation

Angular momentum is **always** conserved in hadron physics and particle physics. This follows from Lorentz group symmetry. If you do not violate Lorentz symmetry, angular momentum is always conserved. You make it conserved by including orbital angular momentum; there is no violation of the Lorentz feature.

<hr>
#### Isospin Conservation

Isospin is **not** conserved. How do we see that it is not conserved?

| Particle | Isospin ( $I$ ) | Multiplicity | Charge Partners |
|----------|----------------|--------------|-----------------|
|  $\Lambda$  | 0 | 1 | singlet |
|  $p$  |  $\frac12$  | 2 |  $p$ ,  $n$  |
|  $\pi$  | 1 | 3 |  $\pi^+$ ,  $\pi^-$ ,  $\pi^0$  |

For the transition  $\Lambda \to p \pi$ , combining a vector of length  $\frac12$  (proton) with a vector of length  $1$  (pion) cannot yield  $0$  (the isospin of the  $\Lambda$ ). Therefore isospin is broken. This is a property of the weak interaction: isospin is always broken, either severely or a little bit, just as for parity.

<hr>
#### Identifying the Decaying Particle in the Dalitz Plot

The final state contains three particles:  $p$ ,  $K^-$ , and  $\pi^+$ . The initial state contains one particle. Thus it is a  $1 \to 3$  decay, represented on a Dalitz plot. The axes are:

-  $x$  axis:  $m^2(p K^-)$ 
-  $y$  axis:  $m^2(K \pi^+)$  (see @fig-fg9) (see @fig-fg13)

On the Dalitz plot:

- A **horizontal band** corresponds to a  $\Lambda$  resonance decaying into  $p K^-$ .
- **Vertical bands** correspond to  $K^*$  resonances decaying into  $K \pi$ .


::: callout-note
The decay is  $\Xi_c^+ \to p K^- \pi^+$ .
:::

<b>How to find the mother particle?</b>
Compute the mass from the phase-space boundaries. The maximum on the  $x$  axis is  $(M_0 - m_\pi)^2$ , the minimum is  $(m_K + m_\pi)^2$ . On the  $y$  axis, the maximum is  $(M_0 - m_p)^2$ , the minimum is  $(m_p + m_K)^2$ . Taking the square root of the highest value and adding the mass of the pion (or the proton) gives  $M_0 \approx 2.6$  GeV. Then look in the PDG for a particle with that mass.

<b>Quark content analysis:</b>

- Proton:  $uud$ 
-  $K^-$ :  $s\bar{u}$ 
-  $\pi^+$ :  $u\bar{d}$ 

The  $u\bar{d}$  pair can come from the vacuum. That leaves  $uds$  as the core quark content — so the decaying particle could be a pentaquark decaying strongly, or a weak decay. In fact, it is the weak decay of the  $\Xi_c^+$ .

A student suggested a strong decay to  $\Sigma^+ \pi^+$ . However, isospin could be conserved there:  $\Sigma^+$  has  $I = 1$ , proton  $I = \frac12$ ,  $K$  $I = \frac12 $, pion$ I = 1 $; combining$ \frac12 $and$ \frac12 $and$ 1$ can give  $1$ . Nevertheless, the actual identification comes from the  $\Xi_c$  angular analysis.



## Isospin Rotations and D‑Functions for the Delta Baryon

<b>Isospin operators on the  $\Delta^+$ </b>

The squared isospin operator acting on the  $\Delta^+$  gives  $J(J+1)$ . For the  $\Delta^+$ ,  $J = \frac32$ , so

  $$J^2 |\Delta^+\rangle = \frac{3}{2}\cdot\frac{5}{2} |\Delta^+\rangle = \frac{15}{4} |\Delta^+\rangle.$$  

Thus the first statement is true.

The isospin projection  $I_Z$  on the  $\Delta^+$  gives  $I_Z = \frac12$ . The  $\Delta^+$  belongs to the isospin multiplet with four states:

| State  $|J,M\rangle$  | Particle |  $I_Z$  |
|----------------------|----------|-------|
|  $|\frac32,\frac32\rangle$  |  $\Delta^{++}$  |  $+\frac32$  |
|  $|\frac32,\frac12\rangle$  |  $\Delta^{+}$   |  $+\frac12$  |
|  $|\frac32,-\frac12\rangle$  |  $\Delta^{0}$   |  $-\frac12$  |
|  $|\frac32,-\frac32\rangle$  |  $\Delta^{-}$   |  $-\frac32$  |

Because these states are eigenstates of  $I_Z$ , acting with  $I_Z$  on the  $\Delta^+$  yields  $\frac12$ :

  $$I_Z |\Delta^+\rangle = \frac12 |\Delta^+\rangle.$$  

Hence that statement is also true.

<hr>

<b>Rotation by  $30^\circ$  about the  $y$ -axis</b>

Under a rotation, a state  $|J M\rangle$  transforms according to SU(2). Applying a  $y$ -rotation of  $30^\circ$  to the  $\Delta^+$  state  $|\frac32,\frac12\rangle$  produces a linear combination of all  $\Delta$  states:

  $$R_y(\theta)\,|\tfrac32,\tfrac12\rangle = \sum_{m'} D^{3/2}_{m', \tfrac12}(\theta)\,|\tfrac32, m'\rangle,$$  

where  $D^{3/2}_{m', \tfrac12}(\theta)$  are Wigner  $D$ -functions (tabulated in the PDG Clebsch‑Gordan tables).

For example,  $D^{3/2}_{1/2,1/2}(30^\circ)$  involves a minus sign, a factor of  $\sqrt{3}/2$ , terms with  $1+\cos\theta$ , and a sine term. Squaring and summing all coefficients (including the last one) gives  $1$  – probability is conserved. The state becomes a mixture with probabilities given by those coefficients.

This demonstrates that rotations in isospin space are identical to ordinary rotations – both are governed by the unitary group SU(2).

<hr>

<b>Student question on the  $D$ -function coefficient</b>

<b>Q:</b> The last coefficient  $D^{3/2}_{-3/2,1/2}$  is not listed anywhere. Is it the same as  $D^{3/2}_{1/2,1/2}$ ? I think parity relations are listed.

<b>A:</b> Excellent question. The needed coefficient can be obtained via the symmetry relation for  $D$ -functions:

  $$D^{j}_{-m,-m'}(\theta) = (-1)^{m-m'}\, D^{j}_{m,m'}(\theta).$$  

Thus  $D^{3/2}_{-3/2,1/2}$  can be related to  $D^{3/2}_{-1/2,3/2}$  by swapping indices and inserting a minus sign. (Because of unitarity, these two are actually the same.) If after applying this you still cannot find a listing, the coefficient appears in the Clebsch‑Gordan table provided in the homework.

There is yet another relation: for a negative rotation, complex‑conjugate and transpose the  $D$ -function (transposition means swapping the indices). That relation is easy to remember: transpose and change the sign of the rotation angle. Are you satisfied with this?



## Helicity Formalism for Cascade Decays

### Helicity Formalism: From Two-Body to Cascade Decays

Today’s lecture applies the helicity formalism to compute amplitudes for decays with spin. We will move from a two-body decay to a general cascade, and along the way distinguish model assumptions from exact kinematic results.


::: callout-important
For every step, ask: Is this a general statement or a modeling assumption? The angular functions are exact; factorization into vertex blocks is a model.
:::

<hr>
#### Reminder: Two-Body Decay 




![This figure illustrates the kinematic setup for a two-body decay in the context of the helicity formalism.   On the left, a Feynman-like diagram represents the decay of a parent particle (labeled "0") into two daughter particles (labeled "1" and "2").   On the right, the physical configuration in the rest frame of the parent particle (labeled "0-rest frame") is shown. The z-axis is chosen as the quantization axis for spin. The outgoing particles 1 and 2 emerge back-to-back, with their momenta and helicities (λ₁ and λ₂) indicated. The angles θ (polar) and φ (azimuthal) specify the direction of particle 1 in spherical coordinates with respect to the z-axis.   The figure encapsulates the geometric meaning of the helicity formalism: the matrix element for the decay depends on the spin projections and the angular orientation of the outgoing particles, captured here by θ and φ. The angular dependence of the decay amplitude is encoded in the Wigner D-matrix, reflecting how spin and momentum are coupled in the rest frame of the decaying particle. This diagram provides the foundational visualization for expanding amplitudes in terms of partial waves and for connecting angular momentum conservation to observed decay distributions.](2025-Lecture-07-images/fig1.png){#fig-fg1}






Consider a particle of spin  $j_0$  decaying into two particles with spins  $j_1, j_2$ . In the rest frame of the decaying particle, the spin is quantised along the  $z$ ‑axis. The final state is described by helicity states  $|\lambda_1\rangle$  and  $|\lambda_2\rangle$ . The matrix element depends on: 




![This figure schematically represents the decay of a parent particle into two daughter particles, labeled 1 and 2, within the helicity formalism framework. Each arrow denotes the direction of momentum of the outgoing particles, and the accompanying symbols  $\lambda_1$  and  $\lambda_2$  denote their helicities in their respective rest frames.  The relation  $m = \lambda_1 - \lambda_2$  indicates the conservation of angular momentum along the quantization (typically  $z$ ) axis in the parent's rest frame: the difference in the helicities of the two final-state particles equals the spin projection  $m$  of the parent particle along that axis.  In the helicity formalism, this physical configuration underpins the angular dependence of the decay amplitude. Specifically, it determines which element of the Wigner D-matrix encodes the angular correlations between the spin projections of the initial and final states, a key concept that translates into the general partial wave expansion discussed in this lecture.](2025-Lecture-07-images/fig2.png){#fig-fg2}






* the masses (through the reduced matrix element),
* the helicities  $\lambda_1, \lambda_2$ ,
* the spherical angles  $(\theta,\phi)$  of one decay product.

Since the two particles go back‑to‑back, only one set of angles is needed. The angular dependence is given by a Wigner  $D$ -function. The amplitude reads:

  $$\mathcal{M}^{m_0}_{\lambda_1 \lambda_2}(m_0, m_1, m_2, \varphi, \theta) =
D^{j_0\,*}_{m_0,\;\lambda_1-\lambda_2}(\varphi,\theta,0)\; H_{\lambda_1 \lambda_2}$$  

where the reduced matrix element is

  $$H_{\lambda_1 \lambda_2} = \langle p_2, j_1 \lambda_1 | \otimes \langle p_2, j_2 \lambda_2 | \hat{T} | j_0, \lambda_1-\lambda_2 \rangle$$  

and does not depend on angles. The  $D$ -function follows the Z‑Y‑Z Euler‑angle convention:  $R_Z(0)$  then  $R_Y(\theta)$  then  $R_Z(\phi)$ . Explicitly, for a rotation that brings a particle aligned with the  $z$ ‑axis to spherical angles  $(\theta,\phi)$ , we have

  $$D^{j_0\,*}_{m_0,\Delta\lambda}(\varphi,\theta,0) = e^{-i m_0\varphi}\; d^{j_0}_{m_0,\Delta\lambda}(\theta).$$  

The little  $d$ -function appears in standard tables alongside Clebsch‑Gordan coefficients. The conjugation arises because we use active rotations on the final state.

<hr>
#### Extension to Cascade Decays

The same building blocks can describe a decay chain. Consider a reaction with an intermediate resonance: particle 0 decays into three particles (1,2,3) via an intermediate state  $|j,\lambda\rangle$  that itself decays into particles 1 and 2. 




![This figure illustrates an example of an **experimental topology** for a three-body decay commonly found in hadron physics analyses. The diagram shows the decaying particle at the interaction point, producing three final-state particles labeled 1, 2, and 3, each with momentum vectors radiating outward. The colored boxes, labeled here as  $b_1$  and  $b_2$ , represent two different possible intermediate resonant subsystems (for example, the combinations of particles 1+2 and 2+3, respectively). This reflects how, in an experimental context—such as a Dalitz plot analysis—multiple two-body resonant channels can contribute to the final state.  From the perspective of the **helicity formalism** and **partial wave expansion** discussed in the lecture, this topology visually encodes how the decay amplitude is constructed as a sum over possible intermediate states, each described by its own angles and rest frame. The two boxes illustrate “blocks” where specific two-body resonances may appear, as in the **cascade decay/isobar model**: the decay can proceed via an intermediate resonance formed by a pair of particles (e.g., 1+2 or 2+3) before decaying to the observed three-body final state. The orientation of the outgoing particles also emphasizes the need to define angles (such as  $\theta$  and  $\phi$ ) in the appropriate rest frames when applying the helicity formalism, as different decay chains (topologies) require consistent and careful bookkeeping of kinematic variables and spin quantization axes.](2025-Lecture-07-images/fig3.png){#fig-fg3}

 




![This figure illustrates the kinematic construction and reference frames relevant for the helicity formalism in cascade decays, as discussed in the lecture. It shows how to define the angles and axes necessary for correctly describing the spins and momentum directions of multiple particles in sequential decays.  - The **lab frame** (upper left, in purple) depicts the flight of the parent particle "0" with helicity  $\lambda_0$ . As particle 0 decays, its spin quantization axis is defined in this frame. - The event is boosted to the **rest frame of particle 0** (center), where the decay  $0 \to (12) + 3$  is considered. Here, the helicities of outgoing particles (e.g.,  $\lambda_3$ ) are defined with respect to the z-axis in this frame, and the relevant angles  $(\theta_{12,3}, \varphi_{12,3})$  specify the orientation of the (12)-3 system. - A further boost (indicated by "boost $^{-1}$ ") brings us to the **(12) rest frame** (top right, red/blue), where the pair (1,2) is at rest, and their decay kinematics can be fully described by  $(\theta_{12}, \varphi_{12})$ . The quantization axes and the definition of helicities  $\lambda_1$ ,  $\lambda_2$  are with respect to the new z-axis in this frame. - The diagram shows how each particle's momentum and spin orientation are defined in the appropriate rest frame along a specific z-axis, and emphasizes how the definition of the kinematic angles ( $\theta$  and  $\varphi$ ) depends on these sequential boosts and rotations.  **Physical Meaning:**   The figure provides a geometrical visualization of how to construct the angular variables and reference frames needed for a full helicity amplitude calculation in a decay chain. It clarifies that: - **Helicity quantization axes** are defined in different rest frames (a key caveat discussed in the lecture). - **Angles** such as  $\theta_{12}$ ,  $\varphi_{12}$ ,  $\theta_{12,3}$ , and  $\varphi_{12,3}$  specify the orientation of momentum vectors after appropriate boosts. - This construction is essential for writing decay amplitudes in terms of Wigner D-functions, ensuring that rotational properties and conservation of angular momentum are properly encoded in the matrix element for sequential decays.  The diagram is an explicit, practical guide for defining kinematic variables when applying the helicity formalism and partial wave expansions to multi-body (e.g., three-body) decays in particle physics.](2025-Lecture-07-images/fig4.png){#fig-fg4}

 (see @fig-fg5) (see @fig-fg9) (see @fig-fg10) (see @fig-fg14)

### Factorization as a Model Assumption

The amplitude is split into two vertex parts and a propagator:

* The first vertex:  $0 \to 3 + \text{(intermediate)}$ 
* The second vertex: intermediate  $\to 1 + 2$  (see @fig-fg6)

This splitting (factorization) is a model; the angular functions remain exact. The intermediate state carries a helicity  $\lambda$  that will be summed over. (see @fig-fg7)

### Index and Angle Convention

To keep track of the many angles, we adopt a systematic labeling:

| Decay level | Particles involved | Angle symbols | D‑function indices |
|-------------|-------------------|---------------|--------------------|
| First decay (0 → 1+2+3) | 0 → 3 + (12) |  $\theta_{123},\phi_{123}$  |  $D^{j_0\,*}_{m_0,\lambda}(\phi_{123},\theta_{123},0)$  |
| Second decay (12 → 1+2) | (12) → 1 + 2 |  $\theta_{12},\phi_{12}$  |  $D^{j\,*}_{\lambda,\;\lambda_1-\lambda_2}(\phi_{12},\theta_{12},0)$  | (see @fig-fg8) (see @fig-fg12)

The helicity  $\lambda$  of the intermediate resonance appears as the second index of the first  $D$  and as the first index of the second  $D$ .

### Constructing the Cascade in Practice

1. **From lab to 0 rest frame** – Boost particle 0 along its direction of motion. In this frame the quantisation axis is the  $z$ ‑axis (the boost direction). The three final particles are back‑to‑back. The spherical angles of the 1+2 system are  $(\theta_{123},\phi_{123})$ .

2. **From 0 rest frame to (12) rest frame** – Boost the 1+2 system along its direction of motion. Then particle 1 and 2 go back‑to‑back. In the (12) rest frame, the angles of one of them (say particle 1) are  $(\theta_{12},\phi_{12})$ .

In an experimental analysis, one starts with the four‑vectors of particles 1,2,3 in the lab. Using active rotations:

* Determine the spherical angles of the 1+2+3 combination. Rotate so that the 1+2+3 vector points along  $+z$ . Boost to the 0 rest frame.
* Within that frame, obtain the angles of the 1+2 system. Rotate so that the 1+2 vector aligns with  $+z$ . Boost to the (12) rest frame.
* Finally, apply the necessary rotations to obtain  $(\theta_{12},\phi_{12})$ .

### Full Cascade Amplitude

Putting everything together, with a propagator  $P^{j^2}(m_{12}^2)$  for the intermediate resonance:

  $$\mathcal{M}^{m_0}_{\lambda_1 \lambda_2 \lambda_3} =
\sum_{\lambda}
D^{j_0\,*}_{m_0,\lambda}(\varphi,\theta,0) \;
H_{\lambda_3 \lambda} \;
\times \;
D^{j\,*}_{\lambda,\lambda_1-\lambda_2}(\varphi_{12},\theta_{12},0) \;
H_{\lambda_1 \lambda_2} \;
P^{j^2}(m_{12}^2).$$  

The sum over  $\lambda$  enforces angular‑momentum conservation at the intermediate vertex. The angles are specific to each decay, and the reduced matrix elements  $H$  depend only on masses and spins.



## Helicity Quantization and Partial-Wave Expansion in Three-Body Decays

#### Helicity Formalism: Caveats and Simplifications

The topology drawn is not the only one possible. One can imagine the same transition proceeding through the combination of particles 2 and 3, or 3 and 1, and one would write the same expression.

Before proceeding, we discuss that expression, because there are caveats and things to note. (see @fig-fg4)

### Main Caveat: Helicities from Different Rest Frames (see @fig-fg1)

The main caveat is that the helicities appearing in the expression are taken from **different rest frames**. To apply the helicity formalism and replace an expectation value by a reduced matrix element (the helicity coupling), we need to be in the rest frame of the particle. Therefore, the values of  $\lambda$  that appear are taken in the rest frame of the pairs.

Helicity is affected when you boost not along the quantization direction, but off it (as seen in a previous homework). Therefore, it would be preferable to write the amplitude with all  $\lambda$  defined in the same frame. That would be  $\lambda_1, \lambda_2, \lambda_3, \lambda_0$  in the same frame, and one would get a linear combination of amplitudes. The fact that helicities are defined in different frames is considered bizarre.

The only reason we do not use the formalism presented here literally is that we do not care about the  $\lambda$  themselves — we are going to sum them up once we add things together. The consistency of the quantization axis is not a concern unless you are dealing with **coherent processes** that use different quantization axes.

What is important is on which axis the spins in this matrix element are quantized.  $\lambda_0$  comes from the lab frame — it is helicity in the lab frame. That is fine. As soon as we take the square of the matrix element and sum over helicities, we do not care which axis we quantize them on — they will be summed and averaged anyway. But if we want to add this amplitude to something else, for example, an expansion in a different topology, we must be careful with the helicity phases.


::: callout-important
**First important note:** Watch your helicity quantization axis.
:::

### Factorization Assumption and Model Dependence (see @fig-fg2)

<b>Second important note:</b> In this approach we are implicitly assuming **factorization** — the vertices are factorized. Usually this is a very good assumption, especially for a narrow resonance. Even for a broad resonance that drives the dynamics in the  $1$ –$2 $combination, it is a good assumption. One would not assume factorization if you join these two terms in another way.

The Wigner$ D$-functions here are a property of rotations — they are not model assumptions. Lorentz symmetry is a good symmetry, so these functions must be present.

If we take the matrix element without the factorization assumption, use the propagator, and join it into something that requires theory input, the resulting expression is model-independent for the matrix element. (see @fig-fg3) It is safe to pull out the rotational functions; it is not safe to break them.

### Angular Dependence from Helicity Formalism

What we have done is found explicitly what the angular dependence would be if a particle with spin  $J$  is present in the combination. The helicity formalism is a simple way to identify the dependence of the matrix element on the angles. The spin of particles 1 and 2 is not given directly by the angular dependence form — the form gives the appropriate angles, but dealing with spin is more complicated.

### Reducing to the Scalar Case (see @fig-fg11)

Let us reduce the situation to scalar particles: a scalar particle decaying to three scalar particles. Call this the **scalar case**. The matrix element in that case has no indices, but it still depends on the dynamical variables. In the general helicity amplitude expression

  $$\mathcal{M}^{m_0}_{\lambda_1\lambda_2\lambda_3}=\sum_\lambda D^{j_0*}_{m_0,\lambda}(\varphi,\theta,0)H_{\lambda_3\lambda}D^{j*}_{\lambda,\lambda_1-\lambda_2}(\varphi_{12},\theta_{12},0)H_{\lambda_1\lambda_2}P^{j^2}(m_{12}^2)$$  

there are no values for  $\lambda$  except zero. A spin-zero state has a single state in its multiplet, and under rotations it must transform through the states of the multiplet; the only thing that can happen is a phase modification, but there are no possible  $\lambda$  values except zero. Therefore, this term gives  $\delta_{\lambda,0}$ , which we can propagate further and then replace.

The expression becomes very simple:

  $$\mathcal{M} = \sum_\lambda D^{0*}_{0,\lambda}(\varphi_{12,3},\theta_{12,3},0) H_{\lambda,0} D^{j*}_{\lambda,0}(\varphi_1,\theta_1,0) H_{00} P(m_{12}^2) = \delta_{\lambda,0}.$$  

The matrix element in that case does not depend on any angles except one polar angle. In the rest frame of the two-particle system, all other angles drop out; only one angle remains. The convenient way to write this is to move towards matching the expression to the partial-wave expansion series that you see in the homework. That is why we pulled the terms related to the helicity couplings and the reduced matrix element into the function  $X$  and introduced the  $(2J+1)$  coefficient in front.

We started by writing the matrix element for a decay proceeding through a resonance of spin  $J$ , and found that the angular dependence is given by  $d^J_{00}(\Theta)$ , which are in fact Legendre polynomials  $P_J(\cos\Theta)$ . I want to match this to the general technique of analyzing the matrix element by expanding it in a series of Legendre polynomials. The coefficients in this expansion depend only on the mass variable, and they represent the dynamics corresponding to a specific  $J$  of the resonance. We started from a model, but it gives us interpretation and intuition.

### Partial-Wave Expansion

The total matrix element in the scalar transition depends on only two variables: the scattering angle and the mass. That is what we also see in the Dalitz plot — two variables: the mass of one subsystem and the mass of the second subsystem. This dependence can be explored by analyzing the coefficients in the partial-wave expansion. The expansion is an **exact representation**; as soon as you truncate the series, it becomes an approximation.

The partial-wave expansion for the scalar case is

  $$\mathcal{M} = \sum_{j=0}^\infty \sqrt{2j+1} \, d^j_{00}(\Theta_{12}) X_i^j(m_{12}^2)$$  

or equivalently, for the  $S$ –$T $amplitude,

 $$A(s,t) = \sum_{J=0}^\infty (2J+1) a_J(s) P_J(\cos\Theta).$$  

In experiment, we often use a truncated partial-wave series because we can attach a physical intuition to each term: every term corresponds to a particle with spin  $J$ . High spins are not abundant — the PDG shows few particles with high  $J$ , and the amplitude with high  $J$  is suppressed. That gives a natural limit to the expansion. We do not know particles with spin greater than six —  $a_6(2450)$  exists, but no  $a_7$ , although such states exist in the quark model (by combining currents you can make spin-7 and spin-10 particles). Experimentally they have never been observed. The reason is simple: they lie very high in the excitation mass spectrum and are very broad, so they are difficult to observe and their effect is small. Practically, we truncate the series at  $J=6$ ; nothing higher has ever been seen.



## Modeling Dalitz Plot with Helicity Formalism and Resonance Identification

#### Modeling the Dalitz Plot with **Helicity Formalism** (see @fig-fg3) (see @fig-fg7)

The final topic is modeling the Dalitz plot distribution for the decay  $\Xi_c \to p K^- \pi$  using the **helicity formalism**. (see @fig-fg1) (see @fig-fg2) (see @fig-fg4) (see @fig-fg10) (see @fig-fg14)

### Focus on dynamics, not borders (see @fig-fg5) (see @fig-fg6) (see @fig-fg8) 




![This figure shows a schematic representation of a resonance in a two-body invariant mass spectrum, as described in the context of the lecture's discussion of resonance propagators and the Breit-Wigner parameterization. The horizontal axis represents the invariant mass of a two-particle system,  $(m_1 + m_2)$ , while the vertical axis corresponds to the event rate or probability amplitude.  The resonance manifests as a prominent peak, centered at the resonance mass  $m_R$ . The width of the peak, denoted by  $\Gamma$ , characterizes the decay width (or inverse lifetime) of the intermediate resonance state. This shape is modeled by the Breit-Wigner resonance amplitude, a key dynamic function used in the isobar and cascade decay models to describe intermediate resonances in multi-body decays.  Physically, this plot illustrates how a resonance like  $K^*(892)$ ,  $\Lambda(1520)$ , or  $\Delta(1232)$  appears in the invariant mass spectrum of its decay products, with the position and width of the peak directly encoding the resonance’s mass and decay properties.](2025-Lecture-07-images/fig9.png){#fig-fg9}

 (see @fig-fg13)

All inhomogeneities within the phase space are driven by physics: either by resonances that produce bumps, or by structure within the bands that reflect spin and angle distributions. (see @fig-fg11) The helicity formalism encapsulates these effects.

### Input for the helicity formalism

The amplitude can be expressed as:

  $$\mathcal{M}^{m_0}_{\lambda_1\lambda_2\lambda_3}=\sum_{\lambda} D^{j_0*}_{m_0\lambda} H_{\lambda_3\lambda} D^{j*}_{\lambda,\lambda_1-\lambda_2} H_{\lambda_1\lambda_2} P(m_{12}^2)$$  

Application requires:

- the spins of all particles (known),
- the reduced matrix elements,
- a choice for the propagator  $P(m_{ab}^2)$ .

We adopt the **isobar model** and parameterize the propagator with the **Breit–Wigner formula**:

  $$a(m_{ab}^2)=\frac{g^2}{m_R^2-m_{ab}^2-ig^2\mathcal{S}(m_{ab}^2)}$$  

Thus only the mass, width, and spin  $J$  of each resonance are needed.

### Identifying resonances in the decay  $\Xi_c \to p K^- \pi$  (see @fig-fg12)

The two‑particle combinations produce characteristic structures in the Dalitz plot. The axes of the Dalitz plot are scaled as squared invariant masses ( $m^2$ ), so resonance masses appear squared; for example,  $\Lambda(1520)$  appears at  $1.52^2 \approx 2.3\ \mathrm{GeV}^2$ , not at 1.52 GeV.

| Two‑particle system | Appearance in Dalitz plot | Identified resonance(s) |  $J^P$  |
|---------------------|---------------------------|-------------------------|-------|
|  $K\pi$               | Horizontal band           |  $K^*(892)$ , a second  $K^*$  around 1.4 GeV |  $1^-$  |
|  $Kp$                 | Vertical band(s)          |  $\Lambda(1520)$ ,  $\Lambda(1690)$  |  $3/2^-$  |
|  $p\pi$               | Diagonal line             |  $\Delta(1232)$           |  $3/2^+$  |

The  $K^*(892)$  is the first radial excitation, analogous to the  $\rho$  in the strange sector. It has zero orbital angular momentum between the  $s$  and  $\bar{u}$  quarks; the spin wave function gives spin 1 because the spins of the quarks are flipped. There is an additional  $K^*$  resonance around 1.4 GeV, visible as a second horizontal band. The  $\Lambda(1520)$  and  $\Lambda(1690)$  belong to the  $P$  multiplet, with orbital angular momentum between the quarks.  $\Lambda(1405)$  appears as a threshold enhancement near the low‑mass corner. Six further  $\Lambda$  states are not visually prominent.

### General expansion in partial waves

The full amplitude is the sum over all two‑particle subsystems  $ab$ , each expanded in terms of partial waves:

  $$M = \sum_{ab} M_{ab},\qquad M_{ab} = \sum_i \mu_{ab}^i,
\qquad \mu_{ab}^i = \sqrt{2j+1}\, d_{00}^j(\Theta_{ab}) \, X_{ab}^i(m_{ab}^2)$$  

Here  $d_{00}^j(\Theta_{ab})$  is the Wigner  $d$ -matrix element and  $X_{ab}^i$  contains the Breit–Wigner factor.


::: callout-warning
If the decay products are not all spin‑less, the quantization axes for different decay chains are not aligned. For the  $\Xi_c \to p K^- \pi$  decay, the proton has spin, so blindly applying the helicity formalism for separate chains without proper axis transformation will yield incorrect results. The formula given above is correct only if all final particles are scalars.
:::

### Summary of practical steps

1. Look up the known spins and resonance parameters (mass, width,  $J^P$ ) of the isobars from the PDG.
2. Use the helicity‑formalism amplitude with the Breit–Wigner propagator for each resonance.
3. Correctly handle the spin quantization axis for the proton — this is nontrivial and must be done consistently across all decay chains.

